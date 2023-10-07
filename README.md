# Personal-Notes
#Numpy

NumPy is a powerful Python library for numerical and scientific computing. It provides a wide range of
functions for performing operations on arrays and matrices. Here are some 
important NumPy functions along with their common use cases:

1. **`np.array()`**:
   - **Use Case**: Creating NumPy arrays from lists or other iterable objects.
   - **Example**: `arr = np.array([1, 2, 3])`

2. **`np.zeros()`** and **`np.ones()`**:
   - **Use Case**: Creating arrays filled with zeros or ones of a specified shape.
   - **Example**: `zeros_arr = np.zeros((2, 3))`

3. **`np.empty()`**:
   - **Use Case**: Creating an uninitialized array with a specified shape.
   - **Example**: `empty_arr = np.empty((3, 3))`

4. **`np.arange()`**:
   - **Use Case**: Creating an array with regularly spaced values within a specified range.
   - **Example**: `arr = np.arange(0, 10, 2)`

5. **`np.linspace()`**:
   - **Use Case**: Creating an array with evenly spaced values over a specified range.
   - **Example**: `arr = np.linspace(0, 1, 5)`

6. **`np.random.rand()`** and **`np.random.randn()`**:
   - **Use Case**: Generating random numbers from a uniform or normal distribution.
   - **Example**: `rand_nums = np.random.rand(3, 3)`

7. **`np.shape`** and **`np.reshape()`**:
   - **Use Case**: Getting the shape of an array and changing the shape of an array.
   - **Example**: `shape = arr.shape`, `reshaped_arr = arr.reshape(2, 3)`

8. **`np.mean()`**, **`np.median()`**, **`np.std()`**, **`np.var()`**:
   - **Use Case**: Calculating the mean, median, standard deviation, and variance of an array.
   - **Example**: `mean_val = np.mean(arr)`

9. **`np.min()`** and **`np.max()`**:
   - **Use Case**: Finding the minimum and maximum values in an array.
   - **Example**: `min_val = np.min(arr)`

10. **`np.sum()`**:
    - **Use Case**: Calculating the sum of array elements.
    - **Example**: `sum_val = np.sum(arr)`

11. **`np.dot()`**:
    - **Use Case**: Computing the dot product of two arrays (vectors).
    - **Example**: `dot_product = np.dot(arr1, arr2)`

12. **`np.transpose()`**:
    - **Use Case**: Transposing an array (swapping rows and columns).
    - **Example**: `transposed_arr = np.transpose(arr)`

13. **`np.concatenate()`**:
    - **Use Case**: Concatenating arrays along a specified axis.
    - **Example**: `concatenated_arr = np.concatenate((arr1, arr2), axis=0)`

14. **`np.split()`**:
    - **Use Case**: Splitting an array into multiple subarrays.
    - **Example**: `subarrays = np.split(arr, 3)`

15. **`np.argmax()`** and **`np.argmin()`**:
    - **Use Case**: Finding the indices of the maximum and minimum values in an array.
    - **Example**: `max_index = np.argmax(arr)`

16. **`np.where()`**:
    - **Use Case**: Finding indices where a specified condition is met.
    - **Example**: `indices = np.where(arr > 5)`

17. **`np.unique()`**:
    - **Use Case**: Finding unique elements in an array and their counts.
    - **Example**: `unique_elements, counts = np.unique(arr, return_counts=True)`

These are just a few of the many functions provided by NumPy. NumPy is a fundamental library for numerical computing 
in Python and is widely used in data analysis, machine learning, scientific research, and more. Depending on your specific
use case, you'll likely encounter and use many other NumPy functions.
