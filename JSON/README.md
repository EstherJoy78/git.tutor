Overview
This project mainly focuses on identifying the main causes of the Aviation accidents occurring, risk and provide recommendations on how to try and minimize the rates of accidents occurring. Mainly I focused on the United states.

Business Problem
Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

The Data
The data we were given were pulled from the National Transportation Safety Board that includes aviation accident data from 1982 to 2023 about civil aviation accidents and selected incidents in the United States and international waters.
https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses

Questions to consider:
1. What are the common causes of accidents or incidents for each aircraft?
2. How does the aircraft perform in various environmental conditions?
3. What is the availability of training and support for the aircraft model?

Description of Data
#numpy for high level mathematical functions and working with Arrays import numpy as np 
#pandas data manipulation and analysis for tablular data import pandas as pd
#seaborn and matplotlib for data visualization import seaborn as sns import matplotlib.pyplot as plt %matplotlib inline

Loading Data
df= pd.read_csv('AviationData.csv', encoding='cp1252')


Conclusions
From the observations, it can be concluded that favorable weather conditions do not necessarily prevent accidents in aviation. This suggests that other factors, such as pilot error, mechanical failure, or operational issues, play a significant role in aviation accidents.

Although there has been a reduction in the overall number of aviation accidents, California, Texas, and Florida are states where accidents occur more frequently. 

Additionally, the fact that specific aircraft makes, models, and engine types are involved in accidents more frequently suggests potential design or operational vulnerabilities with these aircraft. This could highlight the need for more stringent maintenance, inspections, or operational protocols for those particular types of aircraft.
