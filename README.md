# easy-sample-app — CBRE Sample Dashboard

This tiny sample project demonstrates a minimal static dashboard showing fictional company data and charts.

Files added:

- index.html — main dashboard (fetches data.json and renders charts using Chart.js)
- data.json — sample dataset (fictional)

How to run locally:

1. Clone the repository or download the files.
2. Open index.html in your browser (double-click or use File -> Open).

If you want to serve it from a simple local server (recommended to avoid CORS when fetching files):

- With Python 3:
  python -m http.server 8000
  then open http://localhost:8000/

What I added and next steps

- I created a small static dashboard with a table and two charts (bar and pie) using Chart.js.
- Next, I can: add more datasets, implement filtering, add interactive maps, or deploy to GitHub Pages. Tell me which you prefer and I'll continue.
