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
a=eval(input())
array = np.array(a)
print('Given array','\n',array)
print()
print(np.sort(array,axis=0))
```

## Output
<img width="875" height="657" alt="Screenshot (86)" src="https://github.com/user-attachments/assets/a25b28f5-120a-4c5c-a7a1-2d7c722189cb" />


## Result
Thus the python program was created successfully.
