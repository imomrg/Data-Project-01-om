



## \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* PANDAS \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*



#### 1\. Pandas

\-> Open source Python library

\-> Used to read, organize, clean, analyse \& manipulate data.

\-> Mostly used in Machine Learning \& Data Analysis.



Uses:

\- Read CSV / Excel files

\- Filter data

\- Sort data

\- Clean missing data

\- Analyse data

\- Prepare dataset for ML



\---------------------------------------------------------------

#### 

#### 2\. Import Pandas



import pandas as pd



pd --> Alias (short name of pandas)



\---------------------------------------------------------------



#### 3\. DATA STRUCTURES IN PANDAS



A) SERIES

\-> 1D Array (Single Column)



import pandas as pd



marks = pd.Series(\[90,86,98])



print(marks)



OUTPUT



0    90

1    86

2    98







B) DATAFRAME

\-> 2D Table

\-> Contains Rows + Columns

\-> Most used in ML



data = {

&#x20;   "Name":\["A","B"],

&#x20;   "Marks":\[80,90]

}



df = pd.DataFrame(data)



OUTPUT



&#x20;  Name  Marks

0    A      80

1    B      90



\---------------------------------------------------------------



#### 4\. READ DATASET



CSV File



df = pd.read\_csv("student.csv")



Excel File



df = pd.read\_excel("student.xlsx")



\---------------------------------------------------------------



#### 5\. VIEW DATA



First 5 rows

df.head()



First 10 rows

df.head(10)



Last 5 rows

df.tail()



\---------------------------------------------------------------



#### 6\. BASIC FUNCTIONS



df.shape

\-> Returns (Rows, Columns)



Example:

(1000,5)

1000 = Rows

5 = Columns



\----------------------------



df.columns

\-> Shows all column names



\----------------------------



df.info()



Shows:

\- Column Names

\- Data Types

\- Missing Values

\- Number of Rows



\----------------------------



df.describe()



Shows:

\- Count

\- Mean

\- Std (Standard Deviation)

\- Min

\- Max

\- Quartiles



\---------------------------------------------------------------



#### 7\. SELECT DATA



Single Column



df\["Marks"]



Multiple Columns



df\[\["Name","Marks"]]



\---------------------------------------------------------------



#### 8\. FILTER DATA



Marks > 80



df\[df\["Marks"] > 80]



\---------------------------------------------------------------



#### 9\. SORT DATA



Ascending



df.sort\_values("Marks")



Descending



df.sort\_values("Marks", ascending=False)



\---------------------------------------------------------------

#### 

#### 10\. MISSING VALUES



Check Missing Values



df.isnull()



Count Missing Values



df.isnull().sum()



Remove Missing Values



df.dropna()



Fill Missing Values



df.fillna(0)



\---------------------------------------------------------------



#### 11\. IMPORTANT FUNCTIONS



Average         df\["Marks"].mean()



Maximum         df\["Marks"].max()



Minimum         df\["Marks"].min()



Sum             df\["Marks"].sum()



Count           df\["Marks"].count()



Unique Values   df\["Grade"].unique()



\---------------------------------------------------------------

#### 

#### 12\. SAVE DATA

#### 

CSV



df.to\_csv("new.csv")



Excel



df.to\_excel("new.xlsx")



\---------------------------------------------------------------



#### 13\. ML FLOW



Dataset

&#x20;  ↓

Pandas

&#x20;  ↓

Read CSV

&#x20;  ↓

Clean Data

&#x20;  ↓

Analyse Data

&#x20;  ↓

Train ML Model

&#x20;  ↓

Prediction



\---------------------------------------------------------------



