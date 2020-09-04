# Decision-Trees-From-Scratch

## Objective
The goal of this project is to implement the following algorithms from scratch using PyTorch:
- Decision Trees
- Random Forest
- AdaBoost<br>
and see how it performs on real-world data.<br>
During this experiment, we will try to predict if a patient has a heart disease or not.

## Dataset
We will be using the Heart Disease Dataset:
https://archive.ics.uci.edu/ml/datasets/heart+Disease

14 features were selected among 76 attributes: 
1. age: age in years
2. sex:
    - 1: male
    - 0: female
3. cp: chest pain type
    - 0: asymptomatic
    - 1: atypical angina
    - 2: non-anginal pain
    - 3: typical angina
4. trestbps: resting blood pressure
5. chol: serum cholestoral in mg/dl
6. fbs: fasting blood sugar > 120 mg/dl
7. restecg: resting electrocardiographic results
    - 0: showing probable or definite left ventricular hypertrophy by Estes' criteria
    - 1: normal
    - 2: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
8. thalach: maximum heart rate achieved
9. exang: exercise induced angina 
10. oldpeak: ST depression induced by exercise relative to rest
11. slope: the slope of the peak exercise ST segment
    - 1: upsloping
    - 2: flat
    - 3: downsloping
12. ca: number of major vessels (0-3) colored by flourosopy
13. thal:
    - 3 : fixed defect
    - 6 : normal
    - 7 : reversable defect
14. disease:
    - 0: artery diameter narrowing < 50%
    - 1-3: artery diameter narrowing > 50%, close to 3 is very severe

## Setup
In order to install the conda environment needed to run the notebook, run the following line:
```console
conda env create --file requirements.yml
conda activate torch
```

## Notebook
The experiment can be found in the notebook at the root of the project.
