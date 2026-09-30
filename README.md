# Causal Inference with Scientific Computing

Source for <https://yoonismo.github.io/causal-computing/>, built with [Quarto](https://quarto.org).

## How the site is built

You do not need Quarto on your computer. Every push to `main` triggers `.github/workflows/publish.yml`, which renders the site on GitHub's machines and publishes it to GitHub Pages.

One-time setup: **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Files

| File | Page |
|---|---|
| `index.qmd` | Introduction |
| `installation/index.qmd` | Installation overview |
| `installation/macos.qmd` | Installation on macOS |
| `installation/windows.qmd` | Installation on Windows |
| `week1.qmd` | Week 1 |
| `_quarto.yml` | Site settings and sidebar |
| `references.bib` | Bibliography |

The `_notes/` folder holds private working notes and is excluded from both the site and Git.
