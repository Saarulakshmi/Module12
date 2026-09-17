# 🌀 Queue using Linked List - Insert, Display, and Delete

## 🎯 Aim

To write a Python program that:
- Inserts elements into a queue.
- Displays all inserted elements.
- Deletes the first element.
- Displays the updated queue after deletion.

---

## 🧠 Algorithm

1. **Create a Queue**:
   - Initialize an empty list named `queue`.

2. **Insert Elements**:
   - Use the `append()` method to insert elements `'a'`, `'b'`, and `'c'` into the queue.

3. **Display Initial Queue**:
   - Print the message `"Queue after elements are inserted:"` followed by the queue contents.

4. **Delete First Element**:
   - Use `pop(0)` to remove the first inserted element (FIFO - First In First Out).
   - Print the message `"Deleting the first element inserted:"` and the element removed.

5. **Display Updated Queue**:
   - Print the message `"Queue after the first element is deleted:"` followed by the updated queue contents.

---

## Program

```

# Queue implementation using list (Linked List concept simulation)

queue = []

# Insert elements
queue.append('a')
queue.append('b')
queue.append('c')

# Display initial queue
print("Queue after elements are inserted:")
print(queue)

# Delete first element (FIFO)
deleted_element = queue.pop(0)
print("\nDeleting the first element inserted:")
print(deleted_element)

# Display updated queue
print("\nQueue after the first element is deleted:")
print(queue)

```

## Output

<img width="576" height="332" alt="image" src="https://github.com/user-attachments/assets/1729379f-88ef-4818-9d0c-880e0532e191" />



## Result:

The program is excuted successfully and the output is verified
