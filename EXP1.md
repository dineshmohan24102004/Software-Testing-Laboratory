# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:  13-03-2025                                                                        
### REGISTER NUMBER : 212222040039

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:
### do…while: 
```
def display(): 
start=input("Enter a positive value for START: ") 
end=input("Enter a positive value for END: ") 
if start.isnumeric() and end.isnumeric(): 
while True: 
start=int(start) 
end=int(end) 
print(start,end=‘ ‘) 
if start<end: 
start+=1 
else: 
break 
else: 
print("Enter a valid positive number.") display()
```

### while…do 
```
start=input("Enter a positive value for START: ") end=input("Enter 
a positive value for END: ") 
if 
start.isnumeric() 
start=int(start) 
end=int(end) 
while start<end: 
print(start) 
start+=1 
else: 
and end.isnumeric(): 
print("Enter a valid positive number.")
```

### switch 
```
def switch(): 
switcher={ 
0:"even", 
1:"odd" 
} 
n=input('Enter a value for N: ') try: 
n=int(n) 
print(switcher[n%2]) 
except ValueError: 
print("Enter a valid number.") 
switch()
```

###  if else 
```
def compare(): 
a=input("Enter a value for A: ") 
b=input("Enter a value for B: ") 
try: 
a=int(a) 
b=int(b) 
if a>b: 
print("A is greater than") 
elif a<b: 
print("B is greater than") 
else: 
print("A is equal to B") 
except ValueError: 
print(“Enter a valid number.”)
```

###  for
```
def iterate(): 
string=input("Enter a string: ") for 
i in string: 
print(ord(i),end=" ") 
iterate()

```












### Output:
![Screenshot 2025-03-13 082735](https://github.com/user-attachments/assets/1011ee30-5e67-4229-933a-80868d12ef99)

![Screenshot 2025-03-13 083525](https://github.com/user-attachments/assets/052e2f4e-1aa8-4393-922e-a8fdd1a4c8e0)
![Screenshot 2025-03-13 083924](https://github.com/user-attachments/assets/38b49e91-5271-4dbf-875a-69329829884e)



![Screenshot 2025-03-13 084249](https://github.com/user-attachments/assets/2da1225c-d418-48a9-8b3f-0bbd21f95399)
![Screenshot 2025-03-13 084643](https://github.com/user-attachments/assets/6e380c98-c172-4683-b89e-88a4de62dee6)







### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.


