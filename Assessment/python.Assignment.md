Here's a comprehensive Python assignment that covers beginner, intermediate, and advanced topics. The assignment is divided into three sections: Basic, Intermediate, and Advanced, with practical tasks and coding challenges.

---

### **Python Assignment**

#### **Basic Level**

1. **Hello, World!**  
   Write a Python program that prints "Hello, World!" to the console.

2. **Simple Calculator**  
   Write a Python program to create a simple calculator that can perform addition, subtraction, multiplication, and division operations.

   **Input Example**:  
   ```python
   Enter first number: 10
   Enter second number: 5
   Enter operation (+, -, *, /): *
   ```

   **Output Example**:  
   `Result: 50`

3. **List Operations**  
   Write a Python program that takes a list of numbers and performs the following:
   - Sort the list in ascending order.
   - Remove duplicates.
   - Find the largest and smallest numbers.

   **Example Input**: `[5, 3, 7, 1, 3, 5, 9]`  
   **Example Output**:  
   ```
   Sorted List: [1, 3, 5, 7, 9]
   Largest Number: 9
   Smallest Number: 1
   ```

4. **Even Numbers Checker**  
   Write a Python program that asks the user for a number and checks if it is even or odd.

5. **Dictionary Manipulation**  
   Create a Python dictionary with at least 5 key-value pairs. Write a program to:
   - Print all keys.
   - Print all values.
   - Add a new key-value pair.
   - Remove an existing key.

---

#### **Intermediate Level**

1. **Palindrome Checker**  
   Write a Python program that checks if a given word is a palindrome (a word that reads the same backward as forward).

   **Input Example**:  
   `madam`  
   **Output Example**:  
   `Yes, it is a palindrome!`

2. **Fibonacci Sequence Generator**  
   Write a Python function that generates and prints the Fibonacci sequence up to a given number `n`.

   **Example Input**: `10`  
   **Example Output**: `[0, 1, 1, 2, 3, 5, 8]`

3. **File Handling**  
   Create a Python program that reads a text file, counts the number of words, and prints the top 3 most common words.

   **Example Input**: A text file named `example.txt`.  
   **Example Output**:  
   ```
   Word Count: 100
   Top 3 Words: "python", "programming", "data"
   ```

4. **Prime Number Checker**  
   Write a Python function that checks if a given number is prime.

   **Example Input**: `17`  
   **Example Output**:  
   `Yes, 17 is a prime number!`

5. **List Comprehensions**  
   Write a Python program that uses list comprehensions to create a new list containing the squares of all even numbers from 1 to 20.

   **Expected Output**: `[4, 16, 36, 64, 100, 144, 196, 256, 324, 400]`

---

#### **Advanced Level**

1. **Class and Object Manipulation**  
   Create a `BankAccount` class that:
   - Has attributes: `account_number`, `balance`.
   - Has methods for `deposit()`, `withdraw()`, and `display_balance()`.

   **Task**: Create an object of the class and perform deposit and withdrawal operations.

2. **Decorator for Timing Functions**  
   Write a decorator function that times the execution of any function it wraps and prints the duration.

   **Example**:  
   ```python
   @time_it
   def example_function():
       # Some code
   ```

   **Expected Output**:  
   `Function example_function took 2.45 seconds to execute.`

3. **Recursion - Factorial Calculation**  
   Write a recursive Python function to calculate the factorial of a number.

   **Input Example**: `5`  
   **Output Example**: `Factorial of 5 is 120`

4. **Data Analysis - Numpy and Pandas**  
   - Create a NumPy array of random integers.
   - Convert it into a Pandas DataFrame.
   - Perform basic operations like mean, median, and standard deviation on the data.

   **Example**:  
   ```python
   import numpy as np
   import pandas as pd

   data = np.random.randint(1, 100, (10, 5))
   df = pd.DataFrame(data, columns=['A', 'B', 'C', 'D', 'E'])

   # Find mean, median, standard deviation
   ```

5. **Generator for Infinite Sequence**  
   Create a generator in Python that generates an infinite sequence of even numbers. Use this generator to print the first 10 even numbers.

   **Expected Output**: `[0, 2, 4, 6, 8, 10, 12, 14, 16, 18]`

---

### **Submission Instructions**

- Create a Python script for each task.
- Include appropriate comments in the code explaining your logic.
- Submit your work as a ZIP file containing all the scripts.
