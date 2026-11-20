# Science Communication for Bioengineers

Course/workshop site built with [Quarto](https://quarto.org), publishing to GitHub Pages.

This site is public. Restricted files live in a UO-only SharePoint folder and are linked from `materials.qmd`. Never commit restricted files to this repository.

## Structure

- `_quarto.yml`: site config (title, navigation, theme)
- `index.qmd`: home page
- `about.qmd`, `schedule.qmd`, `materials.qmd`, `resources.qmd`: content pages
- `styles.css`: small custom style overrides
- `.github/workflows/publish.yml`: GitHub Action that renders the site and deploys it on every push to `main`

## Editing content

Edit any `.qmd` file directly on github.com using Markdown. Commit to `main` and the site rebuilds automatically within a minute or two.

To add a new page:

1. Create a new `.qmd` file (e.g. `contact.qmd`) with a `title:` in its YAML header.
2. Add it to the `navbar` list in `_quarto.yml`.
3. Commit.
