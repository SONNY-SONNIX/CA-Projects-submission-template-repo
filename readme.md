# CA-Projects-template-submission-repo
*short project description*

## Summary
| Code      | Name        | Published Article |  Deployed App |
|-----------|-------------|:-------------:|------:|
| LP1 Data Analytics Project | Seville_LP1_v3| [Article](https://medium.com/@otchie.sonny/title-5fc453c817c9) | [PowerBi ](https://app.powerbi.com/groups/me/reports/fe5d7d9a-b45a-4b84-b804-cac0483f5187/ReportSection09c674bb9a29b589a228) |
|  
## Project Description
Over the last 4 years, India’s start-up ecosystem has been thriving, with entrepreneurs and investors equally looking for the next big idea to disrupt established industries and generate new opportunities. While concepts, creativity, and execution are necessary for a start-up to flourish, they are inadequate on their own. Investor — funding is often necessary to turn those ideas into reality, grow the business, and make a long-term effect. In this article, we will investigate the funding received by start-ups in India from 2018 to 2021, using a dataset of separate CSV files containing information about the start-ups, funding amounts received, and investors..

## Setup
mport pandas as pd 

import numpy as np

pd.set_option('display.max_rows', None)
pd.set_option('display.max_columns', None)

#data visualization

import seaborn as sns

import matplotlib.pyplot as plt

#Others

import re ##for regular expression

import warnings
warnings.filterwarnings('ignore') ##to handle warnings

##for geolocation

from geopy.geocoders import Nominatim

geolocator = Nominatim(user_agent="my-custom-agent", timeout=20)

## App Execution
...

## Author
Sonny Agorvor-Otchie 


