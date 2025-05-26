# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements of a given 2D array in ascending order.
## Case 1: Sort array by the second row
## Case 2: Sort the array by the second column

## 🧠 Algorithm

1.Start

2.Input a 2D list from the user (as a string, e.g., [[...], [...], [...]])

3.Convert the input string to a NumPy array

4.Print the original array

5.Sort by second row (row index 1):

a. Get the sort order of columns using argsort() on the second row

b. Rearrange the columns accordingly

c. Print the sorted array

6.Sort by second column (column index 1):

a. Get the sort order of rows using argsort() on the second column

b. Rearrange the rows accordingly

c. Print the sorted array

7.End


## 🧾 Program
``` python
import numpy as np
a = np.array(eval(input()))
print("Printing Original array")
print(a)
sorted_by_row = a[:, a[1].argsort()]
print("Sorting Original array by second row")
print(sorted_by_row)
sorted_by_col = a[a[:, 1].argsort()]
print("Sorting Original array by second column")
print(sorted_by_col)
```
## Output
![Screenshot 2025-05-24 161130](https://github.com/user-attachments/assets/1919ef72-b6ab-43e9-ad08-f3c36128449a)

## Result
Thus the **NumPy** program that sorts the elements of a given 2D array in ascending order is executed successfully.
