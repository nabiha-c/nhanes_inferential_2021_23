# NHANES 2021–2023 Inferential Analytics Assignment

This project uses NHANES 2021–2023 public data to perform basic inferential statistics in Python using Google Colab.

## Objective
To explore relationships and differences between selected health and demographic variables from the NHANES dataset using various analyses.

## Variables Used
- Marital Status (`DMDMARTZ`)
- Education Level (`DMDEDUC2`)
- Age (`RIDAGEYR`)
- Systolic Blood Pressure (`BPXOSY3`)
- Diastolic Blood Pressure (`BPXODI3`)
- Vitamin D (`LBDVD2LC`)
- Hepatitis B Antibodies (`LBXHBS`)
- Weak/Failing Kidneys (`KIQ022`)
- Minutes of Sedentary Behavior (`PAD680`)
- Self-Reported Weight (`WHD020`)

## Analyses
1. **Chi-square test** – Association between marital status and education level  
2. **T-test** – Difference in sedentary time between married and not married participants  
3. **ANOVA** – Effect of age and marital status on systolic blood pressure  
4. **Correlation** – Relationship between self-reported weight and sedentary behavior  
5. **Creative question** – Additional inferential analysis using one of the NHANES variables

## Tools Used
- Google Colab  
- Python (pandas, numpy, scipy, seaborn, matplotlib, statsmodels)

## How to Run
1. Download NHANES `.xpt` files from the [CDC NHANES 2021–2023 page](https://wwwn.cdc.gov/nchs/nhanes/continuousnhanes/default.aspx?Cycle=2021-2023).
2. Upload them into your Colab session.
3. Run each code cell to reproduce the analyses.

