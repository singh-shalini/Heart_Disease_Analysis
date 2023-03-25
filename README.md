# Heart Disease Analysis
Heart disease is the number one cause of death globally. It is concertedly contributed by hypertension, diabetes, overweight and unhealthy lifestyle.
This project covers manual explorartory data analysis using python.

## Problem Statement
Given the data about heart disease and numerous factors that cause it, perform exploratory data analysis and visualize the insights and patterns.

## Understanding the Data
- **age**
- **sex**
    - Value 0:Female
    - Value 1:Male
-**chest pain type**(4 values)
    - Value 0: typical angina
    - Value 1: atypical angina
    - Value 2: non-anginal pain
    - Value 3: asymptomatic
-**trestbps**: resting blood pressure in mg/dl
-**chol**: serum/cholestrol in mg/dl
-**fbs**: (fasting blood sugar>120 mg/dl)(1=true;0=false)
-**restecg**: resting electrocartiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of>0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
-**thalach**: maximum heart rate achieved
-**exang**: exercise induced angina (1=yes; 0=no)
-**oldpeak**: ST depression induced by exercise relative to rest
-**slope**: the slope of the peal exercise ST segment
    -  Value 1: upsloping
    -  Value 2: flat
    -  Value 3: downsloping
- **ca**: number of major vessels(0-3) colored by floursopy
- **thal**: 3=normal, 6=fixed defect, 7=reversible defect
- **target**: 0=less chance of heart attack, 1=more chance of heart attack

## Code Snippets
![image](https://user-images.githubusercontent.com/83388070/224418565-fce0c488-c4d9-43ab-ac7a-bafcbe39f05e.png)

Checking correlation
![image](https://user-images.githubusercontent.com/83388070/224417421-21a3c9b9-0533-40e5-80e0-3f5102a66c11.png)

## Conclusion
This project deploys python libraries like numpy, pandas and matplotlib for plotting the insights. This is a simple project to start with and can be even more insightful depending on the one solving the problem.
