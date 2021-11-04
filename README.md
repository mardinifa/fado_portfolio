# fado_portfolio
Example Data Science Portfolio
  project 1: Exploratory Data Analysis (EDA)project  ❤❤
Exploratory Data Analysis, or EDA, is an important step in any Data Analysis or Data Science project. EDA is the process of investigating the dataset to discover patterns, and anomalies (outliers), and form hypotheses based on our understanding of the dataset.

EDA involves generating summary statistics for numerical data in the dataset and creating various graphical representations to understand the data better. In this article, we will understand EDA with the help of an example dataset. We will use Python language (Pandas library) for this purpose.

EDA and its role in improving business operations - Selerity

Importing libraries
We will start by importing the libraries we will require for performing EDA. These include NumPy, Pandas, Matplotlib, and Seaborn.

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns
Reading data
We will now read the data from a CSV file into a Pandas DataFrame. You can download the dataset for your reference.

df = pd.read_csv(r'C:UsersVipinData AnalyticsStudentsPerformance.csv')
