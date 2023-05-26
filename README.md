# Data Analysis of Best-selling Phones of All Time.

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
import matplotlib.pyplot as plt
import seaborn as sns #data visualization 
sns.set_style("white")
Data Analysis of Best-selling Phones of All Time.
# /kaggle/input/best-selling-mobile-phones/best-selling-mobile-phones.csv we are going to use this dataset for our analysis
best_selling = pd.read_csv("/kaggle/input/best-selling-mobile-phones/best-selling-mobile-phones.csv")
#shape of the dataset
print("Shape of the dataset is",best_selling.shape)
#information about the dataset
best_selling.info()
#check for null values
best_selling.isna().value_counts()
