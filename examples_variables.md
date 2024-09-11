## Examples: Python Variables

### Naming Your Variables

- Use lowercase 
- No special characters allowed in Python variables
```python
# No special characters allowed in Python variables
# The dollar signs should not be part of the variable name
book_price$$$ = 19.99
```
- Use short, descriptive variable names
    - `fn` and `ln` are short, but not descriptive
    - `first_name` and `last_name` are short and specific and clearer variable names than `fn` and `ln`
- No blank spaces in variable names (use the underscore character instead)
    - NOT OK: student id 
    - OK: student_id
- Variable name can't start with a number
    - NOT OK: 225_order_number
    - OK: order_number225
- Don't use Python keywords (also known as *reserved words*) as variable names
    - Some examples of Python keywords include `print`, `import`, and `return`
    - These words have a special meaning in Python
    - You'll get an error when you run your code if you try to use any of the Python keywords as variable names


### Assigning a Value to a Variable

- In programming, you use the **assignment operator** (=) to assign a value to a variable
```python
# Assigning the value 17 to the variable `age`
# The value 17 is a number (known in programming as numeric data)
age = 17

# Assigning the name Carter to the variable first_name
# Carter is a piece of text (known as a string in programming)
# Use a pair of quotation marks to mark the beginning and end of a string
# You can use a pair of single quotes or double quotes to create your string
first_name = 'Carter'
school = "Bellaire High School" 
```

