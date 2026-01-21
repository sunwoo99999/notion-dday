# Notion D-Day, Week Widget

![Notion](https://img.shields.io/badge/Notion-black?logo=notion&logoColor=white)

Minimalist D-Day tracker for Notion.
Designed to work as an embed (`/embed`) without database headers or padding.

## Usage

1. Copy the URL.
2. Type `/embed` in Notion and press Enter.
3. Paste the URL and click **Embed link**.
4. **Resize** to remove whitespace.

### 1. Default (July 20, 2026)

https://sunwoo99999.github.io/notion-dday/

### 2. Custom Date

Add `?date=YYYY-MM-DD`.
https://sunwoo99999.github.io/notion-dday/?date=2025-12-25

### 3. Hide Week Count

Add `&week=false`.
https://sunwoo99999.github.io/notion-dday/?date=2025-12-25&week=false

---

## ❓ Troubleshooting

**Widget shows "Click to view content" or a grey box?**
This happens when Notion caches an old version of the link.

1. Select the embed block in Notion.
2. Press **`Ctrl` + `R`** (Windows) or **`Cmd` + `R`** (Mac) to reload Notion.
3. If it still fails, delete the block and re-embed the link.

---

## Deployment

1. Fork this repo.
2. Go to **Settings** > **Pages**.
3. Enable GitHub Pages (Source: `main`).

## Preview

(Add your screenshot here)

## License

MIT License

## Author

Seonwoo Kang
