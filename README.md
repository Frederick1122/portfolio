# Fedor Zaletov — Portfolio

Static one-page portfolio for GitHub Pages.

## Local preview

Open `index.html` in a browser.

## Content

The page is ready with:

- English/Russian language switching based on browser locale, with manual override
- project media in `images/`
- project, Steam, itch.io, LinkedIn, Telegram and email links
- responsive layout, accessibility focus states and reduced-motion support

To preview media and the language switcher locally, serve the folder over HTTP:

```bash
python -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

Before publishing, verify that all project descriptions and media are approved for public use.

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
