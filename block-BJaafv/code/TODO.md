1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
In first return is there so proper output will come but in second it will give undefined.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`. // first- number , second- undefined

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why? //71

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why? // yes

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.
  function sayHello(name){
    return "Hello Arya";
   }

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage(); // "Hello, John"
```

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 // 'John'

showMessage(); // Output 2 // 'Hello, John'

alert(userName); // Output 3 // 'John'
```

8. What is a Anonymous Function give example of three functions.
  An anonymous function can also have multiple arguments, but only one expression. We may also declare an anonymous function using the arrow function technique which is shown below: ( () => { // Function Body... } )

9. Can function declaration be a Anonymous Function? Explain
  It is a function that does not have any name associated with it. Normally we use the function keyword before the function name to define a function in JavaScript, however, in anonymous functions in JavaScript, we use only the function keyword without the function name.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
isEven, isOdd
```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
