# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
x=int(input())
y=int(input())
d=lambda x,y:x if(x>y) else y
print("The greatest number is:",d(x,y))
```

### OUTPUT

![image](https://github.com/user-attachments/assets/d7de65cb-89d3-4f10-a271-46cfc8ae03da)


### RESULT

Thus a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function is done and executed.

