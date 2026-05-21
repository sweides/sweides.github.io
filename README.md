# sweides.github.io

Personal academic website for Sophie E. Weides — plant ecologist, PhD student at the University of Basel.

Built with [Quarto](https://quarto.org) and deployed via GitHub Pages.

## Structure

```
_quarto.yml         # Site configuration
index.qmd           # Homepage / About
research.qmd        # Research overview
publications.qmd    # Publications list
teaching.qmd        # Teaching experience
cv.qmd              # Full CV
styles/             # Custom SCSS + CSS
assets/             # Images (add profile.jpg here)
.github/workflows/  # GitHub Actions deployment
```

## Local development

```r
# In R or terminal
quarto preview
```

## Deploying to GitHub Pages

The GitHub Actions workflow (`.github/workflows/publish.yml`) automatically renders and deploys whenever you push to `main`.

**One-time GitHub setup:**
1. Go to **Settings → Pages**
2. Set source to **Deploy from a branch**
3. Branch: `gh-pages` / folder: `/ (root)`
4. Save

After the first push, the site will be live at `https://sweides.github.io`.

## Adding a profile photo

Place a photo at `assets/profile.jpg`. Aim for a square crop, at least 400×400px.

## Adding a CV PDF

Export your CV to PDF, save it as `assets/weides_cv.pdf`, and uncomment the download link in `cv.qmd`.
