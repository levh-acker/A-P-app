Task notes (Nemotron 3.5 Super VL / OpenRouter edition) - install steps

1. Upload all 6 files, together in one folder, to your host (GitHub Pages: the docs folder),
   replacing the old ones with the same names:
   index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png, apple-touch-icon.png

2. Open the app twice with signal. The first open fetches the update, the second shows it.

3. New in this version:
   - Your AI instructions: in a note's Rough notes box, tap "Your AI instructions" and write how
     you like notes written. Saved on the device, used every time, included in backups.
   - Photo of a task card: tap "Add photo of task card" (up to 4 pages), then "Write up from photo".
     The AI fills title, SEQ, aircraft, date, areas, description, AMM refs and steps.
     Anything read from a photo is listed in the "Check against the AMM" box so you can compare it
     with the card. Never trust a number the AI read until you have checked it on the card.
   - Photos go to the model set in Settings > Photo reading model. Default is the
     free Nemotron 3.5 Super VL, the same model as the main one, because it reads both text and images.

4. Privacy: free OpenRouter models may log what they receive, including photos. Only send task
   cards you are allowed to share.

5. Your API key is entered in Settings only, never in these files.

6. Model: the app now uses NVIDIA's free Nemotron 3.5 Super VL for both text and photos. If you had
   the older defaults saved, they switch to it automatically. Nemotron 3 Ultra and Nemotron 3 Super
   are still in Settings > Model (text only). Reasoning is kept light so replies stay quick.
