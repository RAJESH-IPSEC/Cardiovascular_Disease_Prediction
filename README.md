# Cardiovascular_Disease_Prediction
Cardiovascular Disease Prediction using AI utilises machine learning to analyse medical records, genetics, and lifestyle factors, predicting an individual's risk of heart issues. These models enable early detection and personalised interventions to improve patient outcomes.

## Dataset

This dataset is openly accessible and was downloaded from Github, which is provided by CORIZO.
There are three types of input features:

1. Objective: Factual and demographic information
2. Examination: Results of the medical examination
3. Subjective: information provided by the patient

Following features are available in the data.

|Feature Name |Kind |Header|DataType|
|:-|:-|:-|:-|
|Age | Objective Feature | age | int (days) |
|Height | Objective Feature | height | int (cm) |
|Weight | Objective Feature | weight | float (kg) |
|Gender | Objective Feature | gender | categorical code |
|Systolic blood pressure | Examination Feature | ap_hi | int |
|Diastolic blood pressure | Examination Feature | ap_lo | int |
|Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
|Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
|Smoking | Subjective Feature | smoke | binary |
|Alcohol intake | Subjective Feature | alco | binary |
|Physical activity | Subjective Feature | active | binary |
|Presence or absence of CVD |**Target Variable**| cardio | binary |

Python libraries:
* pip install pandas
* pip install numpy
* pip install opendatasets
* pip install matplotlib
* pip install seaborn
* pip install sklearn


