# Personal website

A small static personal website with About, Blog, and Projects views, light and dark themes, and a responsive team photo section.

## Preview

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

Visit http://localhost:8000.

## Add your content

Edit `index.html` directly. No dependencies or build step are required.

- Replace the bracketed introduction, bio, and profile photo placeholders.
- Replace each team photo placeholder with an image and update its caption. Store photos in `images/`, use descriptive `alt` text, and give images `width: 100%; height: auto` to preserve their proportions.
- Add project entries inside `#project-list` and articles inside `#blog-posts` when ready. These containers are intentionally empty.
- Add published article links inside `#latest-posts` when ready.

## Hosting

This repository is ready for static hosting. To use GitHub Pages, enable Pages for the `main` branch at the repository root in Settings → Pages. This step is separate from uploading the source.

Layout adapted from https://aandyw.github.io/. Personal content, team photos, projects, and posts are not copied from the reference.
