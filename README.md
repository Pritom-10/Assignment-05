          My Honest Answer


1. What is the difference between var, let, and const?

=> A var variable works inside a function. If it is declared inside { } (like in an if block), it can still be accessed outside that block.

=>A let variable only works inside the block { } where it is declared.

=>const works the same as let in terms of scope. It is also block scoped.

2. What is the spread operator (...)?

=>The spread operator (...) in JavaScript is used to expand or spread elements of an array or object into individual elements.

It is commonly used with arrays, objects, and function arguments.

3. What is the difference between map(), filter(), and forEach()?

=>map() is used to create a new array by transforming each element of the original array.
a.Returns a new array
b.The length of the new array is the same as the original

=>filter() is used to select elements based on a condition.
a.Returns a new array
b.The new array may have fewer elements

=>forEach() is used to loop through an array and perform an action.
a.Does not return a new array
b.Mainly used for side effects like printing or updating values.

4. What is an arrow function?

=>An arrow function is a shorter and modern way to write functions in JavaScript.
It was introduced in ES6

Example--> const add = (a, b) => {
  return a + b;
};

5. What are template literals?

=>Template literals are a modern way to create strings in JavaScript.
They were introduced in ES6 and use backticks ( ) instead of single (' ') or double (" ") quotes.