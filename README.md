# ❤️ Healthcare Patient Risk Analysis Dashboard

An analytical Power BI dashboard designed to assess and visualize health risks across a population of 5,191 patients, focusing on demographics, pre-existing conditions, and lifestyle factors.

### Short Description / Purpose

This dashboard serves as an interactive tool for healthcare providers, public health analysts, and hospital administrators. Its primary purpose is to identify at-risk patient cohorts by analyzing key health indicators like stroke history, heart attack rates, and overall health risks. The insights generated can be used to develop targeted preventative care programs and allocate medical resources more effectively.

### Tech Stack

The dashboard was built using the following tools:
* 📊 **Power BI Desktop** – Main data visualization and report creation platform.
* 📂 **Power Query** – Used for data cleaning, transformation, and preparation.
* 🧠 **DAX (Data Analysis Expressions)** – Implemented for creating key measures and KPIs.
* 📝 **Data Modeling** – Established relationships between data tables to enable interactive cross-filtering.

### Data Source
**(Please update this section)**
The analysis is based on a fictional healthcare dataset containing patient demographic and health information. The data likely includes fields such as `Patient ID`, `Zone`, `Gender`, `Age Group`, `Health Status`, `Health Risk`, `Exercise Habits`, `Stroke`, and `Heart Attack` history.
*(Note: The provided dataset image was for a different project, so the data structure has been inferred from the dashboard visuals.)*

---

## Features / Highlights

### Business Problem
In healthcare, proactive and preventative care is essential for improving patient outcomes and managing costs. To achieve this, providers need a quick and effective way to segment their patient population and identify individuals at high risk for serious health events. Key questions include:
* What are the most prevalent health risks in the patient population?
* What percentage of patients have a history of stroke or heart attack?
* How do factors like gender, age, and exercise correlate with specific health risks?
* Are there patient groups with high risk but otherwise good health that would be ideal for early intervention?

### Goal of the Dashboard
To deliver a clear, interactive visual tool that enables users to:
* Explore the distribution of patients across various health risk categories.
* Identify correlations between patient demographics, lifestyle, and health outcomes.
* Support data-driven decisions for preventative medicine and patient outreach programs.

### Walkthrough of Key Visuals

* **Key KPIs (Top Row)**
    * **Total Patients:** The report analyzes a total of `5,191` patients.
    * **Patient Segmentation:** The population is broken down by gender and weight status: `Female Overweight` (`1616`), `Female Not Overweight` (`1409`), `Male Overweight` (`1373`), and `Male Not Overweight` (`793`).

* **Risk and Condition Analysis**
    * **Count of Zone by healthRisk (Bar Chart):** The `normal` health risk category contains the largest number of patients (approx. 2.5K), followed by `moderate high` (approx. 1.5K).
    * **%GT Count of Zone by Stroke (Donut Chart):** `98.27%` of the patient population has no history of stroke, while `1.73%` does.
    * **HeartAttack %GT (Table):** Similar to stroke, `97.26%` of patients have not had a heart attack, while `2.74%` have.

* **Correlated Insights**
    * **Count of Zone by Health and healthRisk (Area Chart):** This chart reveals that a large number of patients with a `critical` health risk also report being in `Good` or `VeryGood` health, highlighting a potential group for preventative action.
    * **Exercise & HealthRisk Breakdown (Table):** Provides a granular view of patient counts based on exercise levels and health risk. For example, among patients with `<30` exercise, `1434` are in the `normal` risk category and `688` are in the `moderate high` risk category.

### Business Impact & Insights
* **Targeted Intervention Opportunity:** The dashboard identifies a key patient segment: individuals with a "critical" healthRisk who still maintain "Good" overall health. This group is ideal for targeted preventative care to avoid future health degradation.
* **Low Prevalence of Major Events:** The overall incidence of stroke (`1.73%`) and heart attack (`2.74%`) is low in this population, suggesting the majority of patients can be managed with preventative rather than acute care.
* **Demographic Focus:** The patient population consists of more females (3,025) than males (2,166). Wellness programs could be tailored with this gender distribution in mind.
* **Lifestyle Correlation:** The dashboard allows for a deep dive into how exercise habits correlate with health risks across different age groups, enabling the creation of specific wellness recommendations.

### Screenshots / Demos

![Healthcare Patient Dashboard](https://github.com/Dhaval-DS/HEALTHCARE-PATIENT-DASHBOARD/blob/main/HealthcarePatient-Dashboard.png)
