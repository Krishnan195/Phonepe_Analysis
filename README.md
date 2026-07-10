# Phonepe_Analysis
Interactive Power BI dashboard analyzing PhonePe transaction data — built entirely with Power Query (data cleaning, null handling) and a custom date table, featuring KPIs, trend analysis, and user segmentation.

# PhonePe Payment Insights Dashboard 💜

An interactive Power BI dashboard analyzing digital payment transactions, 
built to surface key business metrics and usage patterns from raw transaction data.

## 🔧 Tools & Techniques
- **Power BI Desktop** for visualization and report building
- **Power Query (M)** for data cleaning — removed null/blank values, handled data type corrections
- **Custom Date Table** created via Power Query for proper time intelligence (month, weekday/weekend flags, etc.)
- DAX measures for KPIs, growth %, and success rate calculations

## 📊 Dashboard Features
- **KPI Cards**: Total Transactions, Total Value, Unique Users, Success Rate (with MoM % growth)
- **Transactions Over Time**: Dual-line trend of transaction count vs. value across months
- **Age Segment Contribution**: Donut chart breaking down users by age group
- **Service Transaction Value Analysis**: Bar chart comparing Loans, Insurance, Money Transfer, Recharge/Bills
- **Top 5 Users by Transaction Value**
- **Weekday vs Weekend Usage** split
- **Auto-generated Insights panel** highlighting key takeaways (e.g., weekday transaction peaks, top-performing service)
- Slicers for **Month** and **Payment Status** (Failed / Pending / Successful)

## 💡 Key Insights
- Weekday transactions significantly outperform weekends (71.6% vs 28.4%)
- Loans service generates the highest transaction value among all services
- Overall success rate stands at 96%

## 📁 Files
- `PhonePe_Dashboard.pbix` — Power BI report file
- Dataset used: *(mention source here — sample/synthetic/Kaggle etc.)*

## 📸 Preview
*(insert dashboard screenshot here)*
