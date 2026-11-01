# Design: Night Lantern Notes

## Overview
Single HTML file, inline CSS and JavaScript. No build step, no framework,
no backend. This keeps GitHub Pages deployment to one file and the demo
to one screen.

## Architecture
- View: `index.html` renders the form, the search box and the note list.
- Storage: `localStorage` key `night-lantern-notes-v1`, JSON array of
  `{title, body, createdAt}`. Newest first.
- Export: build CSV in the browser, download via a Blob URL, with a UTF-8
  BOM so spreadsheets open Chinese text correctly.

## Components
- Add form: title input, body textarea, add button, export button.
- Search input: filters by title + body, case-insensitive.
- Note item: title, timestamp, body, delete button.

## Visual
Dark indigo background, warm amber accent (lantern light), large touch
targets for phone use. No images, no external assets.

## Testing
Manual checks, matching requirements.md:
1. Add, reload, note still there.
2. Offline (airplane mode / file open), add/search/delete/export work.
3. Export CSV opens correctly with Chinese text.
