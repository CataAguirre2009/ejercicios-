# ejercicios-
02.py
import pandas as pd
df=pd.read_csv('StudentsPerformance.csv')
#print(df['gender'])
print(df[['gender']].head())
#print(df[['gender']].head(12))
#print(df[['gender']].tail())
#print(df[['gender']].tail(12))
