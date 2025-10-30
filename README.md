# SwiftCalc — Browser Edition (GitHub Pages)

This folder is ready to upload to **GitHub** and serve via **GitHub Pages**.

## Quick Deploy
1. Create a new repo, e.g. `swiftcalc-browser`.
2. Upload all files in this folder to the repo root (keep the subfolders).
3. In **Settings → Pages**, set:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`), **Folder**: `/ (root)`
4. Click **Save**. After 1–2 minutes, your site will be live:
   - `https://<your-username>.github.io/<repo-name>/`

## Open the apps
- SwiftCalc v6: `/swiftcalc/SwiftCalc_v6_singlefile.html`
- Docs Generator: `/docs/SwiftCalc_Docs_Generator.html`

## Workflow
1. In SwiftCalc v6, build an estimate and **Export Proposal JSON**.
2. In Docs Generator, **Load JSON**, add logo & notes, then **Print / Save PDF**.

> These are single-file apps; no build step, no server.
