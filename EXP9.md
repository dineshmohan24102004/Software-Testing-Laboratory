# Ex.No: 9  Pytest program for Sum of Digits 

### DATE: 1-5-25                                                                           
### REGISTER NUMBER : 212222040039
### AIM: 
To write a python program for sum of digits and validate the code using Pytest. 
### Algorithm:

1. Write the python program for sum of digits of a number. 
2. Make sure that function name should be “def test_*():” and the line to be tested 
should have assert keyword at the beginning. 
3. Write some test cases for to be tested and save it as “test_sumofdig.py”. 
4. Open command prompt and change the directory to where pytest is installed
5. Executethe program as “pytest test_sumofdig.py”. 
6. Stop the program.

### Program:
```
def sumOfDigits(n): 
sum = 0 
while (n != 0): 
sum = sum + int(n % 10) 
n = int(n/10) 
return sum 
def test_1(): 
assert sumOfDigits(123) == 6 
def test_2(): 
assert sumOfDigits(256) == 2
```
### Output:
![Screenshot 2025-05-10 231256](https://github.com/user-attachments/assets/86c28954-422d-4b3e-aaee-fe066b9a7688)


### Result:
Thus, the python program for sum of digits is tested using pytest and executed and output is verified successfully.

