# For Koushani ✦

A mobile-first, interactive birthday surprise made with plain HTML, CSS and JavaScript. No backend, login, database, build step, or external audio files required.

## Files
- `index.html` — the complete website and interaction logic
- `assets/koushani-caricature.png` — custom illustrated birthday caricature

## Run locally
Open `index.html` in a modern browser. For best results, serve the folder locally (some browsers limit features for `file://` pages):

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish
**GitHub Pages:** create a repository, upload `index.html` and the `assets` folder, then open **Settings → Pages** and deploy from the main branch/root.

**Netlify:** drag the whole `koushani-birthday` folder into Netlify Drop, or connect the repository.

**Vercel:** import the repository and use the default static deployment settings.

## Audio / voice notes
- Audio is not started until the visitor taps the opening button.
- The music and sound effects are synthesized in-browser with Web Audio; there are no external audio files.
- The voice uses the browser's built-in speech synthesis and prefers Bengali (India) if installed, then Indian English. Voice availability depends on the visitor's browser/device and installed voices. If Bengali is unavailable, it may use the device's default voice.
- The sound toggle can silence music and voice. The final “শুনবি নাকি?” button reads a short birthday message aloud.

## Customization
Edit the Bengali message directly in `index.html`. Replace `assets/koushani-caricature.png` with another image using the same filename if desired.
