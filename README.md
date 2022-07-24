# EDA-On-Meteorological-Data
# EDA On Meteorological Data (Weather Dataset)

- This notebook contains Exploratary Data Analysis on Weather Dataset and creation of Dashboard using Pywedge 0.5.1.8 Python package. The dataset contains 96,453 entries and 12 attributes related to meteorological data.

- Download dataset from here : https://www.kaggle.com/datasets/muthuj7/weather-dataset?datasetId=6087&sortBy=voteCount

# Mandatory package you have to install for dashboard creation is "pywedge" python package :-
- !pip install pywedge

- After installing pywedge run bellow code for auto dashboard creation :
>>> import pywedge as pw
>>> x = pw.Pywedge_Charts(df_weather,c=None,y="Humidity")
>>> charts = x.make_charts()
