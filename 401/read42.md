# Read 42 Pythonisms

## Reading Questions
1. What are dunder methods in Python, and how do they allow for the customization of built-in behavior in classes? Provide an example of a common dunder method and its purpose.
* Dunder is short for "double underscore". These are special methods recognized by Python's syntax that start and end with double underscores `(__)`. They allow for the customization of built-in behavior in classes, such as arithmetic operations, string representation, and object creation. A common example is the __init__ method, used for initializing newly created objects.

2. Explain the concept of an iterator in Python. How do you create a custom iterator using the iter() and next() methods, and why are they important for enabling iteration in a class?
* An iterator in Python is an object that implements the iterator protocol, which consists of the methods __iter__() and __next__(). To create a custom iterator, a class must implement these two methods. The __iter__() method returns the iterator object itself, and the __next__() method returns the next value from the sequence. This is important for enabling objects of the class to be iterated over with a for loop or other iteration contexts.

3. What is a generator in Python, and how does it differ from a regular function? Illustrate your answer with an example of a generator function using the ‘yield’ keyword.
* A generator in Python is a type of iterable, like lists or tuples, but it generates items on the fly instead of storing them in memory. It is defined using a function but instead of returning a value, it yields a series of values, one at a time, using the yield keyword. This allows for efficient use of memory. An example of this is:

        def count_up_to(max):
            count = 1
            while count <= max:
                yield count
                count += 1

4. Define decorators in Python and explain their primary use case. How can you create and apply a custom decorator to a function or method? Provide a simple example to demonstrate this concept.
* Decorators in Python are a shorthand way to modify the behavior of functions or methods, allowing for code reuse and adding functionality before or after the target function runs. To create and apply a custom decorator, you define a wrapper function that takes a function as its argument and returns another function that enhances the original. An example of this is:

        def my_decorator(func):
            def wrapper():
                func()
            return wrapper

        def say_hello():

        say_hello()

## Things I want to know more about 
I want to know how to better use Python's built-in functions for what I need to do with my coding. 