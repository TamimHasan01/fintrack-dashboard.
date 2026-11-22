# 📊 FinTrack — Financial Analytics & Ledger Suite

A modular financial analytics dashboard built using **Vanilla JavaScript (ES6 Modules)**, **Tailwind CSS**, and **Chart.js**. Engineered with clean separation of concerns across state management, data visualization, UI rendering, and CSV reporting modules.

## 🚀 Live Demo
[Insert your GitHub Pages / Vercel Link Here]

## 🏗️ Modular Architecture
```text
├── index.html          # Semantic dashboard layout & modals
├── css/styles.css      # Custom animations & scrollbar styling
└── js/
    ├── app.js          # Main application controller & event bindings
    ├── state.js        # Centralized Store & LocalStorage persistence
    ├── charts.js       # Chart.js Bar & Doughnut visualization engine
    ├── ui.js           # Dynamic DOM & KPI progress rendering
    └── utils.js        # Currency formatting, notifications & CSV export
```

## ✨ Core Capabilities
- **Interactive Data Visualization:** Real-time Income vs. Expense bar charts and category breakdown doughnut charts via Chart.js.
- **Dynamic Budget Threshold Alerts:** Visual progress tracking with automatic color-coded alerts when spending exceeds 70% and 90% of the monthly budget.
- **Multi-Criteria Ledger Filtering:** Instant search and filtering by transaction type and category.
- **One-Click CSV Export:** Generates and downloads formatted `.csv` financial statements directly from client state.
- **Theme Persistence:** Full Dark/Light mode support synchronized with chart themes.

## 🛠️ Running Locally
Because this project uses native ES6 Modules (`type="module"`), serve it via a local development server:
1. Open the project folder in **VS Code**.
2. Right-click `index.html` and select **Open with Live Server**.
