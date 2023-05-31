# Ex-07-Feature-Selection
## AIM
To Perform the various feature selection techniques on a dataset and save the data to a file. 

# Explanation
Feature selection is to find the best set of features that allows one to build useful models.
Selecting the best features helps the model to perform well. 

# ALGORITHM
### STEP 1
Read the given Data
### STEP 2
Clean the Data Set using Data Cleaning Process
### STEP 3
Apply Feature selection techniques to all the features of the data set
### STEP 4
Save the data to the file

# CODE
import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

df=pd.read_csv('/content/titanic_dataset.csv')

df.head()

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/b3dd73ae-2567-438d-bcc7-03e7cdd72209)

df.isnull().sum()

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/ea9fd4d2-3210-4a02-977c-780380847028)

# OUTPUT

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/62f01b97-9209-4f80-9529-6c15c21b7965)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/cfa40a08-2bd9-4204-adb2-e94459d6df23)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/2cc03ade-e56d-4e6c-bd2b-6b601c585533)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/88bf59a7-b563-435d-bb84-2ee18efe12d8)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/656897a0-324d-493b-9fdc-bb912db34a4d)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/06f32a4a-241b-42af-9eb4-1bc291f9e728)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/1bbdb1de-3f46-43f2-afce-dc7737fb37f6)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/e0f534b1-195f-4f45-b799-ba255f64411a)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/2f6c02b6-f09a-46ac-a4d1-e6f5fdadafce)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/51765a40-69b7-4903-9552-5e5e84804c52)

![image](https://github.com/Rajasree-321/Ex-07-Feature-Selection/assets/96918911/b73a9b39-cb52-4c02-b5cf-6de3f5c8c8b8)



# RESULT
 Thus the feature selection techniques for the given datasets had been executed successfully.
