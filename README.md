# WordPalette App

A fully static, browser-only brand system generator. A word or local image becomes a deterministic palette, naming territory, slogans, font pairing, design tokens, motion presets, a moodboard and a compact brandbook.

## Run locally

Open `index.html` directly in a modern browser. No install, build command, server, API key or account is required.

For the best clipboard behavior, you can optionally serve the folder locally:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Push these files to a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the repository's main branch and `/ (root)`, then save.

## Privacy and architecture

- Vanilla HTML, CSS and JavaScript only
- No backend, API calls, analytics or external fonts
- Word generation is deterministic and algorithmic
- Names, slogans and prompts are template-based
- Image analysis uses Canvas and k-means locally in the browser
- Preferences and saved palettes use `localStorage`
- PNG and JSON exports are generated on-device

Everything runs in your browser. No images or prompts are uploaded.
