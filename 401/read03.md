# Read 03 FilelO & Exceptions

## Reading Questions
1. What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?
* The purpose of the 'with' statement when opening a file in Python is used is to make sure file streams are properly cleaned up after their use. This statement closes a file allowing for cleaner code and helps in handling any errors you may encounter. It assigns a part into a variable within the block. 

2. Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.
* The differences between the two is that‘read()’ reads the entire content of the file in a string while ‘readline()’ reads only one line from the file each time it is called. You would use ‘read()’ when you want to grab everything from the file while you want to use ‘readline()’ when you want context one line at a time. 

3. Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.
* Exception handling in Python involves managing errors that come up when a program is executed. Python allows you to catch these errors during the execution and to fix them without halting the program. The ‘try’block allows you to test a block of code for errors, ‘except’ is where you handle these errors, and ‘finally’ allows you to execute the code regardless of the other blocks. 

try:

    result = 10 / divisor
except ZeroDivisionError:

    print("You can't divide by zero!")
else:

    print("The result is", result)
finally:

    print("This is the 'finally' block, executed after 'try' and 'except'.")


## Things I want to know more about
I want to become more familiar with error handling in Python. It seems that there are alot of different trouble shooting methods that are extremely useful in this language. 