# Exp.No:3a
## STRING - FIND AND REPLACE

---

### AIM  
To write a Python function to accept a string, identify a word to be replaced, and replace it with a new word provided by the user.

---

### ALGORITHM

1. Begin the program.  
2. Input the original string `str1` and the word to be replaced `replace_str`.  
3. Ask the user to input the new replacement word `str2`.  
4. Use the `replace()` method in Python to replace all occurrences of `replace_str` in `str1` with `str2`.  
5. Store the modified string in `str3`.  
6. Display the original string (`str1`) and the modified string (`str3`).  
7. Terminate the program.

---

### PROGRAM

```
def replacestr(s,d):
    a=input()
    f=s.replace(d,a)
    print("The old string is {}\nthe new string is {}".format(s,f))
```

### OUTPUT
![Screenshot 2025-04-27 153159](https://github.com/user-attachments/assets/ad71ca68-fa7c-49d3-bb2b-a28df1e940df)
### RESULT
Thus the python program to identifing and replacing with new word has been implemented and executed successfully.
