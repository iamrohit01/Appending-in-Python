# LinkedList Implementation with Append Method

This project demonstrates the implementation of a singly linked list with an `append` method in Python.

## Overview

The code defines two classes:

-   `Node`: Represents a node in the linked list, containing a `value` and a reference to the `next` node.
-   `LinkedList`: Represents the linked list itself, with methods for initialization, printing the list, and appending new nodes.

## Files

-   `append.py`: Contains the complete implementation of the linked list with the `append` method.
-   `Readme.md`: This file, providing an overview of the project.

## Usage

To use the linked list, you can create an instance of the `LinkedList` class and then use the `append` method to add elements to the list. The `print_list` method can be used to display the elements in the list.

```python
# filepath: c:\Users\HP\OneDrive\Desktop\DSA\Append\append.py
my_linked_list = LinkedList(1)
my_linked_list.append(2)
my_linked_list.append(3)
my_linked_list.print_list()