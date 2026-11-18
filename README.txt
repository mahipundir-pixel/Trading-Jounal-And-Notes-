TRADE JOURNAL
==============
Web/PWA:
- Upload the contents of the web folder (index.html, manifest.webmanifest, sw.js, icon.svg) to any HTTPS static host.
- Open the HTTPS URL in Chrome on Android and choose Install app / Add to Home screen.
- The PWA works offline after its first successful load.
- Data is saved locally in the browser. Use Settings > Export backup regularly.

Android:
- Open the android/ folder in Android Studio.
- Let Gradle sync, then Build > Build Bundle(s) / APK(s) > Build APK(s).
- This source project is a WebView wrapper around the same journal. It is not a pre-signed APK.
- For a production release, configure signing in Android Studio.

Features:
- Add any symbol; no HDFC-only restriction.
- Date, symbol, buy, sell, quantity, stop loss, P/L and automatic Win/Loss.
- Edit/delete trades, symbol filter, monthly summary, win rate, profit factor, net P/L.
- Local device storage, JSON backup export/import.
