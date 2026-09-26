Task notes (Nemotron 3 Ultra / OpenRouter edition) - install steps

1. Upload these files, together in one folder, to any HTTPS web host
   (GitHub Pages, Netlify, Cloudflare Pages all work):
   index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png

   If you already have a GitHub Pages repo set up (e.g. a "docs" folder),
   just replace the old files with these - same names, same folder.

2. Open the link on your phone.
   Android (Chrome): menu, then Install app / Add to Home screen.
   iPhone (Safari): Share, then Add to Home Screen.

3. Open the app once with a signal so it can save itself for offline use.

4. AI write-up: open Settings and paste a free OpenRouter API key
   (create one at openrouter.ai/keys - sign in with Google, GitHub or
   email, no credit card needed). The app is set to NVIDIA's
   Nemotron 3 Ultra, which is free to use on OpenRouter.

   Why OpenRouter and not NVIDIA directly: NVIDIA's own API
   (build.nvidia.com) doesn't allow a webpage to call it directly from
   the phone's browser - it blocks that for security reasons. OpenRouter
   sits in front of it and does allow this, and offers the same model
   for free, so it's the practical way to use Nemotron from an app like
   this one with no backend server.

5. Notes and photos are stored on the phone only. Use Settings > Download backup now and then.

Same features as the other versions: Date, Areas affected, Findings,
status filter, Duplicate note, and Share note.

Don't put your API key in these files. Enter it in the app.
If you change index.html later, bump CACHE in sw.js (e.g. task-notes-v2) so phones pick up the update.
