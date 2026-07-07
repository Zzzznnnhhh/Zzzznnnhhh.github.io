# Nonghai Zhang — Personal Homepage

Static academic homepage (plain HTML/CSS, no build step). Ready for GitHub Pages.

## Preview locally
Just open `index.html` in a browser.

## Deploy to `<username>.github.io`
1. Create a **public** repo named exactly `Zzzzzzzzclock.github.io`
   (replace `Zzzzzzzzclock` with your real GitHub username — the repo name must match your username).
2. Put `index.html` (+ `avatar.jpg`, `cv.pdf`) at the repo root and push:
   ```bash
   cd homepage
   git init && git add . && git commit -m "personal homepage"
   git branch -M main
   git remote add origin https://github.com/<username>/<username>.github.io.git
   git push -u origin main
   ```
3. Your site goes live at `https://<username>.github.io` (usually within a minute).

Alternatively, host it in any repo and enable **Settings → Pages → Source: main branch /(root)**.

## TODO — replace placeholders
- [ ] **`avatar.jpg`** — add your profile photo (square) to this folder (page hides it gracefully if missing).
- [ ] **`cv.pdf`** — drop your CV here so the "CV" link works.
- [ ] **GitHub link** — I used `github.com/Zzzzzzzzclock`; confirm/adjust the username.
- [ ] **Google Scholar** — replace the placeholder `scholar.google.com/` with your profile URL (or remove the link).
- [ ] **arXiv links** — add real paper URLs in the Publications section when available.
- [ ] Review the ByteDance dates (your CV listed 2026.01–present; I placed StepFun as current per your note).

## Notes
- Fonts load from Google Fonts (needs internet; falls back to system fonts offline).
- Accent color is a muted terracotta (a nod to ancient pottery 🏺) — change `--accent` in the `<style>` block to recolor.
