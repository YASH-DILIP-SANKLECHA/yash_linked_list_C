# yash_linked_list_C
Singly Linked List in C (All 12 Operations)

This project implements a complete singly linked list in C with 12 fundamental operations, written cleanly and modularly — ideal for college lab programs or data structures practice.

A singly linked list is a linear data structure where each node points to the next, forming a sequence. This program allows insertion, deletion, and display of elements in multiple ways using a menu-driven interface.

Operations implemented:

1. Insert at front


2. Insert at rear


3. Insert after a specific element


4. Insert before a specific element


5. Insert at a given position


6. Delete from front


7. Delete from rear


8. Delete after a specific element


9. Delete before a specific element


10. Delete at a given position


11. Display list from front to rear


12. Display list from rear to front (using recursion)



Structure used: struct Node { int info; struct Node *next; }; struct Node *first = NULL;

How to run: For Linux or macOS: gcc linked_list.c -o linkedlist ./linkedlist

For Windows: gcc linked_list.c -o linkedlist.exe linkedlist.exe

Sample menu: ---- Singly Linked List Operations ---- 1.Insert Front 2.Insert Rear 3.Insert After 4.Insert Before 5.Insert At Position 6.Delete Front 7.Delete Rear 8.Delete After 9.Delete Before 10.Delete At Position 11.Display Forward 12.Display Reverse 13.Exit

Example run: Enter choice: 1 Enter value: 10 Enter choice: 2 Enter value: 20 Enter choice: 11 List (front → rear): 10 20

Notes:

Uses int info and first pointer for clarity.

Fully dynamic memory allocation using malloc() and free().

Recursive reverse display without using extra array.

Separate clean functions for each operation.


Author: Yash
Engineering Student (CSE)
SDM College of Engineering and Technology

License: This project is open-source under the MIT License.
