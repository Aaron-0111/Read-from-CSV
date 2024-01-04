# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
Step 1:
Import pandas as pd.

Step 2:
Read the CSV file using read_CSV method.

Step 3:
Use head and tail method to get the required contents from the file.

Step 4:
Use len() method to get the number of rows and columns.

Step 5:
Display the result.

## PROGRAM:
Developed by: Aaron Rajesh R
RegisterNumber: 23008897
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
## OUTPUT:
<img width="644" alt="292658958-930f2610-3e9b-4fa5-a8af-d555b2f3f40c" src="https://github.com/Aaron-0111/Read-from-CSV/assets/149347631/b6ea4ce3-d107-4883-a6fb-772b314da832">

## RESULT:
Thus python program for reading content from a CSV file is successful.

