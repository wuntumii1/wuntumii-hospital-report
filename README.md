# WunTumii Monthly Hospital Report Generator

A simple, static single-file web UI to help district hospitals in Ghana draft monthly administrative reports and produce a printable PDF.  
This repository contains a lightweight HTML page (wuntumii-hospital-report.html) that:

- Collects facility-level inputs (OPD, admissions, MCH, achievements, challenges, actions, recommendations).
- Generates a clear AI prompt for drafting a formal monthly report.
- Renders a printable preview and lets users export a PDF (client-side).
- Provides buttons to copy the prompt or download it as a .txt file.

Important
- Do NOT paste or upload patient-identifiable data (names, IDs, personal identifiers). This tool is intended for aggregated administrative summaries only.

Files
- `wuntumii-hospital-report.html` — single-file web UI (form, preview, PDF export).
- `README.md` — this file.

How to publish (GitHub Pages)
Option A — Quick (GitHub web UI)
1. Open https://github.com/wuntumii1/wuntumii-hospital-report
2. Click "Add file" → "Upload files".
3. Upload both:
   - `wuntumii-hospital-report.html`
   - `README.md`
4. In the commit box choose "Create a new branch for this commit" and name it `gh-pages`.
5. Commit the files.
6. Go to Settings → Pages (or Settings → Pages in the left sidebar).
7. Under Source choose: Branch = `gh-pages`, Folder = `/ (root)` → Save.
8. Wait ~1–5 minutes, then open:
   `https://wuntumii1.github.io/wuntumii-hospital-report/wuntumii-hospital-report.html`

Option B — Command line (one-shot initial commit)
1. Save the two files into a local folder.
2. Run these commands (HTTPS):
   - git init
   - git add wuntumii-hospital-report.html README.md
   - git commit -m "Initial site: add WunTumii Monthly Report page and README"
   - git branch -M main
   - git remote add origin https://github.com/wuntumii1/wuntumii-hospital-report.git
   - git checkout -b gh-pages
   - git push -u origin gh-pages
3. Enable Pages in repo Settings → Pages (choose `gh-pages` / root).
4. Visit: `https://wuntumii1.github.io/wuntumii-hospital-report/wuntumii-hospital-report.html`

Optional enhancements
- Rename `wuntumii-hospital-report.html` to `index.html` (then the Pages root URL will be `https://wuntumii1.github.io/wuntumii-hospital-report/`).
- Add CSS/JS separate files for easier edits.
- Add a short LICENSE if you want to publish with explicit reuse permissions.

Need me to do it for you?
I cannot push files directly because the repository is currently empty and I don’t have additional permissions from this chat. I can:
- Provide the exact commands to run in your environment (see Option B), or
- Give a single ZIP you can upload, or
- Walk you step-by-step via the web UI and confirm when the site is live.

Which would you like? If you
