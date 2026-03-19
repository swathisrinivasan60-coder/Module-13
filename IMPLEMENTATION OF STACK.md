# Exp.No:31  
## IMPLEMENTATION OF STACK

---

### AIM  
To write a Python program to implement a stack using a list and its built-in methods (`append()`, `pop()`).

---

### ALGORITHM

1. **Start the program.**
2. **Define a class `st`** with the following methods:
   - `push(self, num)`: Adds the number `num` to the stack.
   - `pop(self)`: Removes and returns the top element from the stack.
3. **Create a stack object `s`** using the class `st`.
4. **Input the stack size**: Take an integer input `size` to define the size of the stack.
5. **Loop through numbers from 1 to size**: Add only the odd numbers to the stack using the `push()` method.
6. **Display the elements** in the stack after the loop completes.
7. **Call `pop()`** to remove the top element from the stack and display the popped element.
8. **Display the stack again** to show the remaining elements.
9. **End the program.**

---

### PROGRAM

```
stack = []
stack.append(input())
stack.append(input())
stack.append(input())
print("Stack before elements are popped")
print(stack)
stack.pop()
stack.pop()
stack.pop()
print("\nStack after elements are popped:")
print(stack)

```
### OUTPUT
<img width="758" height="221" alt="image" src="https://github.com/user-attachments/assets/c5ecbfda-c222-4400-8042-cea218f9a5ab" />

### RESULT
Successfully implemented a stack using Python list. Items were added using append() and removed using pop(), demonstrating LIFO (Last In First Out) behavior of stack.
