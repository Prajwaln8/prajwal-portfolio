# Prajwal Portfolio

Personal portfolio/resume website for **Prajwal N**, built as a lightweight static site using React (via CDN) and custom CSS.

## What's in this project
- Single-page personal portfolio (`index.html`)
- Styling for responsive split-layout design (`css/style.css`)
- Local image assets under `img/`

## Run locally
Because this site is static, you can open `index.html` directly in your browser.

For a simple local server:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Recent updates
- Added a new **Highlights** section in the profile content.
- Improved external link safety/accessibility using `rel="noreferrer"` and `aria-label`s.
- Added a **Last updated** marker in the right panel.