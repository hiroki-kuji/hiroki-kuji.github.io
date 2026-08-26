# Hiroki Kuji

Source for [Hiroki Kuji's academic website](https://hiroki-kuji.github.io/).

The site is built with [Jekyll](https://jekyllrb.com/) and the
[al-folio](https://github.com/alshedivat/al-folio) theme.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in a browser.

## Deployment

Pushing to `main` runs the GitHub Actions workflow in
[.github/workflows/deploy.yml](.github/workflows/deploy.yml) and deploys the
generated site to GitHub Pages.

The theme source remains covered by the included [MIT License](LICENSE).
