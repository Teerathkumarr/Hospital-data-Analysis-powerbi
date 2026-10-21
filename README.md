# Hospital-data-Analysis-powerbi

Introduction
Healthcare analytics applies data analysis techniques to hospital and patient data in order to identify patterns in admissions, diagnoses, treatment costs, and resource utilization. These insights help hospital management make informed decisions about staffing, department efficiency, and patient care quality.
This project analyzes hospital patient data using Power BI to extract meaningful insights such as patient distribution, disease trends, department performance, and hospital revenue. The objective is to build an interactive dashboard that summarizes key hospital metrics and to present the resulting insights in a clear, structured report.


2. Dataset Description
The dataset used in this project was obtained from Kaggle: [insert exact dataset name / link here]. It contains [insert number] patient records across [insert number] columns, covering demographic details, diagnosis information, admission and discharge dates, treating doctor and department, and treatment cost.
The table below describes the key columns used in the analysis:
Column	Description
Patient_ID	Unique identifier assigned to each patient record
Age	Age of the patient at the time of admission
Gender	Gender of the patient (Male / Female)
Disease / Diagnosis	Primary diagnosis recorded for the patient
Admission_Date	Date the patient was admitted to the hospital
Discharge_Date	Date the patient was discharged
Doctor	Attending doctor responsible for treatment
Department	Hospital department (e.g., Cardiology, Neurology)
Treatment_Cost	Total cost billed for treatment
City / Hospital	Location or branch where treatment was provided
Before analysis, the data was cleaned in Power Query: null values were removed, date columns were converted to the Date type, treatment cost was converted to Decimal, and calculated columns (Length of Stay, Month, Year) were added to support time-based and duration-based analysis. 

