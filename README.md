# Healthcare-Analytics-Dashboard
🏥 **Healthcare Analytics Dashboard** (Power BI)

This project presents a complete Healthcare Analytics Dashboard built using Power BI and SQL, analyzing a 19-month emergency room dataset (Apr 2023 – Oct 2024). The dashboard provides insights into patient flow, wait times, demographics, referral patterns, and overall hospital performance.

🚀 **Objective**

To analyze emergency room operations and uncover insights into patient volume, admission patterns, wait times, and referral behavior.
The project focuses on data cleaning, modeling, and visualization to help healthcare teams improve patient care, staffing, and resource allocation.

📁 ** Dataset Summary**

The dataset simulates real-world emergency room activity and includes:

9,216 patient encounters

Patient demographics (age, gender, race)

Wait times & satisfaction scores

Admission vs. non-admission records

Department referrals

Hourly & daily visit patterns

Includes intentional inconsistencies (nulls, mixed date formats, irregular categories) for realistic data-cleaning practice.

🧹 **Data Cleaning & Validation**

Performed using SQL + Power Query to prepare high-quality analytical data.

Key steps:

Removed duplicates and cleaned null values

Standardized date formats (Y-Q-M-D hierarchy)

Validated age ranges and categorical fields

Cleaned race, gender, and referral categories

Created a Date dimension for time intelligence

Modeled fact tables for Patients, WaitTime, Referrals

Key Columns Used:

PatientID, Gender, Age, Race

Admission Status

Wait Time

Referral Department

Date (Year, Quarter, Month, Day)

📌** Key KPIs & Visualizations**
KPI	Description	Visualization
👥 Total Patients	Count of unique ER visits	KPI Card
⏱️ Avg Wait Time	Avg time patients waited before service	KPI Card
⭐ Patient Satisfaction Score	Avg feedback score	KPI Card
↪️ Patients Referred	Count of patients sent to departments	KPI Card
🕒 % Seen Within 30 Min	Service efficiency metric	Donut Chart
👶 Patients by Age Group	Volume by age bracket	Bar Chart
🚹🚺 Patients by Gender	Male–Female distribution	Donut Chart
🌎 Race Distribution	Patient diversity	Horizontal Bars
🧭 Visits by Day & Hour	Peaks across weekdays & hours	Heatmap
🏥 Department Referrals	Top referred specialties	Bar Chart
🖥️ Dashboard Pages
1️⃣ Monthly View (Apr 2024)

Short-term snapshot showing:

469 patients

Avg wait time: 35 min

57% seen within 30 min

Peak age groups: 20–29 & 30–39

Busiest: Tuesday

Top referrals: General Practice & Orthopedics

2️⃣ Consolidated View (Apr 2023 – Oct 2024)

Full 19-month overview showing:

9,216 total patients

35.3 min avg wait time

50% admitted, 50% not admitted

Busiest days: Monday, Saturday, Tuesday

Largest age groups: 30–39 and 20–29

5.4K patients with no referral

3️⃣ Patient Details

A drill-down table with:
Patient ID, Gender, Age, Race, Wait Time, Referral Department, Admission Status, and full date breakdown.

4️⃣ Key Takeaways (Summary Page)

High patient volume across 19 months

Satisfaction score remains strong (4.99)

Referrals dominated by General Practice & Orthopedics

Peak hours around 11 AM & 7 PM

Diverse racial demographics

Nearly equal admitted vs non-admitted patients

🧮 **Tools & Technologies**

SQL Server → Data cleaning & validation

Power BI → Data modeling, DAX, dashboard creation

DAX → Custom KPIs & time-intelligence metrics

Power Query → ETL & data shaping

Excel → Initial data review

🧠 **Key Insights**

High evening & late-night traffic requires optimized staffing

Nearly half of patients do not require specialist referrals

Young and middle-aged groups form the majority of ER visits

Balanced admission vs non-admission shows diverse case severity

Consistently high satisfaction score (4.9+) indicates good patient experience

📸 **Dashboard Preview**

<img width="1555" height="957" alt="Screenshot 2025-11-25 164340" src="https://github.com/user-attachments/assets/7fa7a160-4389-42c3-ac5f-2caad99061e7" />
<img width="1553" height="949" alt="Screenshot 2025-11-25 164403" src="https://github.com/user-attachments/assets/915d5d0a-699c-4823-9c56-4a11cb8eb3bb" />
<img width="1548" height="949" alt="Screenshot 2025-11-25 164422" src="https://github.com/user-attachments/assets/829f79e3-ed01-40ef-9f4c-7c492a7e222e" />
<img width="1551" height="947" alt="Screenshot 2025-11-25 164435" src="https://github.com/user-attachments/assets/e9292fdc-b45f-473e-b355-6546a3a5514f" />


✅ **Conclusion**

The Healthcare Analytics Dashboard provides a clear view of patient trends, operational efficiency, and referral behavior. It demonstrates strong skills in data cleaning, modeling, DAX, and dashboard storytelling, enabling healthcare teams to make informed decisions and improve emergency care delivery.
