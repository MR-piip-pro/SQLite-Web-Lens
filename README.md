# 🔍 Advanced SQLite Viewer

A professional, privacy-first, web-based SQLite database browser. Built entirely with single-file HTML, Tailwind CSS, and WebAssembly (`sql.js`), this tool allows you to examine and export your `.db` or `.sqlite` files completely locally, right from your browser—no backend or uploads required!

## ✨ Key Features

- **🛡️ 100% Local & Private**: All database processing happens within your browser. Your sensitive files never leave your machine.
- **💎 Sleek, Modern UI**: Engineered with Tailwind CSS for a premium, responsive, and intuitive user experience.
- **📊 Instant Table Browsing**: Easily navigate through all database tables via a convenient, scrollable sidebar.
- **🔍 Real-Time Quick Search**: Instantly filter through currently loaded records as you type.
- **🏗️ Schema Inspector**: View detailed table structures including column names, data types, Primary Keys, and Nullability factors with a single click.
- **📥 CSV Export**: Seamlessly export any table's data into a `.csv` file for use in Excel or other data analysis software.
- **⚡ Performance Optimized**: Handles data retrieval gracefully with built-in loading states and optimized DOM rendering.

## 🚀 Getting Started

1. **Launch**: Simply double-click on `index.html` to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
2. **Load Database**: Click the **"Open New File"** button and select your `.db`, `.sqlite`, or `.sqlite3` file.
3. **Explore Data**: Click on any table from the left "Available Tables" sidebar to view its contents.
4. **Analyze & Export**: Use the top search bar to find specific records, inspect the schema using the "Structure" button, or click **"Export CSV"** to save the view.

## 🛠️ Technology Stack

- **[SQL.js](https://sql.js.org/)**: A WebAssembly (WASM) port of SQLite that powers the local, in-browser database engine.
- **[Tailwind CSS](https://tailwindcss.com/)**: Delivered via CDN for sleek, beautiful, and consistent UI styling without local setup.
- **Vanilla JavaScript**: Lightweight, framework-free frontend logic for fast execution.
- **Google Fonts (Inter)**: Crisp, modern typography optimized for readability.

## 📁 Project Structure

```text
├── index.html       # The complete application (UI, Logic, and Styling)
└── README.md        # Documentation (You are here)
```
## Your site is live at [SQL-Web](https://mr-piip-pro.github.io/SQLite-Web-Lens/)

## 📜 License

This project is licensed under the MIT License. Feel free to fork, modify, and use it in your own projects!
