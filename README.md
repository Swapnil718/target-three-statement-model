# 📊 Target Corporation | Three-Statement Financial Model

An Excel financial model using Target Corporation's published financial statements for FY2023–FY2025 to build assumption-based forecasts for FY2026–FY2028. The workbook links the income statement, balance sheet, and cash flow statement and includes supporting schedules, model checks, and an executive summary.

> All financial amounts are in USD millions unless stated otherwise. Forecasts are independent project assumptions, not Target Corporation guidance.

---

## 📋 Project Overview

The goal was to turn reported financial data into a connected model that shows how changes in sales, profitability, working capital, and capital spending affect earnings, cash flow, and the balance sheet.

| Period | Treatment |
|---|---|
| FY2023–FY2025 | Historical results from Target's financial reporting |
| FY2026–FY2028 | Forecasts calculated from stated assumptions |

## 🛠️ Tools & Techniques

- Microsoft Excel: linked formulas, financial schedules, formatting, and charts
- Three-statement modeling and financial statement analysis
- Historical ratio analysis and assumption-based forecasting
- Balance sheet reconciliation and model checks

## 📁 Files Included

- [`Target_Three_Statement_Model.xlsx`](Target_Three_Statement_Model.xlsx) — completed Excel model
- [`2025-Annual-Report-Target-Corporation.pdf`](2025-Annual-Report-Target-Corporation.pdf) — annual report used for historical financial data
- `README.md` — project documentation

## 🧱 Workbook Structure

| Sheet | Purpose |
|---|---|
| Historical | Organizes reported financial data for FY2023–FY2025 |
| Assumptions | Holds the inputs used to forecast FY2026–FY2028 |
| Schedules | Calculates supporting forecast items |
| Three Statements | Connects the forecast income statement, balance sheet, and cash flow statement |
| Checks | Tests whether the model balances |
| Summary | Presents selected results and a free cash flow chart |

## 🔄 How I Built the Model

1. **Collected historical figures:** Entered reported FY2023–FY2025 results from Target's annual report into a consistent, year-by-year format.
2. **Analyzed historical relationships:** Used historical results, including FY2025 ratios, to establish forecast drivers for working capital and capital spending.
3. **Set forecast assumptions:** Applied sales growth of 5% for FY2026 and 3% for both FY2027 and FY2028, along with a 23% tax rate. The model holds debt and lease balances constant, uses the FY2025 cash dividend amount, and models interest at 0.4% of sales.
4. **Built and linked the statements:** Forecast operating results feed net earnings; net earnings and balance sheet changes feed cash flow; ending cash flows into the balance sheet.
5. **Validated the model:** Used the Checks sheet to confirm that assets equal liabilities plus equity in the modeled years.
6. **Summarized the results:** Compared historical and forecast figures and charted free cash flow, defined here as operating cash flow less capital spending.

## 📈 Selected Model Results

| Metric | FY2025 actual | FY2026 forecast |
|---|---:|---:|
| Net sales | 104,780 | 110,019 |
| Operating margin | 4.9% | 6.0% |
| Free cash flow | 2,835 | 4,699 |

The FY2026 forecast shows **5.0% sales growth** and **$1,864 million more free cash flow** than FY2025. These are model outputs based on the assumptions above; they are not predictions or company guidance.

## 📚 Data Sources

- [Target Corporation 2025 Annual Report](https://corporate.target.com/investors/annual/2025-annual-report) — historical financial statements
- [Target Q2 2026 earnings release](https://corporate.target.com/press/release/2026/08/target-corporation-reports-second-quarter-earnings) — context noted in the workbook

## ⚠️ Model Scope

This is an educational portfolio model. The FY2026–FY2028 figures depend on simplified assumptions, including constant debt and lease balances and interest modeled as a percentage of sales. They should not be treated as investment advice or Target's official outlook.
