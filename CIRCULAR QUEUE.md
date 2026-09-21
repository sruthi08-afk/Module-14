# Exp No: 36  
## Circular Queue 
---

### AIM  
To write a Python program with a function to insert float values into a Circular Queue.

---

### ALGORITHM

1. Start  
2. Check if the Circular Queue is full  
   - If `size == max_size`, print `"Queue is full"` and exit the function  
3. If the queue is not full:  
   - Read the element to be inserted  
   - Convert it to float  
   - Insert the element at the `tail` position  
   - Update tail using: `tail = (tail + 1) % max_size` (circular increment)  
   - Increment `size` by 1  
4. End

---

### PROGRAM

```python
# Queue simply works in FIFO
class Queue:
    def __init__(self, size):
        self.items = [0] * size
        self.max = size
        self.head, self.tail, self.size = 0, 0, 0

    def enqueue(self,item):
        if self.is_list_full():
            print("Queue is full")
            return
        self.items[self.tail]=item
        self.tail=(self.tail+1) % self.max
        self.size+=1
    def dequeue(self):
        item=self.items[self.head]
        self.head=(self.head+1) % self.max
        self.size-=1
        return item
    def is_list_full(self):
        if self.size==self.max:
            return True
        return False
        

    def is_empty(self):
        if self.size==0:
            return True
        return False
        

size=int(input())
queue=Queue(size)
a=float(input())
b=float(input())
c=float(input())
queue.enqueue(a)
queue.enqueue(b)
queue.enqueue(c)
print(queue.items)


```

### OUTPUT
<img width="652" height="344" alt="image" src="https://github.com/user-attachments/assets/3b162ecd-1b63-4b7f-afa8-eb3560021e19" />

### RESULT 
Thus the python programwith a function to insert float values into a Circular Queue has been implemented and executed successfully.




### RESULT
