# 📊 App Reviews & Developer Engagement Analysis (Power BI)

## Overview

This project explores how user reviews and developer engagement impact app performance. Using Power BI, I built a multi-page report to analyze rating accumulation, review quality, response behavior, and rating stability.

The goal was not just to visualize data — but to interpret how review volume and developer responsiveness influence user perception.

---

## Business Questions Explored

- Do developers with more reviews accumulate higher total ratings?
- Does review volume affect rating stability?
- Which developers are most responsive to user feedback?
- Does developer engagement correlate with stronger ratings?
- How does filtering by meaningful review volume (>500 reviews) change interpretation?

---

## Key Insights

- High total rating scores are often driven by larger review volume.
- Apps with fewer reviews show greater rating volatility, suggesting limited sample size effects.
- Developers with higher response rates demonstrate stronger engagement with users.
- Helpful review averages provide clearer quality insight than raw rating totals.

---

## Technical Skills Demonstrated

### 🔹 Data Modeling
- Created a many-to-one relationship between `Reviews` and `Apps` tables (`app_id` → `id`)
- Applied visual-level filtering (`reviews_count > 500`) for focused analysis

### 🔹 DAX Calculations
- Built calculated columns using conditional logic
- Created response-rate logic using binary indicators (0/1)
- Used appropriate aggregation functions (SUM vs AVG) based on analytical intent

### 🔹 Data Visualization & Storytelling
- Designed clear, business-friendly visual titles and axis labels
- Replaced auto-generated labels for professional polish
- Added interpretation annotations to support stakeholder understanding
- Structured visuals to compare volume-driven metrics vs quality-driven metrics

---

## Dashboard Components

- KPI: Total Number of Apps
- Review Volume Trend Over Time
- Rating Stability vs Review Volume (Scatterplot)
- Total Rating Score by Developer
- Average Helpful Review Score by Developer
- Developer Response Rate by Developer (Filtered to meaningful review counts)

---

## Tools Used

- Power BI
- DAX
- Data modeling
- Analytical storytelling

---

## Author

Elizabeth Parr  
Aspiring Business Intelligence / Data Analyst  
Focused on Accuracy, Insight & Efficiency