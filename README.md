# Electrical Services Survey App – Version 2.6

## Version 2.6 updates
- **Comment placement** now opens the same full-screen drawing placement view as Symbol. Tap the drawing to position a comment, enter the text, and save it.
- Removed the non-functioning PDF page navigation buttons. Import each survey sheet as its own PDF drawing using **Add PDF**.
- Removed the four quick-access symbol buttons below Done / Undo / Redo. Symbols remain available through **+ Symbol** and the full-screen symbol selector, and can still be maintained in **Edit symbol library**.
- Added **Audio Visual** and **Call Systems** as service categories in the symbol library and placement filters, each with its own colour.
- Symbol descriptions are now stored with newly placed symbols to keep the exported symbol key accurate.

## Retained from version 2.5
- Standard Photo and Panoramic Photo selection.
- Sequential three-digit photo references (001, 002, 003, etc.) shown on drawing pins and in the photo register.
- PDF export containing the marked-up drawing, symbol key and photo register with embedded photographs.
- Project backup including photograph files.
- Existing drawing, symbol placement, rotation, comment, undo/redo, and pan/zoom functionality.

## Deployment
Extract the ZIP and deploy the `electrical-survey-app` folder to Netlify Drop. PDF.js and pdf-lib are loaded from CDNs and require internet access. Survey data is stored locally in the browser; export project backups regularly.

**Note:** Import each individual survey sheet as a separate PDF drawing. The page navigation controls have been removed as requested.
