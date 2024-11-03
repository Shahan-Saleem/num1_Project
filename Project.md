# Project statement
```python
# Get the first integer input from the user
num1 = int(input("my dog name shaggy and his age: "))

# Get the second integer input from the user
num2 = int(input("and shaggy dad age: "))

# Calculate the sum of the two integers
sum = num1 + num2

# Print the result
print("The sum of age", num1, "and", num2, "is:", sum)
```

**Explanation:**

1. **`num1 = int(input("Enter the first integer: "))`**
   - This line prompts the user to enter the first integer using `input("Enter the first integer: ")`.
   - `int()` converts the user's input (which is a string) into an integer and stores it in the variable `num1`.

2. **`num2 = int(input("Enter the second integer: "))`**
   - This line does the same as the previous line, but for the second integer.

3. **`sum = num1 + num2`**
   - This line adds the two integers `num1` and `num2` and stores the result in the variable `sum`.

4. **`print("The sum of", num1, "and", num2, "is:", sum)`**
   - This line prints a formatted message showing the original numbers and their sum.

**How to run the program:**

1. Save the code as a Python file (e.g., `sum_calculator.py`).
2. Open your terminal or command prompt.
3. Navigate to the directory where you saved the file.
4. Run the program using the command `python sum_calculator.py`.
5. The program will prompt you to enter two integers. Enter the values and press Enter.
6. The program will then display the sum of the two integers.