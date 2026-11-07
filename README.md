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
- Writing is a list in `#blog-posts`: each row has a small animated preview, title, and description. All entries are labeled placeholders; animations do not represent real data. Hover over a preview to animate it. It pauses when the pointer leaves. Touch screens and reduced-motion preferences get still previews.
- Projects are listed beneath writing in `#project-list`. Each preview and title opens an accessible video placeholder dialog. No demo videos are included yet. Replace the shared placeholder with the selected project's video, using native `controls`, `playsinline`, and a poster; pause playback when the dialog closes.
- Replace the bracketed article and project titles and descriptions with real content, and edit the linked placeholder pages in `writing/` when the stories are ready.
- Navigation uses in-page anchors; old `#blog` links redirect to `#writing`.

## Hosting

This repository is ready for static hosting. To use GitHub Pages, enable Pages for the `main` branch at the repository root in Settings → Pages. This step is separate from uploading the source.

Layout adapted from https://aandyw.github.io/. Personal content, projects, and posts are not copied from the reference.
