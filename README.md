# Personal website

A static personal website with an introduction, visual writing, and projects at the bottom of one responsive page. Includes light and dark themes.

## Preview

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

Visit http://localhost:8000.

## Add your content

Edit `index.html` directly. No dependencies or build step are required.

- Replace the bracketed introduction, bio, and profile photo placeholders.
- Replace the clearly marked animated writing placeholder with your own data story. The existing bars are illustrative, not real data. The Play/Pause control demonstrates animation and respects reduced-motion preferences.
- For real stories, include a title, short description, source data, date, and article link. Use responsive SVG, an interactive chart, or a video with controls and a static poster.
- Add project entries inside the empty `#project-list` at the bottom. Add articles inside `#blog-posts`, replacing the layout preview.
- Navigation uses in-page anchors; old `#blog` links redirect to `#writing`.

## Hosting

This repository is ready for static hosting. To use GitHub Pages, enable Pages for the `main` branch at the repository root in Settings → Pages. This step is separate from uploading the source.

Layout adapted from https://aandyw.github.io/. Personal content, projects, and posts are not copied from the reference.
