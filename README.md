# Mohamed Bashir — Portfolio

Personal portfolio of **Mohamed Bashir**, Backend Developer working with .NET Core, microservices, and cloud across transportation, government, and finance sectors.

Live: _add your GitHub Pages URL here once deployed_

## Stack

Single-file static site. Pure HTML + CSS + vanilla JavaScript. No build step, no dependencies.

- Typography: **Fraunces** (editorial serif) + **Inter** (sans body) from Google Fonts
- Editorial light theme — warm cream background `#F2EFE8`, deep-sage accent `#3F4F2E`
- Two-row scrolling marquee of capabilities
- Numbered capability sections (01–04)
- Featured work cards with cursor-following gradient
- Editorial experience timeline
- Big italic name signature in the footer
- Respects `prefers-reduced-motion`
- SEO meta tags + inline SVG favicon
- WAI-friendly focus styles and `rel="noopener noreferrer"` on external links

## Run locally

Just open `index.html` in a browser, or serve the folder:

```bash
# Python
python -m http.server 8080
# Node
npx serve .
```

Then visit `http://localhost:8080`.

## Deploy on GitHub Pages

1. Push this repo to GitHub.
2. Repository → **Settings → Pages**.
3. Source: **Deploy from a branch**, Branch: `main` / root.
4. Wait ~1 minute. Your site will be live at `https://<user>.github.io/<repo>/`.

## Customising

- **Photo**: replace the `MB` block in the About section's `.about-photo` with an `<img src="photo.jpg" alt="Mohamed Bashir" />` — the round 4:5 frame already exists in CSS.
- **Accent color**: change `--accent` in `:root` (default deep sage `#3F4F2E`).
- **Copy / projects**: all content lives inside `index.html` — no JSON or build config to chase.

## Contact

- Email: mohamed.basher.daoud@gmail.com
- LinkedIn: [linkedin.com/in/mohamed-basher](https://linkedin.com/in/mohamed-basher)
- GitHub: [github.com/mohamedbashir](https://github.com/mohamedbashir)

---

© 2026 Mohamed Bashir
