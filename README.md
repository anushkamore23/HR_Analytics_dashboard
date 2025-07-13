# 👩‍💼 HR Analytics - Employee Presence Insights Dashboard

A **Power BI Dashboard** designed to help the HR team understand employee working preferences (WFH vs WFO), sick leave usage, and attendance behavior across multiple months.

---

## 📌 Problem Statement

The HR department wants to analyze:
- Whether employees prefer **Work From Home (WFH)** or **Work From Office (WFO)**
- The percentage of **Sick Leaves (SL%)** taken
- Overall **Presence/Attendance** rates
- Trends based on **Day of the Week**

---

## 📊 Dashboard Highlights

| Component                      | Insight Provided                                    |
|-------------------------------|-----------------------------------------------------|
| ✅ KPI Cards                  | Quick view of Present %, WFH %, SL %               |
| 📆 Monthly Slicer             | Analyze April, May, June 2022 separately            |
| 📈 Line Charts                | Trends for Present %, WFH %, SL % over time         |
| 🧾 Detailed Log               | Individual presence markings over dates             |
| 📊 Day-of-week Analysis       | Best/Worst days for WFH, Attendance, or SL          |
| 👤 Employee Table             | Sorted view of WFH and Present % per person         |

---

## 📁 Dataset

- Includes fields like: `Name`, `Date`, `Presence Status`, `WFH`, `SL`, etc.
- Format: `.csv` or integrated directly in Power BI

---

## 📎 Files Included

- `HR_Presence_Insights.pbix` – Main Power BI dashboard file
- `attendance_data.csv` – Optional sample dataset
- `screenshots/hr_dashboard_preview.png` – Dashboard preview image

---

## 📸 Dashboard Preview
<img width="1000" height="1000" alt="HR_analytics" src="https://github.com/user-attachments/assets/c7d1f829-9869-4135-86f3-7e719bdec238" />

---

## 🚀 How to Use

1. Download and open the `HR_Presence_Insights.pbix` file in Power BI Desktop.
2. Use the **Month slicer** to filter results by April, May, or June.
3. Analyze key patterns using:
   - Line charts (for trends)
   - Day-of-week breakdowns
   - Employee-wise WFH/Presence %

---

## 🔧 Tools Used

| Tool         | Purpose                        |
|--------------|-------------------------------|
| Power BI     | Dashboard development          |
| Excel / CSV  | Data source                    |
| DAX & M Query| Data transformation & modeling |

---

## 💡 Insights Example

- 📅 **Tuesday** is the most present day at 93.03%
- 📊 **Friday** has the highest WFH % at 13.01%
- 🤒 **SL%** peaked at 3.80% in late June
- 👤 Some employees had **100% WFH** (e.g., Thanos Thakur)



