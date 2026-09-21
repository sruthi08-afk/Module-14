# Exp.No:39  
## DEQUE - INSERTION

---

### AIM  
To write a Python program to insert elements at REAR END of deque using a collection built-in function.

---

### ALGORITHM  

1. Import the `deque` class from the `collections` module.  
2. Initialize an empty deque.  
3. Start an infinite loop using `while True`.  
4. In each iteration, take input from the user.  
5. If the input is an empty string, break the loop.  
6. If the input is not empty, convert it to an integer and append it to the deque.  
7. After the loop ends, append the values `14` and `15` to the deque.  
8. Print the message `"The deque after appending at right is :"`.  
9. Print the contents of the deque.  

---

### PROGRAM  

```python
from collections import deque
a=int(input())
b=int(input())
c=int(input())
de=deque([a,b,c])
de.appendleft(14)
de.appendleft(15)
print(f"The deque after appending is :\n{de}")

```

### OUTPUT
<img width="762" height="298" alt="image" src="https://github.com/user-attachments/assets/928c4d31-f6d3-4b43-b823-3af1aa0cb422" />


### RESULT
Thus the python program for to insert elements at REAR END of deque using a collection built-in function has been implemented and executed successfully.
