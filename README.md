# Kian Rigel Perez — Graphics Design Portfolio

A static single-page portfolio built with semantic HTML, modern CSS and vanilla JavaScript, aligned to Kian's uploaded Prelim/Midterm visual direction.

## Run
Open `index.html` directly, or run `python -m http.server 8000` inside this folder. No build process and no runtime packages are required.

## Deploy via GitHub Pages
1. Upload `index.html`, `styles.css`, `script.js` to the root of `kianrigel/graphics-portfolio` (main branch).
2. In GitHub → Settings → Pages, select **Deploy from a branch**, **main**, **/(root)**, then Save.
3. The expected project URL will be `https://kianrigel.github.io/graphics-portfolio/` once GitHub confirms deployment. This URL is not verified live.

## Assets and disclosure
- The project archive contains links/thumbnail URLs for files located in the two user-supplied Google Drive folders.
- To show thumbnails and PDF/video previews to anonymous visitors, their Drive permissions must permit public viewing. Cross-origin streaming of Drive MP4 files may be blocked; the film has an original-Drive fallback.
- The contact form performs client-side validation then opens a **mailto draft without a recipient**. No message is sent automatically. Replace the empty mailto recipient in `script.js` with a verified email address if desired.
- The Selection Sort paper was not located in the given graphics-design folders; do not treat the research card as a quotation from that paper. The original may be connected later.
- Project tools are high-level design discipline tags. Some cannot be verified directly from file contents and should be edited to reflect each project's actual creation process.
- Browser-based Google Fonts require network access. Font fallbacks are provided.

## Source organization
- `index.html` — structure, navigation, sections, accessible modal and form
- `styles.css` — responsive design system, interactions, effects
- `script.js` — project records, filters, modal, video player, validation, cursor and canvas effects
