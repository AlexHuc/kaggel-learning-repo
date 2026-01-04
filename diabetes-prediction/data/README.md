# Kaggle Competition: Playground Series - Season 5, Episode 12

**Competition link:**  
[https://www.kaggle.com/competitions/playground-series-s5e12/data](https://www.kaggle.com/competitions/playground-series-s5e12/data)

## Description
This dataset is part of Kaggle’s *Playground Series* and focuses on health and lifestyle indicators relevant to diabetes risk.  
It contains demographic information, lifestyle habits, clinical measurements, and medical history for a large synthetic population.  
The dataset is suitable for exploratory data analysis, feature engineering, and building classification models to predict diabetes diagnosis.

## Dataset Schema

| Column Name                        | Data Type | Description                                                   |
|------------------------------------|-----------|---------------------------------------------------------------|
| id                                 | int       | Unique identifier for each individual record                  |
| age                                | int       | Age of the individual in years                                |
| alcohol_consumption_per_week       | int       | Number of alcoholic drinks consumed per week                  |
| physical_activity_minutes_per_week | int       | Total minutes of physical activity per week                   |
| diet_score                         | float     | Composite score representing overall diet quality             |
| sleep_hours_per_day                | float     | Average number of hours slept per day                         |
| screen_time_hours_per_day          | float     | Average daily screen time in hours                            |
| bmi                                | float     | Body Mass Index (weight-to-height ratio)                      |
| waist_to_hip_ratio                 | float     | Ratio of waist circumference to hip circumference             |
| systolic_bp                        | int       | Systolic blood pressure (mmHg)                                |
| diastolic_bp                       | int       | Diastolic blood pressure (mmHg)                               |
| heart_rate                         | int       | Resting heart rate (beats per minute)                         |
| cholesterol_total                  | int       | Total cholesterol level (mg/dL)                               |
| hdl_cholesterol                    | int       | HDL (“good”) cholesterol level (mg/dL)                        |
| ldl_cholesterol                    | int       | LDL (“bad”) cholesterol level (mg/dL)                         |
| triglycerides                      | int       | Triglyceride level (mg/dL)                                    |
| gender                             | string    | Gender of the individual                                      |
| ethnicity                          | string    | Ethnic background of the individual                           |
| education_level                    | string    | Highest level of education attained                           |
| income_level                       | string    | Income category of the individual                             |
| smoking_status                     | string    | Smoking behavior (e.g., smoker, former smoker, never smoked)  |
| employment_status                  | string    | Current employment status                                     |
| family_history_diabetes            | int       | Indicator of family history of diabetes (0 = No, 1 = Yes)     |
| hypertension_history               | int       | Indicator of prior hypertension diagnosis (0 = No, 1 = Yes)   |
| cardiovascular_history             | int       | Indicator of cardiovascular disease history (0 = No, 1 = Yes) |
| diagnosed_diabetes                 | float     | Diabetes diagnosis status (typically 0 = No, 1 = Yes)         |
