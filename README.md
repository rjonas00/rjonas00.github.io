# raffaeljonas.dev — personal academic site

A minimal, static one-page site. No build step, no framework — just `index.html` and `style.css`.

## Local preview

```bash
python -m http.server 5173
```

Then open http://localhost:5173.

## Deploying with GitHub Pages

1. Create a GitHub repository named **`rjonas00.github.io`** (must match your username exactly for a user site).
2. Push this project to it:

   ```bash
   git remote add origin https://github.com/rjonas00/rjonas00.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. In the repo's Settings → Pages, set the source to the `main` branch, root folder.
4. The site will be live at `https://rjonas00.github.io` within a few minutes.

## Editing content

All content lives directly in `index.html` — there's no CMS or data file. Update the relevant `<section>` and re-deploy by pushing to `main`.
