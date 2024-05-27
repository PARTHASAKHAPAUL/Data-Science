# Data-Science(ED5340)

## Lab: 1
- Calculate specific mathematical expressions and differences in areas of circles.
- Count odd and even numbers between 7 and 80 without loops and print using format strings.
- Explain and demonstrate Python data types, including size and type.
- Calculate cuboid surface area with random sides; solve quadratic equations with user inputs.
- Perform string manipulations, discuss Python's OOP differences, explain five built-in functions, and analyze strings for vowels and palindromes.

## Lab: 2
1. Print numbers divisible by both 7 and 8 within 1 to 1000 using continue and pass statements.
2. Calculate sum of even and odd digits in a given number.
3. Describe and implement conditional expression to find maximum and minimum numbers in a list.
4. Print Pascal’s Triangle pattern for a given number of rows.
5. Check if a number and a string are palindromes.
6. Explain and demonstrate chr() and ord() functions; use them to print a specific pattern.
7. Manipulate a list of names: print first names, last names, combine names, and sort by last name.
8. Find the minimum of 3 and 4 numbers using conditional expressions and nested conditionals.
9. Perform various operations on a list of departments at IIT Madras.
10. Explain the differences between deep copy and shallow copy.

## Lab: 3(Part-1)
1. Write a program to manage a library catalog with functionalities to add, delete, sort, and remove duplicates based on specific criteria.
2. Use list comprehension to add, multiply elements of two lists, and extract unique characters from a string.
3. Utilize the zip function to add and multiply elements of two matrices.
4. Implement operations on a square matrix to calculate row/column sums, trace, transpose, symmetry check, and positive definiteness of the identity matrix.
5. Write a program to filter sublists within a list of lists based on a specified numerical range.
## Lab: 3(Part-2)
6. Given two lists of equal length (list1 with integers, list2 with alphabets), use list comprehension to generate: a) list of squares from list1, b) list of tuples pairing corresponding elements, c) list of all possible combinations, d) list of alternating elements.
7. Identify and list the methods that are applicable to lists but not tuples.
8. Write a code snippet that takes a string input and returns a tuple of tuples, each containing a character from the string and its ASCII value.
9. Create a program to filter a list of tuples, retaining only those whose first element (student name) starts with a vowel.
10. Create a set of numbers between 1 and 20 that are divisible by 3 or 5 using set comprehension.
11. Explain what a frozenset is and provide examples.

## Lab: 4(Part-1)
1. Explore the use and syntax of common built-in functions: range(), iter(), eval(), enumerate(), zip(), lambda, input(), map(), filter(), next(), reduce(), including descriptions and practical code examples.
2. Write a Python function to sort a dictionary based on the length of its values.
3. Develop a Python program that prompts the user for a string and performs the following tasks: a) creates a frequency dictionary of characters, b) sorts dictionary by frequency, c) sorts dictionary by characters, d) identifies the three most frequently occurring characters.
4. Write a function `lookup_student` to search for a student's roll number in a dictionary and return it if found, otherwise return "Not Found".
5. Given a list of integers, write a Python program to: a) find the frequency of each integer and store it in a dictionary, b) print the maximum integer and its frequency, c) remove duplicates without changing order without using a set, d) remove duplicates using a set.
## Lab: 4(Part-2)
6. Store employee details in nested dictionaries and: a) sort by salary, b) add a new employee in the correct sorted position.
7. Create a function to combine two dictionaries, summing values for common keys.
8. Write a function to convert a list of lists (each containing a key and value) into a list of dictionaries.
9. Illustrate the usage of positional and keyword arguments with examples.
10. Write a function to find the maximum of n numbers using variable length positional arguments.
11. Write a function to concatenate n strings using variable length keyword arguments.

## Lab: 5(Part-1)
1. **Write a program using loops and recursion:**
    - Factorial of n where n is a non-negative integer.
    - For calculating the Nth Fibonacci number.
    - To calculate a^b where a > 0, b >= 0.

2. **Query for 2 integers N and M from the user where 0 <= N <= 100 and 0 <= M <= 9. These will be the inputs to your function. Using recursion, compute the number of times the integer M occurs in all non-negative integers less than or equal to N.**
    - Example: For N=13 and M=1, count=6 (numbers 1,10,11,12,13).

3. **Programs using lambda functions:**
    - Given a list of names, use `map` to create a list where each name is prefixed with "Hello, ".
        - Example Input: `['Alice', 'Bob', 'Charlie']`
        - Example Output: `['Hello, Alice', 'Hello, Bob', 'Hello, Charlie']`
    - Use `filter` and a lambda function to extract all even numbers from a given list.
        - Example Input: `[1, 2, 3, 4, 5, 6]`
        - Example Output: `[2, 4, 6]`
    - Use `reduce` and lambda to concatenate all strings in a given list.
        - Example Input: `['Python', 'is', 'awesome']`
        - Example Output: `'Pythonisawesome'`

4. **Define a class `Complex` that defines a complex number with attributes real and imaginary. Define operators for addition, subtraction, multiplication, and division (Do with both operator overloading as well as without overloading). While printing the output, print in the form of complex number form like (a + ib).**

## Lab: 5(Part-2)
5. **WAP to implement a class called "Bank_Account" representing a person's bank account with attributes account_holder_name, account_number, address, and balance, and methods for deposit, withdraw, check_balance, update_details, and display_details.**

6. **Define a `Matrix` class of dimensions m X n with methods for matrix addition, subtraction, multiplication, element-by-element multiplication, scalar multiplication (using map), and use operator overloading where possible.**

7. **Create a Python class named `Time` that represents a moment of time with attributes hour, minute, and second, and methods including a constructor with validation, `__str__()` method, `set_time()`, `get_time()`, and `add_seconds()`.**

8. **Create a class named `Geometry` that provides static methods for various geometric calculations like area and perimeter for shapes such as circles, rectangles, and squares, ensuring valid input checks.**


## Lab: 6(Part-1)
1. **Design a class named `Polygon` that initializes with the length of a side and derive a class named `Square` from the `Polygon` class, implementing a method `findArea()` to calculate and return the square's area.**

2. **Create a class `Father` with attributes `father_name`, `father_age`, `father_talents`, and a class `Mother` with attributes `mother_name`, `mother_age`, `mother_talents`; create a class `Child` inheriting both, with attributes `child_name`, `child_age`, `child_gender`, and methods to get and print details, and display talents inherited from both parents.**

3. **Create a text file with the pledge of India, write a Python program to read and count the occurrences of each word, and write the result to a new text file.**

4. **Create a parent class `Bill` with properties `Customer name`, `Table Number`, and `Order`; create a child class `Restaurant Bill` with a `Price list` property, methods to calculate total bill amount and print the complete bill including taxes and service charges.**

5. **Modify the previous restaurant bill program to take customer name, table number, and order details from a file, and the price list from another file, and print the complete bill to a new file.**


## Lab: 6(Part-2)
6. **Create a base class `Vehicle` with attributes `make`, `model`, `year`, and methods to initialize and display these attributes; create a `Car` class with an additional attribute `fuel_type` and a `Bike` class with an additional attribute `gear_count`, each with methods to initialize and display these attributes, and demonstrate the methods with objects of `Car` and `Bike`.**

7. **Create a `Student` class to manage student data with instance attributes `name`, `age`, `grade`, and `class_schedule`, and class variables `school_name`, `total_students`, and `number_of_classes`; demonstrate the use of class variables with an example program.**

8. **Create a `Numbers` class with attributes `a`, `b`, and methods `find_gcd()` and `find_lcm()`, and derived classes `EvenNumbers`, `OddNumbers`, and `CompositeNumbers` that override these methods appropriately; create an object of `CompositeNumbers` and demonstrate the methods.**

9. **Create a Python script to manage a library's book collection by reading from and writing to a CSV file, with functionalities to add new books and list all books currently stored in the file.**

10. **Create a pandas DataFrame with a list of words, sort them in ascending order, and copy the sorted words to a new file.**


## Lab: 7(Part-1)
1. **Write a program that takes coefficients A, B, C, D, and E as inputs representing a 4th degree polynomial in the form Ax^4 + Bx^3 + Cx^2 + Dx + E, calculate the values of this polynomial for x in the range from -100 to 100 with constant discrete intervals, store the resulting x and y values as a NumPy array, and use Matplotlib to plot the graph using the generated NumPy array.**

2. **Given a dictionary containing information about monthly sales for different products over a period of time, convert this dictionary into a pandas DataFrame, calculate the total sales for each product over the entire period, and create a bar plot using Matplotlib to visualize the total sales for each product.**

3. **Create visualizations for the following mathematical functions using Matplotlib:**

   **(a) Plot the single-variable functions over the range [-10,10] with a title and labels for the axes:**
   - **y = cos(x)**
   - **y = e^x**
   - **y = log(x), where x>0**

   **(b) Generate surface plots for the multi-variable functions over the range x=[-10,10] and y=[-10,10], ensuring to add a title and labels for all axes:**
   - **z = cos(sqrt(x^2 + y^2))**
   - **z = e^(-(x^2 + y^2))**
   - **z = log(x^2 + y^2) where x^2 + y^2 > 0**

4. **For the function J(w) = w^2 + (54/w), implement the bracketing method (choose your own a, b, n).**


## Lab: 7(Part-2)
5. **Write a program to plot a 3D graph of the helical wave signal using the scatter method and normal line method separately, and specify legends for each.**

6. **Given a dictionary of dictionaries representing countries, create a DataFrame using Pandas.**

7. **Create a DataFrame using Pandas from a string containing tabular data.**

8. **Given an N x M integer array matrix with space-separated elements (N = rows, M = columns), print the transpose and flatten results using NumPy.**

9. **Write a program to capitalize a column of names in a Pandas DataFrame.**

10. **Use the central difference method to find the first and second-order derivatives of the function \( f(x) = 3x^2 + 2x \). Verify the result manually and write it on paper for comparison.**


## Lab: 8
1. **Implement methods to find the critical point of the function \( J(w) = w^2 + \frac{54}{w} \) using (a) interval halving method and (b) Newton-Raphson method. Verify the result manually using the optimality criteria. Post the write-up as an image.**

2. **Plot the surface \( J(w_1, w_2) = (w_1 - 10)^2 + (w_2 - 10)^2 \) and generate the corresponding contour plot. Label the plots appropriately and provide a suitable title for the figure.**

3. **Using line search along the direction (2, 5) for the function \( (w_1 - 10)^2 + (w_2 - 10)^2 \), find the minimum value starting from the point (2, 1). Plot the function and its contours along with the minimum value in that direction.**

## Lab: 9
1. **Comment on whether the search direction in the last week's lab question is a gradient descent one.**

2. **Using steepest gradient descent, find all the local minima for the function \( J(x_1, x_2) = (x_1^2 + x_2 - 11)^2 + (x_1 + x_2^2 - 7)^2 \). Perform the following steps:**
    - **(a) Fix the value for alpha**
    - **(b) Use line search to determine the value for alpha.**
    - **Plot the intermediate steps in the iteration to show one of the minimal points.**

**Note:** *Plan your coding to enable reusability (use classes/functions). The code developed can be used for solving future problems, especially in ML, where both multivariable and single-variable optimization are significant.*


## Lab: 10
1. **Implement the generalized equation for finding the gradient of m-samples, each having n-features. Additionally, implement the gradient descent approach with a constant learning rate.**

2. **Using the code developed for problem 1, perform linear regression for the univariate problem using the provided data file "univariate_linear_regression.csv". Plot the cost function (both as surface and contour) as well as the best fit line.**

3. **Using the code developed for problem 1, conduct linear regression for the multivariate problem using the provided data file "heart.data.csv". Plot the best fit plane for the given data. Additionally, interpret the result by considering one independent variable at a time.**


## Lab: 11(Part-1)
1. **Plot the sigmoid function. Provide an interpretation of why this function is useful for a classification problem.**

2. **Plot the log functions in the cost function individually. Offer an interpretation of the log functions.**

3. **Utilize your own data for a single feature problem, considering it as a linear regression problem. Plot the cost function and its contours. Additionally, use cross entropy as the cost function and plot it along with its contours.**


## Lab: 11(Part-2)
4. **Implement logistic regression using the data provided in "Logistic_regression_ls.csv". Plot the decision boundary (linear) using optimization of the sigmoid function.**


## Lab: 12
1. **Support Vector Machine (SVM):**
    - Load the iris dataset and the digits dataset [find details from this link](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html).
    - Visualize the data for both datasets.
    - Split the data into training and testing sets.
    - Initialize and train the SVM model for classifying iris flowers based on sepal length and width, and for classifying handwritten digits.
    - Test the model and evaluate its performance.
    
2. **Principal Component Analysis (PCA):**
    - Use Eigen decomposition available in numpy to perform PCA.
    - Load the dataset provided in the [link](https://scikit-learn.org/stable/auto_examples/decomposition/plot_pca_3d.html#sphx-glr-auto-examples-decomposition-plot-pca-3d-py).
    - Implement PCA using numpy.
    - Compare the results obtained with the results available in the provided [link](https://scikit-learn.org/stable/auto_examples/decomposition/plot_pca_3d.html#sphx-glr-auto-examples-decomposition-plot-pca-3d-py).


## Lab: 13(Part-1)
1. **Generate Data and Write to CSV:**
    - Generate 10 random points in each of the three circles specified.
    - Write the generated data to a CSV file.
    - Plot the generated data.

2. **Implement K-Means Clustering Algorithm:**
    - Implement the K-Means clustering algorithm without using the sklearn library.
    - Show the change in centroids and class assignments during the iterations.
    - Plot the cost function for K varying from 1 to 5 to determine the optimal number of clusters.
    - Plot the K classes for the final K-value obtained from the cost function.

## Lab: 13(Part-2)
