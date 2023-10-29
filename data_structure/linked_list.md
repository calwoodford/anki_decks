###### Question 1.
What is a linked list in data structures? (1)

<details><summary><b>Answer</b></summary>
<p>
A linked list is a linear data structure that consists of a sequence of elements, each containing a reference (link) to the next element in the sequence. Each element in a linked list is called a node, and each node contains two fields: a data field that stores the element, and a next field that stores the reference to the next node in the sequence.

</p>
</details>
<br><br>

###### Question 2.
How does a singly linked list differ from a doubly linked list? (1)

<details><summary><b>Answer</b></summary>
<p>
In a singly linked list, each node has a reference to the next node in the sequence, but not to the previous node. In contrast, a doubly linked list has nodes that contain references to both the next and the previous nodes in the sequence. This allows for easier traversal in both directions (forward and backward) in a doubly linked list.

</p>
</details>
<br><br>

###### Question 3.
What are the basic operations that can be performed on a linked list? (1)

<details><summary><b>Answer</b></summary>
<p>
The basic operations that can be performed on a linked list are:

Insertion: Adding a new node to the list.
Deletion: Removing a node from the list.
Traversal: Accessing each node in the list, typically to display or process its data.
Searching: Finding a node with a specific data value in the list.
Updating: Changing the data value of a node in the list.
</p>
</details>

###### Question 4.
How do you reverse a linked list? (1)

<details><summary><b>Answer</b></summary>
<p>
To reverse a singly linked list, you can use the following steps:
Initialize three pointers: prev, current, and next. Set prev to NULL, and current to the head of the list.
Iterate through the list until current is NULL. In each iteration, do the following:

a. Save the next node of current in next.
b. Change the next pointer of current to prev.
c. Move prev to current and current to next.

After the iteration, set the head of the list to prev.
This will reverse the order of the nodes in the list, making the last node the new head.

</p>
</details>
<br><br>

###### Question 5.
What are the advantages and disadvantages of a linked list over an array? (1)

<details><summary><b>Answer</b></summary>
<p>
Advantages of a linked list over an array:
Dynamic size: A linked list can easily grow or shrink in size, while an array has a fixed size or requires reallocation to change size.
Ease of insertion and deletion: Inserting or deleting an element in a linked list can be done with O(1) time complexity if the node is known, whereas in an array, it requires shifting of elements and has O(n) time complexity.
Disadvantages of a linked list over an array:

Memory overhead: Each element in a linked list requires additional memory for the next (and possibly previous) pointer, whereas an array only needs memory for the elements themselves.
Random access: Arrays provide constant time complexity for random access of elements, while linked lists have O(n) time complexity for random access since they need to be traversed from the head to the desired element.
</p>
</details>
<br><br>

###### Question 6.
What is a circular linked list? (1)

<details><summary><b>Answer</b></summary>
<p>
A circular linked list is a type of linked list in which the last node in the list points to the first node, forming a loop or circle. In other words, in a circular linked list, the next pointer of the last node does not point to NULL (as in a regular singly linked list), but instead points to the first node. This allows for more convenient circular traversal of the list.
There are two types of circular linked lists:

Singly circular linked list: Where each node has a reference only to the next node in the sequence.
Doubly circular linked list: Where each node has references to both the next and the previous nodes in the sequence.
</p>
</details>
<br><br>