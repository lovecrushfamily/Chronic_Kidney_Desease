# Chronic_Kidney_Disease

Author : LoveCrush <br>
Time : Within a week <br>
Dataset : Chronic kidney Disease <br>

You can follow this link to get fully intuition about this dataset  <a href="https://www.kaggle.com/datasets/rabieelkharoua/chronic-kidney-disease-dataset-analysis?fbclid=IwY2xjawFeRztleHRuA2FlbQIxMAABHcLQT3UlwrltJlqVMmmRKwylG3AVzxWISDasV1OrpX4O1yVAQhfvl8AitQ_aem_41MZIo-G7lN6wNkGxwAdew">Chronic Kidney Disease - Kaggle Dataset</a> 


## Motivation

This project was doing along with the Alzheimer Disease project of mine. I'm considering it as a extra one for me to test my skill set. The dataset in this project was shared by Rabie El Kharoua, He's definitely a master of datasets on Kaggle. I see that all the dataset was shared by now was documented very well, and with high applicable in reality. Not a big deal but you can find him via the dataset link I tagged above. Peace

## Dataset

Features (cols) :54 <br>
Samples  (rows) : 1659


| S.No | Name                          |  Dtype                   |  Description  | 
| ---- | ------------------------      | ------------------- | --------      |
|      | **Demographic Detail**        |
| 1    | Age                           |    -> numerical    |  Age of patient ranges from 20 -> 90 years   |
| 2    | Gender                        |    -> categorical  |  Gender of the patients, O represents Male and vice versa    |
| 3    | Ethnicity                     |    -> categorical  |  The ethnicity of the patients, already encoded (irrelevant in detail)       |
| 4    | SocioeconomicStatus           |    -> categorical  |  The socioeconomic status of the patients, already encoded (irrelevant in detail)       |
| 5    | EducationLevel                |    -> categorical  |  The educational level of patient, already encoded (irrelevant in detail)        |
|      | **Lifestyle Factor**          |
| 6    | BMI                           |    -> numerical    |  Body Mass Index of the patients, ranging from 15 -> 40        |
| 7    | Smoking                       |    -> categorical  |  Smoking status, where 0 indicates No and 1 indicates Yes        |
| 8    | AlcoholConsumption            |    -> numerical    |  Weekly alcohol consumption in units, ranging from 0 -> 20        |
| 9    | PhysicalActivity              |    -> numerical    |  Weekly physical activity in hours, ranging from 0 -> ten        |
| 10    | DietQuality                  |    -> numerical    |  Diet quality score, ranging from 0 -> 10         |
| 11    | SleepQuality                 |    -> numerical    |  Sleep quality score, ranging from 4 -> 10        |
|      | **Mediacal Hostory**          | 
| 12   | FamilyHistoryKidneyDisease    |    -> categorical  |  Family history of kidney disease, 0 indicated No and 1 indicated Yes         |
| 13   | FamilyHistoryHypertension     |    -> categorical  |  Family history of hypertension, 0 indicates No, 1 indicates Yes         |
| 14   | FamilyHistoryDiabetes         |    -> categorical  |  Family history of diabetes, 0 indicates No and 1 indicates Yes        |
| 15   | PreviousAcuteKidneyInjury     |    -> categorical  |  History of previous acute kidney injury, where 0 indicates No and 1 indicates Yes        |
| 16   | UrinaryTractInfections        |    -> categorical  |  History of Urinary Tract Infections, 0 indicates No and 1 indicates Yes        |
|      | **Clinical Measurements**     |
| 17   | SystolicBP                    |    -> numerical    |  Systolic blood pressure, ranging from 90 -> 180 mmHg        |
| 18   | DiastolicBP                   |    -> numerical    |  Diastolic blood pressure, ranging from 60 to 120 mmHg        |
| 19   | FastingBloodSugar             |    -> numerical    |  Fasting Blood Sugar levels, ranging from 70 to 200 mmHg        |
| 20   | HbA1c                         |    -> numerical    |  Hemoglobin A1c levels, ranging from 4% to 10.0%        |
| 21   | SerumCreatinine               |    -> numerical    |  Serum Creatinine levels, ranging from 0.5 -> 5.0 mg/dL        |
| 22   | BUNLevels                     |    -> numerical    |  Blood Urea Nitrogen levels, ranging from 5 -> 50 mg/dL       |
| 23   | GFR                           |    -> numerical    |  Glomerular Filtration rate, ranging from 15 to 120 mL/min/1.73 m².      |
| 24   | ProteinInUrine                |    -> numerical    |  Protein levels in urine, ranging from 0 -> 5 g/day      |
| 25   | ACR                           |    -> numerical    |  Albumin-to_Creatinine Ratio, ranging from 0 -> 300 mg/day  |
| 26   | SerumElectrolytesSodium       |    -> numerical    |  Serum Sodium level, ranging from 135 -> 145 mEq/L  |
| 27   | SerumElectrolytesPotassium    |    -> numerical    |  Serum potassium level, ranging from 3.5 -> 5.5 mEq/L  |
| 28   | SerumElectrolytesCalcium      |    -> numerical    |  Serum calcium level, ranging from 8.5 -> 10.5 mg/dL  |
| 29   | SerumElectrolytesPhosphorus   |    -> numerical    |  Serum phosphorus level, ranging from 2.5 -> 4.5 mg/dL  |
| 30   | HemoglobinLevels              |    -> numerical    |  Hemoglobin level, ranging from 10 -> 18 g/dL  |
| 31   | CholesterolTotal              |    -> numerical    |  Total Cholesterol level, ranging from 150 -> 300 mg/dL  |
| 32   | CholesterolLDL                |    -> numerical    |  Low-Density lipoprotein cholesterol level, ranging from 50 -> 200 mg/dL  |
| 33   | CholesterolHDL                |    -> numerical    |  High-Density lipoprotein cholesterol level, ranging from 20 -> 100 mg/dL  |
| 34   | CholesterolTriglycerides      |    -> numerical    |  Triglycerides levels, ranging from 50 -> 500 mg/dL  |
|      | **Medications**               |
| 35   | ACEInhibitors                 |    -> categorical  |  use of ACE Inhibitors, 0 indicates No and 1 indicates Yes |
| 36   | Diuretics                     |    -> categorical  |  Use of Diuretics, 0 indicates No and 1 indicates Yes |
| 37   | NSAIDsUse                     |    -> numerical    |  Frequency of NSAIDs use, ranging from 0 -> 10 times per weeks |
| 38   | Statins                       |    -> categorical  |  Use of Statins, 0 indicates No and 1 indicates Yes |
| 39   | AntidiabeticMedications       |    -> categorical  |  Use of Anti diabetic medications, 0 indicates No and 1 indicates Yes |
|      | **Symptoms and Quality of Life**                   |
| 40   | Edema                         |    -> categorical  |  Presence of Edema, 0 indicates No and 1 indicates Yes |
| 41   | FatigueLevels                 |    -> numerical    |  Fatigue Levels, ranging from 0 -> 10 |
| 42   | NauseaVomiting                |    -> numerical    |  Frequency of nausea and vomiting, ranging from 0 -> 7 times per week|
| 43   | MuscleCramps                  |    -> numerical    |  Frequency of muscle cramps, ranging from 0 -> 7 times per week|
| 44   | itching                       |    -> numerical    |  itching severity, ranging from 0 -> 10 |
| 45   | QualityOfLifeScore            |    -> numerical    |  Quality of life score, ranging from 0 -> 100 |
|      | **Evironmental and Occupational Exposures**  |
| 46   | HeavyMetalsExposure           |  -> categorical    |  Exposure to heavy metals, where 0 indicates No and 1 indicates  Yes|
| 47   | OccupationalExposureChemicals |  -> categorical    |  Occupational exposure to harmful chemical, where 0 is No and 1 is Yes        |
| 48   | WaterQuality                  |    -> categorical  |  Quality of Water, where 0 indicates Good and 1 indicates Poor        |
|      | **Health Behaviors**          |
| 49   | MedicalCheckupsFrequency      |    -> numerical    |  Frequency of medical check-ups per year, ranging from 0 -> 4        |
| 50   | MedicationAdherence           |    -> numerical    |  Medication adherence score, ranging from 0 -> 10       |
| 51   | HealthLiteracy                |    -> numerical    |  Health literacy score, ranging from 0 -> 10       |
|      | **Diagnosis Information**     |
| 52   | Diagnosis                     |    -> categorical  |  Diagnosis status for Chronic Kidney Disease, where 0 indicates No and 1 indicates Yes         |
|      | **Confidential Information**                       |
| 53   | DoctorInCharge                | -> categorical     | (irrelevant) The confidential information about the doctor in charge, already encoded as "Confidential" for all patients         |
| 54   | PatientID                     |    -> numerical    | (irrelevant) A unique identifier assigned to each patient   |











