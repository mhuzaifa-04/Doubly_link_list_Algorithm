# Doubly_link_list_Algorithm


A doubly linked list is a linear data structure where each node contains:
- Data field
- Pointer to the next node
- Pointer to the previous node

This implementation allows traversal in both forward and backward directions, making it more flexible than singly linked lists.

## Features

✅ Insert operations (beginning, end, specific position)  
✅ Delete operations (beginning, end, by value)  
✅ Bidirectional traversal (forward and backward)  
✅ Search functionality  
✅ Interactive menu-driven interface  
✅ Proper memory management  
✅ Error handling  

## Usage

After running the program, you'll see an interactive menu:

```
=== Doubly Linked List Menu ===
1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete from beginning
5. Delete from end
6. Delete by value
7. Display forward
8. Display backward
9. Search
10. Exit
Enter your choice:
```

Simply enter the number corresponding to your desired operation and follow the prompts.

## Operations

### 1. Insert at Beginning
Adds a new node at the start of the list.
- **Input:** Integer value
- **Time Complexity:** O(1)

### 2. Insert at End
Adds a new node at the end of the list.
- **Input:** Integer value
- **Time Complexity:** O(n)

### 3. Insert at Position
Inserts a new node at a specific position (1-indexed).
- **Input:** Integer value and position
- **Time Complexity:** O(n)

### 4. Delete from Beginning
Removes the first node from the list.
- **Time Complexity:** O(1)

### 5. Delete from End
Removes the last node from the list.
- **Time Complexity:** O(n)

### 6. Delete by Value
Removes the first occurrence of a specific value.
- **Input:** Integer value to delete
- **Time Complexity:** O(n)

### 7. Display Forward
Displays all elements from head to tail.
- **Time Complexity:** O(n)

### 8. Display Backward
Displays all elements from tail to head.
- **Time Complexity:** O(n)

### 9. Search
Searches for a value and returns its position.
- **Input:** Integer value to search
- **Time Complexity:** O(n)

### 10. Exit
Frees all memory and exits the program.

| Insert at Beginning | O(1) |
| Insert at End | O(n) |
| Insert at Position | O(n) |
| Delete from Beginning | O(1) |
| Delete from End | O(n) |
| Delete by Value | O(n) |
| Display Forward | O(n) |
| Display Backward | O(n) |
| Search | O(n) |

---------------

