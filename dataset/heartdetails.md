# Heart Attack Analysis & Prediction Dataset
*(A dataset for heart attack classification)*
### **About this dataset**
1. **age**: Age of the person

2. **sex**: Gender of the person
    * 0: Female
    * 1:Male

3. **cp**: Chest Pain type chest pain type
    * Value 1: typical angina
    * Value 2: atypical angina
    * Value 3: non-anginal pain
    * Value 4: asymptomatic

4. **trtbps**: resting blood pressure (in mm Hg)

5. **chol**: cholestoral in mg/dl fetched via BMI sensor

6. **fbs**: (fasting blood sugar > 120 mg/dl) 
    * 1 = true
    *  0 = false

7. **restecg**: resting electrocardiographic results:
    * Value 0: normal
    * Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria.

8. **thalachh**: maximum heart rate achieved

9. **exang**: exercise induced angina 
    * 1 = yes
    * 0 = no

10. **oldpeak**: Previous peak

11. **Slope**: 

12. **ca**: number of major vessels (0-3)

13. **thall**: Thal rate
>About Thallium itself you can find more information here: https://www.healthline.com/health/thallium-stress-test
Basically it is a radioactive element injected into the bloodstream of the patient. Then the blood flow of the patient is observed while they are doing exercise and resting.
>There are inaccuracies between this dataset and the one from the UCI repository. You can check what each value in this dataset is related to the original one by comparing their distributions:

    * 0 maps to null in the original dataset.
    * 1 maps to 6 in the original dataset. This means that a fixed defect was found.
    * 2 maps to 3 in the original dataset. This means that the blood flow was normal.
    * 3 maps to 7 in the original dataset. This means that a reversible defect was found.

14. **output**: Target varible
    * 0= less chance of heart attack 
    * 1= more chance of heart attack
