# VIRTUALWORKS LAB-HEALTHCARE-PHARMACY-DATA-ANALYTICS-INTERNSHIP-TASKS
This repository includes projects done by SNEHA P as part of VIRTUALWORKS LAB INTERNSHIP. Projects are focused on Applied data analytics in healthcare, clinical, and pharmaceutical domains

---
# Adverse Drug Reaction Data Analysis[ID:task4]
Analyzed ADR datasets containing patient details, medication usage,ADR reported, SOC affected and onset timelines to determine seriousness of ADRs. Identified high-risk medicines, commonly reported ADRs, most ADR reported countries and evaluated percentage of serious ADRs reported.

### View Full Project: [ADR_ANALYSIS.xlsx](./ADR_ANALYSIS.xlsx)

# Project Overview
## Worksheet 1 - ADR Analysis 
1.Created an ADR dataset with patient details, medication usage,ADR reported, SOC affected and onset timelines to determine seriousness of ADRs.SERIOUS Column was entered considering ONSET column values using IF Function- ADRs with onset of more than 2 days was labelled serious.

Highlighted the following using Conditional formatting:

✅ADRs with onset of not more than 2 days with green

✅Serious column entry YES with red 

2.Summarised the following using Excel functions:

✅total ADR reports [COUNTA FORMULA]

✅percentage of serious ADRs reported[basic percentage formula]

✅SOC-wise ADR distribution, Number of serious ADRs[COUNTIF FORMULA]

✅countries which reported ADRs[UNIQUE FORMULA]

3.Built Pivot tables on Country-wise percentage of reported ADRs , DRUG WISE SERIOUS/UNSERIOUS ADRs DISTRIBUTION.

### Worksheet 1- ADR ANALYSIS SCREEN CAPTURE

![Alt Text](ADR_ANALYSIS_DATASET.png)


![Alt Text](ADR_ANALYSIS_SUMMARY_PIVOT%20TABLES.png)


## Worksheet 2-ADR ANALYSIS VISUALIZATION

1.Built Pivot charts based on :

✅COUNTRY WISE PERCENTAGE OF REPORTED ADRs 

✅SOC WISE ADR REPORTING

✅DRUG WISE SERIOUS/UNSERIOUS ADRs[Drug Slicer included]


### Worksheet 2- ADR ANALYSIS VISUALIZATION SCREEN CAPTURE

![Alt Text](ADR_ANALYSIS_VISUALIZATION.png)


## KEY INSIGHTS

✅A total of 25 ADRs were reported

✅Most serious ADRs happened with Diclofenac 

✅High risk medicines include Diclofenac, Allopurinol and Metformin

✅India reported with most ADRs

✅Most ADRs were associated with Gastrointestinal and Skin disorders

✅68% of ADRs were reported serious


---
---
# Pharmacy Sales and Drug Analysis [ID: task3]
Analyzed pharmacy sales data to identify medicine usage trends and revenue patterns. Evaluated top-selling medicines, monthly sales growth, and compared branded versus generic medicines using sales datasets.

### View Full Project : [PHARMACY_SALES_ANALYSIS.xlsx](./PHARMACY_SALES_ANALYSIS.xlsx)

# Project Overview
## Worksheet 1 - Pharmacy sales data
1.Created a pharmacy sales dataset with date, drug details, quantity ordered, price and sales. Sales was calculated with formula PRODUCT(QUANTITY*PRICE)

2.Highlighted the following using Conditional formatting:

✅highest/least selling drugs(yellow data bars)

✅highest/least drug quantity orders(highest-red/least-green)

✅Drugs with top 5 sales (red bordered cells with bold text)

3.Calculated highest/least selling drug and highest/least drug quantity orders using formulas MIN, MAX.

4.Built a pivot table out of the dataset summarising monthly drug sales and comparison of generic/brand drug sales

### Worksheet 1- Pharmacy sales data SCREEN CAPTURE

![Alt Text](PHARMACY_SALES_DATASET_ANALYSIS.png)

![Alt Text](PHARMACY_SALES_TOP_SALES.png)


## Worksheet 2- Pharmacy sales visualization
1. Visualized "monthly drug sales" and "generic vs brand drug sales" using pivot chart. Added slicers to look for specific information, say to find the monthly sale for Amoxicillin, one can select Amoxicillin option from slicer. The pivot chart will display monthly sales for Amoxicillin alone.

### Worksheet 2- Pharmacy Sales visualization SCREEN CAPTURE

![Alt Text](PHARMACY_SALES_VISUALISATION.png)

### Key Insights

✅Most selling drug : Azithromycin

✅Generic drugs are mostly ordered

✅Cheapest Drug : Paracetamol

✅Most Expensive drug: Azithromycin

✅Antibiotics are the top selling drugs.

✅Sales peaked in February 


---
---
# Healthcare Data Visualization [ID: task2]
Created visual representations of healthcare data using charts and graphs. Using the cleaned dataset, generated graphs and charts such as frequency of diseases, age group wise disease distribution, gender wise disease distribution, and dosage distribution to better understand healthcare trends and patterns.

### 📄View Full Project: [Dataset_Visualisation_PatientRecords.xlsx](./Dataset_Visualisation_PatientRecords.xlsx)

# Project Overview
## Worheet 2 - Clean and Analysed Patient Records
1. Created a visualization of the various disease trends among female/male patients using Column Sparklines in the pivot table representing Gender wise disease distribution


### Worksheet 2- Clean & Analysed Patient Records SCREEN CAPTURE

![Alt Text](Worksheet2_VISUALISATION_OF_DISEASE_TRENDS_GENDER_WISE.png)


## Worksheet 3 - Data Visualization
1. Built Pivot charts from the pivot tables of 2nd worksheet.


2. Added slicers beside each pivot chart to clearly extract specific information.For example, in the slicer beside pivot chart representing Frequency of Diseases,one can select any of the diseases,say Diabetes and the pivot chart will display number of patients affected with diabetes.


### Worksheet 3 - Data Visualization SCREEN CAPTURE

![Alt Text](Worksheet3_DATA_VISUALIZATION_CHARTS_SLICERS_FREQUENCY_GENDER.png)


![Alt Text](Worksheet3_DATA_VISUALIZATION_CHARTS_SLICERS_AGEWISE_DOSAGE.png)


---
---
# Healthcare Data Cleaning & Understanding  [ID: task1]
Worked with a healthcare dataset containing patient information such as age, gender, disease, medication, and dosage. Explored the dataset, identified and cleaned missing or duplicate records, and performed basic analysis such as patient count, common diseases, and different patient age groups. 

### 📄View Full Project: [Data_Cleaning_And_Basic_Analysis_PatientRecords.xlsx](./Data_Cleaning_And_Basic_Analysis_PatientRecords.xlsx)

# Project Overview
## Worsheet 1 - Unclean Patient Records
1.Created a sample patient records dataset with missing and duplicate entries


2.Identified and highlighted missing entries and duplicate patient IDs using Conditional Formatting.


3.Created a SUMMARY OF ERRORS  spotted from dataset which summarized the number of duplicate patient IDs and missing entries using SUMPRODUCT, COUNTIF and COUUNTBLANK FUNCTIONS.


### Worksheet 1- Unclean Patient Records SCREEN CAPTURE
![Alt Text](Worksheet1_Unclean_Dataset.png)



## Worksheet 2 - Clean & Analysed Patient Records
1.Removed duplicate patient entries and filled in missing data.


2.Built Pivot tables from Cleaned dataset and extracted key insights, including :

 ✅Frequency of each disease

✅Gender wise Prevalence of each disease 

✅Highest Dosage Medications

✅Age groups consulted

 
### Worksheet 2- Clean & Analysed Patient Records SCREEN CAPTURE
![Alt Text](Worksheet2_Clean_Analysed_Dataset.png)
