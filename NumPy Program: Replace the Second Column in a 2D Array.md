# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program

```
import numpy as np

original_array = np.array([[1, 2, 3],
                           [4, 5, 6],
                           [7, 8, 9]])

new_column = np.array([10, 11, 12])  # Must match number of rows

modified_array = np.delete(original_array, 1, axis=1)

updated_array = np.insert(modified_array, 1, new_column, axis=1)

# Step 5: Display updated array
print("Updated array:\n", updated_array)
```

## Output



![Screenshot 2025-05-23 211308](https://github.com/user-attachments/assets/0a599a3f-bd90-421a-b223-378831150b08)


## Result

Thus, the program is verified successfully.
