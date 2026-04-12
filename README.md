# Care Data Services — Multi-Site Dashboard

A browser-based dashboard for care home operators to track support plan renewals, DoLS authorisations, and facility expenses across multiple sites.

## What it does

Upload the Excel tracker file and the dashboard instantly shows:

- **Support plan renewals** — traffic light status, days until due, overdue alerts
- **DoLS authorisations** — expiry timeline with automatic red/amber/green status
- **Expenses** — spend by facility, category, and month
- **12-week renewal calendar** — colour-coded heatmap of upcoming due dates

All four pages filter simultaneously by facility using the tabs at the top.

## How to use it

1. Visit the dashboard URL
2. Drag and drop the `CareDataServices_MultiSite_Tracker.xlsx` file onto the upload screen
3. The dashboard loads instantly — no login, no account needed

The Excel file is read locally in your browser. Nothing is uploaded to any server.

## Updating the data

The consultant updates the Excel tracker and either:
- Shares the new file directly with the care home to upload, or
- Places the file in the `data/` folder of this repository so the dashboard auto-loads it on every visit

## Built with

- [SheetJS](https://sheetjs.com) — reads the Excel file in the browser
- [Chart.js](https://chartjs.org) — renders the charts
- Hosted free on GitHub Pages

---

*Managed by Care Data Services*
