+++
title = 'Data Structure'
date = 2024-05-03T11:55:55+08:00
draft = true
+++

**String**
- _Definition:_ A sequence of characters representing text.
- _Example:_
```
    let myString = "Hello, JavaScript!";
```

**Array**
- Definition: A collection of elements, each accessed by an index.
- Example:
```
     let myArray = [1, 2, 3, 4, 5];
```

**Linked List**
- Definition: A linear data structure where each element is a node that contains a value and a pointer to the next node. 
- Example:
```
     class LinkedListNode {
         constructor(data) {
             this.data = data;
             this.next = null;
         }
     }

     let head = null; // Start with an empty list
```
**Stack**
- Defination: A Last-In-First-Out (LIFO) data structure.
- Example:
```
class Stack {
         constructor() {
             this.items = [];
         }
         push(item) { 
            this.items.push(item); 
         }
         pop() { 
            return this.items.pop(); 
         }
     }

     let myStack = new Stack();
     myStack.push(1);
     myStack.push(2);
```
    
**Queue**
- Definition: A First-In-First-Out (FIFO) data structure.
- Example:
```
class Queue {
         constructor() {
             this.items = [];
         }
         enqueue(item) { 
            this.items.push(item); 
        }
         dequeue() { 
            return this.items.shift(); 
        }
     }

     let myQueue = new Queue();
     myQueue.enqueue(1);
     myQueue.enqueue(2);
```
**Tree**
- Definition: A hierarchical data structure with a root node and child nodes.
- Example:
```
     class TreeNode {
         constructor(value) {
             this.value = value;
             this.left = this.right = null;
         }
     }

     let root = new TreeNode(1);
     root.left = new TreeNode(2);
     root.right = new TreeNode(3);
```

- [] heap
(Not directly supported in JavaScript, but can be emulated with priority queues or libraries)

**Hash Table**
- Definition: A data structure that stores key-value pairs using a hash function for fast lookups.
- Example:
```
    let myHashTable = {};
     myHashTable['key1'] = 'value1';
     console.log(myHashTable['key1'])
     out: value1
```
