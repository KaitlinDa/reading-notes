# Read 07 Ten Thousand 2

## Reading Questions
1. Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.
* Variable scope in Python refers to the context in which variabled are defined and accessed. The scope determines the lifespan and visibility of a variable. Local scope is specific to the function in which the variable is defined while global scope refers to variables defined at the top level of a module outside of all functions.
    - Local Scope:

        def my_function():

             local_var = 10  # Local variable

    - Global Scope:

        global_var = 20  # Global variable

            def my_function():


2. How do the global and nonlocal keywords work in Python, and in what situations might you use them?
* Global and nonlocal keywords are used in Python to modify the scope of the variables from within a function. They allow the user to assign values to variables in an outer scope rather than creating a new local variable. Global is used to declare variables defined at the global level and would be useful when you need to modify a variable that exists outside of a function while nonlocal is used to declare variables in the nearest enclosing scope and would be useful in nested functions where the user wants to modify a variable defined in an outer function. 

3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.
* Big O notation allows for a higher level of understanding of an algorithm in terms of time and space complexity. It is a critical took used in context of algorithm analysis. It helps the user make informed decisions based on efficiency.

4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.
* You would use the `random` module to simulate a dice roll in Python. This provides functions for generating random numbers. You would use the `roll_dice` function to simulate a dice roll and the `calculate_probablity` function to roll the dice n number of times. It will calculate the frequency of the target number dividing it by the number of trials. This will give you the probablity.

## Things I want to know more about
If Python can find the probablity in calculations, I bet it can find the probablity in situations. I would like to know how to do this. 