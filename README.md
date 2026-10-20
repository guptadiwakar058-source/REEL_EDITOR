# CutSync Studio — Instagram & YouTube Video Analyzer & Template Remixer

Zero-backend Progressive Web App (PWA) for reverse-engineering Instagram Reels, YouTube Shorts, and videos into editable timeline templates with custom gallery media replacement.

## Repository Files
- `index.html` — Complete self-contained CutSync Studio web application (HTML5 Canvas 60FPS compositor, Web Audio BPM beat synth, speed-ramp curve editor, VFX stack, 3D `.CUBE` LUT generator, and local video frame analyzer).
- `manifest.json` — Web App Manifest for standalone full-screen installation.
- `sw.js` — Offline caching Service Worker.

## How to Host on GitHub Pages
1. Create a new GitHub repository and upload or paste `index.html`, `manifest.json`, and `sw.js` into the root branch (`main`).
2. Go to **Settings → Pages** in your GitHub repository.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and click **Save**.
4. Your app will be live at `https://<your-username>.github.io/<your-repo>/`.

## How to Install on iOS iPhone
1. Open your GitHub Pages URL in **Safari** on your iPhone.
2. Tap the **Share** button at the bottom of Safari and tap **Add to Home Screen**.
3. Launch **CutSync** from your Home Screen — it runs full-screen and connects directly to your iPhone Photo Library / Camera Roll when replacing cuts.
