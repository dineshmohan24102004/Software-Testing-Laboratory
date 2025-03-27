![image](https://github.com/user-attachments/assets/1de47229-9b6e-4c92-93bd-0108328b3753)# Ex.No: 2   Matrix Multiplication 

### DATE: 27-03-2025                                                                      
### REGISTER NUMBER : 212222040039

### AIM: 
Write a python program for matrix multiplication and inspect for failures.
 
### Algorithm:

Algorithm:
1. Start the program.
2. Create empty list formatrix1, matrix2 and result.
3. Get the rows and columns count from the user.
4. Get the values of two matrix.
5. Perform matrix multiplication and store the answer in result.
6. Stop the program.
### Program:
```
r1, c1 = input("Enter row and column count in matrix 1: ").split()
r2, c2 = input("Enter row and column count in matrix 2: ").split()

matrix1 = []
matrix2 = []
result = []

if r1.isnumeric() and c1.isnumeric() and r2.isnumeric() and c2.isnumeric():
    r1 = int(r1)
    c1 = int(c1)
    r2 = int(r2)
    c2 = int(c2)

    if c1 != r2:
        print("Matrix multiplication not possible")
    elif max(r1, c1, r2, c2) > 20 or min(r1, c1, r2, c2) == 0:
        print("Matrix multiplication not possible")
    else:
        print("Enter elements for Matrix 1 (space-separated row-wise):")
        for i in range(r1):
            while True:
                row = input().split()
                if len(row) == c1 and all(num.lstrip('-').isdigit() for num in row):
                    matrix1.append([int(num) for num in row])
                    break
                else:
                    print(f"Invalid input. Enter exactly {c1} space-separated numbers.")

        print("Enter elements for Matrix 2 (space-separated row-wise):")
        for i in range(r2):
            while True:
                row = input().split()
                if len(row) == c2 and all(num.lstrip('-').isdigit() for num in row):
                    matrix2.append([int(num) for num in row])
                    break
                else:
                    print(f"Invalid input. Enter exactly {c2} space-separated numbers.")

        # Matrix multiplication
        result = [[0 for _ in range(c2)] for _ in range(r1)]

        for i in range(r1):
            for j in range(c2):
                for k in range(c1):  # c1 is correct for multiplication
                    result[i][j] += matrix1[i][k] * matrix2[k][j]

        # Displaying result
        print("Resultant Matrix:")
        for row in result:
            print(" ".join(map(str, row)))

else:
    print("Enter a valid number")



```










### Output:
![Screenshot 2025-03-27 082829](https://github.com/user-attachments/assets/15373933-0b91-4e68-b847-5257357b1e51)






### Result:
Thus, the python program for matrix multiplication is implemented and the causes for its failure is introspected successfully.

