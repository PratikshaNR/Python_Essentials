1. Matplotlib

Matplotlib is a Python library for creating static, animated, and interactive visualizations.

Key Features:

Line, bar, scatter, histogram, and pie charts.

Customizable plots (colors, labels, titles, legends).

Supports interactive mode for real-time plotting.

Basic Example:

import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
y = [10, 20, 25, 30]

plt.plot(x, y, marker='o', color='blue', linestyle='--')
plt.title("Sample Plot")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()




2. Object-Oriented Programming (OOPs)
OOP is a programming paradigm that organizes code into classes and objects.

Core Concepts:

Class → Blueprint for objects.

Object → Instance of a class.

Encapsulation → Restricting access to data.

Inheritance → Reusing code from another class.

Polymorphism → Same interface, different implementation.

Abstraction → Hiding internal details.

Basic Example:
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def start(self):
        print(f"{self.brand} {self.model} is starting...")

car1 = Car("Toyota", "Corolla")
car1.start()

3. Pandas
Pandas is a Python library for data manipulation and analysis.

Key Features:

- DataFrame and Series structures.

- Easy data cleaning, merging, filtering, grouping.

- Handles CSV, Excel, SQL, and JSON.

Basic Example:

import pandas as pd

data = {'Name': ['Alice', 'Bob', 'Charlie'],
        'Age': [25, 30, 35]}

df = pd.DataFrame(data)
print(df.head())

#Filtering
print(df[df['Age'] > 28])

4. Regular Expressions (Regex)
Regular Expressions are patterns used to match and manipulate strings.

Common Functions:

re.match() → Checks if the pattern matches at the start.

re.search() → Searches for the first occurrence.

re.findall() → Returns all matches.

re.sub() → Replaces matches.

Basic Example:

import re

text = "My phone number is 9876543210"
pattern = r"\d{10}"

match = re.search(pattern, text)
if match:
    print("Found:", match.group())
