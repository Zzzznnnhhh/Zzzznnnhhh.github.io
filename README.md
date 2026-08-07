# Nonghai Zhang — Personal Homepage

Static academic homepage (plain HTML/CSS, no build step). Ready for GitHub Pages.

## Preview locally
Just open `index.html` in a browser.

## Deploy to `Zzzznnnhhh.github.io`
1. Create a **public** repo named exactly `Zzzznnnhhh.github.io`.
2. Put `index.html` (+ `avatar.jpg`, `cv.pdf`) at the repo root and push:
   ```bash
   cd homepage
   git init && git add . && git commit -m "personal homepage"
   git branch -M main
   git remote add origin https://github.com/Zzzznnnhhh/Zzzznnnhhh.github.io.git
   git push -u origin main
   ```
3. Your site goes live at `https://Zzzznnnhhh.github.io` (usually within a minute).

Alternatively, host it in any repo and enable **Settings → Pages → Source: main branch /(root)**.

## TODO — replace placeholders
- [ ] **`avatar.jpg`** — add your profile photo (square) to this folder (page hides it gracefully if missing).
- [ ] **`cv.pdf`** — drop your CV here so the "CV" link works.
- [x] **GitHub link** — set to `github.com/Zzzznnnhhh`.
- [ ] **Google Scholar** — replace the placeholder `scholar.google.com/` with your profile URL (or remove the link).
- [ ] **arXiv links** — add real paper URLs in the Publications section when available.
- [x] **Experience dates** — StepFun starts in 2026.05; ByteDance ends in 2026.05.

## Notes
- Fonts load from Google Fonts (needs internet; falls back to system fonts offline).
- Accent color is a muted terracotta (a nod to ancient pottery 🏺) — change `--accent` in the `<style>` block to recolor.
