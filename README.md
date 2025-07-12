# Web Traffic Analysis Dashboard  
**Power BI Project | Data-Driven Insights for Digital Strategy**

---

## 🧠 Project Overview

The **Web Traffic Analysis Dashboard** is a Power BI-driven solution designed to transform raw web analytics into strategic insights. It focuses on key digital KPIs such as sessions, bounce rate, device usage, and conversion performance, allowing marketers, analysts, and stakeholders to monitor website engagement and optimize user experience.

This dashboard brings clarity and interactivity into one workspace—turning data into decisions.

---

## 🎯 Objectives

- Analyze user behavior trends over time
- Monitor website performance using dynamic KPIs
- Identify high-performing traffic sources and devices
- Enable data-driven decisions for digital optimization

---

## 🛠 Tools and Technologies Used

| Tool            | Purpose                                 |
|-----------------|------------------------------------------|
| Power BI        | Visualization and dashboard development  |
| DAX             | KPI calculations and custom measures     |
| Power Query     | Data transformation and shaping          |
| Excel           | Initial data structuring and formatting  |
| Data Modeling   | Table relationships and schema design    |

---

## 📂 Dataset Overview

The dataset contains real-world-style web analytics information including:

- Session Date and Time
- Traffic Source / Medium
- Device Category (Mobile, Desktop, Tablet)
- Bounce Rate
- Avg. Session Duration
- Conversion Indicator
- Pages per Session
- Landing Page URLs

It simulates user-level session data typically tracked via platforms like Google Analytics.

---

## 🧹 Data Cleaning & Preparation

Performed in Power Query and Excel:

- Removed duplicates and empty records
- Normalized inconsistent source/medium values
- Parsed datetime fields into proper components
- Created calculated columns for engagement levels and performance groupings
- Built star-schema data model in Power BI

---

## 📌 Key KPIs

- Total Sessions  
- Unique Users  
- Bounce Rate (%)  
- Avg. Session Duration (mm:ss)  
- Pages per Session  
- Conversion Rate (%)  
- Sessions by Device Type  
- Traffic Channel Contribution

All KPIs were calculated using **DAX** and support time-sliced and dimension-filtered analysis.

---

## 🎨 Dashboard Design Strategy

- Clean and light theme with accent colors
- Filters (slicers) for device, traffic source, and date range
- Bookmark navigation and tooltip pages
- Drill-through pages for landing page and traffic channel deep-dives
- Responsive layout designed for clarity and interaction

---

## 📈 Visualizations

### Chart 1 – Sessions Over Time  
[Insert Chart Here]  
Displays user traffic trends by day/week/month. Useful for understanding traffic patterns.

### Chart 2 – Bounce Rate by Source  
[Insert Chart Here]  
Compares engagement quality across various sources (Organic, Referral, Social, Direct).

### Chart 3 – Device Usage  
[Insert Chart Here]  
Shows session counts by device type (Desktop, Mobile, Tablet).

### Chart 4 – Conversion vs. Bounce  
[Insert Chart Here]  
Visualizes conversion efficiency vs. bounce risk.

### Chart 5 – Top Landing Pages  
[Insert Chart Here]  
Highlights high-traffic landing pages with performance metrics.

### Chart 6 – Channel Contribution  
[Insert Chart Here]  
Shows contribution of each source to sessions and conversions.

---

## 🔍 Insights Summary

- Organic search drives the most sessions but has a lower conversion rate than Direct traffic.
- Mobile sessions dominate but have lower average session duration.
- Bounce rate is significantly higher for Social Media traffic.
- Referral traffic shows higher engagement with better conversion rates.
- Midweek and early afternoon are peak session periods.

---

## ⚙️ Challenges Faced

| Issue | Resolution |
|-------|------------|
| Inconsistent source/medium labels | Cleaned via Power Query transformations |
| Bounce rate missing for some entries | Handled using DAX with `BLANK()` defaults |
| Session duration in raw seconds | Converted to readable time format via calculated columns |
| Need for cross-KPI filtering | Used slicers, drill-through, and bookmarks for UX optimization |

---

## 🧠 Business Applications

- Evaluate content strategy and UX performance
- Inform marketing campaign scheduling
- Improve mobile site experience based on traffic analysis
- Identify high-performing acquisition channels

---

## 🚀 Future Enhancements

- Connect to live Google Analytics API
- Add demographic segmentation
- Compare new vs. returning user behavior
- A/B testing insights panel

---

## 📌 Repository Contents

- `.pbix` Power BI File  
- Sample dataset (`.csv` or `.xlsx`)  
- Screenshot folder for dashboard visuals  
- `README.md` documentation  

---

## 📋 Author

**Abdullah Imran**  
Data Analyst | Business Intelligence | Power BI Developer

- 📧 Email: [abdullahimran017@gmail.com](mailto:abdullahimran017@gmail.com)  
- 🔗 LinkedIn: [linkedin.com/in/abdullah-imran-211658230](https://www.linkedin.com/in/abdullah-imran-211658230/)  
- 💻 GitHub: [github.com/MirAb-77](https://github.com/MirAb-77)

---

## ⭐ Connect & Feedback

If you found this project insightful or would like to collaborate, feel free to connect via [LinkedIn](https://www.linkedin.com/in/abdullah-imran-211658230/) or explore more projects on my [GitHub](https://github.com/MirAb-77). Contributions, suggestions, or questions are always welcome.

---

