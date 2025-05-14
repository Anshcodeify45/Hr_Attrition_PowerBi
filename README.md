# Hr_Attrition_PowerBi
# Workforce Attrition Dashboard

## 📄 Project Overview  
This interactive Power BI dashboard provides HR and business leaders with a one-stop view into workforce attrition across departments, roles, demographics and tenure. By tracking key metrics and drilling into trends, you can quickly diagnose drivers of turnover and translate data into targeted retention actions.

---

## 🎯 Key Objectives  
- **Monitor Attrition Trends**  
  • Track headcount vs. exits over time  
  • Calculate overall and segment-level attrition rates  
- **Spot Demographic Risk Factors**  
  • Compare age groups, gender splits, and education fields  
  • Highlight where churn is unusually high  
- **Analyze by Role & Department**  
  • Identify high-risk job roles (e.g. Laboratory Technicians, Sales Executives)  
  • Filter for specific business units (HR, R&D, Sales, Manufacturing, etc.)  
- **Drive Actionable Insights**  
  • Built-in commentary panel with top 3–5 recommendations  
  • Executive-ready KPIs for instant status reporting  

---

## 🖥️ Dashboard Pages & Components  

| Page / Section             | Description                                                                                       |
|----------------------------|---------------------------------------------------------------------------------------------------|
| **Overview (Home)**        | Top-line KPIs (Total Employees, Attrition Count & Rate, Avg Age, Avg Salary, Avg Tenure)         |
| **By Job Role**            | Bar chart showing attrition count by each job title; sortable by count and rate                  |
| **By Education Field**     | Donut chart breaking out exits by highest-level qualification (Life Sciences, Medical, etc.)    |
| **By Age Group**           | Column chart comparing churn across age brackets (18–25, 26–35, 36–45, 46–55, 55+)                |
| **By Gender**              | Donut chart split with percentage callouts for male vs. female attrition                          |
| **Dept × Tenure Matrix**   | Small-multiples table showing exits by department and years of service                            |
| **Insights & Actions**     | Narrative panel with bullet-point recommendations based on the data (e.g. “Monitor Overtime…”).   |

---

## 🔧 Tech Stack & Implementation  
- **Power BI Desktop & Service**  
- **Data modeling** with a star schema: Employees → Demographics, Tenure → Attrition facts  
- **DAX measures** for dynamic calculations (e.g. `Attrition Rate = DIVIDE(AttritionCount, TotalEmployees)`)  
- **Slicers & Bookmarks** for seamless filtering (Gender, Department)  
- **Custom theme** (dark background + neon accents) to enhance readability and impact  

---

## 🚀 Getting Started  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Anshcodeify45/Hr_Attrition_PowerBi.git
   cd workforce-attrition-dashboard
