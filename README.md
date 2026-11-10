<div align="center">

# Sello Mpho

### Data Analyst | Power BI & Excel Dashboards | Data Cleaning & Validation

I turn messy, real-world datasets into verified, decision-ready dashboards.

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-MPHO--SELLO.VERCEL.APP-1F4E79?style=for-the-badge)](https://sello-mpho-portfolioo.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-MPHO%20SELLO-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mpho-sello-692193241)
[![Email](https://img.shields.io/badge/EMAIL-SELLOMPHO1601%40GMAIL.COM-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sellompho1601@gmail.com)

📍 Bloemfontein, South Africa

</div>

---

## About Me

I work through data the way an analyst should: **clean it, verify it, then visualise it, and document every decision along the way.** My projects don't stop at charts. Each one includes a verification layer that cross-checks the numbers, and a write-up explaining what was recovered, what was flagged, and why.

---

## Featured Analytics Projects

### 📶 MTN Customer Churn Analytics Dashboard
**Modelling purchase lines vs customers, and reconciling to raw totals** · `Power BI` `Power Query` `DAX` `Data Modelling` `Excel`

A churn analysis of 974 purchase lines belonging to just 496 customers. The central challenge was that each row was a purchase, not a customer, so counting rows would have inflated customers, churn and revenue.

- Split the data into **Customers** and **Purchases** tables in Power Query, related on Customer ID, and wrote DAX measures for churn rate and revenue
- Caught a duplicate-removal step that silently cut revenue from 199M to 96M by **reconciling the dashboard against the raw total** before sharing it
- Found Excel misreading `Jan-25` as 25 January 2026, and rebuilt the dates from the source
- **Findings:** churn is 29.4% (146 of 496 customers), about half of all churn reasons are price-related (better offers from competitors, high call tariffs, costly data plans), and churn is flat across tenure

**Repository:** [MTN-Customer-Churn-Analytics-Dashboard---Power-BI](https://github.com/Sellomphoo/MTN-Customer-Churn-Analytics-Dashboard---Power-BI)

---

### 📡 Telecom Customer Analytics Dashboard
**Customer profiling and revenue drivers** · `Power BI` `DAX` `Power Query` `Slicers` `Map Visual`

An analysis of 7,043 telecom customers covering demographics, contracts, internet services, payment methods and locations, built to show where revenue comes from.

- Profiled the data before building any visuals, separating structural nulls (blanks that mean "not applicable", such as no internet service) from real errors, and flagging 120 rows with invalid negative monthly charges
- Verified that Total Revenue reconciles with Total Charges, refunds, extra data charges and long distance charges, with zero mismatches
- Built an Age Group calculated column and a customer-count measure in DAX, with Gender and Customer Status slicers and a customer location map
- Kept the scope to customer analysis and noted that the contract chart shows revenue, not customer counts
- **Findings:** 7,043 customers generate 21.37M in revenue, two-year contracts bring in the most (about 42%), and Fiber Optic accounts for about two-thirds of internet charges

**Repository:** [Telecom-Customer-Analytics-Dashboard-Power-BI-](https://github.com/Sellomphoo/Telecom-Customer-Analytics-Dashboard-Power-BI-)

---

### 🛍️ Store Sales Dashboard
**Transaction analysis, assumption testing and payment behaviour** · `Excel` `PivotTables` `PivotCharts` `Slicers`

Analysis of 5,000 retail transactions covering customer demographics, categories, seasons and payment methods. The central challenge was a correctness question: did the discount still need to be applied to the sales amount, or was it already included?

- Built a test column to reverse the discount and compare implied original prices per item
- The test **disproved my own assumption**: the same item (e.g. Handbag) implied prices from R21.86 to R261.13, so no fixed "original price" existed
- Resolved the ambiguity against the dataset's source documentation (`Amount` = total transaction value) rather than guessing, preventing double-discounted, understated revenue
- Verified every breakdown (category, season, gender, payment method) reconciles to 5,000 orders
- **Finding:** Card payments make up ~80% of orders (4,009 vs 991 Cash on Delivery) and this holds across every season

**Repository:** [Store-Sales-Dasboard](https://github.com/Sellomphoo/Store-Sales-Dasboard)

---

## Analytics Toolkit

| Area | Technologies |
|---|---|
| Business Intelligence | Power BI (Power Query, data modelling, DAX measures, slicers, map visuals) |
| Spreadsheets & Dashboards | Microsoft Excel, PivotTables, PivotCharts, Slicers, KPI cards |
| Data Modelling | Separating customer-level and transaction-level data, one-to-many relationships, distinct counts |
| Data Cleaning | Missing-value recovery, null standardisation, text parsing (`TEXTAFTER`), median imputation, `IFERROR` / `ISNUMBER` guards |
| Formulas & Lookups | DAX (`CALCULATE`, `DIVIDE`, `DISTINCTCOUNT`, `SWITCH`), `COUNTIFS`, `SUMIF`, `VLOOKUP`, array formulas, helper columns |
| Data Validation | Reconciliation against raw totals, cross-checks, hypothesis testing |
| Documentation | GitHub, README write-ups, documented cleaning decisions |

---

## How I Work

- **Verify before visualising.** A chart is only as trustworthy as the number behind it, so every dashboard figure is cross-checked first.
- **Recover only what can be proven.** If a missing value can be deduced with certainty, I fill it. If it can't, I flag it instead of guessing.
- **Test assumptions against the data.** When a hypothesis fails, I change the approach rather than force the result.
- **Check the source.** When the data can't settle a question, I go to the dataset's documentation.
- **Document the decisions.** Every project explains what was cleaned, what was imputed and what was left alone.

---

## Let's Connect

🌐 [mpho-sello.vercel.app](https://sello-mpho-portfolioo.vercel.app/)
💼 [LinkedIn](https://www.linkedin.com/in/mpho-sello-692193241)
📧 [sellompho1601@gmail.com](mailto:sellompho1601@gmail.com)
📍 Bloemfontein, South Africa

**Open to Data Analyst opportunities.**
