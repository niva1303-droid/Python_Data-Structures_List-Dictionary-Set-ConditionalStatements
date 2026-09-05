# Python Assignment 2 – Data Structures & Conditional Statements

## 📌 Project Overview

This repository is part of my Python learning journey and focuses on fundamental **Python data structures and conditional statements**. The exercises were completed using Google Colab and are organized as practical coding tasks.

- List operations and modifications
- Dictionary methods
- Set operations
- Conditional statements (`if`, `elif`, `else`)
- User input and validation

The exercises demonstrate how Python data structures can be created, modified, accessed, and used to solve simple programming problems.

---

## 🎯 Objectives

The main objectives of this assignment are to:

- Understand how to create and work with Python lists.
- Perform different list operations such as append, insert, remove, pop, extend, and sort.
- Access individual list elements using indexing and slicing.
- Understand dictionary creation, modification, and access.
- Use dictionary methods such as `keys()`, `values()`, and `items()`.
- Understand how sets store unique elements.
- Perform union and intersection operations on sets.
- Understand why sets do not support indexing.
- Apply `if`, `elif`, and `else` conditional statements.
- Validate user input using conditional logic.
- Build a simple performance-category program.

---

## 🛠️ Technologies Used

Python, Google Colab, GitHub

---

# 📚 Topics Covered

## 1. List – Creation, Modification & Access

A Python list is an ordered and mutable collection that can contain multiple elements.

### List Operations

The assignment demonstrates the following operations:

| Operation                                | Method     |
| ---------------------------------------- | ---------- |
| Add an element at the end                | `append()` |
| Insert an element at a specific position | `insert()` |
| Remove an element                        | `remove()` |
| Remove and return an element             | `pop()`    |
| Add multiple elements                    | `extend()` |
| Sort elements                            | `sort()`   |
| Find smallest value                      | `min()`    |
| Find largest value                       | `max()`    |
| Calculate total                          | `sum()`    |

### Accessing List Elements

Python allows elements to be accessed using indexing and slicing.

First Element = print(list[0])

Last Element = print(list[-1])

Elements from index = print(list[x2:x5])

Reverse the list = list.reverse()

## 2. Dictionary – Creation, Modification & Access

A dictionary stores data in key-value pairs.

Python allows Users to access a particular value, add a new value and update an existing value.

### Dictionary Methods

| Method     | Purpose                       |
| ---------- | ----------------------------- |
| `keys()`   | Returns all dictionary keys   |
| `values()` | Returns all dictionary values |
| `items()`  | Returns key-value pairs       |

---

## 3. Sets – Creation & Operations

✅ A set is an unordered collection of unique elements.

✅ Sets automatically remove duplicate values.

✅ Sets use curly brackets { }, similar to dictionaries. However, dictionaries contain key-value pairs, while sets contain only unique values.

✅ Sets do not support indexing. Sets are unordered collections, so elements cannot be accessed using positions such as [0], [1], or [4].

✅ Union combines all unique elements from both sets whereas Intersection returns the elements that are common to both sets.

---

## 4. Conditional Statements – IF, ELIF & ELSE

Conditional statements are used in Python to make decisions based on whether a condition is true or false. They allow a program to execute different blocks of code depending on the situation.

Python mainly uses three conditional statements:

| Method     | Purpose                       |
| ---------- | ----------------------------- |
| if  | executes a block when a condition is true.   |
| elif | checks another condition if the previous if or elif condition was false. |
| else  | executes when none of the preceding conditions are true.       |

**Example:  Performance Category Program**

```
score = int(input("Enter the Score (0 to 10): "))

if score < 0 or score > 10:
    performance_category = "Not Valid"
    print("Invalid score. Please enter a score between 0 and 10.")

elif score > 7:
    performance_category = "Above Average"
    print("Well done, keep up the good work")

elif 4 <= score <= 7:
    performance_category = "Average"
    print("Good effort! Keep practicing, there's room for improvement.")

else:
    performance_category = "Below Average"
    print("Need to improve your performance; consistent practice will lead to better results.")

print("Performance Category:", performance_category)
```

---

## 💡 Key Learnings

Through this assignment, I gained practical understanding of:

🔖 Creating and modifying Python lists.

🔖 Using indexing and slicing to access list elements.

🔖 Performing common list operations.

🔖 Working with dictionaries and key-value pairs.

🔖Using built-in dictionary methods.

🔖 Understanding sets and their unique-element behavior.

🔖 Performing union and intersection operations.

🔖 Understanding why sets cannot be indexed.

🔖 Applying conditional logic using if, elif, and else.

🔖 Validating user input using conditions.

🔖 Building a simple real-world classification program.

---

## 📂 Project Structure

```
Python-Assignment-2/
│
├── Python_Assignment_2.ipynb
└── README.md
```

---

## 🔗 Google Colab Notebook

https://colab.research.google.com/drive/1_ggWAE2tDgbxSuaw9XWiuqKrwpEFrOW4?usp=sharing

---

## ⭐ Conclusion

This assignment strengthened my understanding of Python's fundamental data structures and conditional statements. These concepts form an important foundation for progressing toward Python-based data analysis using Pandas, NumPy, and visualization libraries.
