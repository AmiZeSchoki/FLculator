LEASING & FINANZIERUNGSRECHNER — INSTALLABLE PWA

Files:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

IMPORTANT:
Android/Chrome only offers proper PWA installation when the app is served over HTTPS (or localhost for development). Opening index.html directly from Downloads with file:// is not enough for an installable PWA.

QUICK INSTALL PATH:
1. Upload the contents of this folder to any HTTPS static host, for example GitHub Pages, Netlify, Cloudflare Pages, or your own website.
2. Open the resulting HTTPS URL in Chrome on Android.
3. Chrome menu -> Add to Home screen / Install app.
4. After the first load, the calculator works offline via the service worker.

No backend or database is required.
