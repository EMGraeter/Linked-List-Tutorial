# Linked-List-Tutorial
A Linked List Tutorial written by a student

In this tutorial I will be teaching you about the data structure Linked List. A linked list is a sequence container where the sequence can be changed very easily. It is useful when you want an easy way to add elements anywhere in your list or the list needs to change frequently. It also doesn't require the memory to be in the same place so the memory can be allocated to any available spot with enough room for the element. Elements in linked lists are referred to as nodes, because unlike arrays or vectors, each node holds more that just the value of the variable. It holds the value of the variable and the pointer to the next node. Depending on the type of linked list it can also hold a pointer to the previous node. Using pointers also allows nodes to be added to the beginning of the list as well as in the middle and the end very easily without causing problems.

Linked Lists can be used in two ways in C++, with 'forward_list' as a singly linked list or with 'list' as a doubly linked list. The difference between these two is that a singly linked list can only go from the beginning of the list and follow the nodes to the end of the list and a doubly linked list can start from the beginning and go to the end or start from the end and go to the beginning. In a singly linked list each node holds one pointer to the next node, but in a doubly linked list each node holds two pointers, one ot the next node and one to the previous node. If a node is at the end of the list then it points to null.

In order to make a linked list the type of list needs to be specified followed by the type of values the list will be holding the the name of the list suche as forward_list<int> singlyList;. In both forward_list and list there are the modifiers push_front() and pop_front(). push_front() puts whatever value stated in the function to the front of the list. pop_front() deletes the first value from the front of the list. list also has push_back() and pop_back() which are similar to the previous functions but they push and pop values from the end of the list.
  
Both list and forward_list have insert_after and erase_after modifiers where either a new node is inserted in the list after a specified point or a node is erased from the list (such as singlyList.erase_after(singlyList.begin()); this will erase the second node in the list). There is also clear() which will erase all the nodes in the list.

There are also operations that can be used with the lists. remove() removes nodes with a specified value (such as singlyList.remove(7); this will remove all nodes with the value of 7 from the list). There is also a remove_if() operator which will remove elements if they meet a specified condition. There is another operator called unique() which will remove any nodes with a duplicate value from the list leaving only one. There is also merge() which merges two lists together but only if they are sorted first. Luckily there is also an opperator called sort() which puts the nodes in order from least to greatest. There is another operator called reverse() which reverses the order of everything in the list.

Linked lists are used for many different things. One of the most common that is overlooked often is in web browsing. The back and forward buttons at the top left of the window are a great example of a linked list. It has pointers from when you started searching, following the links you cliked on to get to the current page you are on. Even if you go back there are still pointers to let you go forward in the list agian. The list doesn't know how long it will be or if you will go back to the middle of the list, click on a different link, and start a new part of the list.

A linked list might have to start from one end of the list to find an element in the middle instead of just skipping straight to the element you want like in arrays or vectors but it is much more dynamic and easier to add elements to. With a vector or array you would have to shift all the elements down one to add something to the begining of the list whereas with a linked list you simply change some pointers.




https://www.youtube.com/watch?v=o5wJkJJpKtM (How to Create a Linked List C++ Introduction to Linked Lists)
https://www.youtube.com/watch?v=_jQhALI4ujg (Linked Lists - Computerphile)
https://www.youtube.com/watch?v=njTh_OwMljA (Data Structures: Linked Lists)
https://www.youtube.com/watch?v=pBrz9HmjFOs (Data Structures: Introduction to Linked Lists)
http://www.cplusplus.com/reference/forward_list/forward_list/ (C++ forward_list references)
http://www.cplusplus.com/reference/list/list/ (C++ list references)
https://www.youtube.com/watch?v=KJWOm1bXUxM (C++ Tutorial 17 : Sequence Containers)
https://www.youtube.com/watch?v=k0pjD12bzP0 (What is a Doubly Linked List?)
