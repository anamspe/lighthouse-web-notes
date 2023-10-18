## When creating functions:

* Give your functions precise verb/action based names
* Use `camelCasedNames` (like this one)
* Properly indent the function code
* Functions should focus on a single task: returning a value or causing a side effect. _Break your function into additional smaller functions if you find it doing two or more things._
  * One single task could be to compute and return a value
  * Another single task could be to perform a side effect such as logging a message to the screen

* It is ideal if functions try to avoid reading outer scope variables. If a function needs some information / data, then that data should instead be passed in as a parameter, making it available within the function's _inner (local) scope_.


```javascript
const person = "Martha";

// BAD
const sayHelloBadly = function() {
  console.log(`Howdy, ${person}`);
}
sayHelloBadly(); // Works, but not ideal!

// GOOD
const sayHelloGoodly = function(name) {
  console.log(`Howdy, ${name}`);
}
sayHelloGoodly(person);
```

Always keep these rules in mind :)