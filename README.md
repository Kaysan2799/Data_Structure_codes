# Data Structures and Algorithms in C++

This repository contains various implementations of fundamental data structures and algorithms in C++. Each program focuses on a specific concept or technique, making it a valuable resource for learning and reference.

## Programs

1. **Bubble_sort.cpp**
   - Implements the Bubble Sort algorithm, which repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The process is repeated until the list is sorted.

2. **Insertion_sort.cpp**
   - Implements the Insertion Sort algorithm, which builds the final sorted array one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.

3. **Linked_list_insertion.cpp**
   - Demonstrates the insertion operations in a singly linked list, including inserting a new node at the beginning, middle, or end of the list.

4. **Linked_list_deletion.cpp**
   - Demonstrates the deletion operations in a singly linked list, including deleting a node from the beginning, middle, or end of the list.

5. **Linked_list_traversal.cpp**
   - Shows how to traverse a singly linked list and print the value of each node. This is fundamental for understanding how linked lists work and for implementing more complex operations.

6. **Doubly_linked_list.cpp**
   - Implements a doubly linked list, where each node contains a reference to the next and previous node. This allows traversal in both directions and more efficient deletion operations.

7. **Stack_array.cpp**
   - Demonstrates the implementation of a stack data structure using an array. It includes basic stack operations such as push, pop, and peek.

8. **Stack_linklist.cpp**
   - Demonstrates the implementation of a stack data structure using a linked list. This approach can be more flexible than using an array, especially for dynamic data.

9. **Parenthesis_matching.cpp**
   - Implements an algorithm to check for balanced parentheses in an expression. This is a common problem in compilers and interpreters to ensure the correct nesting of parentheses, brackets, and braces.

## Getting Started

### Prerequisites

- C++ compiler (e.g., GCC)

### Compilation

To compile any of the programs, use the following command:

```sh
g++ -o output_program_name program_name.cpp
```

### For example, to compile Bubble_sort.cpp, use:
```sh
g++ -o bubble_sort Bubble_sort.cpp
```

## Running the Program
To run the compiled program, use the following command:
```sh
./output_program_name
```

### For example, to run the bubble_sort program, use:
```sh
./bubble_sort
```

## Authors
Abdul Malik

## License
This project is licensed under the MIT License.

Feel free to adjust the author section and any other details as needed.
