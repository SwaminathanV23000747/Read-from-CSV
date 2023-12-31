# Read-from-CSV

## AIM:
To read from CSV
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output:
## PROGRAM:
```python
#Program to read contents from a csv file
#Developed by : Swaminathan V
#Register nuumber:23000747
import pandas as pd
df=pd.read_csv('/content/cars (1) (4).csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```
## OUTPUT:
![Screenshot 2023-12-31 142938](https://github.com/SwaminathanV23000747/Read-from-CSV/assets/148931113/29bb3c49-338b-44a4-bd62-1e18c2d1e010)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
