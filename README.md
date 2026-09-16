# M. P. Siva — Portfolio

Personal portfolio site. Single static HTML file, no build step, no dependencies.

```
index.html          the whole site (HTML + CSS inline)
assets/profile.webp profile photo, circular, transparent background
assets/profile.png  same photo as PNG, if you ever need a fallback
```

## Host it on GitHub Pages

1. Create a new repository named **`mpsiva26082002.github.io`**.
   The name matters — using your username makes the site live at
   `https://mpsiva26082002.github.io` with no extra path.

2. Upload these files (drag and drop works, or use git):

```bash
git init
git add .
git commit -m "Portfolio site"
git branch -M main
git remote add origin https://github.com/mpsiva26082002/mpsiva26082002.github.io.git
git push -u origin main
```

3. In the repo, open **Settings → Pages**. Under "Build and deployment",
   set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**.
   Save. The site goes live in about a minute.

If you name the repo something else (say `portfolio`), the site lives at
`https://mpsiva26082002.github.io/portfolio/` instead. Everything else is the same.

## Editing

Open `index.html` in VS Code. The CSS sits in the `<style>` block at the top;
the colours are all CSS variables under `:root`, so changing `--gold`
(currently the blue `#2E90FA`) recolours the whole page.

To swap the photo, replace `assets/profile.webp` with a file of the same name.
