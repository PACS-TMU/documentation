# NumPy Documentation
<sup style="display: inline-block;">**Note:** This document is meant for internal PACS use only.</sup>

This documentation covers basic NumPy concepts and helps you get started with using NumPy. A table of common, helpful built-in functions is shown at the end.

## Quick Links
#### [What is NumPy - Quick Summary](#what-is-numpy---quick-summary-1)
#### [Importing NumPy - Creating your First NumPy Array](#importing-numpy---creating-your-first-numpy-array-1)
#### [Indexing NumPy Arrays](#indexing-numpy-arrays-1)
#### [Common NumPy Functions](#common-numpy-functions-1)

## What is Numpy - Quick Summary
NumPy is the fundemental library for numerical and scientific computation in Python. The library offers a multi-dimensional array object, and various objects derived from it. NumPy is faster than using regular Python because the array object is homogeneous (it only allows one type of object to be stored in it, i.e., a NumPy array can be all integers, all strings, etc., but not a mix of objects). The multi-dimensional array object is NumPy is called ndarray (N-Dimensional Array) by convention.

## Importing NumPy - Creating your First NumPy Array
To import NumPy, we can add the following line of code at the top of our Python file:
```python
import numpy as np
```
>Note: The import statement above only works if you have installed NumPy. To install NumPy, follow the tutorial in the <a href="https://github.com/PACS-TMU/documentation/blob/main/Data-Science/00%20getting-started.md#section-3-installing-numpy-and-pandas---pip" target="_blank">getting started doc</a>.

To create our first NumPy ndarray, we can run the following:
```python
import numpy as np

arr = np.array([1,2,3,4,5])

print(arr)
print(type(arr))
```

The expected output is:
```python
[1 2 3 4 5]
<class 'numpy.ndarray'>
```

When using NumPy, we usually work with multi-dimensional arrays. Therefore, it's helpful to see how we can create NumPy arrays of different dimensions.

<details>
  <summary>0-D Arrays</summary>

  ```python
  import numpy as np
  
  arr = np.array(42)
  
  print(arr)
  ```
  
</details>

<details>
  <summary>1-D Arrays</summary>

  ```python
  import numpy as np
  
  arr = np.array([4, 3, 5, 7])
  
  print(arr)
  ```
  
</details>

<details>
  <summary>2-D Arrays</summary>

  ```python
  import numpy as np
  
  arr = np.array([[1, 2, 3, 4, 5],
                  [4, 2, 6, 7, 8],
                  [1, 4, 7, 8, 3]])
  
  print(arr)
  ```
  
</details>

<details>
  <summary>3-D Arrays</summary>

  ```python
  import numpy as np
  
  arr = np.array([[[1, 2, 3],
                   [4, 5, 6]],
                  [[1, 2, 3],
                   [4, 5, 6]]])
  
  print(arr)
  ```

</details>

### Checking Array Dimensions
To check the dimension of a NumPy array, we can use the following built-in function, `ndim`:
```python
import numpy as np

# We can create a NumPy array from a tuple
arr = np.array((1,2,3,4,5))

print(arr)
print(arr.ndim) # prints 1, since arr has 1 dimension
```

### Practice
Question: Create 4 NumPy arrays, each with different dimensions. Print the dimensions of each, and check that the result is as expected.

<details>
  <summary>Suggested Solution</summary>

  ```python
  import numpy as np

  a = np.array(42)
  b = np.array([1, 2, 3, 4, 5])
  c = np.array([[1, 2, 3], [4, 5, 6]])
  d = np.array([[[1, 2, 3], [4, 5, 6]], [[1, 2, 3], [4, 5, 6]]])
  
  print(a.ndim)
  print(b.ndim)
  print(c.ndim)
  print(d.ndim)
  ```

  Expected Output:
  ```python
  0
  1
  2
  3
  ```

</details>

## Indexing NumPy Arrays

## Common NumPy Functions
