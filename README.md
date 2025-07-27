# Calculator-practice-
🎉 Fun Calculator! 🎉
This is a simple, interactive Python script that performs basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers provided by the user. It's designed to be straightforward and easy to use, making number crunching a bit more fun!

✨ Features
Addition: Calculates the sum of two numbers.

Subtraction: Finds the difference between two numbers.

Multiplication: Computes the product of two numbers.

Division: Determines the quotient of two numbers.

Decimal Support: Handles floating-point numbers for more precise calculations.

🚀 How to Use
To run this calculator, follow these simple steps:

Ensure Python is Installed:
Make sure you have Python installed on your system. You can download it from the official Python website.

Save the Code:
Save the provided code into a file named calculator.py (or any other .py extension).

# 🎉 Welcome to the Fun Calculator! 🎉
# We're going to add, subtract, multiply, and divide two numbers like a boss! 😎

# Step 1: Ask the user to input the first number
# We're using 'float()' to make sure our numbers can have decimals too. Fancy, right? ✨
num1 = float(input("Enter the first number: "))

# Step 2: Ask the user to input the second number
# Same trick here—using 'float()' for decimal magic! 🧙‍♂️
num2 = float(input("Enter the second number: "))

# Step 3: Time to do some math! 🧠 Let's compute the sum, difference, product, and quotient.

# Add the two numbers (Yay! Addition is the first step to fun!) ➕
sum_result = num1 + num2

# Subtract the second number from the first (Negative vibes, but necessary! 😜) ➖
difference_result = num1 - num2

# Multiply the two numbers (More bang for your buck! 💥) ✖️
product_result = num1 * num2

# Divide the first number by the second (Be careful with zero here, no math disasters! 😅) ➗
# We'll assume the user is being responsible and not dividing by zero for now!
quotient_result = num1 / num2

# Step 4: Show the user what we got! 🥳 Time for the big reveal! 🎉
print(f"Results of your two numbers:")
print(f"Sum: {sum_result}")  # ➕
print(f"Difference: {difference_result}")  # ➖
print(f"Product: {product_result}")  # ✖️
print(f"Quotient: {quotient_result}")  # ➗

# 🏁 And that's it! I've just made a mini-calculator! 😎💻

Run from Terminal/Command Prompt:
Open your terminal or command prompt, navigate to the directory where I had  saved calculator.py, and run the script using the command:

python calculator.py

Enter Numbers:
The script will prompt you to enter the first number, then the second number. After you provide both, it will display the sum, difference, product, and quotient.

Enter the first number: 10.5
Enter the second number: 2
Results of your two numbers:
Sum: 12.5
Difference: 8.5
Product: 21.0
Quotient: 5.25

⚠️ Important Note on Division
This calculator assumes the user will not attempt to divide by zero. Dividing by zero will result in a ZeroDivisionError. Future enhancements could include error handling for this scenario!

Enjoy your fun calculations! 🥳
