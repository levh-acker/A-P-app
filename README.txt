Task notes (Nemotron 3 Ultra / OpenRouter edition) - install steps

1. Upload these files, together in one folder, to any HTTPS web host
   (GitHub Pages, Netlify, Cloudflare Pages all work):
   index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png
   Already have it on GitHub Pages? Replace all 6 files, same names, same folder.

2. Open the link on your phone and add it to the Home screen
   (Android Chrome: menu, Install app. iPhone Safari: Share, Add to Home Screen).

3. After an update, open the app twice with signal: the first open fetches the
   new version in the background, the second open shows it. (sw.js in this
   bundle has a new cache name, so phones pick the update up on their own.)

4. AI write-up: open Settings and paste your API key. Keys are entered in the
   app only, never in these files.

5. Notes and photos stay on the phone only. Use Settings > Download backup now and then.

What's new in this version:
- SEQ box, Steps (was Sequence), Folders (create, rename, delete, file notes into them), Filter and sort panel (status, folder, area, aircraft, date range) and sorting by last edited, date, title or SEQ. Filters and sort are saved on the device and come back when you reopen the app.
- Note: the AI still fills description, AMM reference and steps only. SEQ, folder,
  date, areas and findings are always yours.
