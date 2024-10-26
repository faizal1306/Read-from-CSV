# DATE
# EX-12 Read-from-CSV
# Name:Mohamed Faizal M
## AIM:
To write a python program for reading the csv file content
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
Developed By:Bhuvaneshwari M
Registration No: 212223230033
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![12 1](https://github.com/user-attachments/assets/4eff1cb3-7325-457f-b84a-7c79c7957ade)
![12 2](https://github.com/user-attachments/assets/eeca835e-ef04-4910-8c95-6307162676da)
## RESULT:
Thus the program is written to read the csv file.
