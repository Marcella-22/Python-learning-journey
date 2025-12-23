# Multiplication table generator
Description :
  This project is a simple programme that generates the multiplication for a number entered by the user.It demonstrates the use of loops, user input, variables and basic calculations.
  
  Language:
    Python
    
  How to run: open an online python compiler. copy and paste the code. click the run button.Enter a number when prompted.
  
  Code :
```python
number = int(input("Enter a number: "))

print("Multiplication Table for", number)

for i in range(1, 6):
    result = number * i
    print(number, "x", i, "=", result)

  
