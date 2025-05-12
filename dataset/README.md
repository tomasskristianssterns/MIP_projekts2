# Heart Failure Prediction Dataset

## Context

Cardiovascular diseases (CVDs) are the **number 1 cause of death globally**, taking an estimated **17.9 million lives** each year, which accounts for **31% of all deaths worldwide**. Four out of five CVD deaths are due to **heart attacks and strokes**, and one-third of these deaths occur **prematurely** in people under 70 years of age.

Heart failure is a common event caused by CVDs. This dataset contains **11 features** that can be used to **predict a possible heart disease**.

People with cardiovascular disease or who are at **high cardiovascular risk** (due to the presence of one or more risk factors such as **hypertension, diabetes, hyperlipidaemia**, or already established disease) need **early detection and management**, where a **machine learning model** can be of great help.

## Attribute Information

- **Age**: Age of the patient *(years)*
- **Sex**: Sex of the patient *[M: Male, F: Female]*
- **ChestPainType**: Chest pain type  
  *[TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]*
- **RestingBP**: Resting blood pressure *(mm Hg)*
- **Cholesterol**: Serum cholesterol *(mg/dl)*
- **FastingBS**: Fasting blood sugar  
  *[1: if FastingBS > 120 mg/dl, 0: otherwise]*
- **RestingECG**: Resting electrocardiogram results  
  *[Normal: Normal, ST: ST-T wave abnormality, LVH: Left ventricular hypertrophy]*
- **MaxHR**: Maximum heart rate achieved  
  *(Numeric value between 60 and 202)*
- **ExerciseAngina**: Exercise-induced angina  
  *[Y: Yes, N: No]*
- **Oldpeak**: ST depression induced by exercise relative to rest  
  *(Numeric value)*
- **ST_Slope**: Slope of the peak exercise ST segment  
  *[Up: upsloping, Flat: flat, Down: downsloping]*
- **HeartDisease**: Output class  
  *[1: heart disease, 0: Normal]*

## Source

This dataset was created by combining different datasets already available independently but not combined before. In this dataset, **5 heart datasets** are combined over **11 common features**, making it the **largest heart disease dataset** available so far for research purposes.

### Datasets Used:
- **Cleveland**: 303 observations  
- **Hungarian**: 294 observations  
- **Switzerland**: 123 observations  
- **Long Beach VA**: 200 observations  
- **Stalog (Heart) Data Set**: 270 observations

### Total:
- **1190 observations**
- **272 duplicated**
- **Final dataset**: **918 observations**

> Every dataset used can be found under the [Index of heart disease datasets](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/) from UCI Machine Learning Repository.

## Citation

**fedesoriano**. (September 2021). *Heart Failure Prediction Dataset*. Retrieved [Date Retrieved] from [Kaggle](https://www.kaggle.com/fedesoriano/heart-failure-prediction).

## Acknowledgements

### Creators:
- **Hungarian Institute of Cardiology**, Budapest: *Andras Janosi, M.D.*
- **University Hospital**, Zurich,
