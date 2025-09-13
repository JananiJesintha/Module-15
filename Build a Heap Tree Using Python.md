# Ex. No: 15D - Build a Heap Tree Using Python

## AIM:
To write a Python program to build a heap tree using appropriate Python package and function.

---

## ALGORITHM:

1. **Start the program.**
2. Import the `heapq` module.
3. Define a function `heaptree(H)` that takes a list `H` as input.
4. Use `heapq.heapify(H)` to convert the list into a min-heap.
5. Print the created heap.
6. **End the program.**

---

## PROGRAM:

```
from binarytree import heap,build,Node 
def heaptree(L):
    x=L
    t=build(x)
    for i in t.values:
        print(i,"-->",end='')
    print("\nHeight : ",t.height)
    print("Is min heap? : ",t.is_min_heap)
    print("Is complete tree? : ",t.is_complete)
```

## OUTPUT

<img width="933" height="157" alt="image" src="https://github.com/user-attachments/assets/a9da2e4d-55e9-4495-ab6f-d72b48517b54" />

## RESULT

Thus, the python code is written and executed successfully.
