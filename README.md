# Brianna Liu — Portfolio

Personal portfolio site. Plain HTML, CSS and JavaScript — no build step.

```
index.html          page content
styles.css          all styling (desktop first, with tablet and phone breakpoints)
script.js           mobile menu, scroll fade-in, footer year
assets/images/      headshot, logos, hobby icons
assets/favicon.svg  browser tab icon
```

## Preview locally

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Publish on GitHub Pages

1. Create a new repository on GitHub. Name it `<your-username>.github.io` if you want the site at `https://<your-username>.github.io`; any other name puts it at `https://<your-username>.github.io/<repo-name>`.
2. Upload everything in this folder (or push it with git).
3. In the repo, go to **Settings → Pages**, set **Source** to “Deploy from a branch”, pick `main` and `/ (root)`, and save.
4. The site goes live in a minute or two at the URL shown on that page.

## Still to fill in

- `assets/Brianna_Liu_CV.pdf` — add your CV with this exact filename (the “Download CV” links point here).
- Artwork “View portfolio” and Cello “I played the cello” links — replace the `#` in `index.html` (marked with `TODO`).
