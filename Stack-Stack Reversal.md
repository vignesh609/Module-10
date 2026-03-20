# # Stack-Stack Reversal Program 🔁

This Python program demonstrates how to reverse the values in a stack using basic stack operations like push and pop.

## 🎯 Aim

To write a Python program that reverses the values in a stack using standard stack operations.

## 📋 Algorithm

1. Create an empty stack.
2. Read an integer `n` from the user (number of elements to push).
3. Loop `n` times:
   - Read an integer from the user.
   - Push it onto the stack.
4. Create an empty list called `reverse`.
5. While the stack is not empty:
   - Pop the top element.
   - Append it to `reverse`.
6. Print the reversed list.


### Program:
```
def fun(r):
    de =deque([])
    n=int(input())
    for i in range(n):
        de.append(input())
    print("Stack before rotation",de)
    de.rotate(r)
    print("Stack after rotation",de)
```
## 🧪 Sample Input and Output
<img width="1171" height="303" alt="444742273-2962a068-4787-4ebe-a9e5-71d113539af5" src="https://github.com/user-attachments/assets/0961ce26-c829-4962-948a-335f180090cb" />

## Result
Thus the program is verified
