# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()`  to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
``` python
import pandas as pd
d=eval(input())
df=pd.DataFrame(d)
print("Original Dataframe",end='\n ')
print(df)
new=eval(input())
df.loc[len(df)]=new
print("combined Dataframe",end='\n ')
print(df)
```
## Output
![image](https://github.com/user-attachments/assets/c4e08917-65a0-4d8d-95f3-e72b1440bd2a)

## Result
Thus the Python program using Pandas to **join two DataFrames along rows** is executed successfully.
