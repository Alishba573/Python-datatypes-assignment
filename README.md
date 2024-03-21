# Python-datatypes-assignment
### Assignment 1: Primitive Types

You are tasked with creating a Python program that demonstrates various primitive types and their usage. Below are the questions you need to address:

#### 1. Temperature Conversion

You are building a simple weather application. The temperature is represented as a float value, and the application needs to convert temperatures between Celsius and Fahrenheit. The formula for conversion is: \(F = \frac{9}{5} \times C + 32\), where \(F\) is the temperature in Fahrenheit and \(C\) is the temperature in Celsius.

#### 2. Login System

You are creating a login system for a website. You need to store information about whether a user is an administrator or not. This information is represented by a boolean value.

#### 3. Student Information System

You are creating a system to store student information. Each student has a name (string), age (integer), and a flag indicating whether the student has completed their assignments (boolean).

#### 4. Book Reading Time

Write a Python program to store the number of pages in a book and calculate how long it will take to read the book. Assume that it takes 2 minutes to read one page of the book. Store the number of pages in a variable named `num_pages` and calculate the time to read the book in a variable named `reading_time`.

#### 5. Item Price Calculation

Store the price of an item and apply a discount to calculate the final price. Assume that the discount is 10%. Store the price in a variable named `original_price`, apply the discount, and store the final price in a variable named `final_price`.
#### 6. Rectangle Area Calculation

Calculate the area of a rectangle and display it. Store the length of the rectangle in a variable named `length` and the width in a variable named `width`. Store the result of the calculation in a variable named `area`. Display the value of `area`.

For each question, provide a Python code solution along with an explanation of the problem and the solution.
# 1. Temperature Conversion
def convert_temperature(celsius):
    fahrenheit = (celsius * 9/5) + 32
    return fahrenheit

celsius_temp = 25
fahrenheit_temp = convert_temperature(celsius_temp)
print(f"{celsius_temp}°C is equal to {fahrenheit_temp}°F")

# 2. Login System
is_admin = False

# 3. Student Information System
student_name = "Alice"
student_age = 22
assignments_completed = True

# 4. Book Reading Time
num_pages = 300
reading_speed = 3  # pages per minute
reading_time = num_pages / reading_speed
print(f"If you read at a speed of {reading_speed} pages per minute, it will take you {reading_time} minutes to read the book.")

# 5. Item Price Calculation
original_price = 50
discount_rate = 20  # percentage discount
discounted_price = original_price * (1 - discount_rate / 100)
print(f"The original price of the item is ${original_price}, and after applying a {discount_rate}% discount, the final price is ${discounted_price}.")

# 6. Rectangle Area Calculation
length = 8
width = 6
area = length * width
print(f"The area of the rectangle with length {length} units and width {width} units is {area} square units.")
25°C is equal to 77.0°F
If you read at a speed of 3 pages per minute, it will take you 100.0 minutes to read the book.
The original price of the item is $50, and after applying a 20% discount, the final price is $40.0.
The area of the rectangle with length 8 units and width 6 units is 48 square units.
