# InDriver Income Tracker

A PWA for ride-hailing drivers to track fares, expenses, and shifts from their phone. Works fully offline — no backend, no account needed.

**[Live Demo →](https://indrivermaster.netlify.app/)**

![App Preview](assets/icon.png)

## Features
- Shift timer with live earnings per hour
- Quick-add fare chips (+30, +50, +100, +150)
- Expense logging by category (Fuel, Wash, Maintenance, Other)
- Daily goal tracker with progress bar
- Weekly and monthly earnings chart
- CSV and PDF export
- 5-second undo on accidental entries
- Fully offline via Service Worker

## Tech Stack
HTML5 · Vanilla JS · CSS3 · Chart.js · Service Worker · localStorage

## Run Locally
```bash
git clone https://github.com/yousef-ehabb/IncomeApp.git
cd IncomeApp
python -m http.server 8000
```
Open http://localhost:8000

## License
MIT
