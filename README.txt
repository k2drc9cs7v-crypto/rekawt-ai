REKAWT AI — iPhone PWA starter

WHAT THIS IS
A first installable web-app prototype with Kurdish, Arabic and English UI,
an offline app shell, simple local starter replies, and optional browser speech
recognition where Safari supports it.

IMPORTANT LIMITATIONS
- This is not yet a full ChatGPT-like AI. The current offline responses are
  basic starter logic, not a local language model.
- Online AI is not connected yet. A secure backend/API endpoint must be chosen
  and configured. Never put a private API key in app.js or any browser file.
- iOS Safari speech recognition support varies. Text chat works regardless.
- The service worker requires HTTPS hosting (or localhost for testing).

INSTALL ON IPHONE
1. Host the contents of this folder on an HTTPS website.
2. Open that website in Safari on the iPhone.
3. Tap Share, then "Add to Home Screen".
4. Name it REKAWT AI and tap Add.

NEXT DEVELOPMENT STEP
Connect a secure backend for online AI, then evaluate a small quantized local
model for offline inference. iPhone 11 memory/performance constraints mean
offline model size must be selected carefully.
