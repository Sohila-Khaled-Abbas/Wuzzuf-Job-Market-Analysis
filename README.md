# Job Market Analytics Dashboard

## 📌 Overview
This Power BI dashboard provides a comprehensive analysis of the job market in Egypt, focusing on hiring trends, job role analysis, and company insights. The data was scraped from Wuzzuf using Python and cleaned using advanced Power BI techniques.

## 🔍 Key Features
- **Real-time insights** into hiring trends
- **Dynamic filtering** using slicers and parameters
- **Advanced DAX measures** for KPI tracking


---

## 📊 Page 1: Job Market Overview
### **Key Insights:**
- **Total Job Postings:** 217
- **Top Hiring City:** New Cairo
- **Top Hiring Company:** Confidential
- **Avg Jobs per Month:** 72

### **Visualizations:**
- **Job Posting Trends** (Line Chart)
  - Shows job postings from January to March 2025.
  - **DAX Title:** `"📈 Job Posting Trends (Jan - Mar 2025)"`
 
- **Top Hiring Companies** (Bar Chart)
  - Highlights the companies with the highest job postings.
  - **DAX Measure:** `TopHiringCompanies`


- **Job Distribution by Cities** (Map)
  - Displays hiring activity across different cities.
  - **DAX Title:** `"📍 Job Openings by Location"`

---

## 📊 Page 2: Job Role Analysis
### **Key Insights:**
- **Most Common Job Title:** Data Analyst
- **Most Requested Skill:** AI
- **Highest Median Salary:** 142K EGP

### **Visualizations:**
- **Top 10 In-Demand Job Titles** (Bar Chart)
  - Highlights the most frequently posted job titles.
  - **DAX Measure:** `Most_Common_Job_Title`

- **Skills Analysis** (Word Cloud)
  - Extracts frequently mentioned skills from job descriptions.
  - **DAX Measure:** `Extracted_Skills`

- **Job Duration Analysis** (Gauge Chart)
  - Measures the average time job listings stay open.
  - **DAX Measure:** `Job_Open_Duration`

---

## 📊 Page 3: Company Insights
### **Key Insights:**
- **Longest Job Openings:** 29 Days
- **Most Stable Location:** New Cairo
- **Top Stable Company:** Confidential
- **Average Salary:** 18.53K EGP

### **Visualizations:**
- **Hiring Trends for Selected Companies** (Stacked Column Chart)
  - Shows hiring trends over time for key companies.
  - **DAX Measure:** `HiringTrends_Companies`

- **Job Stability by Location** (Column Chart)
  - Displays hiring consistency across different locations.
  - **DAX Measure:** `Job_Stability_Score`

- **Hiring Speed Distribution** (Donut Chart)
  - Categorizes job postings based on hiring speed.
  - **DAX Title:** `"⏳ Hiring Speed Categories"`
  - **Conditional Formatting:**
    - 🔴 Urgent Hiring (<10 Days)
    - 🟡 Moderate Hiring (10-30 Days)
    - 🟢 Slow Hiring (>30 Days)

---

## 📌 Tooltip Pages
### **Advanced Tooltips for Contextual Insights**
- **Hiring Demand:** Shows top 3 job titles for selected city.
- **Company Insights:** Displays hiring trends for a selected company.
- **Job Stability:** Highlights locations with the highest job consistency.

---

## 🎨 **Dashboard Design & Formatting**
- **Color Palette:**
  - `#0511F2` (Primary)
  - `#0460D9` (Accent)
  - `#0583F2` (Secondary)
  - `#0468BF` (Highlights)
  - `#0D0D0D` (Background)
- **Conditional Formatting Applied:**
  - Job Growth Rate
  - Hiring Speed
  - Salary Comparisons

---

## 📂 Repository Structure
```
📂 Job-Market-Analytics-Dashboard
│-- 📁 data
│   │-- wuzzuf_jobs_cleaned.csv
│   │-- salaries_table.csv
│-- 📁 reports
│   │-- wuzzuf_jobs_dashboard.pbix
│-- 📁 images
│   │-- page1_overview.png
│   │-- page2_roles.png
│   │-- page3_company.png
│   │-- details_page.png

│-- README.md
```

---

## 🚀 How to Use
1. **Clone the repository**: `git clone https://github.com/Sohila-Khaled-Abbas/Wuzzuf-Job-Market-Analysis.git`
2. **Open `wuzzuf_jobs_dashboard.pbix`** in Power BI.
3. **Customize filters and parameters** to explore different insights.
4. **Use tooltip pages** for in-depth contextual analysis.

---

## 📢 Feedback & Contributions
Feel free to raise issues, suggest improvements, or contribute enhancements to this project!

### 🔗 **Live Dashboard Preview**: [Power BI Service](https://app.powerbi.com/view?r=eyJrIjoiMGNjZmFlOWItMWU3My00ZjM4LTlhYjQtMWY5N2QzOGQwMTAyIiwidCI6IjI1Y2UwMjYxLWJiZDYtNDljZC1hMWUyLTU0MjYwODg2ZDE1OSJ9)

---

