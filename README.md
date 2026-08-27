# Utility Hub GitHub Pages Site

Upload the contents of this folder to the root of a GitHub Pages repository. Keep `index.html`, the `categories/` and `tools/` folders, and the `assets/` folder together so relative links and shared JavaScript/CSS resolve correctly.

The homepage is `index.html`. Each card links to a dedicated tool page. PDF processing loads the qpdf WebAssembly package from jsDelivr on first use; all selected files remain in the browser. Reminder contacts and task data use browser localStorage, and exports pause for the five-star confirmation gate.

For a fully local PDF deployment, replace the jsDelivr import in `assets/app.js` with a self-hosted compatible pdfstudio bundle and its WebAssembly assets.
