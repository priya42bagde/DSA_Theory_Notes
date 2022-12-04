# Faang_DSA_Theory_Notes
Udemy: https://ibm-learning.udemy.com/course/js-algorithms-and-data-structures-masterclass/learn/lecture/8344148#overview </br>
Youtube Channel: Aditya Verma for DP etc, Apni Kaksha in C++ DSA, take U forward by strivers, </br>
Sheet: Love Babbaer sheet(450) </br>
GFG: https://www.geeksforgeeks.org/must-do-coding-questions-for-companies-like-amazon-microsoft-adobe/ </br>
Learning: https://www.programiz.com/dsa </br>
LinkList types:Singular, Double and Circular </br>

Time Complexity: Relation between input size and running time(operations).
means how much time a code run(depend on number of execution) in worst, average and best cases which is based on the input length, it doesn't means how much time system taking to execute a code.


Bubble- adjacent comparision
Insertion - unsorted value insert in sorted
selection- find lowest n move left
merge- divide and conquer, divide in 2 half
Shell- based on insertion, divide n swap
Quik Sortinh-2 partition, pivot value
Heap sort- similar to selection sort
Bucket- distributes in nu,ber of buckets
Radix- Least to most significant digit


sorting, linkedlist, binary tress
dfs and bfs traversal of graph
linkedin flaten
striver sde sheet download

design pattern
responsive grid system
viewport
Tree shaking
atomic design pattern

https://amazon.jobs/en/landing_pages/software-development-topics
 

------
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
<b>Extract-Max/Min </b>: Extract-Max returns the node with maximum value after removing it from a Max Heap whereas Extract-Min returns the node with minimum after removing it from Min Heap. <br/>
<b>Heap Data Structure Applications </b>: Heap is used while implementing a priority queue. Dijkstra's Algorithm. Heap Sort <br/>

<b>A fibonacci heap</b> is a data structure that consists of a collection of trees which follow min heap or max heap property. min heap and max heap property in the Heap Data Structure article. These two properties are the characteristics of the trees present on a fibonacci heap. In a fibonacci heap, a node can have more than two children or no children at all. Also, it has more efficient heap operations than that supported by the binomial and binary heaps.

The fibonacci heap is called a fibonacci heap because the trees are constructed in a way such that a tree of order n has at least Fn+2 nodes in it, where Fn+2 is the (n + 2)th Fibonacci number. <br/>

<b>Properties of a Fibonacci Heap</b>: Important properties of a Fibonacci heap are:
It is a set of min heap-ordered trees. (i.e. The parent is always smaller than the children.)
A pointer is maintained at the minimum element node.
It consists of a set of marked nodes. (Decrease key operation)
The trees within a Fibonacci heap are unordered but rooted. <br/>

<b>Tree</b> : A tree is a nonlinear hierarchical data structure that consists of nodes connected by edges. <br/>
<b>Why Tree Data Structure?</b>
Other data structures such as arrays, linked list, stack, and queue are linear data structures that store data sequentially. In order to perform any operation in a linear data structure, the time complexity increases with the increase in the data size. But, it is not acceptable in today's computational world.

Different tree data structures allow quicker and easier access to the data as it is a non-linear data structure. <br/>

<b>Tree Terminologies</b> <br/>
<b>Node</b>:A node is an entity that contains a key or value and pointers to its child nodes.The last nodes of each path are called leaf nodes or external nodes that do not contain a link/pointer to child nodes. The node having at least a child node is called an internal node.

<b>Edge</b>: It is the link between any two nodes.

<b>Root </b>: It is the topmost node of a tree.

<b>Height of a Node </b>: The height of a node is the number of edges from the node to the deepest leaf (ie. the longest path from the node to a leaf node).

<b>Depth of a Node </b> : The depth of a node is the number of edges from the root to the node.

<b>Height of a Tree </b>: The height of a Tree is the height of the root node or the depth of the deepest node.

<b>Degree of a Node </b>: The degree of a node is the total number of branches of that node.

<b>Forest</b>: A collection of disjoint trees is called a forest. You can create a forest by cutting the root of a tree. <br/>

<b>Types of Tree</b>: 
Binary Tree,
Binary Search Tree,
AVL Tree,
B-Tree

<b>Tree Traversal</b>: In order to perform any operation on a tree, you need to reach to the specific node. The tree traversal algorithm helps in visiting a required node in the tree.


<b>Tree Applications</b>:
Binary Search Trees(BSTs) are used to quickly check whether an element is present in a set or not.
Heap is a kind of tree that is used for heap sort.
A modified version of a tree called Tries is used in modern routers to store routing information.
Most popular databases use B-Trees and T-Trees, which are variants of the tree structure we learned above to store their data
Compilers use a syntax tree to validate the syntax of every program you write.

<b>Tree Traversal - inorder, preorder and postorder<b>: Traversing a tree means visiting every node in the tree. You might, for instance, want to add all the values in the tree or find the largest one. For all these operations, you will need to visit each node of the tree. Linear data structures like arrays, stacks, queues, and linked list have only one way to read the data. But a hierarchical data structure like a tree can be traversed in different ways. <br/>
  
Inorder traversal: First, visit all the nodes in the left subtree, Then the root node, Visit all the nodes in the right subtree <br/>
Preorder traversal Visit root node, Visit all the nodes in the left subtre, Visit all the nodes in the right subtree <br/>
Postorder traversal : Visit all the nodes in the left subtree, Visit all the nodes in the right subtree, Visit the root node <br/>

<b> Binary Tree</b>: A binary tree is a tree data structure in which each parent node can have at most two children. Each node of a binary tree consists of three items: data item, address of left child and address of right child.
  
<b>Binary Tree Applications</b>: For easy and quick access to data, In router algorithms, To implement heap data structure and Syntax tree <br/>
  
<b> Types of Binary Tree</b>: <br/>
1. Full Binary Tree: A full Binary tree is a special type of binary tree in which every parent node/internal node has either two or no children. It is also known as a proper binary tree. <br/>
2. Perfect Binary Tree: A perfect binary tree is a type of binary tree in which every internal node has exactly two child nodes and all the leaf nodes are at the same level. <br/>
3. Complete Binary Tree : A complete binary tree is just like a full binary tree, but with two major differences are Every level must be completely filled, All the leaf elements must lean towards the left, The last leaf element might not have a right sibling i.e. a complete binary tree doesn't have to be a full binary tree. <br/>
4. Degenerate or Pathological Tree: A degenerate or pathological tree is the tree having a single child either left or right. <br/>
5. Skewed Binary Tree: A skewed binary tree is a pathological/degenerate tree in which the tree is either dominated by the left nodes or the right nodes. Thus, there are two types of skewed binary tree: left-skewed binary tree and right-skewed binary tree. <br/>
6. Balanced Binary Tree:  It is a type of binary tree in which the difference between the height of the left and the right subtree for each node is either 0 or 1. A balanced binary tree, also referred to as a height-balanced binary tree, is defined as a binary tree in which the height of the left and right subtree of any node differ by not more than 1.

To learn more about the height of a tree/node, visit Tree Data Structure.Following are the conditions for a height-balanced binary tree:

difference between the left and the right subtree for any node is not more than one
the left subtree is balanced
the right subtree is balanced <br/>
  
<b>Binary Search Tree(BST) </b>: Binary search tree is a data structure that quickly allows us to maintain a sorted list of numbers.

It is called a binary tree because each tree node has a maximum of two children.
It is called a search tree because it can be used to search for the presence of a number in O(log(n)) time. <br/>
The properties that separate a binary search tree from a regular binary tree is

All nodes of left subtree are less than the root node
All nodes of right subtree are more than the root node
Both subtrees of each node are also BSTs i.e. they have the above two properties <br/>
  
There are two basic operations that you can perform on a binary search tree: <br/>
Search Operation:The algorithm depends on the property of BST that if each left subtree has values below root and each right subtree has values above the root.
If the value is below the root, we can say for sure that the value is not in the right subtree; we need to only search in the left subtree and if the value is above the root, we can say for sure that the value is not in the left subtree; we need to only search in the right subtree. <br/>
  
Insert Operation : Inserting a value in the correct position is similar to searching because we try to maintain the rule that the left subtree is lesser than root and the right subtree is larger than root.We keep going to either right subtree or left subtree depending on the value and when we reach a point left or right subtree is null, we put the new node there. <br/>
  
Deletion Operation: There are three cases for deleting a node from a binary search tree.

Case I: In the first case, the node to be deleted is the leaf node. In such a case, simply delete the node from the tree. <br/>
Case II: In the second case, the node to be deleted lies has a single child node. In such a case follow the steps below:
Replace that node with its child node.
Remove the child node from its original position. <br/>
Case III: In the third case, the node to be deleted has two children. In such a case follow the steps below:
Get the inorder successor of that node.
Replace the node with the inorder successor.
Remove the inorder successor from its original position. <br/>
  
Binary Search Tree Applications <br/>
In multilevel indexing in the database
For dynamic sorting
For managing virtual memory areas in Unix kernel <br/>
  

  


  



