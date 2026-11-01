# Chukwuma Maxwell — Portfolio

A static portfolio for **Chukwuma Maxwell** — Python developer, data science and web development.

Built with plain HTML, CSS and JavaScript. No build step, no dependencies. Designed to be hosted directly on GitHub Pages.

## Live site

> Replace this line with the live URL after publishing.
> `https://<username>.github.io/<repository>/`

## Structure

```
.
├── index.html                  # All page content
├── styles.css                  # Design system, layout, responsive rules
├── script.js                   # Menu, project filters, scroll reveals, scrollspy
├── favicon.svg
├── .nojekyll                   # Tells GitHub Pages to serve files as-is
└── assets/
    ├── bg/                     # Hero, contact and social-preview imagery
    ├── cv/Chukwuma_Maxwell_CV.docx
    └── projects/               # Project screenshots
```

## Preview locally

From this folder:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Publish to GitHub Pages

A GitHub **repository** link shows source code, not the website. Share the **Pages** URL instead.

### Option A — user site (recommended)

Repository name: `<username>.github.io`

1. Create the repository on GitHub.
2. Push this folder to the `main` branch.
3. In **Settings → Pages**, set *Source* to **Deploy from a branch**, branch **main**, folder **/ (root)**.
4. The site goes live at `https://<username>.github.io/`.

### Option B — project site

Any repository name, for example `portfolio`:

1. Push this folder to `main`.
2. Enable Pages the same way.
3. The site goes live at `https://<username>.github.io/portfolio/`.

Because all asset paths are relative, both options work without changes.

## Updating

- **CV:** replace `assets/cv/Chukwuma_Maxwell_CV.docx` — the download button keeps working.
- **Projects:** add a screenshot to `assets/projects/`, then copy one `<article class="project-card">` block in `index.html` and update its link, copy and filter (`product`, `commerce` or `community`).
- **Social preview:** `assets/bg/og-image.jpg` is the image shown when the link is shared. Update the `og:image` URL in `index.html` to the absolute Pages URL once the final domain is known.

## Contact

- Email: Chukwumamaxwell7@gmail.com
- GitHub: [Maxc123456789](https://github.com/Maxc123456789)
- LinkedIn: [maxwell-chuks-265b70383](https://linkedin.com/in/maxwell-chuks-265b70383)
- Website: [maxc12.pythonanywhere.com](https://maxc12.pythonanywhere.com)
