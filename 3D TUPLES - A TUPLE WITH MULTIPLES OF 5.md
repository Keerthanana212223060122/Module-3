# Exp.No:3d  
## TUPLES - A TUPLE WITH MULTIPLES OF 5

---

### AIM  
To write a Python program to create a tuple containing all multiples of 5 up to a given number **N**.

---

### ALGORITHM

1. Begin the program.  
2. Accept an integer `N` from the user.  
3. Use a generator expression inside the `tuple()` function to create a tuple `multiples_of_5` with values starting from `5` up to `N - 1`, stepping by `5`.  
4. Return the tuple `multiples_of_5`.  
5. Print the resulting tuple.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No-212223060122
# Name-Keerthana S

n=int(input())
result=tuple(i for i in range(5,n,5))
print(result)
```

### OUTPUT
![image](https://github.com/user-attachments/assets/2acf552f-5c39-4e6f-9b27-36afcc734a1e)

### RESULT
Thus , a Python program to create a tuple containing all multiples of 5 up to a given number **N** are verified.
