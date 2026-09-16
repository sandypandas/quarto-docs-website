# Docs in Motion

This repository contains a small public Quarto website with three documentation articles on practical writing, maintainable information design, and static site publishing.

## Live directory page

- [Docs in Motion website](https://sandypandas.github.io/quarto-docs-website/)

## Quarto

- [Quarto official website](https://quarto.org/)

## Project structure

- `_quarto.yml` — Quarto site configuration
- `index.qmd` — home page with decorative header image
- `docs/articles/article-1.qmd` — article on planning documentation
- `docs/articles/article-2.qmd` — article on writing clear technical content
- `docs/articles/article-3.qmd` — article on Quarto publishing
- `styles.css` — site styling
- `images/` — article and home page illustration assets

## Local preview

```bash
quarto render
quarto preview
```

## GitHub Pages deployment

This project uses a GitHub Actions workflow to render and deploy the site to GitHub Pages from the repository.
