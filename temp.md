How can you reverse a list? (2)
<details><summary><b>Answer</b></summary>
<p>
1. Using the `reverse()` method:
```python
my_list = [1, 2, 3, 4, 5]
my_list.reverse()
print(my_list)
# Output: [5,4,3,2,1]
```
2. Using slicing to make a reversed copy:
```python
my_list = [1, 2, 3, 4, 5]
reversed_list = my_list[::-1]
	@@ -70,7 +73,9 @@ print(reversed_list)
What is a lambda function? How are these written in Python? (1)
<details><summary><b>Answer</b></summary>
<p>
A lambda function in Python is a small anonymous function defined using the `lambda` keyword. It can have any number of parameters but can have only one statement.
```python
add = lambda x, y: x + y
result = add(5, 3)
	@@ -80,36 +85,54 @@ print(result)  # Output: 8
</details>
<br><br>

###### Question 5

What are modules and packages in Python? (1)
<details><summary><b>Answer</b></summary>
<p>
Python packages and Python modules are two mechanisms that allow for modular programming in Python.

**Modules** are Python files with a `.py` extension and can have a set of functions, classes and variables and can be imported using the `import` command
```python
import foo
import numpy as np
```

**Packages** are basically modules combined into a folder and help by providing a hierarchical structuring of module namespaces. You can import modules from a package using the `from` command.
```python
from my_package import module1
from scipy import integrate
```
</p>
</details>
<br><br>

###### Question 6

What is the `pandas` library used for in Python? (1)
<details><summary><b>Answer</b></summary>
<p>
Pandas is an open-source, python library used in data manipulation of applications that require high performance. Pandas help perform five significant data analysis steps: load the data, clean/manipulate it, prepare it, model it and analyse it.
</p>
</details>
<br><br>
