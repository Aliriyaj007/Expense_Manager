


# Personal Expense Manager

<div align="center">

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: Stable](https://img.shields.io/badge/Status-Stable-green.svg)](https://aliriyaj007.github.io/Expense_Manager/)
[![GitHub Stars](https://img.shields.io/github/stars/Aliriyaj007/Expense_Manager?style=social)](https://github.com/Aliriyaj007/Expense_Manager)

**Zero-dependency. Offline-first. Data Sovereignty.**

Track expenses, manage budgets, and visualize insights in a browser-native environment. No databases, no tracking, no fluff.

[Web App](https://aliriyaj007.github.io/Expense_Manager/) • [Report Bug](https://github.com/Aliriyaj007/Expense_Manager/issues) • [Request Feature](https://github.com/Aliriyaj007/Expense_Manager/issues)

</div>

---

## Why this tool exists

Most expense trackers are either heavy SPAs that drain battery or SaaS products that monetize your financial data.

**Personal Expense Manager** is different. It is a utility-focused tool designed for developers and power users who value **privacy** and **simplicity**. It proves its value by working instantly without a backend.

### The Workflow Shift

| 🛑 Before (Spreadsheets) | 🚀 After (This Tool) |
| :--- | :--- |
| Manual math for totals. | **Real-time** automatic calculation. |
| "Where did I save that file?" | **Browser LocalStorage** (always there). |
| No visual representation of spending. | **SVG Charts** (Pie & Bar) generated on the fly. |
| Manual backup to USB/Email. | **One-click Google Drive Sync.** |

---

## ⚡ Quick Start (Under 60 Seconds)

You don't need to build anything.

### Option 1: Use it Now
Open the hosted version and start tracking. Your data lives in your browser.

1.  Go to: **[https://aliriyaj007.github.io/Expense_Manager/](https://aliriyaj007.github.io/Expense_Manager/)**
2.  Select a Theme (e.g., "Hacker").
3.  Add an expense.
4.  Done.

### Option 2: Self-Host
Download the single HTML file and drop it into your own server or open it locally.

```bash
git clone https://github.com/Aliriyaj007/Expense_Manager.git
cd Expense_Manager
# Open index.html in your browser
```

---

## 🚀 Features

| Feature | Details |
| :--- | :--- |
| **🔒 Data Privacy** | 100% Client-side. Data stored in `localStorage` until you decide to sync. |
| **☁️ Cloud Sync** | Optional Google Drive integration (JSON format). No third-party servers involved. |
| **🎨 Theming Engine** | 12 Built-in Themes: Light, Dark, Hacker, Ocean, Sunset, Forest, Berry, Midnight, Coffee, Lavender, Slate, High Contrast. |
| **📊 Visualizations** | Native SVG rendering for Category Breakdown (Pie) and Budget vs. Spent (Bar). |
| **📄 CSV Export** | Export Expenses, Budgets, and Shopping Lists to `.csv` for Excel/Google Sheets analysis. |
| **🛒 Shopping List** | Integrated checklist to manage planned purchases. |
| **🌍 Multi-Currency** | Support for INR, USD, EUR, GBP, and more via `Intl.NumberFormat`. |

---

## 📥 Installation & Usage

### Hosted Version
The easiest way to use this tool is via the hosted web app.

[🌐 Live Web App](https://aliriyaj007.github.io/Expense_Manager/)

### Direct Download
Grab the raw source and run it anywhere.

[📥 Direct Download Link](https://github.com/Aliriyaj007/Expense_Manager/raw/main/index.html) *(Right-click -> Save Link As)*

### Developer Setup
If you want to modify the source code:

1.  Clone the repository:
    ```bash
    git clone https://github.com/Aliriyaj007/Expense_Manager.git
    ```
2.  Open `index.html` in any modern text editor.
3.  To enable Google Drive sync, replace `REPLACE_ME.apps.googleusercontent.com` in the script with your own Google Client ID.
4.  No `npm install` required. It's Vanilla JS.

---

## 📸 Preview

*   **Dashboard:** Quick view of Total Expenses, Budget status, and Shopping progress.
*   **Charts:** Auto-generated SVG graphics that adapt to your selected color theme.
*   **Data Management:** Export to CSV or JSON with a single click.

---

## 🤝 Contributing

This is a utility project. It doesn't need "help wanted" signs; it needs utility.

**Areas for contribution:**
*   **Localization:** Adding support for more languages/regions.
*   **Charts:** Adding new visualization types (e.g., Line charts for spending trends).
*   **Themes:** Creating new color palettes.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 👤 Author & Contact

**Riyajul Ali**

*   GitHub: [@Aliriyaj007](https://github.com/Aliriyaj007)
*   LinkedIn: [linkedin.com/in/Aliriyaj007](https://linkedin.com/in/Aliriyaj007)
*   Email: [aliriyaj007@protonmail.com](mailto:aliriyaj007@protonmail.com)

---

<div align="center">

**If this tool saves you time, give it a ⭐**

Made with ❤️ by Aliriyaj007

</div>
