# Python Variable Annotations

This repository contains a series of Python scripts that demonstrate the use of type annotations in Python. Each script focuses on a specific aspect of type annotations, from basic function annotations to more complex type hints involving lists, unions, and callables.

## Tasks

### 0. Basic annotations - add
**File:** `0-add.py`  
Write a type-annotated function `add` that takes two floats `a` and `b` and returns their sum as a float.

**Example:**
```python
add(1.11, 2.22) == 3.33

1. Basic annotations - concat
File: 1-concat.py
Write a type-annotated function concat that takes two strings str1 and str2 and returns their concatenation as a string.

Example:concat("egg", "shell") == "eggshell"

2. Basic annotations - floor
File: 2-floor.py
Write a type-annotated function floor that takes a float n and returns its floor as an integer.

Example:floor(3.14) == 3

3. Basic annotations - to string
File: 3-to_str.py
Write a type-annotated function to_str that takes a float n and returns its string representation.

Example:to_str(3.14) == "3.14"

4. Define variables
File: 4-define_variables.py
Define and annotate the following variables with the specified values:

a: integer with value 1

pi: float with value 3.14

i_understand_annotations: boolean with value True

school: string with value "ALX"

5. Complex types - list of floats
File: 5-sum_list.py
Write a type-annotated function sum_list that takes a list of floats input_list and returns their sum as a float.

Example:sum_list([3.14, 1.11, 2.22]) == 6.47

6. Complex types - mixed list
File: 6-sum_mixed_list.py
Write a type-annotated function sum_mixed_list that takes a list mxd_lst of integers and floats and returns their sum as a float.

Example:sum_mixed_list([5, 4, 3.14, 666, 0.99]) == 679.13

7. Complex types - string and int/float to tuple
File: 7-to_kv.py
Write a type-annotated function to_kv that takes a string k and an integer or float v and returns a tuple where the first element is k and the second element is v squared (as a float).

Example:to_kv("eggs", 3) == ("eggs", 9)
to_kv("school", 0.02) == ("school", 0.0004)

8. Complex types - functions
File: 8-make_multiplier.py
Write a type-annotated function make_multiplier that takes a float multiplier and returns a function that multiplies a float by multiplier.

Example:fun = make_multiplier(2.22)
fun(2.22) == 4.9284

9. Let's duck type an iterable object
File: 9-element_length.py
Annotate the function element_length to specify that it takes an iterable of sequences and returns a list of tuples where each tuple contains a sequence and its length.

Example:element_length(["hello", "world"]) == [("hello", 5), ("world", 5)]

Requirements
All files should be executable and contain shebangs.

All functions and variables must be type-annotated as specified.

The code should pass mypy type checking.

Repository
GitHub repository: alx-backend-python

Directory: 0x00-python_variable_annotations
