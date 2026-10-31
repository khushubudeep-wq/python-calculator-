# 🧮 Python Calculator
My Day 2 Project - 16 y/o AIML Journey | Goal: Remote Job by 18

Hi! I'm Khushbu from Saintala, Odisha. This is my first Python project on my 730 days journey to become a Remote Data Analyst.

### ✨ Features
- Addition, Subtraction, Multiplication, Division
- User Input Support
- Error Handling (Zero Division)

### 🛠️ Tech Used
- Python 3

### 💻 Code Example
```python

## taking two number and an operator as input from the user.
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
op = input("Enter operator (+, -, *, /): ")

## check the first the first  condition independently use if.
if op == '+':
    print(f"Result: {num1 + num2}")
## check the next condition only if the previous one is false use elif
elif op == '-':
    print(f"Result: {num1 - num2}")
elif op == '*':
    print(f"Result: {num1 * num2}")
elif op == '/':
## Inner check to prevent division zero.
    if num2 == 0:
        print("Error: Division by zero is not allowed!")
## Executes if non of the above operators match.

    else:
        print(f"Result: {num1 / num2}")
else:
    print("INVALID OP")
```
### 🤝 Connect With Me
- [LinkedIn](https://www.linkedin.com/in/khushubu-deep-120200447)
- Location: Saintala, Odisha | Goal: Remote Data Analyst by 18
