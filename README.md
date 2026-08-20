# Cecilia Xing — Personal Portfolio

This is the source for [xxy-08.github.io](https://xxy-08.github.io/). It is a
plain static website, so it does not need a backend, database, or paid hosting
service.

## How to update the website

You can edit everything directly on GitHub:

1. Open `index.html` and click the pencil icon.
2. Change the text you want, then click **Commit changes**.
3. GitHub Pages will publish the update automatically.

Common edits:

- Main text, experience, education, projects, and links: `index.html`
- Colors, spacing, fonts, and mobile layout: `styles.css`
- Main portrait: replace `cecilia-portrait.jpg` with a file using the same name
- About photo: replace `cecilia-about.jpg` with a file using the same name
- Résumé: replace `Cecilia-Xing-Resume.pdf` with a file using the same name
- Social preview: replace `og.png` with a file using the same name

## Enable GitHub Pages

In the repository, open **Settings → Pages**. Under **Build and deployment**,
select **Deploy from a branch**, choose `main` and `/ (root)`, then save.

The public address will be:

`https://xxy-08.github.io/`

## Local preview (optional)

Opening `index.html` directly works for most edits. If you have Python installed,
you can also run `python -m http.server 8000` in this folder and visit
`http://localhost:8000`.
