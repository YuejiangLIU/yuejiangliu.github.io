# Yuejiang Liu personal website

A minimal Quarto personal academic website for GitHub Pages.

## Local preview

```bash
quarto preview
```

## Render

```bash
quarto render
```

## Deployment

Push to `master`. GitHub Actions renders the site with Quarto and publishes the built output to the `gh-pages` branch.

In the GitHub repository settings, configure Pages to deploy from the `gh-pages` branch.

## Editing content

- Edit homepage content in `index.qmd`.
- Edit visual styles in `styles.scss`. Quarto copies it to a generated `styles.css` during render.
- Replace the profile image at `images/profile.jpg`.
- Update links in `index.qmd`.
- Update news items in the News section.
- Update selected publications in the Selected Publications section.

No CV file or CV link is included for now.
