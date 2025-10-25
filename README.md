# Data-Pre-Processing-and-EDA

### project overview
The goal is to predict the urgency with which a COVID-19 patient will need to be admitted to the hospital from the time of onset of symptoms. The dataset contains some COVID-19 symptoms and demographic information.  This dataset was collected in the peak of a COVID-19 wave and hence may have some errors and missing data. The aim of this exercise is to pre-process the given data and create a clean dataset to use for modelling and inference. Additionally, you are required to perform some EDA to understand the data better. 

### Data Source
The data used for this analysis was obtained from Edx, which provides information on patient symptoms and hospital admission status.

### Primary predictors:

age 

sex

cough, fever, chills, sore_throat, headache, fatigue. For each: 1 if have symptom, 0 if no symptom 

### Response variable:  
Urgency of admission where 

1 => High Urgency which means the patient was admitted within 1 day from the onset of symptoms

0 => No Urgency - everyone else
### Findings 
- Among all age groups, the 40-50 age group exhibited the highest level of urgency for hospital bed requirements. 
- Among patients with an urgent need for hospitalisation, fever was identified as the most common symptom. .
- Notably, patients without an urgent need for hospitalisation exhibited a higher prevalence of cough symptoms compared to those requiring urgent care. Specifically, about 70% of patients without urgency presented with cough symptoms, while 30% of patients with urgency exhibited similar symptoms
