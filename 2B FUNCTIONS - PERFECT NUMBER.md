# Exp.No:2b  
## FUNCTIONS -  check if a number is a strong number using function.

### AIM  
To write a Python programto check if a number is a strong number using function.

---

### ALGORITHM

1.Start
2.Input an integer num from the user.
3.Set temp = num.
4.Initialize tot = 0 to store the sum of factorials of digits.
5.Repeat while temp > 0:
6.Extract the last digit: digit = temp % 10
7.Initialize fact = 1 to calculate factorial of the digit.
8.For i from 1 to digit, do:
  fact = fact * i
9.Add the factorial to the total: tot = tot + fact
10.Remove the last digit from temp: temp = temp // 10
   If tot == num, then:
11.Print "The number is a strong number"
12.Else:
13.Print "The number is not a strong number"
14.End
---

### PROGRAM
```
#Reg.No:
#Name:
#Add your Code Here
num=int(input())
temp=num
tot=0
while temp>0:
    digit=temp%10
    fact=1
    for i in range(1,digit+1):
        fact=fact*i
    tot=tot+fact
    temp//=10
if tot==num:
    print("The number is a strong number")
else:
    print("The number is not a strong number") 

```
### OUTPUT


### RESULT
Thus  a Python programto check if a number is a strong number using function is done and verified.
