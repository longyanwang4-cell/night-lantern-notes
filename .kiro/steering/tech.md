# Tech steering

- Static only: one HTML file, inline CSS/JS, no build step.
- No external requests at runtime: no CDN, no fonts, no APIs.
- Storage: browser localStorage only.
- Encoding: UTF-8 everywhere; CSV export includes a BOM for spreadsheets.
- The `.kiro` directory must stay in the repo and must not be gitignored.
