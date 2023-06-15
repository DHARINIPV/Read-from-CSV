# Read-from-CSV

## AIM:
To read files from csv files using python program.

## ALGORITHM:
 1. First we want to import pandas.
 2. Then we want to create csv file.
 3. Both python and csv files are in the same folder.
 4. Then write the revalent code in the python file
 5. Then check the result.

## PROGRAM:
 To read files from csv files using python program.
 
 Developed by: Dharini PV
 
 Register no: 212222240024
```
import pandas as pd

df = pd.read_csv('nba.csv')

print(df.head(10))

print(df.tail())

print("Number of rows:",len(df.axes[0]))

print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/DHARINIPV/Read-from-CSV/assets/119400845/3f4556e4-d11e-4ec8-8122-296023833853)

## RESULT:
The result for read from csv is came successfully

