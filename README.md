# Read-from-CSV
## AIM:
To write a python program for reading the csv file content
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
## Step 2:
To write a python program for reading the csv file content
## Step 3:
The number of rows returned is defined in Pandas option settings.
## Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
## Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by:LOGA MITHRA.R
#Register Number: 212223100027

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![output](/img%201.png)
## RESULT:
Thus the program is written to read the csv file.