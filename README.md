# Anushka Chandra — Personal Website

A clean, professional personal portfolio website built with plain HTML, CSS, and vanilla JavaScript. Designed for GitHub Pages hosting.

## Folder Structure

```
├── index.html      ← Main page (all sections)
├── styles.css      ← All styling
├── script.js       ← Minimal JS (navigation, scroll animations)
├── resume.pdf      ← Resume (not linked on site; keep for reference)
└── README.md       ← This file
```

## Local Preview

Open `index.html` directly in a browser, or start a local server:

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Deploy to GitHub Pages

### Option A: User/Org Site (yourname.github.io)

1. **Create a GitHub repository** named exactly `<your-github-username>.github.io`.
2. **Initialize and push:**
   ```bash
   cd /path/to/this/folder
   git init
   git add index.html styles.css script.js README.md
   git commit -m "Initial commit: personal website"
   git branch -M main
   git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```
3. Your site will be live at `https://<your-github-username>.github.io` within a few minutes.

### Option B: Project Site (any repo name)

1. **Create a GitHub repository** with any name (e.g., `portfolio`).
2. **Push code** using the same steps as above.
3. Go to **Settings → Pages** in your repo.
4. Under "Source", select **Deploy from a branch**, choose `main`, folder `/ (root)`.
5. Your site will be at `https://<your-github-username>.github.io/portfolio/`.


## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — custom properties, Grid, Flexbox, clamp(), media queries
- **Vanilla JS** — Intersection Observer for scroll reveals, mobile nav
- **Google Fonts** — Cormorant Garamond + Inter
- **No frameworks, no build tools, no dependencies**

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). Includes `prefers-reduced-motion` support and print styles.

---

*This site was vibe-coded with [Claude Opus 4.6](https://www.anthropic.com) via GitHub Copilot.*
