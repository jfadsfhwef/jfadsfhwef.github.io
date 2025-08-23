# BeC — Reading Paper Blog

This repo powers `https://jfadsfhwef.github.io/` — a lightweight static blog for paper readings, personal comments, and reproduction notes by **BeChal Shum**.

## Structure

- `index.html`: homepage and post list
- `assets/styles.css`: global styles (responsive, dark theme)
- `assets/icon.jpeg`: site icon (place the provided image here)
- `posts/YYYY-MM-DD-slug.html`: individual post pages

## Add a new post

1. Duplicate an existing file in `posts/`, e.g. `posts/2025-02-23-sida.html`.
2. Update the `<title>`, headings, content, and dates.
3. Add a link in the post list inside `index.html` under the `Latest readings` section.
4. Commit and push to `main` — GitHub Pages will update automatically.

## Icon

Place your desired blog icon at `assets/icon.jpeg`. The homepage preloads this path.

## Local preview

Open `index.html` directly in a browser, or serve with a simple local server:

```bash
cd /Users/hinglingshum/Documents/web/jfadsfhwef.github.io
python3 -m http.server 8000
# then open http://localhost:8000
```

## License

Content © BeChal Shum. Code is MIT.
