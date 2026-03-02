# Jordan Chamberlin – Curriculum Vitae

[![Build and publish CV](https://github.com/chamb244/cv/actions/workflows/build.yml/badge.svg)](https://github.com/chamb244/cv/actions/workflows/build.yml)

**Live CV:** [chamb244.github.io/cv](https://chamb244.github.io/cv/)

---

## About

LaTeX source for my academic CV, automatically compiled and published via GitHub Actions.

## How to update

1. Edit `main.tex` and/or `own-bib.bib` locally
2. Commit and push to `main`:
   ```bash
   git add main.tex own-bib.bib
   git commit -m "Update CV"
   git push origin main
   ```
3. GitHub Actions compiles the PDF and deploys it to GitHub Pages automatically

Check the [Actions tab](https://github.com/chamb244/cv/actions) to monitor the build or debug any LaTeX errors.

## Stack

- **LaTeX** — source format ([`main.tex`](main.tex), [`own-bib.bib`](own-bib.bib))
- **GitHub Actions** — compiles PDF on every push using [`xu-cheng/latex-action`](https://github.com/xu-cheng/latex-action)
- **GitHub Pages** — hosts the compiled PDF at the live link above

> The PDF is auto-generated — do not commit it manually.
