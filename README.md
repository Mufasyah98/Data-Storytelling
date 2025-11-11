# Portfolio Case Studies (Excel Only)

This repository showcases **four real-world data analysis case studies** completed entirely using **Microsoft Excel**.  
Each case study includes clear objectives, key business questions, cleaning steps, pivot table builds, KPI calculations, and recommended charts for insight storytelling.

This repository is suitable for:
- Professional portfolio presentation
- Client training materials
- Internal analytics capability development
- Interview / skill demonstration

---

## Folder Structure

├── data/
│ └── raw/ # Place all original Excel data files here
│
├── 01_maventoys_retail/
├── 02_hotel_bookings_mhg/
├── 03_us_labor_stats/
└── 04_us_music_revenues/


**Required raw data files (place in `data/raw/`):**
- `MavenToys_Monthly_Sales.xlsx`
- `MHG_Booking_Data.xlsx`
- `US_Labor_Statistics.xlsx`
- `US_Music_Revenues.xlsx`

---

## Case Study 1 — Maven Toys (Retail Sales Analysis)

**Objective**
- Evaluate store performance, product/category contribution, and revenue/profit trends over time.

**Key Business Questions**
- What are the month-to-month Revenue and Profit trends?
- Which Products / Categories drive the most profit and sales volume?
- Which Stores / Regions perform most consistently?

**Excel Steps**
1. Remove any `Unnamed:*` columns if present.
2. Create a proper Date field:


3. Build PivotTable(s):
- Rows → Date (Grouped by Month/Year)
- Values → Revenue, Profit
- Columns → Product Category / Store / Region

**Recommended Charts**
- Line Chart → Monthly Revenue Trend
- Combo Chart (Line + Column) → Revenue vs Profit
- Treemap → Category Contribution

**Output Suggested**
- `01_maventoys_retail/Analysis.xlsx`

---

## Case Study 2 — MHG Hotel Bookings (Cancellation & Pricing Analysis)

**Objective**
- Understand what drives booking cancellations and how pricing behaves across seasons and segments.

**Key Business Questions**
- Which customer segments have the highest cancellation rate?
- Does lead time affect cancellation likelihood?
- What is the seasonal pattern of ADR (Average Daily Rate)?

**Excel Steps**
1. Format `Booking Date` and `Arrival Date` as valid date fields.
2. Create a Cancellation Indicator:


3. Build PivotTable(s) for:
- Cancellation Rate by Customer Type / Channel / Country
- ADR Changes Over Time

**Recommended Charts**
- Bar Chart → Cancellation % by Customer Type
- Line Chart → ADR Trend by Month/Season
- Map Chart → Bookings by Country (Excel 365+)

**Output Suggested**
- `02_hotel_bookings_mhg/Analysis.xlsx`

---

## Case Study 3 — US Labor Statistics (Workforce & Wage Analysis)

**Objective**
- Compare workforce distribution and wage levels across states and industries.

**Key Business Questions**
- Which states/industries show the strongest employment growth?
- How do state wages compare to the national average?
- Which industries are dense in small business presence (high Establishments vs Employees)?

**Excel Steps**
1. Calculate Growth (CAGR):
2. Use PivotTables to compare:
- Employees by Industry & State
- Average Annual Wage by Industry & State

**Recommended Charts**
- Bar Ranking → Wage comparison
- Slope Chart → Wage growth across years
- Bubble Chart → Employees vs Wage (by Industry)

**Output Suggested**
- `03_us_labor_stats/Analysis.xlsx`

---

## Case Study 4 — US Music Revenues (Industry Format Shift Analysis)

**Objective**
- Analyze the shift from Physical → Digital → Streaming formats and its revenue impact over time.

**Key Business Questions**
- When did streaming become the dominant revenue source?
- How has total music industry revenue changed year-to-year?
- Which formats are growing vs declining?

**Excel Steps**
1. Standardize column names to:
2. Create PivotTable:
- Rows → Year
- Columns → Format
- Values → Sum of Revenue

**Recommended Charts**
- Stacked Area Chart → Revenue by Format Over Time
- Line Chart → Total Revenue Trend
- Waterfall Chart → YoY Revenue Change

**Output Suggested**
- `04_us_music_revenues/Analysis.xlsx`

---

## Usage Notes

- All insights and dashboards can be produced **entirely within Excel**—no Python or BI tools required.
- Visuals and reports can be exported to **PDF** for presentations or professional portfolios.

---

## Recommended Next Step (Optional)

| Enhancement | Benefit |
|------------|---------|
| Combine all dashboards into one Master Excel Workbook | Portfolio-ready presentation |
| Add slicers & PivotCharts | Interactive exploration |
| Create Executive Summary Sheet | Suitable for management reporting |

---


