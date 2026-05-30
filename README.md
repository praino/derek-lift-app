# Lift Log Pro

A static, GitHub Pages-ready fitness dashboard generated from `New Lift Log.xlsx`.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `data.js` to the repository root.
3. Go to **Settings → Pages**.
4. Set **Source** to `Deploy from a branch`, choose `main`, and `/root`.
5. Save. GitHub will publish the app URL.

## User progress

The app saves edits in the browser using `localStorage`. Users can:

- **Export Progress** to download a JSON backup.
- **Import Progress** to restore or move progress to another device/browser.
- Add new workout sets and bodyweight check-ins.

## Files

- `index.html` — full app UI, dashboard, charts, forms, import/export logic.
- `data.js` — initial data extracted from the Excel workbook.
