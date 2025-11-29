# Clinical-Trial-Analytics-Dashboard-Power-BI
# 🧬 Clinical Trial Analytics Dashboard (Power BI)

## 📌 Project Overview  
This project presents a complete **Clinical Trial Analytics Dashboard** built using **Power BI** and a fully synthetic, patient-level clinical trial dataset (1200 subjects, 15 sites, 10 planned visits).  
The dataset mimics real-world CDISC-style domains and demonstrates analytics typically performed in clinical trials and CRO environments.

This project showcases skills relevant for:

- Clinical Data Analyst  
- Healthcare Data Analyst  
- Product/Business Analyst (Healthcare)  
- Real-World Evidence / Biometrics Teams  
- Data Analyst roles in pharma, CROs, and healthcare organizations  

---

## 🎯 Key Dashboard Features

### **1️⃣ Study Overview**
- Total subjects, treatment arms, countries, and sites  
- Enrollment distribution by geography  
- Demographic summaries (age, race, sex)  
- Subjects per treatment arm and site  

### **2️⃣ Visit Compliance**
- Completed vs missed visits  
- Visit window deviation (Early / On-Time / Late)  
- Compliance trends across all 10 planned visits  
- Subject-level visit details  

### **3️⃣ Safety (Adverse Events)**
- AEs by severity (Mild / Moderate / Severe)  
- Serious vs Non-serious AEs  
- AE counts by treatment arm  
- Most frequent AE terms  
- Subject-level AE logs  

### **4️⃣ Labs & Vitals**
- Lab abnormality distribution (LOW / NORMAL / HIGH)  
- Trends for key lab parameters (ALT, AST, HGB, PLT, Creatinine)  
- Vital trends by visit (SBP, DBP, HR, Weight)  
- Comparisons across treatment arms  

---

## 🗂️ Dataset Description

This project uses a **synthetic but realistic clinical trial dataset** generated to resemble CDISC SDTM-like structures.

### **Included Data Domains**

| File Name        | Description |
|------------------|-------------|
| `dm.csv`         | Demographics: age, sex, race, site, arm, randomization date |
| `sites.csv`      | Site metadata: country, region, investigator |
| `randomization.csv` | Treatment arm allocation + stratification |
| `visits.csv`     | Planned vs actual visit dates, completion, window flag |
| `exposure.csv`   | Drug exposure, dose, start/end treatment dates |
| `ae.csv`         | Adverse events: severity, seriousness, outcome, duration |
| `vs.csv`         | Vital signs: SBP, DBP, HR, Weight per visit |
| `lb.csv`         | Laboratory values: LBVAL, LLN, ULN, abnormal flag |

### **Data Volume**
- **1200 subjects**
- **15 sites**
- **~12,000 visit records**
- **1300+ adverse event records**
- **10,000+ lab records**

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop**  
- **Power Query / DAX**  
- **Python (for dataset generation)**  
- **CSV / Excel**  

---

## 🗃️ Folder Structure
