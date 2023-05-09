# CA-Projects-template-submission-repo
*short project description*

## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
<<<<<<< HEAD
| LP2  | Building Accurate Models for Unit Sales Prediction in Favorita Stores using Time Series Forecasting |  [Mediun Link](https://medium.com/@otchie.sonny/building-accurate-models-for-unit-sales-prediction-in-favorita-stores-using-time-series-forecasting-8ebe181e1164) | [PowerBi](/) |

## Project Description
Time series data is a sequence of data points that are indexed and ordered chronologically over time. Time series forecasting is a statistical technique used to make predictions about the future values of a variable based on its past behavior.

Favorita Corporation is an Ecuadorian company that creates and invests in commercial, industrial, and real estate areas. This project aims to forecast unit sales of products across different stores to optimize inventory management, marketing strategies, and pricing decisions. The company will adopt this model to help Favorita Corporation make insightful decisions in relation to their retail sales, promotions, and customer satisfaction.

In this article, I will discuss the significant procedures used in building accurate models for sales prediction in Favorita stores using time series forecasting.
=======
| LP1 Data Analytics Project | Seville_LP1_v3| [Article](https://medium.com/@otchie.sonny/title-5fc453c817c9) | [PowerBi ](https://app.powerbi.com/groups/me/reports/fe5d7d9a-b45a-4b84-b804-cac0483f5187/ReportSection09c674bb9a29b589a228) |
|  

## Setup
# Data handling
import pandas as pd 
import numpy as np
# Vizualisation (Matplotlib, Plotly, Seaborn, etc. )
import matplotlib.pyplot as plt 
import seaborn as sns 
import plotly.express as ex
import plotly.offline as po
import plotly.graph_objects as go
from matplotlib import dates as mpl_dates
from datetime import datetime
# EDA (pandas-profiling, etc. )
...

# Feature Processing (Scikit-learn processing, etc. )
...

# Machine Learning (Scikit-learn Estimators, Catboost, LightGBM, etc. )
...
import statsmodels.api as sma

from statsmodels.graphics.tsaplots import plot_acf as ACF
from statsmodels.graphics.tsaplots import plot_pacf as PACF

from sklearn.model_selection import train_test_split
from pmdarima import auto_arima
from prophet import Prophet

# Use sklearn.impute.SimpleImputer
from sklearn.impute import SimpleImputer
from sklearn.compose import ColumnTransformer
from sklearn.preprocessing import OneHotEncoder

from sklearn.preprocessing import MinMaxScaler
from keras.models import Sequential
from keras.layers import LSTM, Dense
from keras.callbacks import EarlyStopping
from sklearn.metrics import mean_squared_error
from sklearn.preprocessing import OneHotEncoder
from sklearn.metrics import mean_squared_log_error

# Hyperparameters Fine-tuning (Scikit-learn hp search, cross-validation, etc. )
...

# Other packages
import os
import warnings 
warnings.filterwarnings("ignore")
import summarytools as dfSummary 

## App Execution
...

## Author
Sonny Agorvor-Otchie 
<<<<<<< HEAD
=======

>>>>>>> 19e924d97565eac1103efa191d3da58c950245f2

