# OriginTag Website

Landing page for [OriginTag](https://github.com/reyghifari/OriginTag) — digital passports for physical goods on BNB Chain.

Plain HTML + CSS, no build step.

## Run locally

```bash
python3 -m http.server 8080
```

Open http://localhost:8080.

## Deploy

Any static host works:

- **GitHub Pages** — Settings → Pages → deploy from branch `main`, folder `/ (root)`.
- **Vercel / Netlify** — import the repo, no build command, output directory `.`.

## Structure

```
index.html          page content
styles.css          styles (tokens match the Android app theme)
assets/logo.svg     logo / favicon
assets/logo.png     social preview image
assets/screens/     app screenshots in phone frames
assets/demo.mp4     demo video (2:20) + demo-poster.jpg
```

The Android button links to the APK on Google Drive (update the link in both `.store` buttons for new versions). The iOS button stays disabled until the app ships.
