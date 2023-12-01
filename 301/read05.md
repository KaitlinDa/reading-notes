# Read 05 Putting it all together

## React Docs - Thinking in React

1. What is the <code> single responsibility principle</code>   and how does it apply to components?

    •It is a programming principle aimed at creating flexible and maintainable software. It requires that only one class be changed, making it have only one job. It applies to components in that each component should only do one thing as well.

2. What does it mean to build a ‘static’ version of your application?

• This is a snapshot of your applications content. Interactivity is built later on.

3. Once you have a static application, what do you need to add?

    •It depends on what you want to do with your application. After the static version is complete, you could add your interactivity, API’s, security, and so forth.

4. What are the three questions you can ask to determine if something is state?

    •If any of these questions are yes, then it is NOT a state.

        o Does it remain unchanged over time?

        o Is it passed in from a parent via props?

        o Can you compute to

5. How can you identify where state needs to live?

    •By identifying which component is responsible for changing its own state.

## Higher-Order Functions

1. What is a “higher-order function”?

    •This is a concept in programming that refers to a function that can return a function as a result and take one or many functions as an argument.

2. Explore the<code> greaterThan</code>   function as defined in the reading. In your own words, what is line 2 of this function doing?

    •It is a function in which is takes a single argument and returns it to another function. Line 2 is a noisy function in which the arrow function takes any number using the spread operator.

3. Explain how either <code> map</code>   or <code> reduce</code> operates, with regards to higher-order functions.

    •The <code> map</code> function takes an array and function as arguments providing the function to every element of the array. It then returns a new array containing the function calls of them.


## Things I want to know more about

I am interested how the <code>map</code>  function works internally and the different callback functions that can be passed through.

## Resources

I used all the reading material and ChatGPT for this assignment.
