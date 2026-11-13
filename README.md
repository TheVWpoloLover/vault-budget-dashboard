# VAULT — Personal Finance Dashboard

A single-file, browser-based dashboard for organizing a personal budget, card bills, loan payments, investments, receivables, and monthly history. It includes editable charts, a budget overview, and JSON backup and restore.

## Start

No build step or package installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.

If your browser restricts local files, run a small local web server from the project folder:

```bash
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Usage

- Add your own card, budget, loan, portfolio, and receivable details in the dashboard.
- Use **Tracker** to save monthly snapshots and view history charts.
- Use **Settings → Export Backup** to download a JSON backup, or **Import Backup** to restore one.
- Use **Reset All Data** in Settings to clear this dashboard's browser storage.

The repository starts with blank financial amounts and generic account labels. The dashboard stores information in the current browser's `localStorage`; it does not send that information to a server. Browser storage is not encrypted, and data does not automatically sync between devices. Export a backup before clearing browser data.

## Project details

- Plain HTML, CSS, and JavaScript in `index.html`
- No build tools, server, or third-party runtime dependencies
- Responsive sidebar and mobile navigation
- Canvas-based monthly history charts
- JSON backup and restore

## License

No license has been selected yet. Add a `LICENSE` file before reusing or redistributing this project under specific terms.

