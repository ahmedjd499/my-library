My Library - installable PWA

1. Host this folder over HTTPS (Netlify Drop, Vercel, GitHub Pages, Cloudflare Pages...).
   Or test locally: `npx serve .` then open http://localhost:3000
2. Open the site in Chrome/Edge (Android/desktop) or Safari (iOS: Share > Add to Home Screen)
   and choose Install / Add to Home Screen.
3. Open it once online so pdf.js gets cached; after that it works fully offline.
Your books stay in the browser's local storage (IndexedDB) on the device.
