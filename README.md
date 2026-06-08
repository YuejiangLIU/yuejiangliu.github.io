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

Push to `main`. GitHub Actions renders the site and deploys `_site/` to GitHub Pages.

In the GitHub repository settings, configure Pages to deploy from GitHub Actions.

## Editing content

- Edit homepage content in `index.qmd`.
- Edit visual styles in `styles.scss`. Quarto copies it to a generated `styles.css` during render.
- Replace the profile image at `images/profile.jpg`.
- Update links in `index.qmd`.
- Update news items in the News section.
- Update selected publications in the Selected Publications section.

No CV file or CV link is included for now.
