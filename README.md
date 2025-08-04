# 🔢 Python Math & Factorial Program

This repository contains two Python programs:

1. **Factorial Calculation using a loop**
2. **Mathematical Operations (Square Root, Log, Sine) using the `math` module**

---

## 🧮 Program 1: Factorial Function

This program defines a function named `factorial` that calculates the factorial of a number using a loop.

### ✅ Sample Code:

```python
def factorial(n):
    if n < 0:
        return "Factorial is not defined for negative numbers"
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result

# Call the function with a sample number
sample_number = 5
output = factorial(sample_number)
print(f"Factorial of {sample_number} is: {output}")



📐 Program 2: Math Operations using math module
This program asks the user for a number and calculates:

Square root

Natural logarithm (base e)

Sine of the number (in radians)

✅ Sample Code:
python
Copy
Edit
import math

# Step 1: Ask the user for a number
num = float(input("Enter a number: "))

# Step 2: Perform mathematical operations using math module

# Calculate square root
square_root = math.sqrt(num)

# Calculate natural logarithm (log base e)
if num > 0:
    natural_log = math.log(num)
else:
    natural_log = "Undefined (logarithm of non-positive number is not defined)"

# Calculate sine of the number (in radians)
sine_value = math.sin(num)

# Display the results
print(f"Square root of {num} is: {square_root}")
print(f"Natural logarithm of {num} is: {natural_log}")
print(f"Sine of {num} (in radians) is: {sine_value}")
