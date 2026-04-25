# Healthcare_dashboard

## 1. 🏷️ Headline

**Ropollo Hospital Performance Dashboard | Patient Insights & Billing Analytics (2022–2024)**

---

## 2. 📋 Purpose

This dashboard provides a comprehensive analytics view of Ropollo Healthcare's hospital operations across **7,157 patient records** spanning December 2022 to March 2024. It empowers hospital administrators and medical staff to monitor patient admissions, track diagnosis and treatment trends, evaluate doctor performance, analyze bed occupancy across ward types, measure diagnostic test usage, and understand billing versus insurance coverage — enabling data-driven decisions for improving patient care and operational efficiency.

---

## 3. 🛠️ Key Technologies Used

- **Microsoft Power BI Desktop** — interactive dashboard creation and visualization (`.pbix`)
- **Microsoft Excel** — primary data source and raw data repository (`.xlsx`)
- **DAX (Data Analysis Expressions)** — calculated KPIs, measures, and custom aggregations in Power BI
- **Power Query (M Language)** — data transformation, date formatting, and cleaning inside Power BI

---

## 4. 📦 Data Source

**More info on where data come from and how it's structured.**
- **Source: Kaggle.**
- **File:** `Ropollo-Healtcare-Dataset.xlsx`
- **Sheet:** `Sheet1`
- **Records:** 7,157 patient entries
- **Date Range:** December 2022 – March 2024
- **Fields (11 columns):**

| Field | Details |
|---|---|
| `Patient_ID` | Unique patient identifier |
| `Admit_Date` / `Discharge_Date` | Hospital stay duration |
| `Diagnosis` | Viral Infection, Typhoid, Malaria, Flu, Pneumonia, Fracture |
| `Bed_Occupancy` | General, ICU, Private |
| `Test` | MRI, CT Scan, X-Ray, Blood Test, Ultrasound |
| `Doctor` | Jay Sinha, Jaya Yaadav, Naresh Goyenka, Tejas Saxena, Mark Joy, Ravi D, Niki Sharma |
| `Followup Date` | Scheduled post-discharge follow-up |
| `Feedback` | Patient satisfaction score (3.5 to 5.0) |
| `Billing Amount` | Total billed (₹1,223 – ₹95,867) |
| `Health Insurance Amount` | Insurance-covered portion of billing |

---

## 5. ✨ Features of the Dashboard

- **Admission & Discharge Trends** — Monthly patient flow tracking over the 15-month period to identify peak admission periods
- **Diagnosis Distribution** — Breakdown of the 6 diagnosis types (Flu, Viral Infection, Malaria, Typhoid, Pneumonia, Fracture) by volume and share
- **Bed Occupancy Analysis** — Visual comparison of General, ICU, and Private ward utilization rates
- **Doctor Performance Overview** — Patient load, average feedback scores, and billing contribution across all 7 doctors
- **Diagnostic Test Usage** — Frequency analysis of MRI, CT Scan, X-Ray, Blood Test, and Ultrasound — showing which tests are most ordered
- **Billing vs. Insurance Coverage** — Side-by-side comparison of total billing amounts against health insurance amounts to reveal out-of-pocket patient burden
- **Patient Feedback / Satisfaction** — Average satisfaction scores per doctor and per diagnosis type (rated 3.5–5.0)
- **Length of Stay Analysis** — Derived from Admit and Discharge dates to identify which diagnoses or ward types result in longer stays
- **Follow-up Scheduling Insights** — Analysis of follow-up patterns after discharge by diagnosis and doctor
- **Interactive Filters / Slicers** — Drill down by date range, diagnosis, doctor, bed type, or test type for dynamic exploration

## 6. ✨ Screenshots of the Dashboard

https://github.com/Goutamee/Healthcare_dashboard/blob/main/Screenshot.png
