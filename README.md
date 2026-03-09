# 📊 E-Commerce Analytics Dashboard

> **A fully interactive business intelligence dashboard built with HTML, CSS, and Chart.js — designed to replicate a real-world Power BI analytics workflow.**

![Dashboard Preview](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chart.js&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

---

## 🚀 Live Demo

**[→ View Live Dashboard](https://your-username.github.io/ecommerce-dashboard/)**

---

## 📸 Screenshots

<!-- Add screenshots after deploying -->
> Dashboard features a dark-mode analytics UI with 5 KPI cards, 5 interactive charts, and real-time cross-filtering.

---

## 🎯 Project Overview

This project simulates the end-to-end workflow of a **Data Analyst** at an e-commerce company. It analyzes **1,000 sales transactions** across 5 product categories, 5 geographic regions, and 12 months of FY 2023.

### Business Problem
> *"How do we help leadership make faster, data-driven decisions without opening Excel every time?"*

This dashboard answers that by centralizing all critical metrics into one interactive view — updated instantly when filters are applied.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📊 **5 Interactive Charts** | Line, Bar, Donut, Horizontal Bar, and Regional charts |
| 🔢 **5 KPI Cards** | Total Sales, Profit, Margin %, Orders, and Avg Order Value |
| 🎛️ **Cross-Filtering** | Filter by Category AND Quarter simultaneously — all charts update live |
| 📱 **Responsive Design** | Works on desktop, tablet, and mobile |
| ⚡ **Zero Dependencies** | No backend, no build tools — just open `index.html` |
| 🌙 **Dark Mode UI** | Professional dark analytics theme |

---

## 📈 Dashboard Charts

1. **Monthly Sales Trend** *(Line Chart)* — Track revenue across Jan–Dec 2023 per category
2. **Sales by Category** *(Bar Chart)* — Compare total revenue across 5 product verticals
3. **Profit by Category** *(Donut Chart)* — Visualize profit share distribution
4. **Sales by Region** *(Bar Chart)* — Analyze geographic revenue performance
5. **Profit Margin by Category** *(Horizontal Bar)* — Rank categories by profitability

---

## 🔍 Key Business Insights

- 📦 **Electronics** drives **55%** of total revenue but has the **lowest margin** (8–18%) — high volume, thin margin
- 👕 **Clothing & Office Supplies** have the **highest margins** (40–60%) — most profitable relative to sales
- 🎄 **November** is the peak sales month — festive season demand surge
- 🌍 All **5 regions** contribute ~20% each — well-distributed national sales network
- 💸 A **22% overall profit margin** indicates a healthy, sustainable business model

---

## 🗂️ Project Structure

```
ecommerce-dashboard/
├── index.html          # Main dashboard (all-in-one file)
└── README.md           # Project documentation
```

> The entire dashboard is contained in a single `index.html` file — no build step needed.

---

## ⚙️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **HTML5** | Semantic structure |
| **CSS3** | Grid layout, CSS variables, animations, responsive design |
| **Vanilla JavaScript** | Data processing, state management, filter logic |
| **Chart.js 4.4** | All chart rendering |
| **Google Fonts** | Syne (display) + Space Mono (monospace) |

---

## 🛠️ How to Run Locally

```bash
# Clone the repo
git clone https://github.com/your-username/ecommerce-dashboard.git

# Navigate to folder
cd ecommerce-dashboard

# Open in browser (no server needed!)
open index.html
# Or just double-click index.html in your file explorer
```

---

## 🌐 Deploy to GitHub Pages

```bash
# 1. Push to GitHub
git init
git add .
git commit -m "feat: initial dashboard"
git remote add origin https://github.com/your-username/ecommerce-dashboard.git
git push -u origin main

# 2. Enable GitHub Pages
# Go to: Settings → Pages → Source: Deploy from branch → main → / (root)
# Your site will be live at: https://your-username.github.io/ecommerce-dashboard/
```

---

## 📊 Dataset Overview

The dashboard uses **1,000 synthetic e-commerce transactions** (FY 2023) with 14 attributes:

| Column | Type | Description |
|--------|------|-------------|
| `Order_ID` | Text | Unique order identifier |
| `Order_Date` | Date | Transaction date |
| `Category` | Text | Product category (5 types) |
| `Sub_Category` | Text | Sub-category within category |
| `Region` | Text | Geographic region (5 zones) |
| `City` | Text | Customer city |
| `Quantity` | Integer | Units sold per order |
| `Unit_Price` | Decimal | Price per unit (INR) |
| `Sales` | Decimal | Total order revenue |
| `Discount` | Decimal | Discount applied (0–20%) |
| `Profit` | Decimal | Order profit after costs |
| `Payment_Mode` | Text | Payment method |
| `Customer_Segment` | Text | Consumer / Corporate / SMB |

---

## 🎓 Learning Outcomes

By building this project, I developed skills in:

- **Data aggregation** — computing KPIs from raw transactional data in JavaScript
- **State management** — maintaining filter state across multiple chart instances
- **Chart.js API** — building, destroying, and re-rendering dynamic charts
- **Responsive CSS Grid** — creating adaptive dashboard layouts
- **Business intelligence** — translating raw data into actionable business insights
- **UI/UX design** — building a professional dark-mode analytics interface

---

## 🔮 Future Enhancements

- [ ] Connect to a live Google Sheets API for real data
- [ ] Add data export (CSV download button)
- [ ] Add a date range picker for custom time periods
- [ ] Build a mobile-first version
- [ ] Add animated counter transitions for KPI cards
- [ ] Add a "Compare Year" mode (YoY analysis)

---

## 👤 Author

**[Your Name]**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-profile)
- Email: your.email@example.com

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Made with ❤️ as a portfolio project · Data Analytics · Business Intelligence
</p>
