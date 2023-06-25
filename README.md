# Read-from-CSV

## AIM:To write a program for reading the csv file content.

## ALGORITHM:
### Step 1:Load the CSV into a DataFrame

### Step 2:Print the number of contents to be displayed using df.head().

### Step 3:The number of row returned is defined in pandas option settings.

### Step 4:Check your systems maximun column with the
pd.options.display.max_columun statement.

### Step 5:: Increase the maximum number of rows to display the entire
DataFrame.

## PROGRAM:
   #Developed by: rohit g

   #RegisterNumber: 212222240083

   import pandas as pd
   
   df=pd.read_csv("nba.csv")
   
   print(df.head(10))
   
   print(df.tail())
   
   print("rows",df.axes[0])
   
   print("columns",df.axes[1])
   
   print("no of rows",len(df.axes[0]))
   
  print("no of rows",len(df.axes[1]))


## OUTPUT:
![image](https://github.com/rohitgunasekaran/Read-from-CSV/assets/119404546/d2a81ef0-f82f-4fe8-b646-0208c545c33c)


## RESULT:
Thus the program executed successfully for read csv
file.
