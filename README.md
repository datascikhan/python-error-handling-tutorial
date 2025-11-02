


# Python Error Handling Tutorial ⚡🐍

Learn **Python error handling** step by step! This tutorial teaches how to use **try, except, else, finally, and raise** blocks to handle runtime errors effectively. Perfect for **beginners, students, and developers** who want to write **robust and user-friendly Python programs**.

---

## 📌 Table of Contents

1. [Introduction](#introduction)
2. [Exception Handling Overview](#exception-handling-overview)
3. [Basic Try-Except](#basic-try-except)
4. [Try-Except-Else](#try-except-else)
5. [Try-Except-Finally](#try-except-finally)
6. [Handling Multiple Exceptions](#handling-multiple-exceptions)
7. [Raising Custom Exceptions](#raising-custom-exceptions)
8. [Summary Table](#summary-table)
9. [Resources](#resources)

---

## Introduction

**Python Error Handling** ka use tab hota hai jab hum chahte hain ki program **errors ke baad bhi crash na ho**.  
Python me errors ko **exceptions** kehte hain. Error handling se program **robust aur user-friendly** ban jata hai.  

**Keywords:** `try`, `except`, `else`, `finally`, `raise`

---

## Exception Handling Overview

| Keyword   | Description                                           |
| --------- | ----------------------------------------------------- |
| `try`     | Code block jahan error aa sakta hai                   |
| `except`  | Error handle karne ka block                           |
| `else`    | Agar error nahi aata toh execute hota hai             |
| `finally` | Hamesha execute hota hai, chahe error aaye ya na aaye |
| `raise`   | Custom error throw karne ke liye                      |

---

## Basic Try-Except

```python
try:
    x = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")

