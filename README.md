# CA05: Logistic Regression Model

**Data Overview** <br />
Cardiovascular Disease (CVD) kills more people than cancer globally. A dataset of real heart patients collected from a 15 year heart study cohort is made available for this assignment. The dataset has 16 patient features. Note that none of the features include any Blood Test information. 

## Steps 
1. Data Quality Anaysis 
2. Data Cleaning
3. Build Logistic Regression Model
4. Display Feature Importance
5. Evaluate Model Performance 

## Packages 
import pandas as pd <br />
import numpy as np <br />
import matplotlib.pyplot as plt <br />
from sklearn.model_selection import train_test_split <br />
from sklearn.datasets import load_iris <br />
from sklearn.linear_model import LogisticRegression <br />
from sklearn import linear_model <br />
from sklearn.preprocessing import StandardScaler <br />
from sklearn.feature_selection import RFE, SelectFromModel <br />
from sklearn.metrics import confusion_matrix, accuracy_score, precision_score, f1_score, roc_curve, roc_auc_score, recall_score, auc <br />

## Author
[Karina Ramirez](https://github.com/kramire8 )

## Contributors 
This project was provided by Dr. Arin Brahma at Loyola Marymount University for the Intro to Machine Learning course. <br />
