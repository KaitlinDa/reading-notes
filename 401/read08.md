# Read 08 Ten Thousand 3

## Reading Questions
1. What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
* The basic syntax for Python list comprehension is `my_new_list = [expression for item in iterable_object]`. It is more flexiable and are usually faster methods to use than loops. An example of a comprehensive list  that squares elements is shown below:

        myList=[1,2,3,4,5,6]

        newList[]
        for item in myList:

            square=item**2
            newList.append(square)

    Output:    
    The original list is: [1, 2, 3, 4, 5, 6]

    The output list is: [1, 4, 9, 16, 25, 36]

2. What is a decorator in Python?
* A decorator in Python is a special kind of function used to modify behavior of another function or class. It adds functionality to existing code without altaring the structure.They are mainly used for logging and performance testing.

3. Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.
* Decorators allow for the modification of functions without the need for changing the actual code. They take another function as its argument and returns a new function. Some common uses for them are logging, authorization, and caching. 

    An example of a simple decorator function:
        def my_decorator(func):

            def wrapper():

                print("Something is happening before the function is called.")

                func()

                print("Something is happening after the function is called.")

            return wrapper
            
        def say_whee():

        say_whee = my_decorator(say_whee)

    Output

    >>> say_whee()
    Something is happening before the function is called.

    Whee!

    Something is happening after the function is called.

## Things I want to know more about
I would like to know more about using decorators in Python. 