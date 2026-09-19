TELUGU BIBLE — INSTALLABLE PWA
==============================

WHAT'S IN THIS FOLDER
  index.html            — the complete app (all 66 books inside)
  manifest.webmanifest  — app details & icons
  sw.js                 — service worker for offline use after install
  icon-192.png, icon-512.png, icon-512-maskable.png, apple-touch-icon.png
  README.txt            — this file

HOW TO MAKE IT INSTALLABLE (one-time, ~5 minutes)
The app must be online ONCE so browsers can install it. Pick any free option:

Option A — Netlify Drop (easiest, no account needed to try)
  1. Go to  https://app.netlify.com/drop
  2. Drag this whole folder onto the page
  3. You get a link like https://something.netlify.app — open it on your phone
  4. In Chrome: menu (⋮) → "Add to Home screen" / "Install app"

Option B — GitHub Pages (free, permanent)
  1. Create a free account at github.com and a new repository (e.g. telugu-bible)
  2. Upload ALL files from this folder to the repository
  3. Settings → Pages → Source: "main branch" → Save
  4. Your app goes live at https://YOURNAME.github.io/telugu-bible/
  5. Open that link on your phone → Chrome menu → "Add to Home screen"

Option C — Cloudflare Pages
  1. Go to pages.cloudflare.com, sign up free
  2. "Create a project" → "Direct Upload" → drag this folder
  3. Open the link on your phone → install as above

AFTER INSTALLING
  The app works fully offline — no internet needed ever again.
  Your themes, verse links and edits are stored on your device.
  Use "More → Save backup" regularly to keep a copy of your data.

TO UPDATE THE APP LATER
  Replace index.html on your hosting site. Users see the new version
  after reopening (the service worker refreshes in the background).

NOTES
  Bible text: public-domain classic Telugu translation (Bible-Database project)
  Theme icons: Font Awesome Free (CC BY 4.0, fontawesome.com)
  This is not the NIV translation and is not affiliated with any publisher.
