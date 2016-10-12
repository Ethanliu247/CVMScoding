Numbers in Python, are, well, real numbers.
You *don't* put quotes around the number, or it's a string.
```python
myNum = 4
myNum2 = 2.5
mySum = myNum + myNum2        # Now mySum is 6.5
myDifference = myNum - myNum2 # Now myDifference is 1.5
myProduct = myNum * myNum2    # Now myProduct is 10 
myQuotient = myNum / myNum2   # Now myQuotient is 1.6
myPower = myNum ** myNum2     # ** means ^ (exponent) in python, so this gives 4^2.5 = 32
```

## Input/Output
#### Printing
First, we have the *print statement*. **No**, this doesn't print something out using a printer. It prints text out onto the console. For example, this will print out `Hello User!` onto the console:
```python
print("Hello User!") # Notice how the text is in quotes, this means it is a string.
```
Here is a **non**-example
```python
print(this will not work) # This won't work, because there are no quotes (not a string). 
#This means it is random text that the program might try to interpret as a variable or keywords.
# Also, the not is red, because the program is interpreting it as a statement, not a string.
```
We only need quotes to represent a string though. If we want to put a variable or number in, we don't need quotes. That's right, we can also use variable sand numbers in print statements.
```python
my_creatively_named_variable = 52
  print(52) # prints in console 52
  print(my_creatively_named_variable) # prints in console 52
  # both print statements do the same thing.
  ```
  **Note**: Print statements print on separate lines. If you ran the code above, the output would contain two lines, each saying 52.
  #### input
  Next, we have the *Input* function. When you call the input function, it lets the user type in the console. When the user presses *enter*, it returns a string with what the user typed. Here's an example:
```python
print("What is your name?")
name = input() # the variable "name" is now whatever the user typed in.
```
You might think that using a separate print statement for the question and an input for the answer might get repetitive. IF so, don't worry! You can put the question inside of the input function's parenthesis. Like this:
```python
name = input("What is your name?") # This does the same this as the previous example.
# The variable "name is now whatever the user typed in."
```
**Note**: The `input()` function returns a string, this means that even if the user enter a number, it isn't stored as a number.
So, if you ask for age, you will get the age, but as a string. This means operations would behave differently. 
For example,"1" + "1" = "11".
