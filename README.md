# Alzheimer's Disease Insights
This interactive narrative visualization project explores the relationships between demographic, lifestyle, and cognitive function variables in patients diagnosed with Alzheimer's disease. Using D3.js, the visualizations present key patterns across different age groups, genders, ethnicities, and behavioral factors such as alcohol consumption and sleep quality.
Link: https://cassyho.github.io/ 

## Visualizations
The web app includes five distinct interactive scenes:

### 1. Age Distribution by Diagnosis

Displays age distribution of patients grouped by Alzheimer's diagnosis (Yes/No).

Includes annotations highlighting the highest count in the 60–69 age group.

### 2. Gender and Diagnosis Comparison

Compares diagnosis frequency across male and female patients.

Annotations emphasize the gender with the highest count of Alzheimer's diagnosis.

### 3. Ethnicity and Diagnosis Comparison

Shows diagnosis trends across different ethnic groups.

Highlights the ethnic group with the highest Alzheimer's diagnosis.

### 4. Cognitive Function vs. Alcohol Consumption

A scatter plot of Alcohol Consumption vs. MMSE or Functional Assessment.

Users can toggle between MMSE and Functional Assessment.

Colored by age groups (10-year intervals).

### 5. Cognitive Function vs. Sleep Quality

A scatter plot of Sleep Quality vs. MMSE or Functional Assessment.

Toggle available between MMSE and Functional Assessment.

Colored by age groups (10-year intervals).

## 🔧 Technologies Used
D3.js – for all data visualizations

HTML/CSS – layout and styling

JavaScript – interactivity and scene management

CSV Dataset – loaded asynchronously via D3

## Data Description
The dataset includes the following columns:

PatientID

Age

Gender (0: Male, 1: Female)

Ethnicity (0: Caucasian, 1: African American, 2: Asian, 3: Other)

Diagnosis (0: No Alzheimer's, 1: Alzheimer's)

AlcoholConsumption, SleepQuality, MMSE, FunctionalAssessment, and others

