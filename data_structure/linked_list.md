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