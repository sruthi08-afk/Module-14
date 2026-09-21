# Exp.No:38  
## Deque - DELETION

---

### AIM  
To write a Python program to delete elements at FRONT END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Create an empty deque.  
3. Define how many elements to input (e.g., 3 inputs as in the example).  
4. Loop through the range of input size:  
   - Read an integer from the user.  
   - Append the integer to the deque.  
5. Remove the front element of the deque using `popleft()`.  
6. Print the final deque after deletion.  

---

### PROGRAM  

```python
from collections import deque


d = deque()


d.append(input())
d.append(input())
d.append(input())


d.popleft()


print("The deque after deletion is :")
print(d)
```

### OUTPUT

<img width="760" height="251" alt="image" src="https://github.com/user-attachments/assets/417ce89a-7dff-43e3-b0a0-8c5e27f568d9" />




### RESULT
Thus the python program for to delete elements at FRONT END of deque using a collection built-in function has been implemented and executed successfully.
