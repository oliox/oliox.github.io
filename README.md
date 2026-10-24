# Personal academic website

## Setup (GitHub Pages)

1. Put these files at the **root** of your GitHub Pages repository
   (`index.html`, `style.css`, `assets/`, `.nojekyll`).
2. Commit and push to `main`.
3. On GitHub: **Settings > Pages > Build and deployment**, choose
   **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
4. After a minute or two the site is live at `https://your-username.github.io/`.

## Customize

- **Text:** edit `index.html`. Everything in `[brackets]`, `Your Name`, and the
  `#` links are placeholders.
- **Portrait:** add your photo as `assets/portrait.jpg` and change the `src` on
  the `<img class="portrait">` line in `index.html`. A square crop works best.
- **CV:** add your PDF as `assets/cv.pdf` (or delete the CV link).
- **Add a publication or project:** copy an existing `<li>...</li>` block inside
  the relevant list and edit it.
- **Style:** colors, font size, and spacing are at the top of `style.css`.

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` in this folder
and visit `http://localhost:8000`.
