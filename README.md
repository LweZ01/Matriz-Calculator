Inside the .zip you'll find the code, the executable, and a User Manual on Spanish but i'm adding the translation here.

**USER MANUAL - MATRIX CALCULATOR V2.0**

## EXECUTION INSTRUCTIONS
Simply double-click the executable file.

## USAGE INSTRUCTIONS
When running the program, the following menu will appear:

`=== MATRIX CALCULATOR V2.0 ===`
`1. Matrix Addition`
`2. Matrix Subtraction`
`3. Matrix Multiplication`
`4. Exit Program`
`Select an option:`

### Operation 1: MATRIX ADDITION

**Required Condition:** Matrices must have the same dimensions (same number of rows and columns).

**Steps:**
1. Select option 1
2. Enter dimensions of the first matrix (rows and columns)
3. Enter all elements of the first matrix
4. Enter dimensions of the second matrix (rows and columns)
5. Enter all elements of the second matrix
6. The program will display both matrices and the result

**Example:**
```
Matrix 1: 2x2
[    1    2 ]
[    3    4 ]

Matrix 2: 2x2
[    5    6 ]
[    7    8 ]

Addition Result:
[    6    8 ]
[   10   12 ]
```

### Operation 2: MATRIX SUBTRACTION

**Required Condition:** Matrices must have the same dimensions.

**Steps:** Identical to addition, but the result will be Matrix1 - Matrix2.

**Example:**
```
Matrix 1: 2x2
[    5    6 ]
[    7    8 ]

Matrix 2: 2x2
[    1    2 ]
[    3    4 ]

Subtraction Result:
[    4    4 ]
[    4    4 ]
```

### Operation 3: MATRIX MULTIPLICATION

**Required Condition:** The number of columns of the first matrix must equal the number of rows of the second matrix.

**Steps:**
1. Select option 3
2. Enter dimensions of the first matrix (rows and columns)
3. Enter elements of the first matrix
4. Enter dimensions of the second matrix (rows and columns)
5. Enter elements of the second matrix
6. View the result

**Example:**
```
Matrix 1: 2x3
[    1    2    3 ]
[    4    5    6 ]

Matrix 2: 3x2
[    7    8 ]
[    9   10 ]
[   11   12 ]

Multiplication Result:
[   58   64 ]
[  139  154 ]
```

## VERSION 2.0 FEATURES

### Dynamic Memory Management
- **Automatic Allocation:** The program dynamically allocates memory based on entered dimensions
- **Automatic Release:** All memory is properly released after each operation
- **Error Detection:** The program detects and handles memory allocation errors

### Matrix Size
- **No Fixed Limit:** Matrices can be any size (limited only by available system memory)
- **Minimum:** 1x1 element
- **Maximum:** Dependent on available RAM
