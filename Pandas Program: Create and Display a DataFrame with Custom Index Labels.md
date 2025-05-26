# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** program to join the two given dataframes along columns and assign all data.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary.

3.Create DataFrames:

Use pd.DataFrame() to convert data1 into df1.

Use pd.DataFrame() to convert data2 into df2.

4.Print the original DataFrames:

5.Display df1 and df2 for verification.

6.Concatenate the two DataFrames:

7.Use pd.concat([df1, df2], axis=1) to join the DataFrames side by side (column-wise).

8.Store the result in a variable (e.g., result).

9.Display the result:

10.Print the concatenated DataFrame.

11.End
---

## 💻 Program
``` python
import pandas as pd
data1 = {'s_id': ['S1', 'S2', 'S3', 'S4', 'S5'],'name': ['Dan', 'Ryder', 'Bryce', 'Bernal', 'Kwame'], 'marks': [200, 210, 190, 222, 199]}
data2 = { 's_id': ['S4', 'S5', 'S6', 'S7', 'S8'], 'name': ['Scart', 'Willy', 'Dani', 'Kaise', 'Madeeha'], 'marks': [201, 200, 198, 219, 201]}
df1 = pd.DataFrame(data1)
df2 = pd.DataFrame(data2)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
print()
result = pd.concat([df1, df2], axis=1)
print("Join the said two dataframes along columns:")
print(result)
```
## Output
![image](https://github.com/user-attachments/assets/969e348d-b477-480c-9f9e-d8f9bcede795)

## Result
Thus the **Pandas** program to join the two given dataframes along columns and assign all data is executed successfully.
