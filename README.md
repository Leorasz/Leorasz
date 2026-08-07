# Leo Rasmussen — Personal Site

Static site for https://leorasz.github.io/Leorasz/

## Files

- `index.html` — Home / About / Experience / Projects
- `research.html` — Independent study paper page (KaTeX math)
- `style.css` — Styles
- `resume.pdf` — Your resume
- `meiss-paper.pdf` — **You need to add this** (compile your LaTeX or export the PDF)

## How to deploy (GitHub Pages)

1. Make sure the repo is `https://github.com/Leorasz/Leorasz` (or rename it).
2. Push all files in this folder to the `main` branch (root of the repo).
3. Go to the repo on GitHub → **Settings** → **Pages**.
4. Under "Source" choose **Deploy from a branch**.
5. Branch: `main` / folder: `/ (root)` → Save.
6. Wait ~1 minute. Your site will be live at:
   **https://leorasz.github.io/Leorasz/**

## Adding the paper PDF

Compile your LaTeX to PDF and name the file `meiss-paper.pdf`, then put it in the same folder and push.

You can also just drop any PDF and update the links in `research.html` and `index.html` if you prefer a different filename.

## Custom domain (optional)

In the Pages settings you can add a custom domain later. For now the github.io URL is free and fine.
