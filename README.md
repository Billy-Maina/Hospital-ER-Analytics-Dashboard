# Hospital Emergency Room Analytics Dashboard

## Project Overview  
This end-to-end analytics project explores emergency room operations over a 19-month period, transforming raw patient records into meaningful insights that support operational improvement, resource planning, patient satisfaction tracking, and healthcare decision-making.  

Using **Power BI**, the solution analyzes patient demographics, wait times, admission patterns, referral trends, and volume behavior across time, enabling leaders to identify inefficiencies, bottlenecks, and improvement opportunities across emergency services.

<img width="919" height="558" alt="Monthly View" src="https://github.com/user-attachments/assets/6ba4cc61-79c7-4504-bab3-fcd7b27c2b27" />


---

## Business Need & Problem Statement  

The hospital requires a clear understanding of emergency room activity to improve operational efficiency, patient care quality, and staffing strategies. Key questions included:

- How many patients visit the ER and how do volumes fluctuate over time?
- What are the wait times and how do they impact satisfaction?
- Which demographic groups and departments receive the most referrals?
- When are peak visit hours and days?
- What proportion of patients are admitted vs. discharged?

The objective was to build interactive dashboards that enable stakeholders to:

- Monitor patient trends across time
- Identify peak operating periods for staffing optimization
- Understand demographic patterns affecting patient demand
- Evaluate care quality metrics such as wait time and satisfaction score
- Support strategic planning through evidence-based insights

---

##  Analytical Objectives

- Measure ER activity metrics such as patient count, referrals, and admissions.
- Monitor patient wait times and compare performance monthly and across ranges.
- Analyze demographic distributions: age, gender, race, and referral departments.
- Identify busiest days and hours for optimized staffing and resource planning.
- Assess patient satisfaction against operational efficiency indicators.
- Enable drill-down and case-level exploration for audit and quality control purposes.

---

## Workflow Summary

| Stage | Description |
|-------|------------|
| **1. Requirement Gathering** | Understood core metrics, reporting expectations, and operational priorities. |
| **2. Data Walkthrough** | Reviewed dataset structure, granularity, and context of medical processes. |
| **3. Data Connection** | Connected the cleaned Excel dataset to Power BI. |
| **4. Data Cleaning** | Standardized fields, fixed categorical inconsistencies, and validated quality. |
| **5. Data Modeling** | Built a clean, scalable star-schema model for analysis and filtering. |
| **6. DAX Calculations** | Created measures for admissions, wait times, satisfaction scoring, timeliness %, and demographic aggregations. |
| **7. Visualization Development** | Built dynamic dashboards with slicers, bookmarks, and drill-through logic. |
| **8. Insights Generation** | Interpreted trends and patterns into strategic operational recommendations. |

#### Model:

<img width="1246" height="562" alt="Model" src="https://github.com/user-attachments/assets/fe89b498-c040-4972-ac3a-e05d2414a379" />

---

## Dashboards & Visualizations

### 1️⃣ **Monthly View**
A focused monthly performance report visualizing emergency room activity trends, including patient volume, wait-time behavior, referral distribution, and demographic patterns across age, gender, and race. It also highlights service efficiency through the percentage of patients seen within the target response time and uncovers peak visitation days and hours to support operational planning and resource allocation.

<img width="919" height="558" alt="Monthly View" src="https://github.com/user-attachments/assets/1e917690-0b71-49ec-b58d-1ff323e5a4fe" />

---

### 2️⃣ **Consolidated View**  
This dashboard provides a concise, high-level overview for any selected time period, designed for leadership reporting. It highlights total patients served, average wait times, satisfaction scores, admission versus non-admission rates, demographic and referral insights, and a visit frequency heatmap.

<img width="918" height="559" alt="Consolidated View" src="https://github.com/user-attachments/assets/f8e98b39-1a79-416f-998d-af54c94c9563" />


---

### 3️⃣ **Patient Details View**
This table offers a detailed, record-level view to support audit validation, compliance, and case tracking. It includes patient IDs and demographics, referral departments, wait times, admission status, and service timestamps.

<img width="918" height="558" alt="Patients Details" src="https://github.com/user-attachments/assets/9039c333-f447-41c5-b4cb-377ec1b8cfb7" />


---

### 4️⃣ **Key Takeaways**
A narrative summary dashboard presenting insights, anomalies, and operational signals.

<img width="918" height="559" alt="Key Takeaways" src="https://github.com/user-attachments/assets/1434c306-ffd0-45fb-983e-4c8a98733bdf" />


---

## DAX Calculations Summary  

Core DAX was used to compute behavioral metrics, quality indicators, and operational aggregations, including:

- Total patients served  
- Average and grouped wait time  
- Admission rate  
- Referral breakdown  
- Demographic segmentation  
- Time-based volume aggregations  
- KPI target performance (within 30-minute standard)

<img width="970" height="321" alt="Waiting Interval Calculated  column" src="https://github.com/user-attachments/assets/77fb7929-fa52-4ea8-8e1f-fd65c6fc27b8" />


---

## Key Insights

- **Patient volume is highest on Mondays, Saturdays, and Tuesdays**, indicating strategic staffing opportunities.
- **Average wait time of ~35.3 minutes suggests delays** requiring operational improvements.
- **Nearly 50% of patients required referrals**, with **General Practice and Orthopedics leading demand**.
- **Peak hours occur midday and late evening**, signaling high-traffic treatment windows.
- **Adults ages 30–50 represent the largest demographic group**, with significant representation across middle-aged and elderly groups.
- **Satisfaction score averages ~4.99**, indicating a generally positive patient experience with opportunities for improvement linked to waiting time.

## Recommendations  

Based on the insights drawn, the following actions are recommended to guide operational and strategic decision-making:  

- **Optimize Staffing**: Adjust staff schedules to match peak patient volumes (Mondays, Tuesdays, Saturdays, midday and late evening) and ensure coverage in high-demand departments like General Practice and Orthopedics.  
- **Reduce Wait Times**: Streamline triage and patient flow processes to target the 30-minute wait standard, minimizing bottlenecks during peak hours.  
- **Manage Referrals Efficiently**: Review referral patterns to balance departmental workload and improve patient routing.  
- **Enhance Patient Experience**: Focus on middle-aged and elderly patient groups with tailored care strategies and monitor satisfaction trends linked to wait times.  
- **Leverage Data Continuously**: Use dashboards for ongoing monitoring, audit validation, and evidence-based decision-making to sustain improvements.  

**Next Step:** Implement these recommendations and continuously monitor KPIs through the dashboards to ensure operational efficiency, improved patient outcomes, and informed leadership decisions.  

---

##  Tools & Technologies

| Component | Technology |
|----------|------------|
| Data Source | Excel |
| ETL & Cleaning | Power Query |
| Data Modeling | Power BI |
| Calculations | DAX |
| Visualization | Power BI Dashboards |
| User Interaction | Slicers, Bookmarks, Drill-Through, Conditional Formatting |

---

## Repository Includes

✔ `.pbix` dashboard  
✔ Dataset (cleaned version )  
✔ Screenshots of all dashboards  
✔ Full project documentation including KPIs and insights  

---

## Summary

This project demonstrates how healthcare operations data can be transformed into actionable intelligence. The dashboards support hospital leaders in improving emergency room efficiency, optimizing staffing schedules, and enhancing patient care experience based on data-driven evidence.

---

