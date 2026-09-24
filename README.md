# 📈 Financial Growth & Investment Projector

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Active-brightgreen.svg)](https://pages.github.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.x-38B2AC.svg)](https://tailwindcss.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-4.x-FF6384.svg)](https://www.chartjs.org/)

An interactive, zero-dependency client-side web application designed to forecast long-term wealth building, salary growth trajectories, tax liabilities, and compound investment strategies over 1 to 40-year horizons.

🔗 **Live Demo:** `https://RyRahman.github.io/financial-growth-calculator/`

---

## 🌟 Key Features

### 💼 Salary & Tax Trajectory Engine
* **Multi-Decade Horizon**: Live dynamic projections for 10, 20, 30, and 40-year milestones.
* **Custom Tax Calculations**: Direct net take-home salary calculations using flat rate tax deductions.
* **Inflation Adjustment**: Real purchasing power calculation alongside nominal salary figures.
* **Granular Breakdown**: Annual, monthly, gross, net, and cumulative tax metric summaries.

### 💰 Investment & Compound Portfolio Builder
* **Flexible Growth Returns**: Full range slider supporting average returns from **1% up to 40%**.
* **Flexible Contribution Intervals**: Supports **Weekly**, **Monthly**, or **Annual** recurring investments.
* **Initial Capital Offset**: Evaluates growth starting from a current portfolio balance.
* **Capital Gains Tax Adjustments**: Estimates net portfolio value after capital gains taxes upon payout.

### 🎨 User Experience & Tools
* **Interactive Visualizations**: Powered by Chart.js for trajectory comparison graphs.
* **Export Options**: Export detailed year-by-year projections directly to **CSV**.
* **Self-Contained File Export**: Export the full web app as a standalone offline HTML file.
* **Privacy-First**: Runs 100% locally in the browser—no backend servers or data tracking.

---

## 🛠️ Built With

* **HTML5 / ES6+ JavaScript** — Lightweight, modular vanilla script execution.
* **Tailwind CSS CDN** — Responsive styling and layout scaffolding.
* **Chart.js** — High-performance dynamic canvas charts.
* **Lucide Icons** — UI SVG icons.

---

## 🚀 Quick Deployment Guide

### Option 1: Direct File Upload on GitHub (No Terminal)
1. Log in to [GitHub](https://github.com) and create a **New Repository** named `financial-growth-calculator`.
2. Select **Public**, leave initialization empty, and click **Create repository**.
3. Click **"uploading an existing file"**, drag your `index.html` and this `README.md` into the box, and click **Commit changes**.
4. Navigate to **Settings > Pages**.
5. Under **Build and deployment > Source**, choose **Deploy from a branch**.
6. Set the branch to `main` and the folder to `/ (root)`, then click **Save**.
7. Wait 1–2 minutes for GitHub to publish your live link!

### Option 2: Using Git CLI

```bash
# Clone or navigate to your local workspace
mkdir financial-growth-calculator && cd financial-growth-calculator

# Initialize local git repository
git init

# Add application files
git add index.html README.md

# Create initial commit
git commit -m "Initial commit: Add Salary and Investment Calculator"

# Rename branch to main and set remote target
git branch -M main
git remote add origin [https://github.com/RyRahman/financial-growth-calculator.git](https://github.com/RyRahman/financial-growth-calculator.git)

# Push to repository
git push -u origin main
