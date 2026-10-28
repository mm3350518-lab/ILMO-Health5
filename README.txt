# ILMO Health — Scientific Library (ZIP package)

## Included
- `index.html` — responsive, searchable offline-friendly web interface.
- `library-data.json` — 13 subject areas and 40+ topic cards with mechanism, uses, risks, interactions, and counselling notes.
- `Summer Training Guide...pdf` — the original source guide supplied in the conversation, included as a companion reference.

## Run locally
1. Extract the ZIP.
2. Keep `index.html` and `library-data.json` in the same folder.
3. Open `index.html` in a browser. Search, save topics, mark reviewed, add study notes, print/save PDF, and export/import a JSON backup.
   - Some browsers restrict `fetch()` when opening a file directly. If the data does not load, upload the extracted folder to GitHub Pages or run a simple local web server.

## Publish with GitHub Pages
Upload `index.html`, `library-data.json`, and the PDF to the root of a repository. In GitHub: Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save. Open the Pages URL after the deployment finishes.

## Important scope note
This is a structured first release of the scientific library, not a verified transcription of every page of the source PDF. The original PDF is included to preserve the full supplied material. The topic notes are educational summaries, not patient-specific prescribing advice. The source guide references older editions in places; verify current doses, contraindications, interactions and monitoring against current local guidelines and product information before clinical use.
