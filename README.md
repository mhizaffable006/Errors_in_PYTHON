# Errors_in_PYTHON
## QUESTION
Different errors in Python, their explanation and at least one example each.

## ANSWERS
Python has several types of errors that can occur during code execution. Common Python errors are:
## 1. SyntaxError
•	Description: This error occurs when the Python interpreter finds syntax that it doesn’t understand or expects differently. It's a parsing error.

•	Example:
python
Copy code
# Missing colon in if statement
if 7 > 4
    print("7 is greater than 4")

•	Explanation: Here, the if statement is missing a colon : at the end, causing a SyntaxError.
________________________________________

## 2. IndentationError
•	Description: Python expects consistent indentation to define code blocks. If the indentation is incorrect or inconsistent, an IndentationError occurs.
•	Example:
python
Copy code
def my_function():
    print("Hello, my name is Becky!")
   print("Incorrect indentation")
 
 •	Explanation: The second print statement has an inconsistent indentation level, resulting in an IndentationError.
________________________________________


## 3. NameError
•	Description: This error occurs when Python encounters a variable or function name that hasn’t been defined.
•	Example:
python
Copy code
print(my_variable)
 
 •	Explanation: my_variable hasn’t been defined, so attempting to print it causes a NameError.
________________________________________
## 4. TypeError
•	Description: This error occurs when an operation or function is applied to an object of inappropriate type.
•	Example:
python
Copy code
result = "9" + 1
 
 •	Explanation: This attempts to add a string ("9") to an integer (1), causing a TypeError.
________________________________________
## 5. IndexError
•	Description: This error happens when trying to access an index that is out of range in a list or other indexed data structure.
•	Example:
python
Copy code
my_list = [1, 2, 3]
print(my_list[5])
 
 •	Explanation: The list has only three elements (index 0 to 2), so accessing index 5 raises an IndexError.
________________________________________

## 6. KeyError
•	Description: This error occurs when trying to access a dictionary key that doesn’t exist.
•	Example:
python
Copy code
my_dict = {"name": "Rebecca", "age": 26}
print(my_dict["address"])
 
 •	Explanation: The dictionary doesn’t contain the key "address", so this raises a KeyError.
________________________________________
## 7. ValueError
•	Description: This error occurs when a function receives an argument of the correct type but an inappropriate value.
•	Example:
python
Copy code
number = int("xyz")
 
 
 •	Explanation: int() expects a string that represents a number, so passing "xyz" raises a ValueError.
________________________________________
## 8. AttributeError
•	Description: This error occurs when an invalid attribute reference is made for an object (e.g., calling a method that doesn’t exist on an object).
•	Example:
python
Copy code
my_string = "hi"
my_string.append("!")
 
 
 •	Explanation: Strings don’t have an append method, so this results in an AttributeError.
________________________________________

## 9. ZeroDivisionError
•	Description: This error occurs when trying to divide a number by zero.
•	Example:
python
Copy code
result = 10 / 0
 
 
 •	Explanation: Division by zero is undefined, so this raises a ZeroDivisionError.
________________________________________
## 10. ModuleNotFoundError
•	Description: This error occurs when Python cannot find a specified module.
•	Example:
python
Copy code
import non_existent_module
 
 •	Explanation: Python attempts to import a module named non_existent_module, which doesn’t exist, resulting in a ModuleNotFoundError.

