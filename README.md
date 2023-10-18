# 2D-Array
A two-dimensional array in C++ is the simplest form of a multi-dimensional array. It can be visualized as an array of arrays. A two-dimensional array is also called a matrix. It can be of any type like integer, character, float, etc. depending on the initialization.  



# **AIM**

Multidimensional Array 

## **THEORY**

A multi-dimensional array can be termed as an array of arrays that stores homogeneous data in tabular form. This article covers Multidimensional Arrays in C++ with working examples. It also covers 2-dimentional and 3-dimentional array.

![Screenshot 2023-10-18 at 8 10 13 PM](https://github.com/sanskkriti/2D-Array/assets/140137289/8fa72e00-0dcb-415c-915e-6b1745afaf95)


**Two-Dimensional Array**

The most basic type of multidimensional array is a two-dimensional array. For ease of understanding, we can think of a two-dimensional array as an array of one-dimensional arrays.

The simplest way to declare a 2-D array of sizes a and b is as follows:

data_type arr_name[a][b];

The type of data that will be stored is indicated here by the variable data type.

A two-dimensional integer array, say, “a,” of size 7,10, can be declared as follows:

int x[7][10]; Two-dimensional array elements are often identified by the notation a[i] [j], where i denote the row number, and ‘j’ denotes the column number

Representation of 2-D Array
Row and column indices are used to access elements in two-dimensional arrays.

A[0] [0]	A[0] [1]	A[0] [2]

A[1] [0]	A[1] [1]	A[1] [2]

A[2] [0]	A[2] [1]	A[2] [2]

## **ALGORITHM**

- **Take matrix input from user and display it**

1.We first get the number of rows and columns from the user.

2.We then declare a 2D array (matrix) with the specified dimensions.

3.We use nested loops to iterate through the matrix and input the elements from the user.

4.Finally, we use another set of nested loops to display the matrix.

5.Compile and run this C++ program, and it will take matrix input from the user and display it on the screen.

- **Addition of matrix**
  
1. Start

2. Declare variables for the number of rows and columns for the matrices (let's call them rows and cols).

3. Get the dimensions (rows and cols) of the matrices from the user.

4. Declare two 2D arrays (matrices) of size rows x cols: matrix1 and matrix2.

5. Input the elements of matrix1 and matrix2 from the user using nested loops.

6. Declare another 2D array (resultMatrix) of the same size (rows x cols) to store the result.

7. Perform matrix addition using nested loops:
   - For each element at position (i, j) in resultMatrix:
     - resultMatrix[i][j] = matrix1[i][j] + matrix2[i][j]

8. Display the resultMatrix, which contains the sum of the two matrices.

9. End

- **Multiplication of Matrix**

1. Start

2. Declare variables for the number of rows and columns for the first matrix (matrix1Rows, matrix1Cols) and the second matrix (matrix2Rows, matrix2Cols).

3. Get the dimensions (rows and columns) of matrix1 and matrix2 from the user.
   
4. Check if matrix1Cols is equal to matrix2Rows. If not, exit the program with an error message because matrix multiplication is not possible.

5. Declare three 2D arrays:
   - matrix1 of size matrix1Rows x matrix1Cols
   - matrix2 of size matrix2Rows x matrix2Cols
   - resultMatrix of size matrix1Rows x matrix2Cols

6. Input the elements of matrix1 and matrix2 from the user using nested loops.

7. Perform matrix multiplication using three nested loops:
   - For each element at position (i, j) in resultMatrix:
     - Initialize resultMatrix[i][j] to 0.
     - Perform the dot product of the ith row of matrix1 and the jth column of matrix2 to calculate resultMatrix[i][j].

8. Display the resultMatrix, which contains the product of the two matrices.

9. End

- **Diagonal Addition**

1. Start

2. Declare variables for the number of rows and columns of the matrix (rows and cols).

3. Get the dimensions (rows and cols) of the matrix from the user.

4. Declare a 2D array (matrix) of size rows x cols to store the matrix elements.

5. Input the elements of the matrix from the user using nested loops.

6. Initialize a variable (diagonalSum) to 0. This variable will store the sum of the diagonal elements.

7. Use a loop to iterate through the diagonal elements of the matrix:
   - For each element at position (i, i), add matrix[i][i] to diagonalSum.

8. Display the value of diagonalSum, which contains the sum of the diagonal elements.

9. End

- **Transpose of Matrix**

1. Start

2. Declare variables for the number of rows and columns of the original matrix (rows and cols).

3. Get the dimensions (rows and cols) of the original matrix from the user.

4. Declare a 2D array (originalMatrix) of size rows x cols to store the original matrix elements.

5. Input the elements of the original matrix from the user using nested loops.

6. Declare a new 2D array (transposeMatrix) of size cols x rows to store the transposed matrix.

7. Use nested loops to copy the elements from the original matrix to the transposed matrix with swapped rows and columns:
   - For each element at position (i, j) in the original matrix, assign originalMatrix[i][j] to transposeMatrix[j][i].

8. Display the transposed matrix (transposeMatrix).

9. End

- **Campare elements of first row to the second row**

1. Start

2. Declare variables for the number of rows and columns of the matrix (rows and cols).

3. Get the dimensions (rows and cols) of the matrix from the user.

4. Declare a 2D array (matrix) of size rows x cols to store the matrix elements.

5. Input the elements of the matrix from the user using nested loops.

6. Initialize a boolean variable (rowsEqual) to true. This variable will be used to track if the elements of the first row are equal to the corresponding elements of the second row.

7. Use a loop to compare the elements of the first row to the second row:
   - For each column index (i) from 0 to cols-1:
     - If matrix[0][i] is not equal to matrix[1][i], set rowsEqual to false and break out of the loop.

8. If rowsEqual is true, display a message indicating that the two rows are equal. Otherwise, display a message indicating that the two rows are not equal.

9. End

### **OUTPUT**

- **Take matrix input from user and display it**
  

![Screenshot 2023-10-18 at 8 12 04 PM](https://github.com/sanskkriti/2D-Array/assets/140137289/af8a0a21-4d8d-497d-8c33-76ad560def34)



- **Addition of matrix**
- 

  ![Screenshot 2023-10-18 at 8 12 14 PM](https://github.com/sanskkriti/2D-Array/assets/140137289/4d2d93de-02fa-40b4-aa7c-6e60f9bd1d8e)


- **Multiplication of Matrix**

- 
![Screenshot 2023-10-18 at 8 12 23 PM](https://github.com/sanskkriti/2D-Array/assets/140137289/31e1b934-af29-4225-b706-9cd82035e310)



- **Diagonal Addition**

- 
![Screenshot 2023-10-18 at 8 12 32 PM](https://github.com/sanskkriti/2D-Array/assets/140137289/6c61e55f-3cfe-4a8e-a22a-89bb365d2e51)


- **Transpose of Matrix**

- 

![Screenshot 2023-10-18 at 8 12 39 PM](https://github.com/sanskkriti/2D-Array/assets/140137289/85844ef4-8a4a-4a21-8129-82eb2ea607ac)





- **Compare elements of first row to the second row**

![Screenshot 2023-10-18 at 8 12 51 PM](https://github.com/sanskkriti/2D-Array/assets/140137289/71c231ff-f0dd-4cf9-bbab-071cdcea77b2)
