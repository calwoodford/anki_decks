###### Question 1.

What is array slicing in python? (1)

<details><summary><b>Answer</b></summary>
<p>

Array slicing in Python is a technique used to extract a section of elements from an array or list by specifying a start and end index, and an optional step size. 
```python
original_list = [1, 2, 3, 4, 5, 6, 7, 8, 9]

# Slicing to get a subset of the original list
subset = original_list[2:6]  # This extracts elements from index 2 to 5 (inclusive)

print(subset)  # Output: [3, 4, 5, 6]

```
</p>
</details>

<br><br>

###### Question 2.

What is the `.split()` method in Python used for? (1)

<details><summary><b>Answer</b></summary>
<p>

The `.split()` method in Python is used to split a string into substrings based on a delimiter
```python
text = "Hello, World! This is a sample sentence."

# Splitting the text into words using the default space delimiter
words = text.split()

print(words)
# Output: ['Hello,', 'World!', 'This', 'is', 'a', 'sample', 'sentence.']

```
</p>
</details>
<br><br>

###### Question 3.

How can you reverse a list? (2)
<details><summary><b>Answer</b></summary>
<p>
- Using the `reverse()` method:
```python
my_list = [1, 2, 3, 4, 5]
my_list.reverse()
print(my_list)
# Output: [5,4,3,2,1]
```
- Using slicing to make a reversed copy:
```python
my_list = [1, 2, 3, 4, 5]
reversed_list = my_list[::-1]
print(reversed_list)
# Output: [5,4,3,2,1]
```
</p>
</details>
<br><br>

###### Question 5.

How can you remove duplicates from a list in Python? (2)
<details><summary><b>Answer</b></summary>
<p>
Use a set to remove duplicates, but this will not preserve the order.
  
```python
Copy code
my_list = [1, 2, 2, 3, 4, 4, 5]
unique_list = list(set(my_list))
print(unique_list)
# Output: [1, 2, 3, 4, 5]
```
Use a loop to maintain order while removing duplicates.
```python
Copy code
my_list = [1, 2, 2, 3, 4, 4, 5]
unique_list = []
for item in my_list:
    if item not in unique_list:
        unique_list.append(item)
print(unique_list)
# Output: [1, 2, 3, 4, 5]
```
</p>
</details>
<br><br>

###### Question 6.
What is the difference between a tuple and a list in Python? (2)

<details><summary><b>Answer</b></summary>
<p>
Lists are mutable, created using square brackets [], and generally require more memory.
  
```python
Copy code
my_list = [1, 2, 3]
my_list[0] = 4  # Valid
Tuples are immutable, created using parentheses (), and are more memory-efficient.
python
Copy code
my_tuple = (1, 2, 3)
# my_tuple[0] = 4  # This would raise an error
```
</p>
</details>
<br><br>






