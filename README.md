# UnittestAutomation

# 🧮 Python Calculator with Unit Tests

This project is a simple Python Calculator implemented with object-oriented programming and tested using the `unittest` module.

It demonstrates:
- Class design
- Basic arithmetic operations
- Exception handling
- Automated unit testing

---

## 📂 Project Structure


- **calculator.py** – Contains the `Calculator` class  
- **test_calculator.py** – Unit tests using Python's `unittest` framework  
- **README.md** – Project documentation  

---

## ⚙️ Calculator Features

The calculator supports the following operations:

- Addition  
- Subtraction  
- Multiplication  
- Division (with zero-division protection)  

---

## 🧪 Running the Tests

Make sure you have Python 3 installed.

Run all tests using:

```bash
python3 -m unittest test_calculator.py

If everything is correct, you will see:

.....
----------------------------------------------------------------------
Ran 5 tests in 0.001s

OK
🚀 How to Use

Example usage:

from calculator import Calculator

calc = Calculator()
print(calc.add(4, 9))        # 13
print(calc.divide(10, 2))    # 5

📦 Future Improvements

Add exponent, square root, modulo operations

Add command-line interface

Add UI with Tkinter

Convert into a Python package
