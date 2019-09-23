# preditionofbest_tearm_datascience
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
#improted wanted libray

saphani=pd.read_csv('results.csv') #gatting csv values from your machine

saphani.head() #displaye you data  it frist display first 5 data

saphani.dtypes #checking data type

saphani.info() #checking null values if it is ther 

saphani.isnull().sum() #easys way of checking null value

sns.heatmap(saphani.corr())

saphani.corr()

saphani.columns
sns.pairplot(saphani)

saphani.head()

saphani.sort_values('home_score',ascending=False).head()
