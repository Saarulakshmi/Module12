# # 📚 Stack using Linked List: Check and Display Whether the Stack is Full or Not

This Python program demonstrates how to check if a stack (using `LifoQueue` from the `queue` module) is full or not. It uses the `full()` method to determine the stack's status and then displays the appropriate message.

## 🎯 Aim

To write a Python program that:
- Creates a stack with a fixed size.
- Adds elements to the stack.
- Checks if the stack is full.
- Displays a message indicating whether the stack is full or not.

## 🧠 Algorithm

1. **Import the LifoQueue class**:
   - Import `LifoQueue` from the `queue` module to create the stack.

2. **Create a Stack**:
   - Instantiate a `LifoQueue` with a maximum size (e.g., 4).

3. **Add Elements to the Stack**:
   - Add elements (e.g., 'a', 'b', and 'c') to the stack using the `put()` method.

4. **Check if the Stack is Full**:
   - Use the `full()` method of `LifoQueue` to check if the stack has reached its maximum capacity.

5. **Display the Status**:
   - Print "Stack is full" if the stack is full.
   - Otherwise, print "Stack is not full".

## 📝 Program

```
from queue import LifoQueue

# Create stack with max size 4
stack = LifoQueue(maxsize=4)

# Push elements into stack
stack.put('a')
stack.put('b')
stack.put('c')

# Check if stack is full
if stack.full():
    print("Stack is full")
else:
    print("Stack is not full")

# Optional: show current size
print("Current stack size:", stack.qsize())

```

## Sample Input & Output:

<img width="582" height="176" alt="image" src="https://github.com/user-attachments/assets/fb1a1c1d-6e56-48a9-ad15-54d13e874ede" />


## Result

The program successfully checks whether the stack is full using LifoQueue.full() and displays the correct status.
