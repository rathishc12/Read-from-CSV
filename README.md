# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.

## PROGRAM:
```
#Developed by: Rathish kumar C
#Reference No: 22009283
import pandas as pd 
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/120539398/214829485-f4293e5a-bd6a-4725-86da-e3bd8c11f7a6.png)


## RESULT:
