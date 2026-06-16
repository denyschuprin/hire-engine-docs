# Hire Engine — User Guide (documentation site)

This folder is a self-contained [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)
site that builds the Hire Engine user guide and publishes it to GitHub Pages.

All content lives in `docs/` as plain **Markdown** — adding or editing a page is
just editing a `.md` file. No HTML, no code.

## Edit the guide

1. Open any file under `docs/` and edit the Markdown.
2. To add a new page: create a `.md` file under `docs/`, then add it to the
   `nav:` list in `mkdocs.yml`.

## Preview locally (optional)

```bash
pip install -r requirements.txt
mkdocs serve
# open http://127.0.0.1:8000
```

## Publish

This is wired to deploy automatically:

1. Push this folder to a **public** GitHub repo as the repo root.
2. In the repo: **Settings → Pages → Build and deployment → Source = GitHub Actions**.
3. Every push to `main` rebuilds and publishes the site via
   `.github/workflows/deploy.yml`.

The live URL will be `https://<account>.github.io/<repo>/`.
