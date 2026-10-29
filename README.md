# Portfolio Site

A plain HTML/CSS/JS recreation of your Replit portfolio — no Node/npm required, since this Mac only has Python.

## Run it locally

```bash
cd "/Users/aarushichugh/Downloads/Claude work/portfolio-site"
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser.

## Add your real assets

- Drop your headshot in as `headshot.jpg` (shows a placeholder initial until then).
- Drop your resume PDF in as `resume.pdf` (the "Download resume" buttons link to it).
- Update the LinkedIn and Diaspora Health URLs in `index.html` (search for `href="https://www.linkedin.com/"` and `diasporahealth.com`) to the real links.

## Files

- `index.html` — all page content/structure
- `style.css` — layout, colors, typography
- `script.js` — active nav-link highlighting on scroll

## Deploying

Since it's static files, you can host it for free on GitHub Pages, Netlify, Vercel, or Cloudflare Pages — just upload this folder.
