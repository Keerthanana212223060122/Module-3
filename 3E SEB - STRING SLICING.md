# Exp.No:3e
## SEB - STRING SLICING

---

### AIM  
To write a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string.

---

### ALGORITHM

1. Begin the program.  
2. Accept a string as input.  
3. Take a slice of the input string from index **2** to **10** (Python uses 0-based indexing, so index 2 refers to the 3rd character, i.e., the 4th character in natural terms).  
4. Reverse the sliced substring.  
5. Extract every second character from the reversed substring using slicing (`[::2]`).  
6. Print the final processed string.  
7. Terminate the program.

---

### PROGRAM

```python
def slice(a):
    b=a[9:1:-2]
    print(f"The reversed string is '{b}'")
```

### OUTPUT
![image](https://github.com/user-attachments/assets/51cb930d-9d5c-4a51-8b60-4393128f50bb)

### RESULT
Thus a Python function that accepts a string and forms a new string by reversing the characters from the **4th position to the 10th position** with **alternate characters**, and then prints the new string was executed and implemented successfully.
