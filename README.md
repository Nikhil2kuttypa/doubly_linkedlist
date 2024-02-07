# doubly_linkedlist
Overview:
This Java program demonstrates the implementation of a Doubly Linked List (DLL) using object-oriented principles. A DLL is a type of linked list where each node contains a data element and two references, one pointing to the next node and another pointing to the previous node.

Files:

dllist.java: This file contains the main class dllist which includes the main method. It demonstrates the usage of the Doubly Linked List by performing various operations such as insertion, deletion, searching, and displaying elements.

Node.java: This file defines the Node class which represents a node in the Doubly Linked List. Each node contains an integer data value, a reference to the next node (next), and a reference to the previous node (prevs).

Double.java: This file defines the Double class which encapsulates the functionality of the Doubly Linked List. It includes methods for insertion at the beginning, insertion at the end, insertion at a specified position, searching for an element, checking if an element exists, displaying elements in both forward and backward directions, and deletion operations.

How to Use:
To use this Doubly Linked List implementation:

Compile the dllist.java, Node.java, and Double.java files.
Run the compiled dllist class.
The program demonstrates various operations on the Doubly Linked List and outputs the results.
Operations:

Insertion:

insertAtFirst(int data): Inserts a new node with the given data at the beginning of the list.
insertAtEnd(int data): Inserts a new node with the given data at the end of the list.
insertAtPosition(int pos, int data): Inserts a new node with the given data at the specified position in the list.
Deletion:

deletePos(int pos): Deletes the node at the specified position.
delete(): Deletes the first node in the list.
deleteAtLast(): Deletes the last node in the list.
Search:

search(int data): Searches for the given data in the list and returns the position of the first occurrence (-1 if not found).
contains(int data): Checks if the given data exists in the list.
Display:

displayFrontwards(): Displays the elements of the list from the head to the tail.
displayBackwards(): Displays the elements of the list from the tail to the head.
Note:

The DLL is implemented with integer data values. Modify the Node class and Double class if you want to store other types of data.
Ensure proper initialization and handling of edge cases (e.g., empty list, deletion from an empty list) to prevent runtime errors.
Feel free to extend the functionality or optimize the code further based on your requirements.
