# 🏥 Hospital Emergency Room (ER) Data Analysis & Visualization

> **DAV Mini Project** | Data Analysis & Visualization  
> **Tools Used:** Power BI / Tableau, Excel, Power Query, DAX  

---

## 📌 Project Overview

Hospital Emergency Rooms (ER) operate in high-pressure environments where long wait times can impact patient care. This project analyzes emergency room patient intake, waiting times, triage severity levels, and department referrals to help hospital administrators reduce bottlenecks and improve operational efficiency.

By transforming raw clinical logs into an interactive **Business Intelligence Dashboard**, this project provides clear, data-driven insights for real-time decision-making.

---

## 🎯 Objectives

- **Analyze Patient Intake:** Identify peak arrival hours, days, and seasonal trends.
- **Track Wait Times:** Measure average wait times across different triage severity levels.
- **Segment Demographics:** Categorize patient trends across age groups and gender.
- **Spot Bottlenecks:** Identify delays in department referrals and patient admissions.
- **Interactive Dashboard:** Build an easy-to-use dashboard with dynamic slicers and visual filters.

---

## 🛠️ Tech Stack & Tools

- **Data Cleaning & ETL:** Power Query (Excel / Power BI)
- **Data Modeling & DAX:** Custom metrics (Average Wait Time, Admission Rate, Critical Care Ratio)
- **Data Visualization:** Power BI Desktop
- **Documentation:** Markdown & PowerPoint

---

## 📊 Key Insights & Findings

1. **Peak Hours:** Patient arrivals spike significantly between **6:00 PM and 10:00 PM**.
2. **Busy Days:** **Mondays** experience the highest intake volume of the week.
3. **Triage Severity:** Non-urgent cases (Triage 4 & 5) make up **~42%** of total visits, causing queues during peak hours.
4. **Senior Care (60+):** Patients aged 60+ have the highest admission rate (**~62%**) and require prioritized care pathways.

---

## 💡 Recommendations

- **Staggered Staff Shifts:** Reallocate nursing staff to cover the 4:00 PM – 12:00 AM peak window.
- **Fast-Track Queue:** Set up a dedicated clinic desk for minor, non-urgent cases (Triage 4 & 5).
- **Streamlined Admissions:** Create fast-track hospital admission pathways for senior patients.

---

## 🗂️ Project Repository Structure

```text
├── Data/
│   └── ER_Patient_Data.csv      # Raw dataset
├── Dashboard/
│   └── ER_Analytics.pbix        # Power BI Dashboard file
├── Presentation/
│   └── DAV_Mini_Project.pptx    # Project presentation deck
├── Report/
│   └── DAV_Project_Report.pdf   # Detailed project report
└── README.md                    # Project overview file
