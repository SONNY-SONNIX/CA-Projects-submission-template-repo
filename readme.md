# LP2 Classification Project 
*short project description*

## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| LP2 Classification Project | LP3_ Customer_Churn_Prediction| [Article](https://medium.com/@otchie.sonny/maximizing-customer-retention-a-churn-prediction-analysis-for-vodafone-group-ee561f98a4cd) | []() |
|  
## Project Description
Customer attrition is a prevalent problem for many businesses, resulting in large financial losses. Customer churn or attrition in this project refers to the percentage of consumers that discontinue using a company’s product or service within a specified time frame. Understanding the primary causes of customer churn can assist businesses in developing effective retention strategies to reduce customer attrition and boost revenue. I propose to investigate how firms such as Vodafone Group can gain insights into customer behavior and factors that contribute to churn by analyzing historical customer data and applying predictive analytics. This enables the organization to take proactive measures to retain at-risk customers and improve overall customer satisfaction.

This project’s dataset includes information about users’ demographics, service usage, and billing information. I will use this dataset to conduct exploratory data analysis in order to find patterns and trends linked to customer attrition. I will next use machine learning techniques to create a predictive model that will estimate the likelihood of a customer leaving the firm.

Our project’s objectives are to:

1. Examine and present the data to discover patterns and trends in customer attrition.

2. Using machine learning methods, develop a prediction model to anticipate client attrition.

3. Identify the key churn indicators, such as client demographics, service usage, and billing data.

4. Develop retention strategies to help reduce client turnover while enhancing consumer loyalty.

5. Evaluate the success of retention efforts and make modifications based on the model’s results.

The project’s findings aim at helping Vodafone better understand customer churn and execute effective retention tactics to reduce customer attrition and improve revenue.

## Setup
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import plotly.express as px
import seaborn as sns 

import matplotlib.pyplot as plt 
%matplotlib inline
import matplotlib.ticker as mtick
import seaborn as sns 
import random
import phik

import warnings

# Suppress all warnings
warnings.filterwarnings("ignore")

# Feature Processing (Scikit-learn processing, etc. )
from sklearn.preprocessing import StandardScaler
from sklearn.preprocessing import OneHotEncoder
from sklearn.preprocessing import LabelEncoder
from sklearn.impute import SimpleImputer
from sklearn.metrics import classification_report
from sklearn.feature_selection import SelectKBest
from sklearn.feature_selection import f_classif

#Algorithms and pipeline

from sklearn.tree import DecisionTreeClassifier
from sklearn.linear_model import LogisticRegression
from sklearn.ensemble import RandomForestClassifier
from sklearn.svm import SVC
from xgboost import XGBClassifier
from sklearn.pipeline import Pipeline
from sklearn.compose import ColumnTransformer 
from imblearn.pipeline import Pipeline
from sklearn.ensemble import BaggingClassifier
from sklearn.pipeline import make_pipeline
from sklearn.model_selection import RandomizedSearchCV

##handling imbalance datasets

from imblearn.over_sampling import SMOTE

from sklearn.utils.class_weight import compute_class_weight

##hyperparameter tuning
from sklearn.model_selection import GridSearchCV


...

# Other packages
import os

## App Execution
...

## Author
Sonny Agorvor-Otchie 


