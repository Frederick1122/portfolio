# Fedor Zaletov — Portfolio

Static one-page portfolio for GitHub Pages.

## Local preview

Open `index.html` in a browser.

## Before publishing

Search inside `index.html` and replace:

- `YOUR_EMAIL_HERE`
- RoadCraft contribution placeholder
- project/media placeholders
- project links, if desired

## Publish to GitHub Pages

Create an empty public repository on GitHub, for example:

`fedor-portfolio`

Then from this folder run:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/fedor-portfolio.git
git push -u origin main
```

Then on GitHub:

**Settings → Pages → Build and deployment → Source: Deploy from a branch**

Choose:

- Branch: `main`
- Folder: `/ (root)`

Save.

The site will be available at:

`https://YOUR_GITHUB_USERNAME.github.io/fedor-portfolio/`

## Optional custom domain

Later you can connect a domain such as `fedorzaletov.dev` in:

**Settings → Pages → Custom domain**
