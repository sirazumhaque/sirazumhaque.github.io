# Sirazum Munira Haque — Academic Website

A simple static academic website designed for GitHub Pages.

## Files

- `index.html` — homepage
- `research.html` — research page
- `teaching.html` — teaching page
- `style.css` — design and mobile formatting
- `files/CV_Sirazum_Haque.pdf` — CV
- `assets/` — add your professional photo here as `headshot.jpg`

## Add your photo

1. Put your professional photo in `assets/`.
2. Rename it `headshot.jpg`.
3. Open `index.html`.
4. Replace the `photo-placeholder` block with:

```html
<img src="assets/headshot.jpg" alt="Sirazum Munira Haque">
```

## Publish

Create a GitHub repository named exactly:

`YOUR-GITHUB-USERNAME.github.io`

Upload all website files to the root of that repository.

Then go to:

Settings → Pages → Build and deployment → Source → Deploy from a branch

Choose:

- Branch: `main`
- Folder: `/(root)`

Save.

Your site will be:

`https://YOUR-GITHUB-USERNAME.github.io/`

## Later

After the GitHub version works:
1. Buy your custom domain.
2. Add it under GitHub Settings → Pages → Custom domain.
3. Configure the Squarespace DNS records.
4. Enable Enforce HTTPS.
