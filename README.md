# DataScienceCourse5_Assignment1
**Mastering Control Structures, Loops, and Operators in Python — DS PGC Course 5 Assignment 1**

---

## 📘 Assignment Overview
This assignment strengthens core **Python programming skills** through tasks involving **control flow, loops, pattern generation, and operators**.  
You practice `if-elif-else`, nested loops, `break`, `continue`, and `pass`, while creating numeric and star-based patterns and exploring type casting and I/O.

---

## 🧩 Tasks Summary
1. Largest of three numbers  
2. Even or odd check  
3. Print numbers 1–100 skipping multiples of 7  
4. Multiplication table of a given number  
5. Right-angled triangle pattern of `*`  
6. Incremental number pattern (1 → 1234…)  
7. Vowel / Consonant check  
8. Diamond pattern of stars  
9. Reverse digits of an integer  
10. Numeric pyramid (palindromic number pattern)

---

## 🧰 Tools & Techniques
- **Language:** Python 3  
- **Editors/Environments:** Jupyter Notebook / Google Colab / VS Code / IDLE  
- **Key Concepts:**  
  - Conditional statements (`if-elif-else`)  
  - `for` and `while` loops  
  - Nested loops and pattern generation  
  - Loop controls (`break`, `continue`, `pass`)  
  - Type casting and user input  
  - String multiplication and range()  
  - Print formatting with f-strings  

---

## 📂 Files Included
- `DataScienceCourse5QProblemStatement.pdf` — Assignment brief  
- `DataScienceCourse5AssignmentPDFForm.pdf` — PDF solution export  
- `DataScienceCourse5AssignmentPythonNotebook.ipynb` — Jupyter Notebook solution  
- `pythonassignment1.py` — Pure Python script version  

---

## 🧮 Code Samples
```python
# Task 1 – Largest of three numbers
a, b, c = float(input("Enter first: ")), float(input("Enter second: ")), float(input("Enter third: "))
print("Largest number is:", max(a, b, c))

# Task 3 – Skip numbers divisible by 7
for i in range(1, 101):
    if i % 7 == 0:
        continue
    print(i, end=" ")

# Task 8 – Diamond pattern
n = 5
for i in range(1, n + 1):
    print("*" * (2 * i - 1))
for i in range(n - 1, 0, -1):
    print("*" * (2 * i - 1))
```

---

## 🧭 How to Review
1. Open the Jupyter Notebook (`.ipynb`) to view code + outputs inline.  
2. Open `pythonassignment1.py` for the raw code version.  
3. Open the PDF to verify screenshots and outputs.  

---

## 👤 Author
**Utkarsh Anand** — DS PGC Course 5 Assignment 1
