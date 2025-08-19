# Minimal PG-Style Blog

This starter mimics the **structure** of paulgraham.com: a very simple index page listing essays, an archive page, and individual essay pages with a title and date. It uses only plain HTML + a tiny CSS file.

## Files

- `index.html` — homepage listing recent essays (by month/year)
- `archive.html` — all essays grouped by year
- `about.html` — optional “about” page
- `styles.css` — minimal typography and layout
- `essays/hello-world.html` — example essay
- `essays/why-cats-are-funny.html` — example essay
- `essays/_template.html` — copy this to create new essays

## Add a New Essay

1. Copy `essays/_template.html` to `essays/my-new-essay.html`.
2. Edit the `<title>`, `<h1 class="title">`, and the date in `<p class="when">`.
3. Add a link to the new essay in `index.html` and `archive.html` (keep newest at the top).

## Local Preview

Open `index.html` in a browser. For best results (and if you add images), serve locally:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.
