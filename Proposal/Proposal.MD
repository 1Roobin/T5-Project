# Project proposal

This Project proposal is for the project of T5 Bootcamp requirements.

# The growth of the temperature over time

As the increase of temperature over time could cause certain issues for the planet, such as global warming, this study came in handy to understand how the average temperature is growing.


# Aims

Understanding how much temperature is growing, and how much it affects global warming.


# Dataset

I'll use (Daily Temperature of Major Cities) dataset because it gives us daily average temperature values recorded in major cities of the world.

***
Dataset Attributes:



 0   Region          object 
 
 1   Country         object 
 
 2   State           object 
 
 3   City            object 
 
 4   Month           int64  
 
 5   Day             int64  
 
 6   Year            int64  
 
 7   AvgTemperature  float64
***

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Tools

EDA tools (***Pandas***,***Numpy***)

Visulizatoin tools (***Seaborn***,***Matplotlib***)

Modeling tools (***sklearn***,***Statsmodels***)

# Steps

* We will start by exploring our data (EDA), then we will create a model to predict the overall increase in temperature
