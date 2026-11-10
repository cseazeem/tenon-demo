# Tenon: showcase page

A static, single-page showcase of the Tenon manufacturing-operations demo. It's plain HTML with a few screenshots (about 1.2 MB in total), and needs no build step or server.

## Publish on GitHub Pages

1. Create a **public** repository named `tenon-demo`.
2. Upload the *contents* of this folder (`index.html`, `assets/`, this README) so that `index.html` sits at the repo root.
3. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and click **Save**.
4. After a minute or two the page is live at `https://<your-username>.github.io/tenon-demo/`.

For a nice link preview on LinkedIn, replace `YOUR-GITHUB-USERNAME` in the `og:image` tag in `index.html` with your GitHub username.

## Contents

- `index.html`: page, styles and a tiny script for the tour and lightbox (no frameworks)
- `assets/*.webp`: screenshots of the working app
- `assets/og.jpg`: 1200×630 link-preview image

All companies, people and data shown are fictional.
