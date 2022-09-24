# Ex03-Univariate-Analysis

# Aim
To read the given data and perform the univariate analysis with different types of plots.
 
# Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means that the data has only one kind of variable. The major reason for univariate analysis is to use the data to describe. The analysis will take data, summarise it, and then find some pattern in the data.
    
# Algorithm

## Step1
Read the given data.
    
## Step2
Get the information about the data.
    
## Step3
Remove the null values from the data.

## Step4
Mention the datatypes from the data.
    
## Step5
Count the values from the data.
    
## Step6
Do plots like boxplots,countplot,distribution plot,histogram plot.
    
# Program
```
Developed by        : AKASH KUMAR B
Registration Number : 212221040011
```
```
import pandas as pd
import numpy as np
import seaborn as sns

df=pd.read_csv('superstore.csv')
df

df.head()
df.info()
df.describe()
df.isnull().sum()

df.dtypes

df['Postal Code'].value_counts()

sns.boxplot(x='Postal Code', data=df)
sns.countplot(x='Postal Code',data=df)
sns.distplot(df["Postal Code"])
sns.histplot(x='Postal Code',data=df)
```

# Output

DATA

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/1.JPG)
 
DATA HEAD

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/2.JPG)

DATA INFORMATION

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/3.JPG)

DATA DESCRIBE

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/4.JPG)

DATA NULL VALUES

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/5.JPG)

DATA'S DATATYPES

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/6.JPG)

DATA'S VALUECOUNT

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/7.JPG)

BOXPLOT

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/8.JPG)

COUNTPLOT

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/9.JPG)
DISTRIBUTION PLOT

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/10.JPG)

HISTOGRAM PLOT

![](https://github.com/AKASHBKUMAR/Ex03-Univariate-Analysis/blob/main/11.JPG)
# Result
Thus we have read the given data and performed the univariate analysis with different types of plots.





    
