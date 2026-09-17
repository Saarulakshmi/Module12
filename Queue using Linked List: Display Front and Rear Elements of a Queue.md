# 🔁 Queue using Linked List: Display Front and Rear Elements of a Queue

## 🎯 Aim

To write a Python program to:
- Insert elements into a queue.
- Display the element at the **front** of the queue.
- Display the element at the **rear** of the queue.

---

## 🧠 Algorithm

1. **Initialize Queue**:
   - Create an empty list called `queue`.

2. **Insert Elements**:
   - Use the `append()` method to add `'a'`, `'b'`, `'c'`, and `'d'` to the queue.

3. **Display Initial Queue**:
   - Print `"Initial Queue:"` followed by the current state of the queue.

4. **Identify Front and Rear**:
   - Set `front = queue[0]` for the front element.
   - Set `rear = queue[-1]` for the rear element.

5. **Print Results**:
   - Display the front and rear elements with appropriate messages.

---
## Program

```

# Queue implementation using list

queue = []

# Insert elements
queue.append('a')
queue.append('b')
queue.append('c')
queue.append('d')

# Display initial queue
print("Initial Queue:")
print(queue)

# Find front and rear elements
if len(queue) > 0:
    front = queue[0]
    rear = queue[-1]

    print("\nFront element of the queue:", front)
    print("Rear element of the queue:", rear)
else:
    print("Queue is empty")
```
## Output

<img width="487" height="263" alt="image" src="https://github.com/user-attachments/assets/4d0239d7-7bb9-4e49-83f2-2d1ca87459ec" />


## Result

The program successfully inserts elements into a queue and displays both the front and rear elements correctly.
