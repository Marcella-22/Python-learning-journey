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
<img width="1366" height="768" alt="Screenshot 2026-03-14 09 36 52" src="https://github.com/user-attachments/assets/af9d50c4-ee4c-4b66-a8d7-fc61f6f800be" />


