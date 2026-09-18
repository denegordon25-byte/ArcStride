# ArcPilot Web & AI – Static Site

Faithful static rebuild of the original ArcPilot marketing site.

## Structure

```
arcpilot/
├── index.html
├── styles.css
├── script.js
├── favicon.png
├── images/
│   ├── arcpilot-ap-mark-transparent.png
│   ├── arcpilot-sme-website-showcase.png
│   ├── arcpilot-industries.png
│   ├── welford-truck-wash-customer-site.png
│   ├── arcpilot-willow-thread-concept.png
│   ├── arcpilot-oakline-electrical-concept.png
│   ├── arcpilot-elan-aesthetics-concept.png
│   └── dene-gordon-founder.jpeg
└── README.md
```

## Deploy

### GitHub Pages
1. Create a new repository (e.g. `arcpilot-site`).
2. Push the contents of this folder to the `main` branch (or `gh-pages`).
3. Settings → Pages → Source: Deploy from a branch → `main` / root.

### Cloudflare Pages
1. Connect the GitHub repo in Cloudflare Pages.
2. Build settings: Framework preset = None, Build command = (leave empty), Output directory = `/`.
3. Deploy.

No build step required – pure static HTML/CSS/JS.

## Notes
- Contact form is front-end only (shows confirmation). Wire it to Formspree, Netlify Forms, or your own endpoint as needed.
- WhatsApp link points to the original number.
- All original copy preserved.
