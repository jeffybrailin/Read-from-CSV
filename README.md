# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Start the program.
### Step 2:
Create a file nba.csv in anaconda navigator.
### Step 3:
Write a program to read the contents in the csv file.
### Step 4:
Run the program.

### Step 5:
Print the output.
## PROGRAM:
# To write a python program for reading content from a csv file
# Developed by: Jeffy Brailin T
# Register number: 212223040076
```
import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
<img width="820" height="725" alt="image" src="https://github.com/user-attachments/assets/570987f5-2505-4caf-9041-960956459c89" />

## RESULT:
Hence, the contents are read successfully.
