#Getting the dependancy libraries
import csv
import pandas as pd
import numpy as np 
import matplotlib
df = pd.read_csv(r"C:\Users\John\Downloads\Churn_Modelling.csv")
df = pd.read_csv(r"C:\Users\John\Downloads\insuramce.csv")

df.info()
df.head()
df.describe()

print(df.duplicated().sum())

#checking for null Value
df.isnull().sum()

df.boxplot()
df.describe()


#find the count of  value with unique columns
df.boxplot()
df.isna().sum()


    
             
 

   

