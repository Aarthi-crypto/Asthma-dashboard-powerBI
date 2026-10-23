# Asthma-dashboard-powerBI
Power BI dashboard analyzing asthma risk factors and control levels using a 10,000-patient synthetic medical dataset.

# Asthma Dashboard (Power BI)

An analysis of asthma patient data in Power BI, exploring how demographics, lifestyle, environmental exposure and clinical measurements relate to asthma diagnosis and control.

## Preview

   ![Dashboard Page 1](screenshots/Screenshot%202026-10-23%20184114.png)

## Dataset

- **Name:** [Asthma Synthetic Medical Dataset](https://www.kaggle.com/datasets/miadul/asthma-synthetic-medical-dataset)
- **Author:** miadul (Kaggle)
- **Type:** Synthetic medical data (no real patient information)
- **Size:** 10,000 patient records, 17 columns, no missing values
- **File in this repo:** `data/asthma_data.xlsx`

Please refer to the Kaggle page for the dataset's license and terms of use

### Columns

| Column | Description |
|---|---|
| Patient_ID | Unique patient identifier |
| Age | Age in years (1 to 89) |
| Gender | Female, Male, Other |
| BMI | Body mass index |
| Smoking_Status | Current, Former, Never |
| Family_History | 1 = family history of asthma, 0 = none |
| Allergies | None, Dust, Pets, Pollen, Multiple |
| Air_Pollution_Level | Low, Moderate, High |
| Physical_Activity_Level | Sedentary, Moderate, Active |
| Occupation_Type | Indoor, Outdoor |
| Comorbidities | None, Diabetes, Hypertension, Both |
| Medication_Adherence | Score from 0 to 1 |
| Number_of_ER_Visits | Emergency room visits |
| Peak_Expiratory_Flow | Lung function measure |
| FeNO_Level | Fractional exhaled nitric oxide (airway inflammation marker) |
| Has_Asthma | 1 = diagnosed, 0 = not diagnosed |
| Asthma_Control_Level | Well Controlled, Poorly Controlled, Not Controlled, or N/A (no asthma) |

## Objectives

- Understand the demographic and health profile of the patients
- Identify which risk factors are most associated with an asthma diagnosis
- Analyze how well asthma is controlled among diagnosed patients
- Present the findings in an interactive Power BI report

## Key Insights

- **Overall prevalence:** 2,433 of 10,000 patients (24.3%) have asthma.
- **Smoking:** Current smokers have a 56.1% asthma rate, compared with 19.1% for never-smokers and 18.5% for former smokers.
- **Air pollution:** Patients in high-pollution areas show a 55.7% rate, versus about 16% for low and moderate levels.
- **Family history:** 51.0% of patients with a family history have asthma, versus 12.7% without.
- **Physical activity:** Sedentary patients have a 40.5% rate, compared with 14.4% for active patients.
- **BMI:** Obese patients (BMI 30+) have a 38.3% rate, versus roughly 21 to 22% for other BMI groups.
- **Allergies:** Patients with no allergies have a 6.3% rate, while those with any allergy type are around 31 to 33%.
- **Asthma control:** Among diagnosed patients, only 84 (about 3.5%) are well controlled, 1,120 are poorly controlled and 1,229 are not controlled.
- **Little difference:** Gender, age group, occupation type and comorbidities show almost no difference in asthma rate (all around 24%).

## Tools & Technologies

- **Power BI Desktop**: data modeling and report building
- **Power Query**: data loading and cleaning
- **DAX**: measures and calculated fields

## Repository Structure

```
asthma-dashboard-powerbi/
├── data/
│   └── asthma_data.xlsx
├── screenshots/
│   └── asthma-dashboard.png
├── ASTHMA.pbix
└── README.md
```

## How to Use

1. Download or clone this repository.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
3. Open `ASTHMA.pbix`.
4. To refresh the data, go to **Home → Transform data → Data source settings → Change Source** and point it to `data/asthma_data.csv` on your computer.

## Acknowledgements

Dataset by [miadul](https://www.kaggle.com/datasets/miadul/asthma-synthetic-medical-dataset) on Kaggle.

## Author

Aarthi G D([(https://github.com/Aarthi-crypto)]
