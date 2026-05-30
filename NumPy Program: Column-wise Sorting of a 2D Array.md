# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

arr = np.array([[9, 4, 7],
                [3, 8, 2],
                [6, 1, 5]])

print("Original Array:")
print(arr)

sorted_arr = np.sort(arr, axis=0)

print("Column-wise Sorted Array:")
print(sorted_arr)
```
## Output
<img width="1195" height="433" alt="{958DEC47-4B41-49E3-9563-532DD2516835}" src="https://github.com/user-attachments/assets/90c783c6-19ec-471d-bdb2-c58c9c85c341" />


## Result
Thus the python program for sorting each column in numpy has been implemented and executed successfully.


