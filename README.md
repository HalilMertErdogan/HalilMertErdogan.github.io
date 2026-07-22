# Halil Mert Erdoğan – Academic Website

This is a static, responsive academic website designed for GitHub Pages.

## Before publishing

1. Open `index.html`.
2. Replace `YOUR-EMAIL@example.com` with your real email address.
3. Replace the Google Scholar, ORCID and ResearchGate links.
4. Add your CV PDF to the `assets` folder with this exact filename:
   `Halil-Mert-Erdogan-CV.pdf`
5. Replace the portrait placeholder if desired.

## Adding a portrait

Put your portrait inside `assets` as `portrait.jpg`.

Then replace this block in `index.html`:

```html
<div class="portrait-placeholder">
  <span>HME</span>
  <small>Replace with portrait</small>
</div>
```

with:

```html
<img class="portrait-placeholder" src="assets/portrait.jpg" alt="Portrait of Halil Mert Erdoğan">
```

## GitHub Pages publishing

Create a repository named:

`YOUR-USERNAME.github.io`

Upload all files and folders from this package to the root of the repository.

Then open:

Settings → Pages → Build and deployment → Source → Deploy from a branch

Choose:

Branch: `main`
Folder: `/ (root)`

Save. Your site address will be:

`https://YOUR-USERNAME.github.io`
