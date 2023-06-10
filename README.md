# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
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
#Developed by:M.PRAKASH
#Register no:21222100035
import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))

```

## OUTPUT:
<img width="552" alt="Screenshot_20230610_115554" src="https://github.com/Prakashmathi2004/Read-from-CSV/assets/118350045/bec20b1d-2307-44ee-a8c7-813036c33c2c">

<img width="567" alt="Screenshot_20230610_115653" src="https://github.com/Prakashmathi2004/Read-from-CSV/assets/118350045/571dec7d-c12a-4355-817f-6dac62a3e36f">

<img width="614" alt="ex 077" src="https://github.com/Prakashmathi2004/Read-from-CSV/assets/118350045/b3c36836-73aa-497d-b441-fb47b8bc035e">


## RESULT:
Thus a python program is written to read the contents of a CSV file.
