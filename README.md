'''Create a simple Python program that asks the user to input two numbers and a mathematical operation
(addition, subtraction, multiplication, or division).Perform the operation based on the user's input and
print the result Example: If a user inputs 10, 5, and +, your program should display 10 + 5 = 15.'''

First_number = float(input("Enter your first number: "))
Second_number = float(input("Enter your first number: "))
operator = input("Enter the operator of choice (+, -, *, /): ")

if operator == '+':
    result = First_number + Second_number
    print(f"{First_number} + {Second_number} = {result}")

elif operator == '-':
    result = First_number - Second_number
    print(f"{First_number} - {Second_number} = {result}")

elif operator == '*':
    result = First_number * Second_number
    print(f"{First_number} * {Second_number} = {result}")

elif operator == '/':
    result = First_number * Second_number
    while Second_number != 0:
        print(f"{First_number} * {Second_number} = {result}")
    else:
        print("ZeroErrorDivision, Please Enter a number that is not zero")


else:
    print("You entered an invalid operator please choose from (+, -, *, /) choices.")

