# Anthyia Consulting

Jekyll site for [anthyiaconsulting.com](https://anthyiaconsulting.com), built for GitHub Pages.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Then open `http://localhost:4000`.

## Deployment

This repository includes:

- `CNAME` for `anthyiaconsulting.com`
- `.github/workflows/pages.yml` for GitHub Pages deployment through GitHub Actions
- A self-contained local Justice theme in `_layouts`, `_includes`, and `assets/css`

In GitHub, set Pages to deploy from GitHub Actions, then push to `main`.
