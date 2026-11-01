# 🛠️ Multi-Utility Toolkit (Python)

## 📌 Project Overview

The **Multi-Utility Toolkit** is a menu-driven Python console application that combines multiple useful utilities into a single program.

It provides different operations related to date and time, mathematical calculations, random data generation, unique identifier generation, and file management.

The project demonstrates Python's modular programming approach by integrating built-in modules, custom modules, and packages.

It is designed to help beginners understand Python modules, packages, functions, exception handling, file operations, and code reusability.

## ✨ Features

### 1. Datetime and Time Operations
- Display current date and time.
- Calculate the difference between two dates.
- Format dates into different formats.
- Stopwatch to measure elapsed time.
- Countdown timer.

### 2. Mathematical Operations
- Calculate factorial of a number.
- Calculate compound interest.
- Perform trigonometric calculations (sin, cos, tan).
- Calculate the area of geometric shapes:
  - Circle
  - Rectangle
  - Triangle
  - Square
- Perform unit conversions:
  - Celsius to Fahrenheit
  - Fahrenheit to Celsius
  - Kilometers to Miles
  - Miles to Kilometers
  - Kilograms to Pounds
  - Pounds to Kilograms

### 3. Random Data Generation
- Generate random numbers within a given range.
- Generate a random list of numbers.
- Create random passwords.
- Generate a six-digit OTP.
- Perform random sampling from a dataset.

### 4. Unique Identifier Generation (UUID)
- Generate a single UUID.
- Display UUID version and string.
- Generate multiple UUIDs for different purposes:
  - File ID
  - Record ID
  - Session ID

### 5. File Operations
Using a custom file operations module, users can:
- Create a new file.
- Write data to a file.
- Read data from a file.
- Append data to a file.
- Delete a file with confirmation.

### 6. Explore Module Attributes
- Explore built-in Python modules.
- Explore custom modules.
- Use the `dir()` function to display module attributes.
- Display the total number of attributes.

## 🛠️ Technologies Used

**Programming Language:** Python 3

### Built-in Modules
- `datetime` – Date and time operations.
- `time` – Stopwatch and countdown timer.
- `math` – Mathematical calculations and trigonometry.
- `random` – Random number, password, OTP, and sampling generation.
- `uuid` – Unique identifier generation.
- `string` – Character sets for password generation.
- `sys` – System-related module import.

### Custom Modules
- `toolkit_package.file_operations` – File handling operations.
- `toolkit_package.math_utilities` – Mathematical calculations and unit conversions.

### Python Concepts Used
- Functions and Modules
- Packages and Imports
- Exception Handling
- File Handling
- Loops and Conditional Statements
- List Comprehensions
- Dynamic Module Importing
- `dir()` Function
- UUID Generation
- Date and Time Formatting
- Menu-Driven Programming

## 📂 Project Structure

```text
Multi-Utility-Toolkit/
│
├── main.py
│
├── toolkit_package/
│   ├── __init__.py
│   ├── file_operations.py
│   └── math_utilities.py
│
└── README.md
```

**Note:** The `__init__.py` file makes `toolkit_package` a Python package. The custom modules contain the functions imported and used by `main.py`.

## ▶️ How to Run the Project

**Step 1:** Install Python 3.x on your computer.

**Step 2:** Download or clone the project repository.

**Step 3:** Open the project folder in VS Code or any Python IDE.

**Step 4:** Make sure the `toolkit_package` folder contains both custom Python modules.

**Step 5:** Open the terminal in the main project directory.

**Step 6:** Run the following command:

```bash
python main.py
```

**Step 7:** Select an option from the main menu and follow the instructions.

## 📋 Main Menu

```text
=======================================================
       Welcome to Multi-Utility Toolkit
=======================================================
Choose an option:

1. Datetime and Time Operations
2. Mathematical Operations
3. Random Data Generation
4. Generate Unique Identifiers (UUID)
5. File Operations (Custom Module)
6. Explore Module Attributes (dir())
7. Exit

=======================================================
```

## 💻 Example Outputs

### 1. Datetime and Time Operations

```text
Current Date and Time: 2026-11-01 10:30:00
Formatted: Sunday, November 01, 2026 at 10:30 AM
```

### 2. Mathematical Operations

```text
Enter a number: 5
Factorial: 120
```

### 3. Random Data Generation

```text
Enter lower bound: 1
Enter upper bound: 100

Random Number: 45
```

*Note: Random values will vary each time the program runs.*

### 4. UUID Generation

```text
Generated UUID: 12345678-1234-4234-8234-123456789abc
UUID Version: 4
```

*Note: UUID values are randomly generated.*

### 5. File Operations

```text
Enter file name: sample.txt

File created successfully!
```

### 6. Explore Module Attributes

```text
Enter module name to explore: math

Available Attributes in math module:
['__doc__', '__file__', '__name__', ...]

Total attributes: 66
```

## 🧠 Important Python Concepts Explained

### 1. Modules
Modules are Python files containing reusable functions, classes, and variables. This project uses built-in modules such as `math`, `random`, `time`, and `uuid`.

### 2. Packages
A package is a collection of related Python modules organized inside a directory.

This project uses a custom package named `toolkit_package`.

### 3. Custom Modules
The project contains two custom modules:

- `file_operations.py`
- `math_utilities.py`

These modules organize related functions and make the code reusable.

### 4. Exception Handling
The `try` and `except` blocks handle errors such as invalid user input and incorrect date formats.

### 5. Dynamic Importing
The `__import__()` function dynamically imports a module based on the user's input.

### 6. dir() Function
The `dir()` function displays the available attributes and methods of a module.

### 7. File Handling
The application performs file creation, reading, writing, appending, and deletion through its custom file operations module.

### 8. UUID
The `uuid.uuid4()` function generates unique identifiers for files, records, and sessions.

## 🎯 Learning Objectives

- Understand Python's built-in modules and packages.
- Learn how to create and import custom modules.
- Understand modular programming.
- Perform mathematical and date-time operations.
- Work with random data generation.
- Generate unique identifiers using UUID.
- Perform file handling operations.
- Handle runtime errors using exception handling.
- Explore module attributes using `dir()`.
- Develop a complete menu-driven Python application.

## 🚀 Future Enhancements

- Add a graphical user interface (GUI).
- Store user data in a database.
- Add more mathematical operations.
- Improve password generation security.
- Add more file management features.
- Create a configuration system for user preferences.

## 👨‍💻 Author

**Developed by:** [Your Name]

## 📜 License

This project is created for educational and learning purposes.
