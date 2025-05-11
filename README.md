# HealthCare_Analysis
# 🏥 Healthcare Analysis – Power BI Dashboard

This repository presents a comprehensive Power BI dashboard analyzing hospital discharge data from the New York State Department of Health. The dashboard delivers insights into patient demographics, clinical procedures, geographic distribution, and healthcare costs across multiple facilities and regions.

---

## 🎯 Objective

To empower healthcare stakeholders with data-driven insights that reveal:
- Patterns in hospital admissions and discharges.
- Key drivers of healthcare costs.
- High-risk patient segments based on clinical severity and demographics.
- Geographic and institutional disparities in care delivery.

---

## 🗂️ Dataset Overview

The dataset includes structured hospital discharge records with the following attributes:

### 📍 Geographic Information
- `health_service_area` – Region where the hospital is located.
- `hospital_county` – County of the facility.
- `zip_code_3_digits` – First three digits of patient ZIP (anonymized).

### 👤 Patient Demographics
- `age_group` – Patient age group (e.g., 0–17, 18–29, etc.).
- `gender` – Male, Female, Unknown.
- `race`, `ethnicity` – Self-identified.

### 🏥 Admission & Discharge Details
- `type_of_admission` – Emergency, Elective, Trauma, etc.
- `patient_disposition` – Outcome/status at discharge.
- `length_of_stay` – Total days hospitalized.
- `discharge_year` – Year of discharge.

### 🧬 Clinical Information
- `ccs_diagnosis_code` / `description` – Diagnosis classification.
- `ccs_procedure_code` / `description` – Procedure classification.
- `apr_drg_code` / `description` – DRG classification group.
- `apr_severity_of_illness_code` – Severity level (1–4).
- `apr_risk_of_mortality` – Mortality risk level (1–4).
- `apr_medical_surgical_description` – Surgical/medical classification.

### 🧑‍⚕️ Provider & Facility Data
- `facility_name`, `facility_id`, `operating_certificate_number`
- `attending_provider_license_number`, `operating_provider_license_number`

### 💰 Financial Metrics
- `total_charges` – Amount billed.
- `total_costs` – Estimated cost of services.

---

## 📊 Dashboard Features

- 📌 **Filters** by year, region, gender, race, admission type, diagnosis, and more.
- 🧑‍⚕️ **Clinical Analysis**: Top diagnoses, procedures, and length of stay by severity or risk of mortality.
- 🗺 **Geographic Mapping**: County-level insights on discharges, costs, and severity.
- 💰 **Cost Comparison**: Analyze billed vs actual costs by hospital, procedure, and diagnosis.
- 📈 **Trends Over Time**: Track admissions, average stay, and total cost over multiple years.
- 🧬 **Risk Stratification**: Identify patient segments with higher severity or mortality risk.

---

## 🛠 Tools Used

- **Power BI Desktop**
- **Power Query (M Language)** – For data transformation and ETL.
- **DAX (Data Analysis Expressions)** – For measures, KPIs, and custom calculations.

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Healthcare_Analysis.pbix` in Power BI Desktop.
3. Use slicers and filters to explore patient populations, costs, and diagnoses.
4. Hover over visuals for tooltips and breakdowns.
5. Share insights with teams by publishing the dashboard to Power BI Service.

---

## 🔄 Future Enhancements

- ➕ Add more recent years of data for extended trend analysis.
- 📉 Integrate predictive analytics for admission or cost forecasting.
- 🔐 Implement row-level security for hospital-level access control.
- 📱 Optimize for mobile and embedded dashboard use.

---

## 📬 Contact

- 📧 Email: islamshawabkeh12@gmail.com  
- 🔗 [LinkedIn](https://www.linkedin.com/in/islamalshawabkeh)  
- 💻 [GitHub Portfolio](https://github.com/islamalshawabkeh/Data_Analysis.git)

---

> ⭐ *If you found this project helpful, consider starring the repository and sharing it with others!*
