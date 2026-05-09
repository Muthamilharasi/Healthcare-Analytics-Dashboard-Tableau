# 🏥 Healthcare Analytics Dashboard — Tableau

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## 📌 Project Overview
An interactive Healthcare Analytics Dashboard built using **Tableau**,
analyzing patient data across hospitals, medical conditions, billing,
and admissions to uncover actionable insights.

---

## 📊 Dashboard Features

| Feature | Description |
|---|---|
| 🏥 Medical Condition Analysis | Patient count by condition |
| 📅 Admission Trends | Monthly patient volume over time |
| 💰 Billing Analysis | Average billing by hospital |
| ⏱️ Length of Stay | Custom calculated field (DATEDIFF) |
| 👥 Demographics | Gender & Age distribution |
| 🧪 Test Results | Breakdown of patient test outcomes |
| 🔍 Global Filters | Interactive filters across all sheets |

---

## 🔍 Key Insights Discovered

### 📈 Insight 1 — Obesity Affects Young People the Most
> Young age groups recorded the **highest admission rates for Obesity**

- Younger patients dominate obesity-related admissions
- Suggests urgent need for **early preventive care programs**
- Linked to sedentary lifestyle, dietary habits & mental health

### 📈 Insight 2 — Arthritis is the #1 Most Common Condition
> **Arthritis had the highest patient count** across all age groups

- Affects patients across ALL age groups
- Most underestimated chronic condition in public health
- High volume = high resource allocation needed

### 💡 Conditions Summary Table
| Condition | Most Affected Group | Key Takeaway |
|---|---|---|
| Obesity | Young patients | Early intervention needed |
| Arthritis | All age groups | Highest overall burden |
| Diabetes | Middle-aged | Lifestyle disease trend |
| Hypertension | Older patients | Monitoring critical |

---

## 🛠️ Tools & Techniques
- **Tool:** Tableau Desktop / Tableau Online
- **Calculated Fields:** `DATEDIFF('day',[Date of Admission],[Discharge Date])`
- **Layout:** Tiled containers (Horizontal + Vertical)
- **Interactivity:** Global Filters + Dashboard Actions
- **Chart Types:** Bar, Line, Pie, Histogram, KPI Cards

---

## 🗂️ Dataset Fields
- Admission Type, Blood Type
- Date of Admission, Discharge Date
- Doctor, Gender, Hospital
- Insurance Provider, Medical Condition
- Medication, Age, Billing Amount
- Test Results, Room Number

---

## 📁 Project Structure
healthcare-tableau-dashboard/
│
├── data/
│   └── cleaned_Health_care_data.csv
├── dashboard/
│   └── Healthcare_Dashboard.twbx
├── screenshots/
│   └── dashboard_preview.png
└── README.md

---

## 🚀 How to Use
1. Clone this repository
   git clone https://github.com/yourusername/healthcare-tableau-dashboard.git
2. Open Healthcare_Dashboard.twbx in Tableau Desktop
3. Explore using the global filters on the dashboard

---

## 🙋‍♀️ Author
**Muthamilharasi G.R**
📧 [Your Email]
🔗 [Your LinkedIn Profile]

⭐ If you found this helpful, please star this repo!
