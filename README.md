# Learning Python: If Statements with For Loops

This simple Python project is part of my learning journey as I practice using **if statements** in combination with **for loops**.

## Goal

To understand how to:
- Loop through a range of numbers using a `for` loop.
- Use `if`, `elif`, and `else` statements to apply logic to each item in the loop.
- Use the modulo operator `%` to check for divisibility.

## Code

```python
for number in range(1, 101): 
    if number % 5 == 0:
        print("Buzz")
    elif number % 3 == 0:
        print("Fuzz")
    else:
        print(number)
