# Task 1.3: Print your name and a greeting
print("Hello, my name is John Doe!")  # Replace with your name
print("Welcome to learning Python!")
print("Hello!")  # Print Hello message
print("My name is John Doe")
# Task 2.1: Area and perimeter of a rectangle
length = 10
width = 5
area = length * width
perimeter = 2 * (length + width)
print("Length:", length)
print("Width:", width)
print("Area:", area)
print("Perimeter:", perimeter)
# Task 2.2: Compare two numbers
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
if a > b:
    print("First number is greater.")
elif a < b:
    print("First number is smaller.")
else:
    print("Both numbers are equal.")
# Task 2.3: Check if year is a leap year
year = int(input("Enter a year: "))
if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(year, "is a leap year.")
else:
    print(year, "is not a leap year.")
# Task 2.4: Arithmetic and logical operators
print("5 + 3 =", 5 + 3)
print("10 // 3 =", 10 // 3)
print("2 ** 4 =", 2 ** 4)
print("True and False =", True and False)
print("not True =", not True)
# Task 2.5: Concatenate two strings
first = "Hello"
second = "World"
result = first + " " + second
print("Concatenated string:", result)
