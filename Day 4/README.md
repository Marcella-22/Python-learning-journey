# Multiplication table generator
Description : generates the multiplication table for a number upto the the limit entered by the user.It demonstrates the use of loops, user input, variables and basic calculations.
  
  Language:
    Python
    
  How to run: open an online python compiler. copy and paste the code. click the run button.Enter a number when prompted.
  
  Code :
``` python
number = int(input("Enter a number: "))
limit = int(input("Enter the limit:"))
print(f"Multiplication Table for, {number}")

for i in range(limit):
    result=number * i
    print(number,"x",i, "=",result)
```

Output : 

