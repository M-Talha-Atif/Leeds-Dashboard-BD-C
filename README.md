# 🌿 LEED Certification Dashboard

A comprehensive, interactive dashboard for analyzing the **financial and strategic implications** of LEED (Leadership in Energy and Environmental Design) certification credits.

![React](https://img.shields.io/badge/React-18.2.0-blue) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.3+-blue)


---

## 📋 Overview

The **LEED Certification Dashboard** empowers project teams, architects, and sustainability professionals to:

* Assess financial impacts of LEED credits
* Compare multiple certification scenarios
* Forecast short and long-term budget implications
* Make **data-driven decisions** for sustainable building projects

---

## ✨ Features

### Dashboard

* 🔍 Interactive filters by category, scenario, and target
* 💰 Financial summary of costs, impacts, and value premiums
* 📈 Waterfall chart for visualizing financial outcomes
* 🧩 Credit toggling system (enable/disable credits dynamically)
* 🔄 Baseline vs. LEED scenario comparison
* 📘 Built-in methodology reference

### Summary

* 🥧 Distribution charts by category
* ✅ Investment verdicts & recommendations
* 💡 Key sustainability insights

### Reports

* 📑 Comprehensive, searchable data table
* 🔎 Quick search by category or credit
* 📤 Export-ready structured data

---

## 🛠 Tech Stack

* **Frontend**: React (18.2+), JavaScript
* **Styling**: TailwindCSS, HeadlessUI, Lucide Icons
* **Data Visualization**: Recharts, Framer Motion
* **Tooling**: Vite, ESLint, PostCSS

---

## 📊 Key Financial Metrics

* Hard & soft costs
* Operational expenditure impacts
* 1-year and 10-year budget projections
* Property value premiums
* Strategic positioning scores

---

## 🗃 Data Model

The dashboard uses a dataset (`leedData`) with **43 credits** across **9 categories**:

1. Integrated Process
2. Natural Systems & Ecology
3. Transport
4. Water Efficiency
5. Energy & Greenhouse Gas Emissions
6. Materials & Resources
7. Quality of Life
8. Innovation
9. Regional Priority

Each credit includes:

* Financial metrics (costs, impacts, premiums)
* Target and value status
* Recommendations & positioning scores

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/Progambler227788/Leeds-Dashboard.git
   cd leed-dashboard
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start development server**

   ```bash
   npm run dev
   ```

4. **Build for production**

   ```bash
   npm run build
   ```

---

## 📂 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Navbar.jsx
│   ├── FilterBar.jsx
│   ├── WaterfallChart.jsx
│   ├── Card.jsx
│   ├── ScenarioComparison.jsx
│   ├── MethodologyModal.jsx
│   ├── FinancialSummary.jsx
│   └── PerformanceInsights.jsx
├── pages/               # Application views
│   ├── Dashboard.jsx
│   ├── Summary.jsx
│   └── Reports.jsx
├── data/                # Application dataset
│   └── index.js
└── App.jsx              # Root component
```

---

## 🎨 Customization

* **Styling**: Update Tailwind classes in components
* **Data**: Modify `leedData` in `/src/data/index.js`
* **Metrics**: Adjust calculations in component logic
* **Charts**: Customize Recharts configuration

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a branch: `git checkout -b feature/your-feature`
3. Commit changes: `git commit -m "Add feature: your-feature"`
4. Push: `git push origin feature/your-feature`
5. Open a PR

---

## 📄 License

Licensed under the [MIT License](LICENSE.md).

---

## 🙏 Acknowledgments

* **LEED standards**: U.S. Green Building Council (USGBC)
* **Financial modeling**: Industry best practices
* **Icons**: [Lucide](https://lucide.dev)
* **Charts**: [Recharts](https://recharts.org)

---

## 📞 Support

For issues or questions:

* 📧 Email: [talhaatif573@gmail.com](mailto:talhaatif573@gmail.com)
* 🐛 [GitHub Issues](https://github.com/Progambler227788/Leeds-Dashboard/issues)
# Leeds-Dashboard-BD-C
