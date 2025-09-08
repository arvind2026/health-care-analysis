# Healthcare Analysis Project

## Project Overview
This project presents an analysis of healthcare data using Power BI to identify patterns, trends, and insights in patient demographics, medical conditions, and healthcare costs. The focus is on understanding disease prevalence, cost distribution, patient characteristics, and healthcare utilization patterns to support better decision making in healthcare management.

## Dashboard Visualizations

### Disease Analysis Dashboard
![Disease Analysis Dashboard](/dashboard/Diesese.jpg)

The disease analysis dashboard provides insights into healthcare costs and patient distribution across medical conditions. Key visualizations include:

- **Total Expense per Disease**: Cancer shows the highest cost ($43.49M), followed by asthma ($43.41M)  
- **Patients by Medical Condition**: Asthma has the highest patient count (1,708)  
- **Blood Type Distribution**: AB- blood type has the largest patient group (1,275)  
- **Blood Type vs Medical Condition Matrix**: Heatmap showing condition distribution by blood type  
- **Test Results Distribution**: 3.5K abnormal, 3.3K inconclusive, 3.3K normal  

### Patient Care Analysis Dashboard
![Patient Care Analysis Dashboard](/dashboard/PatientCare.jpg)

The patient care dashboard focuses on demographics, admissions, and utilization patterns:

- **Gender Distribution**: Balanced (49.2% female, 50.7% male)  
- **Medical Condition Breakdown**: Even distribution across six conditions  
- **Medication Distribution**: Penicillin most prescribed (20.79%)  
- **Admission Type Analysis**: Urgent (33.67%), Emergency (33.91%), Elective (32.42%)  
- **Insurance Provider Distribution**: Cigna leads at 20.4%  
- **Top Hospitals and Doctors**: Smith PLC admits most patients, Michael Johnson has the highest admission frequency (7)  

## Executive Summary Report
This analysis of 10,000 patient records highlights key trends in disease costs, patient demographics, and care utilization.

- Cancer is the costliest disease ($43.49M), while asthma has the highest patient volume (1,708). Arthritis shows the lowest cost burden ($41.56M).  
- Patients are evenly split between males and females, with an average age of 51.45 years and average hospital stay of 15.56 days.  
- Admissions are mostly urgent or emergency (67.5%).  
- Insurance coverage is spread across five providers, with Cigna slightly ahead (20.4%).  
- Penicillin is the most prescribed medication (20.8%).  
- Michael Johnson is the highest frequency patient with 7 admissions, and Smith PLC is the leading facility by patient volume.  
- Test results show a high abnormal rate (35%), pointing to significant disease burden.  

## Dataset Description
The dataset contains healthcare records with the following key variables:

- **Patient Demographics**: Name, Age, Gender, Blood Type  
- **Medical Information**: Medical Condition, Medication, Test Results, Doctor  
- **Administrative Data**: Date of Admission, Discharge Date, Days Spent, Admission Type  
- **Financial Data**: Billing Amount, Insurance Provider  
- **Facility Information**: Hospital, Room Number  

The dataset includes 10,000 patients with an average age of 51.45 years and maximum age of 85 years. Patients spent an average of 15.56 days in healthcare facilities.

## Methodology

### Data Processing
1. **Data Cleaning**: Standardized formats, handled missing values  
2. **Data Transformation**: Created calculated fields (cost per disease, patient segmentation)  
3. **Data Validation**: Checked integrity and consistency across all variables  

### Analysis Framework
The analysis was structured into:  
- **Disease Analysis**: Conditions, costs, and patient distribution  
- **Patient Care Analysis**: Demographics, admissions, and utilization  

## Key Findings

### Disease Analysis
**Cost Distribution by Medical Condition**  
- Cancer is highest at $43.49M  
- Asthma $43.41M with high patient count  
- Arthritis lowest at $41.56M  

**Patient Distribution by Medical Condition**  
- Asthma: 1,708  
- Cancer: 1,703  
- Hypertension: 1,688  
- Arthritis: 1,650  
- Obesity: 1,628  
- Diabetes: 1,623  

**Blood Type Analysis**  
- AB- blood type highest (1,275 patients)  
- Correlation between AB- and obesity  
- Distribution varies across conditions  

### Patient Care Analysis
**Demographics**  
- Gender: 49.2% female, 50.7% male  

**Insurance Coverage**  
- Cigna: 20.4%  
- Blue Cross: 20.32%  
- Aetna: 20.25%  
- UnitedHealthcare: 19.78%  
- Medicare: 19.25%  

**Admission Patterns**  
- Urgent: 33.67%  
- Emergency: 33.91%  
- Elective: 32.42%  

**Medication Distribution**  
- Penicillin: 20.79%  
- Lipitor: 20.15%  
- Ibuprofen: 19.68%  
- Aspirin: 19.76%  
- Paracetamol: 19.62%  

## Healthcare Facility Performance
**Top Healthcare Providers by Patient Volume**  
- Smith PLC: 19  
- Smith and Sons: 17  
- Smith Inc: 14  
- Smith Ltd: 14  

**High-Frequency Patients**  
- Michael Johnson: 7 admissions  

## Test Results Distribution
- Abnormal: 3.5K  
- Inconclusive: 3.3K  
- Normal: 3.3K  

## Business Implications

### Cost Management  
- Cancer treatment needs cost control strategies  
- Asthma’s high patient volume drives large aggregate costs  

### Resource Allocation  
- Asthma prevalence highlights need for respiratory care resources  
- 67.5% urgent/emergency admissions require strong emergency capacity  

### Risk Assessment  
- AB- blood type linked with obesity → preventive focus  
- High abnormal test results → need for better diagnostics and treatment protocols  

## Technical Implementation
**Tools Used**  
- Power BI for visualization  
- Data modeling for relationships  
- DAX for custom metrics and KPIs  

**Dashboard Components**  
- Disease cost analysis  
- Demographics  
- Utilization metrics  
- Facility performance indicators  

## Recommendations
1. **Cost Optimization**: Control cancer-related expenses  
2. **Preventive Care**: Strengthen asthma management programs  
3. **Risk Stratification**: Include blood type in preventive risk protocols  
4. **Capacity Planning**: Expand urgent and emergency care facilities  
5. **Quality Improvement**: Investigate abnormal test results and improve testing processes  


## Conclusion
The analysis highlights high costs for cancer, a large patient base for asthma, and significant reliance on urgent/emergency admissions. Balanced gender distribution and spread of insurance providers show wide healthcare access. Key improvement areas include cost control in cancer care, preventive asthma programs, better diagnostic accuracy, and emergency care capacity expansion.  
