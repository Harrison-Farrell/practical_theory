---
layout: posts
title:  "cpu cache & data structures"
---
The cpu cache is the a small, ultra-fast memory component built directly into or
very near the processor core. The primary purpose of the cpu cache is to maximize
processing speed by reducing the time it takes the cpu to access data from the slow
main memory (RAM).

The cpu cache is often separated into 3 levels L1, L2, L3. Where L1 is the fastest
and smallest of the levels. As depicted in the image below.

![image](./assets/cpu_cache/cpu-architecture.png)

What is a data structure and why use one?  

Well a data structure is a 'specialized' format for organizing, managing, and 
storing data in a computer so that it can be accessed and modified efficiently. 
They're often called "containers" because they hold collections of data.

Data structures provide a meaningful way to arrange data, making it easier to
work with. Data structures are often supported by a complementary set of algorithms
used to access, insert, or remove information from the structure.

The selection of the structure type will influence the type of algorithms used to
support it. This leads to time and space trade-offs.

## Common Data Structures

| Data Structure | Description | Use Cases | Time Complexity (Avg) |
|---|---|---|---|
| Array | Contiguous collection of elements accessed by index | Random access, simple lists | O(1) lookup, O(n) insert/delete |
| Linked List | Sequential collection with nodes pointing to next element | Dynamic sizing, frequent insertions | O(n) lookup, O(1) insert/delete |
| Stack | LIFO (Last In First Out) collection | Undo/redo, function calls, parsing | O(1) push/pop |
| Queue | FIFO (First In First Out) collection | Scheduling, breadth-first search | O(1) enqueue/dequeue |
| Hash Table | Key-value pairs with hash-based lookup | Caching, indexing, fast lookups | O(1) average lookup |
| Binary Search Tree | Hierarchical tree with sorted property | Sorted data, range queries | O(log n) search |
| Heap | Complete tree prioritizing min/max element | Priority queues, sorting | O(log n) insert/delete |
| Graph | Nodes connected by edges | Networks, social connections | Varies by implementation |
| Trie | Tree for string prefix matching | Autocomplete, spell checking | O(m) where m is string length |
| Set | Unordered collection of unique elements | Membership testing, deduplication | O(1) average add/remove |
