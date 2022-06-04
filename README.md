# Faang_DSA_My_Notes
Udemy: https://ibm-learning.udemy.com/course/js-algorithms-and-data-structures-masterclass/learn/lecture/8344148#overview </br>
Youtube Channel: Aditya Verma for DP etc, Apni Kaksha in C++ DSA, take U forward by strivers, </br>
Sheet: Love Babbaer sheet(450) </br>
GFG: https://www.geeksforgeeks.org/must-do-coding-questions-for-companies-like-amazon-microsoft-adobe/ </br>
Learning: https://www.programiz.com/dsa </br>
LinkList types:Singular, Double and Circular </br>

Array -> String -> LinkedList -> Stack & Queue -> Recursion -> DP -> Trees -> Graph -> Heap -> Trie </br>

<b>Algorithm</b>: An algorithm is a set of well-defined instructions to solve a particular problem. It takes a set of input and produces a desired output. For example,An algorithm to add two numbers: Take two number inputs, Add numbers using the + operator, Display the result. Informally, an algorithm is nothing but a mention of steps to solve a problem.  Data structures are used to hold data while algorithms are used to solve the problem using that data.</br>

<b>Data Structures</b>: Data structure is a storage that is used to store and organize data. It is a way of arranging data on a computer so that it can be accessed and updated efficiently. Types of Data Structure: Linear data structure and Non-linear data structure</br>

<b>Linear data structures</b>: In linear data structures, the elements are arranged in sequence one after the other. Since elements are arranged in particular order, they are easy to implement. However, when the complexity of the program increases, the linear data structures might not be the best choice because of operational complexities. Popular linear data structures are: </br>
1. Array Data Structure: In an array, elements in memory are arranged in continuous memory. All the elements of an array are of the same type. </br>
2. Stack Data Structure: In stack data structure, elements are stored in the LIFO principle. That is, the last element stored in a stack will be removed first. It works just like a pile of plates where the last plate kept on the pile will be removed first. In a stack, operations can be perform only from one end (top here). Putting an item on top of the stack is called push and removing an item is called pop.</br> 

Basic Operations of Stack:- Push: Add an element to the top of a stack</br>
Pop: Remove an element from the top of a stack</br>
IsEmpty: Check if the stack is empty</br>
IsFull: Check if the stack is full</br>
Peek: Get the value of the top element without removing it</br>

Working of Stack Data Structure:  The operations work as follows:
A pointer called TOP is used to keep track of the top element in the stack. </br>
When initializing the stack, we set its value to -1 so that we can check if the stack is empty by comparing TOP == -1. </br>
On pushing an element, we increase the value of TOP and place the new element in the position pointed to by TOP. </br>
On popping an element, we return the element pointed to by TOP and reduce its value. </br>
Before pushing, we check if the stack is already full </br>
Before popping, we check if the stack is already empty </br>

Stack Time Complexity: For the array-based implementation of a stack, the push and pop operations take constant time, i.e. O(1). </br>
Application of Stack: Reverse of a word</br>

3. Queue Data Structure: Unlike stack, the queue data structure works in the FIFO principle where first element stored in the queue will be removed first. It works just like a queue of people in the ticket counter where first person on the queue will get the ticket first. In a queue, addition and removal are performed from separate ends.Putting items in the queue is called enqueue, and removing items from the queue is called dequeue.</br>

Basic Operations of Queue: A queue is an object (an abstract data structure - ADT) that allows the following operations:
Enqueue: Add an element to the end of the queue <br/>
Dequeue: Remove an element from the front of the queue <br/>
IsEmpty: Check if the queue is empty <br/>
IsFull: Check if the queue is full <br/>
Peek: Get the value of the front of the queue without removing it <br/>

Limitations of Queue: As you can see in the image below, after a bit of enqueuing and dequeuing, the size of the queue has been reduced. <br/>

Applications of Queue: CPU scheduling, Disk Scheduling, When data is transferred asynchronously between two processes.The queue is used for synchronization. For example: IO Buffers, pipes, file IO, etc. Handling of interrupts in real-time systems. Call Center phone systems use Queues to hold people calling them in order. <br/>

There are four different types of queues:
Simple Queue
Circular Queue
Priority Queue
Double Ended Queue

4. Linked List Data Structure: In linked list data structure, data elements are connected through a series of nodes. And, each node contains the data items and address to the next node. </br>

<b>Non linear data structures </b>: Unlike linear data structures, elements in non-linear data structures are not in any sequence. Instead they are arranged in a hierarchical manner where one element will be connected to one or more elements. Non-linear data structures are further divided into graph and tree based data structures. </br>
1. Graph Data Structure: In graph data structure, each node is called vertex and each vertex is connected to other vertices through edges. </br>
2. Trees Data Structure: Similar to a graph, a tree is also a collection of vertices and edges. However, in tree data structure, there can only be one edge between two vertices. </br>

<b>Asymptotic Analysis</b>: The efficiency is measured with the help of asymptotic notations. The efficiency of an algorithm depends on the amount of time, storage and other resources required to execute the algorithm. Asymptotic notations are the mathematical notations used to describe the running time of an algorithm. There are mainly three asymptotic notations: Big-O notation, Omega notation, Theta notation. </b>
<b>Big-O Notation (O-notation)</b>: Big-O notation represents the upper bound of the running time of an algorithm. Thus, it gives the worst-case complexity of an algorithm. </b>
<b>Omega Notation (Ω-notation)</b>: Omega notation represents the lower bound of the running time of an algorithm. Thus, it provides the best case complexity of an algorithm. </b>
<b>Theta Notation (Θ-notation)</b>: Theta notation encloses the function from above and below. Since it represents the upper and the lower bound of the running time of an algorithm, it is used for analyzing the average-case complexity of an algorithm. </br>

<b>The master theorem</b> is used in calculating the time complexity of recurrence relations (divide and conquer algorithms) in a simple and quick way. </br>
<b>Divide and conquer algorithm</b> is a strategy of solving a large problem by breaking the problem into smaller sub-problems, solving the sub-problems, and
combining them to get the desired output. To use the divide and conquer algorithm, recursion is used. </br>

<b>How Divide and Conquer Algorithms Work?</b> Here are the steps involved: </br>
Divide: Divide the given problem into sub-problems using recursion. </br>
Conquer: Solve the smaller sub-problems recursively. If the subproblem is small enough, then solve it directly. </br>
Combine: Combine the solutions of the sub-problems that are part of the recursive process to solve the actual problem. </br>

<b>Advantages of Divide and Conquer Algorithm </b>: The complexity for the multiplication of two matrices using the naive method is O(n3), whereas using the divide and conquer approach (i.e. Strassen's matrix multiplication) is O(n2.8074). This approach also simplifies other problems, such as the Tower of Hanoi. This approach is suitable for multiprocessing systems. It makes efficient use of memory caches.  </br>

<b>Divide and Conquer Applications</b>:
Binary Search,
Merge Sort,
Quick Sort,
Strassen's Matrix multiplication,
Karatsuba Algorithm </br>

<b>Linked list</b> : It is a linear data structure that includes a series of connected nodes. Here, each node stores the data and the address of the next node. You have to start somewhere, so we give the address of the first node a special name called HEAD. Also, the last node in the linked list can be identified because its next portion points to NULL.The power of a linked list comes from the ability to break the chain and rejoin it. Doing something similar in an array would have required shifting the positions of all the subsequent elements.<br/>
Linked lists can be of multiple types: singly, doubly, and circular linked list.  <br/>
Linked List Applications:
Dynamic memory allocation,
Implemented in stack and queue,
In undo functionality of softwares,
Hash tables, Graphs <br/>

Here's a list of basic linked list operations that we will cover in this article. <br/>
Traversal - access each element of the linked list
Insertion - adds a new element to the linked list
Deletion - removes the existing elements
Search - find a node in the linked list
Sort - sort the nodes of the linked list <br/>

There are three common types of Linked List.

Singly Linked List : It is the most common. Each node has data and a pointer to the next node. <br/>
Doubly Linked List : We add a pointer to the previous node in a doubly-linked list. Thus, we can go in either direction: forward or backward.<br/>
Circular Linked List : A circular linked list is a variation of a linked list in which the last element is linked to the first element. This forms a circular loop. A circular linked list can be either singly linked or doubly linked. <br/>
-->for singly linked list, next pointer of last item points to the first item
-->In the doubly linked list, prev pointer of the first item points to the last item as well. <br/>

<b>Hash Table</b>: The Hash table data structure stores elements in key-value pairs where
Key- unique integer that is used for indexing the values and 
Value - data that are associated with keys. <br/>
<b> Hashing </b>:In a hash table, a new index is processed using the keys. And, the element corresponding to that key is stored in the index. This process is called hashing. <br/>

<b>Hash Collision</b>: When the hash function generates the same index for multiple keys, there will be a conflict (what value to be stored in that index). This is called a hash collision. We can resolve the hash collision using one of the following techniques.
1. Collision resolution by chaining
2. Open Addressing: Linear/Quadratic Probing and Double Hashing <br/>

<b>Heap data structure</b> is a complete binary tree that satisfies the heap property, where any given node is
--always greater than its child node/s and the key of the root node is the largest among all other nodes. This property is also called max heap property.
--always smaller than the child node/s and the key of the root node is the smallest among all other nodes. This property is also called min heap property.
This type of data structure is also called a binary heap.
<b>Heapify</b>: Heapify is the process of creating a heap data structure from a binary tree. It is used to create a Min-Heap or a Max-Heap. <br/>
<b>Peek (Find max/min)</b>: Peek operation returns the maximum element from Max Heap or minimum element from Min Heap without deleting the node. <br/>
<b>Extract-Max/Min </b>: Extract-Max returns the node with maximum value after removing it from a Max Heap whereas Extract-Min returns the node with minimum after removing it from Min Heap.
<b>Heap Data Structure Applications </b>
Heap is used while implementing a priority queue. Dijkstra's Algorithm. Heap Sort <br/>

