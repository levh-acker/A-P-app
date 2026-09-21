Task notes - install steps

1. Upload these files, together in one folder, to any HTTPS web host
   (GitHub Pages, Netlify, Cloudflare Pages all work):
   index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png

2. Open the link on your phone.
   iPhone (Safari): Share, then Add to Home Screen.
   Android (Chrome): menu, then Install app / Add to Home screen.

3. Open the app once with a signal so it can save itself for offline use.

4. AI write-up: open Settings and paste your own Anthropic API key
   (create one in the Anthropic Console and set a low spend limit on it).
   The app works without a key; only the AI write-up needs one.

5. Notes and photos are stored on the phone only. Use Settings > Download backup now and then.

Don't put your API key in these files. Enter it in the app.
If you change index.html later, change CACHE in sw.js (e.g. task-notes-v2) so phones pick up the update.
