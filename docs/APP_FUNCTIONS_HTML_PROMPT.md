# Optional: Make APP_FUNCTIONS easy to read in a browser

Markdown tables can be hard to read. This optional step has Claude turn
docs/APP_FUNCTIONS.md into a clean web page you can open in any browser.

## Paste this into Claude (in VS Code)

```
Read docs/APP_FUNCTIONS.md. Create docs/app-functions.html — a single,
self-contained web page that shows the same information in a clean,
easy-to-read layout.

Rules:
- One file only. No outside scripts, fonts, or images.
- Show the "Last updated" wave and date at the top.
- Color the Status column: green = Working, yellow = Partly working, red = Broken.
- Make it readable on a phone.
- Do not add or change any information. Only show what is in APP_FUNCTIONS.md.
```

## How to open it
Find docs/app-functions.html in VS Code's file list. Right-click it and choose
"Reveal in Finder" (Mac) or "Reveal in File Explorer" (Windows). Double-click it.

## Keep it fresh
APP_FUNCTIONS.md is the real source. Ask Claude to rebuild the HTML page
at the end of each wave, right after it updates APP_FUNCTIONS.md.
