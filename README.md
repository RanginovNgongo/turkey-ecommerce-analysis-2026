# E-Commerce Consumer Behavior and Logistics Analysis (Turkey)

## 📌 Project Overview
This project demonstrates a full data analytics workflow, transforming a raw dataset into a structured 5,000-row source of truth focused on the Turkish market. The goal is to identify high-value customer segments, delivery bottlenecks, and purchasing trends across major Turkish cities.

## 🛠️ Tool Stack
- **Excel:** Data Cleaning, Power Query, Feature Engineering, Pivot Tables.
- **Tableau:** Business Intelligence Reporting and Geospatial Mapping.
- **Dataset:** 5,000 rows (Cleaned) featuring 15 plus variables including demographics, logistics, and session engagement.

## 📈 Phase 1: Excel Data Engineering (The Engine)
Before visualization, the data underwent a rigorous cleaning process to ensure data integrity and professional documentation.

### 1. Data Transformation (Power Query)
- **Standardization:** Cleaned and standardized city names like Ankara, Istanbul, and Bursa to Proper Case for accurate mapping.
- **Data Integrity:** Handled null values and removed duplicate Order ID entries.

### 2. Feature Engineering (Advanced Formulas)
Created Value-Add columns to unlock deeper insights:
- **Age Segmentation:** Used IFS logic to categorize customers into Gen Z, Millennial, Gen X, and Seniors.
- **Time-Series Prep:** Extracted months from date strings using the TEXT function for seasonal trend analysis.
- **Logistics Logic:** Calculated delivery speed categories to identify shipping performance.

### 3. Exploratory Data Analysis (Pivot Tables)
Developed a multi-sheet analysis workbook featuring:
- **Revenue Attribution:** Sales breakdown by Product Category.
- **Device Analysis:** Identifying Mobile vs. Desktop dominance in user orders.
- **Engagement Metrics:** Comparing Pages Viewed between New and Returning customers.

## 📊 Phase 2: Tableau Business Intelligence (The Vision)
The Tableau integration focuses on three core pillars:

- **Geospatial Analysis:** A map of Turkey visualizing revenue concentration across the top 10 cities.
- **Product Hierarchy:** Using Treemaps to show category-wise revenue with specialized currency formatting in Turkish Lira.
- **Behavioral Analysis:** Visualizing the correlation between session duration and total spend per demographic.

## 💡 Key Preliminary Findings
- **Top Performer:** Electronics represents the highest revenue share, totaling approximately 2.3M Turkish Lira in the sample.
- **Mobile First:** Mobile devices account for over 55 percent of total order volume.
- **Logistics Consistency:** Average delivery times across major Turkish cities are stabilized at 6 to 7 days.

## 🎯 Business Decisions and Recommendations
Based on the data analysis, the following strategic actions are proposed:

1. **Mobile Optimization:** Since over half of the orders come from mobile devices, the company should prioritize mobile app UI/UX improvements and mobile-only promotional codes to increase conversion rates.

2. **Inventory Allocation:** Given that Electronics is the primary revenue driver, warehouse stock for these items should be prioritized in high-volume hubs like Istanbul and Ankara to maintain shipping speeds.

3. **Loyalty Programs:** Data shows that returning customers have higher engagement levels. A tiered loyalty program should be implemented to reward repeat buyers and increase their average order value.

4. **Logistics Marketing:** Since delivery times are consistent at 6 to 7 days, marketing campaigns can safely guarantee one-week delivery across major cities to build customer trust.

## Tableau Dashboard
*(Dashboard visualizations are currently in development)*
