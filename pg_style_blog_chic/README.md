# Minimal PG-Style Blog (Chic Landing)

This version adds a **banner** and small **thumbnails** on the landing page while keeping the simple Paul Graham–style structure.

## Files

- `index.html` — landing page with banner + thumbnails
- `archive.html` — all essays grouped by year (text-first)
- `about.html` — about page
- `styles.css` — minimal typography/layout
- `images/` — placeholder images (`banner.jpg`, `cats-thumb.jpg`, `hello-thumb.jpg`)
- `essays/hello-world.html` — example essay
- `essays/why-cats-are-funny.html` — example essay
- `essays/_template.html` — copy this for new essays

## Add a New Essay

1. Copy `essays/_template.html` to `essays/my-new-essay.html`.
2. Edit the `<title>`, `<h1 class="title">`, and the date in `<p class="when">`.
3. Add a list item to `index.html` (with a thumbnail in `images/`) and a link in `archive.html`.

## Replace Images

Drop your own images into `images/`:
- `banner.jpg` – 1440×480 recommended
- `*-thumb.jpg` – 300×300 recommended

Tip: Keep each file ≤ 200 KB for fast loads.
