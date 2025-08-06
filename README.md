# Python List Operations

A step-by-step demonstration of essential Python list operations.

## Code Overview

This script demonstrates 7 fundamental list operations:

1. **Create** an empty list
2. **Append** elements to the list
3. **Insert** element at specific position
4. **Extend** list with another list
5. **Remove** last element
6. **Sort** list in ascending order
7. **Find** index of specific value

## How to Run

```bash
python list_operations.py
```

## Expected Output

```
Step 1 - Empty list: []
Step 2 - After appending 10, 20, 30, 40: [10, 20, 30, 40]
Step 3 - After inserting 15 at position 1: [10, 15, 20, 30, 40]
Step 4 - After extending with [50, 60, 70]: [10, 15, 20, 30, 40, 50, 60, 70]
Step 5 - After removing last element: [10, 15, 20, 30, 40, 50, 60]
Step 6 - After sorting in ascending order: [10, 15, 20, 30, 40, 50, 60]
Step 7 - Index of value 30: 3
```

## Key Methods

- `append(item)` - Add single item to end
- `insert(index, item)` - Add item at specific position
- `extend(list)` - Add multiple items from another list
- `pop()` - Remove and return last item
- `sort()` - Sort list in place
- `index(item)` - Find position of item

## Requirements

- Python 3.x
