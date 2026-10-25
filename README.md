# struct--to---dict
A beginner-friendly Python project that demonstrates how to convert a class object's instance attributes into a dictionary using Python's built-in vars() function.

📌 Project Description
The Struct to Dictionary project demonstrates how structured information stored in a Python object can be converted into a dictionary.

Dictionaries store information as key-value pairs, making individual values accessible through their corresponding keys.

✨ Features
Converts a Python object's instance attributes into a dictionary.
Demonstrates the use of Python classes and objects.
Organizes information into key-value pairs.
Allows individual values to be accessed using dictionary keys.
Uses Python's built-in vars() function.
🛠️ Requirements
Python 3.x
A code editor or terminal to run the program.
🚀 Usage
Run the Python script from your terminal, replacing the filename if necessary:

python3 "struct to dict .py"
The program creates a Student object, converts its instance attributes into a dictionary, and prints the result.

💡 Example
Python code:

class Student:
    def __init__(self, name, age, branch):
        self.name = name
        self.age = age
        self.branch = branch

s = Student("Aditya", 19, "AI/ML")

d = vars(s)

print(d)
Output:

{'name': 'Aditya', 'age': 19, 'branch': 'AI/ML'}
How It Works
The Student class defines three attributes: name, age, and branch.
The Student object s is created with the values "Aditya", 19, and "AI/ML".
The built-in vars(s) function returns a dictionary containing the object's instance attributes.
The print(d) statement displays the resulting dictionary.
You can access individual values using dictionary keys:

print(d["name"])    # Riya
print(d["age"])     # 19
print(d["branch"])  # AI/ML
