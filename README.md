# Kesline Jean Baptiste — Academic Portfolio

A complete static, responsive personal academic website inspired by clean editorial research portfolios. Built with plain HTML, CSS and JavaScript; no install or build step.

## Preview

Open `index.html` in a web browser. For consistent local links, run `python3 -m http.server 8000` from this folder and visit http://localhost:8000.

## Publish to GitHub Pages

1. Create a new public GitHub repository (e.g. `kesline-portfolio`).
2. Upload the files at this folder's root (not inside an extra nested folder).
3. In repository Settings → Pages, choose **Deploy from a branch**, `main`, `/ (root)`, and Save.
4. Your site will be at `https://YOUR_USERNAME.github.io/kesline-portfolio/`. If you create a repository named `YOUR_USERNAME.github.io`, its URL will be `https://YOUR_USERNAME.github.io/`.

## Important before publishing

- Replace `YOUR_EMAIL@example.com` everywhere with your actual contact email.
- Confirm the LinkedIn profile URL in the files; the project currently uses a profile link from conversation context.
- Verify claims, dates, and roles on `cv.html`, `research.html` and `publications.html`. No peer-reviewed publications have been invented.
- Blog posts under `blog/` are **drafts** and should be personalized before being presented as published writing.
- Add your CV PDF to `assets/cv.pdf` and optionally link it on `cv.html`. The existing CV page supports Print → Save as PDF.
- Optional: replace the monogram on the homepage with a portrait.
- Add exact repo URLs for all projects when ready.

## Customize design

Edit `assets/style.css` variables near the beginning to change colors. Content is editable directly in each `.html` file. The project filter in `projects.html` is powered by `assets/script.js`.
