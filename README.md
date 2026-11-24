# Daniela Dominguez — Engineering Portfolio

Aerospace & Mechanical Engineering · New Mexico State University

## Folders
- `index.html` — the whole site (design, animations, interactive demos)
- `data/site.json` — all the text and the list of photos/videos for every page
- `data/mars-data.json` — NASA Horizons data for the Mars explorer
- `img/` — photos and renders
- Videos are hosted on Cloudinary (cloud `vtvazkbc`); `data/site.json` links to them
- `files/` — résumé PDF

## Editing
- Change text: edit `data/site.json`.
- Add a photo: put it in `img/`, then reference it in `data/site.json` as `"src": "img/your-file.jpg"`.
- Add a video: upload it to Cloudinary, copy its link, and use it as the `"src"` with `"kind": "video"`.
  Adding `q_auto/` after `/upload/` in the link makes Cloudinary compress it automatically.
- Keep the text copy inside `index.html` (the `site-fallback` block) in sync if you
  want the very first paint to match; the site reloads from `data/site.json` anyway.

## Preview
Open it through GitHub Pages or a local server (`python3 -m http.server`).
Double-clicking `index.html` won't load the data files.
