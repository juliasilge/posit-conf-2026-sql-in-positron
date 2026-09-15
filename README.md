# SQL as a first-class language in your data science IDE

Companion website for the [posit::conf 2026](https://pos.it/conf) talk by Brian Lambert & Julia Silge. A single-page walkthrough of the talk with recordings of each demo:

- Connect
- Explore
- Iterate
- Understand 

Built with [Quarto](https://quarto.org) and themed with the Posit [brand.yml](https://quarto.org/docs/authoring/brand.html) in `_brand/`. Demo videos live in `videos/` and are checked in directly (GitHub Pages doesn't serve Git LFS content).

## Develop

```bash
quarto preview   # live preview while editing
quarto render    # render to _site/
```

## Publish

The site is published to GitHub Pages from the `gh-pages` branch:

```bash
quarto publish gh-pages
```
