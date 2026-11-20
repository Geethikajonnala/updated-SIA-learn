# Learn Quantum

A standalone interactive-book style learning experience for quantum computing. Built with semantic HTML, CSS, and vanilla JavaScript so it can later be integrated into the SIA LMS Portal without bringing along a framework dependency.

## Run locally

Serve the project folder with a static HTTP server before opening it:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

Do not open `index.html` directly as a `file://` URL. The interactive 3D previews load JavaScript modules, which browsers block when the page is opened from the filesystem.

## Structure

- `index.html` - accessible application shell and layout regions
- `styles.css` - responsive visual system and interactive component styles
- `app.js` - curriculum data, routing, interactive demos, quiz, search, and local progress tracking
