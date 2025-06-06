
DYG Physiotherapy – Maintainable Site Deployment

========================
📦 DIRECTORY STRUCTURE
========================
- includes/: Contains reusable header and footer HTML
- assets/css/: Stylesheets
- assets/js/: JavaScript for dynamic includes
- assets/images/: Placeholder images (gallery, logos)
- docs/: Downloadable PDF documents
- *.html: Main and child pages using shared includes

========================
🛠️ TO EDIT OR EXTEND
========================
1. Open any .html page in a text/code editor.
2. Content inside the <main>...</main> tag is unique to that page.
3. Header and footer are automatically included from /includes/.

========================
🚀 TO PREVIEW LOCALLY IN VSCODE
========================
1. Open the folder in VSCode.
2. Install the "Live Server" extension by Ritwick Dey (if not already installed).
3. Right-click `index.html` and select **"Open with Live Server"**.
4. Your default browser will open a live preview of the site.
5. Edits are auto-refreshed while Live Server is running.

Alternative (no VSCode):
1. Open a terminal in the folder
2. Run: `python3 -m http.server 8000`
3. Go to: http://localhost:8000 in your browser

========================
📝 TO DEPLOY TO HOSTING
========================
- Upload the entire folder (HTML + assets + includes)
- Ensure your host supports JS if using include.js
- OR use server-side includes if available

========================
📎 TO REPLACE PLACEHOLDERS
========================
- Replace image files in /assets/images/
- Replace docs in /docs/
- Edit each HTML page’s <main> content area
- Update Formspree and Elfsight embed codes if applicable
