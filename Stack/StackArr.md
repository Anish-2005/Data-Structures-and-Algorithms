# Stack (Array-based)

A **stack** is a linear data structure that follows the **LIFO (Last In, First Out)** principle. In an array-based implementation of a stack, a fixed-size array is used to store the stack elements, and a variable (`top`) keeps track of the index of the topmost element.

## Key Characteristics:
1. Operates on the LIFO principle.
2. Uses a fixed-size array for storage.
3. Requires a `top` pointer or index to track the topmost element.

## Stack Operations:
1. **Push**: Add an element to the top of the stack.
2. **Pop**: Remove and return the top element of the stack.
3. **Peek (or Top)**: Retrieve the value of the top element without removing it.
4. **IsEmpty**: Check if the stack is empty.
5. **IsFull**: Check if the stack is full.

## Advantages:
1. Simple and easy to implement.
2. Accessing elements is fast due to the direct index-based access.

## Disadvantages:
1. Fixed size limits the number of elements that can be stored.
2. Inefficient memory usage if the array is not fully utilized.
3. Requires resizing if the stack grows beyond the array's capacity.

## Time and Space Complexity Table for Stack Using Array:

| Operation   | Time Complexity | Space Complexity |
|-------------|-----------------|------------------|
| **Push**    | O(1)            | O(1)             |
| **Pop**     | O(1)            | O(1)             |
| **Peek**    | O(1)            | O(1)             |
| **IsEmpty** | O(1)            | O(1)             |
| **IsFull**  | O(1)            | O(1)             |

### Notes:
1. All operations have O(1) time complexity as they involve direct index-based operations.
2. Space complexity is O(n), where `n` is the maximum size of the stack array.
3. The stack's size is limited to the fixed array size (`MAX`).
