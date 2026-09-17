# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program

```

# Stack implementation using list

stack = []

# Insert 3 elements into stack
for i in range(3):
    value = input("Enter value: ")
    stack.append(value)

# Display top element
if len(stack) > 0:
    print("Top element of the stack:", stack[-1])
else:
    print("Stack is empty")

```

## Output

<img width="372" height="228" alt="image" src="https://github.com/user-attachments/assets/67fdda9c-5be9-4e11-97c4-bcfe4413d825" />


## Result

The program successfully implements a stack and displays the top element using stack[-1].
