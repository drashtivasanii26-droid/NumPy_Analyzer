# 🔢 NumPy Analyzer

### Python-Based Data Analytics Project

**Author:** Drashti Vasani  
**Language:** Python 3  
**Library:** NumPy  

---

## 📖 About the Project

NumPy Analyzer is a menu-driven Python application developed using the NumPy library. It allows users to create 1D, 2D, and 3D arrays and perform different numerical and data analysis operations.

The application provides features such as array creation, indexing, slicing, mathematical operations, combining and splitting arrays, searching, sorting, filtering, and statistical calculations. It uses a simple console menu that allows users to select and perform operations easily.

## 🎯 Project Objectives

- Understand NumPy arrays and their dimensions.
- Create and manipulate 1D, 2D, and 3D arrays.
- Perform mathematical operations on arrays.
- Learn indexing and slicing techniques.
- Combine and split arrays.
- Search, sort, and filter array elements.
- Calculate statistical values.
- Practice Python classes, methods, loops, conditions, and exception handling.

## ✨ Features and Functionality

### 1. 🧱 Create a NumPy Array

The program allows users to create three types of arrays:

- **1D Array:** Enter the number of elements.
- **2D Array:** Enter the number of rows and columns.
- **3D Array:** Enter depth, rows, and columns.

The program validates the dimensions and number of elements before creating the array.

### 2. 🔎 Indexing and Slicing

- **Indexing:** Access a particular element using its index.
- **Slicing:** Extract a range of elements using the `start:end` format.
- Supports indexing and slicing for 1D, 2D, and 3D arrays.

### 3. ➕ Mathematical Operations

The program performs the following operations between two arrays:

- Addition
- Subtraction
- Multiplication
- Division

It checks the number of elements in the second array and prevents division by zero.

### 4. 🔗 Combine or Split Arrays

- **Combine Arrays:** Combines two arrays vertically using `np.vstack()`.
- **Split Array:** Divides an array into a selected number of parts using `np.array_split()`.

### 5. 🔍 Search, Sort, and Filter

- **Search:** Finds a value and displays its index using `np.where()`.
- **Sort:** Sorts array values in ascending or descending order.
- **Filter:** Selects values greater than, less than, or equal to a specified number.

### 6. 📊 Aggregates and Statistics

The application calculates:

- **Sum:** Total of all array elements.
- **Mean:** Average of the elements.
- **Median:** Middle value of the data.
- **Standard Deviation:** Measures the spread of values.
- **Variance:** Measures the squared spread of values.

### 7. 🚪 Exit

The program displays a thank-you message and exits when the user selects option 6.

## 💻 Technologies Used

- Python 3
- NumPy Library
- Visual Studio Code
- Git and GitHub

## 📚 Concepts Covered

- Classes and Objects
- Constructor (`__init__()`)
- Functions and Methods
- Variables and `input()`
- `if`, `elif`, and `else`
- `while` and `for` loops
- Lists, Tuples, and Dictionaries
- Exception Handling (`try` and `except`)
- `break`, `continue`, and `return`
- NumPy Array Creation
- Array Reshaping
- Indexing and Slicing
- Mathematical Operations
- Searching, Sorting, and Filtering
- Statistical Functions

## 📂 Project Structure

```text
NumPy_Analyzer/
│
├── Numpy_Analyzer.py
├── README.md
└── Numpy_Analyzer.png
```

## ⚙️ Installation

Install the NumPy library using the following command:

```bash
python -m pip install numpy
```

## ▶️ How to Run the Project

1. Open Visual Studio Code.
2. Open your project folder.
3. Save the Python code as `numpy_analyzer.py`.
4. Open the terminal.
5. Run the following command:

```bash
python numpy_analyzer.py
```

6. Select an option from the main menu and follow the instructions.

## 🖥️ Sample Output

The following sample output demonstrates the execution of the NumPy Analyzer project in Visual Studio Code. It includes array creation, indexing, slicing, mathematical operations, combining arrays, sorting, statistics, and exiting the program.

### 1. 📊 Main Menu and Array Creation

```text
========================================
Welcome to the NumPy Analyzer!
========================================
Choose an option:
1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
Enter your choice: 1

Select the type of array to create:
1. 1D Array
2. 2D Array
3. 3D Array
Enter your choice: 2
Enter number of rows: 2
Enter number of columns: 3
Enter 6 elements separated by space: 10 20 30 40 50 60

Array created successfully:
[[10 20 30]
 [40 50 60]]
```

### 2. 🔎 Indexing and Slicing

**Indexing Operation**

```text
Choose an operation:
1. Indexing
2. Slicing
3. Go Back
Enter your choice: 1

Original Array:
[[10 20 30]
 [40 50 60]]

Enter row index: 0
Enter column index: 2

Indexed Element:
30
```

**Slicing Operation**

```text
Choose an operation:
1. Indexing
2. Slicing
3. Go Back
Enter your choice: 2

Enter row range (start:end): 0:1
Enter column range (start:end): 0:2

Sliced Array:
[[10 20]]
```

**Return to Main Menu**

```text
Choose an operation:
1. Indexing
2. Slicing
3. Go Back
Enter your choice: 3
```

### 3. ➖ Mathematical Operations — Subtraction

```text
========================================
Welcome to the NumPy Analyzer!
========================================
Choose an option:
1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
Enter your choice: 2

Choose a mathematical operation:
1. Addition
2. Subtraction
3. Multiplication
4. Division
Enter your choice: 2

Enter 6 elements for second array: 10 40 20 30 50 60

Original Array:
[[10 20 30]
 [40 50 60]]

Second Array:
[[10 40 20]
 [30 50 60]]

Subtraction:
[[  0 -20  10]
 [ 10   0   0]]
```

### 4. 🔗 Combine Arrays

```text
========================================
Welcome to the NumPy Analyzer!
========================================
Choose an option:
1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
Enter your choice: 3

Choose an option:
1. Combine Arrays
2. Split Array
Enter your choice: 1

Enter 6 elements for second array: 5 4 3 2 1 6

Original Array:
[[10 20 30]
 [40 50 60]]

Second Array:
[[5 4 3]
 [2 1 6]]

Combined Array:
[[10 20 30]
 [40 50 60]
 [ 5  4  3]
 [ 2  1  6]]
```

### 5. 🔃 Sort Array in Descending Order

```text
========================================
Welcome to the NumPy Analyzer!
========================================
Choose an option:
1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
Enter your choice: 4

Choose an option:
1. Search a value
2. Sort the array
3. Filter values
Enter your choice: 2

Choose Sorting Order:
1. Ascending Order
2. Descending Order
Enter your choice: 2

Original Array:
[[10 20 30]
 [40 50 60]]

Descending Order:
[[30 20 10]
 [60 50 40]]
```

### 6. 📈 Aggregates and Statistics — Median

```text
========================================
Welcome to the NumPy Analyzer!
========================================
Choose an option:
1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
Enter your choice: 5

Aggregates and Statistics:
1. Sum
2. Mean
3. Median
4. Standard Deviation
5. Variance
Enter your choice: 3

Original Array:
[[10 20 30]
 [40 50 60]]

Median: 35.0
```

### 7. 🚪 Exit the Program

```text
========================================
Welcome to the NumPy Analyzer!
========================================
Choose an option:
1. Create a NumPy Array
2. Perform Mathematical Operations
3. Combine or Split Arrays
4. Search, Sort, or Filter Arrays
5. Compute Aggregates and Statistics
6. Exit
Enter your choice: 6

Thank you for using NumPy Analyzer!
Program exited successfully.
```

### ✅ Sample Output Summary

The above outputs demonstrate the following operations:

- Creation of a 2D NumPy array
- Indexing and slicing array elements
- Subtraction between two arrays
- Combining arrays vertically
- Sorting array elements in descending order
- Calculating the median
- Exiting the application successfully


## 🚀 Future Improvements

- Support floating-point numbers.
- Add file-based data storage.
- Add more numerical operations.
- Improve input validation.
- Add automated testing.
- Develop a graphical user interface.
- Add charts and data visualization.

## ✅ Conclusion

The NumPy Analyzer project demonstrates how Python and NumPy can be used to perform numerical calculations and analyze array data. It combines array creation, indexing, slicing, mathematical operations, combining and splitting, searching, sorting, filtering, and statistics in a single menu-driven application.

This project provides practical experience with Python programming and builds a foundation for further learning in data analysis and scientific computing.

---

