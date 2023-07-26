# Calculator-Without-GUI-
I am enthusiastic about the Python programming language. I have explained the code I found at¨https://www.programiz.com/python-programming/examples/calculator¨here.
## In this program, we get familiar with the following items.
1)How to define a function:
  
  
  def  function_name (input_parameter1, input_parameter2,..., input_parameterN):
      
      # to do something 
    
      return <answer> 
this program includes four functions:
  ### This function adds two numbers
  def add(x, y):
      return x + y
  
  ### This function subtracts two numbers
  def subtract(x, y):
      return x - y
  
  ### This function multiplies two numbers
  def multiply(x, y):
      return x * y
  
  ### This function divides two numbers
  def divide(x, y):
      return x / y

============================================================================

## Interact with end_users:
1) get a value end_user:
    input_value=iput("please enter a value")
   interact with end_users:

3) display a value to the user
   print("this is a message")

============================================================================
## Define an Infinity loop:
  while true

============================================================================

## Check the conditions: 
In this program we have "if" "elif" to check the conditions.

        if choice == '1':
            print(num1, "+", num2, "=", add(num1, num2))

        elif choice == '2':
            print(num1, "-", num2, "=", subtract(num1, num2))

===========================================================================

## Handel the exception 
in python we use "try" and "except command to handel unexpected values.

the commands in the "try" block are performed by default and the command in the "except" block are perform in a case the program incounter the problem.

        try:
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
        except ValueError:
            print("Invalid input. Please enter a number.")
            continue
