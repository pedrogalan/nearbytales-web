# nearbytales-web

Marketing website for the [Nearby Tales](https://nearbytales.app) mobile app — a hands-free audio city guide.

Plain static HTML, hosted on GitHub Pages. No build step.

## Structure

```
index.html        ← the whole site
assets/
  landing-hero.jpg
  nearby-tales-mark.png
```

## Local preview

Open `index.html` directly in a browser, or use any static server:

```bash
npx serve .
```

## Deploy (GitHub Pages)

1. Push to `main`
2. Go to **Settings → Pages → Source**: Deploy from branch → `main` → `/ (root)`
3. The site will be live at `https://<your-username>.github.io/nearbytales-web/`
