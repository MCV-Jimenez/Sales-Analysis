# Food Sales Predictions
![Project Image](https://v5c5v6u7.stackpathcdn.com/wp-content/uploads/blog/demand-forecasting.jpg)

---

### Table of Contents

- [Description](#description)
- [Methods Used](#methods-used)
- [References](#references)
- [Author Info](#author-info)

---

## Description

This is a basic sales analysis project aimed at analyzing sales data for a company. The project consists of inspecting, cleaning, analyzing, preparing data for machine learining, and executing machine learning models.

#### Methods Used
> All code written using Python
- Pandas for data manipulation: Filling missing values, fixing inconsistent categories
```python
#Libraries used
import pandas as pd
import numpy as np
```
- Exploratory visualizations: Multiple graph visualizations to analyze the data more in depth and draw conclusions
```python
#Libraries used
import matplotlib.pyplot as plt
import seaborn as sn
```
- Machine learning prep: Using column transformers and pipelines to format the dataset to be used in Machine Learning
```python
#Libraries used
from sklearn.preprocessing import StandardScaler, OneHotEncoder
from sklearn.impute import SimpleImputer
from sklearn.compose import make_column_transformer, make_column_selector
from sklearn.pipeline import make_pipeline
from sklearn.model_selection import train_test_split
```
- Regression Models: Applying multiple regression models to make sales predictions on the data 
```python
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score
from sklearn.tree import DecisionTreeRegressor
from sklearn.linear_model import LinearRegression
```
---

## References
>Data: [Sales Predictions](https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view)
---

## Author Info

- Email - jimenezmarco3254@gmail.com
- LinkedIn - [Marco Jimenez](https://www.linkedin.com/in/marco-jimenez-50637922b/)

[Back To The Top](#Food-Sales-Predictions)
