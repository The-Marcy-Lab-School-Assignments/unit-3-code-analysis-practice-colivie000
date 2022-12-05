# unit-3-code-analysis-practice

Using markdown, identify what the following code block does and explain how the `forEach` function works.

```js
function forEach(arr, action) {
  for (let i = 0; i < arr.length; i++) {
    action(arr[i]);
  }
}

forEach(['a', 'b', 'c'], console.log);
```

**Guiding Questions:**
* What does the code do (what does it print? are any variable reassigned? etc...)
* What are the expected data types for each of the parameters?
* When the function is invoked, what value are provided as arguments?
* How does `forEach` use the provided arguments?

**Key Terms to use**: parameters, arguments, invoke/invocation, iterate, "element of the array", increment,  

<hr>

Your explanation here...

When the code is executed, `a`, `b`, and `c` will get logged to the console. The `forEach` function gets declared with two parameters, `arr` and `action`. Within the function, the `arr` argument gets iterated over and the `action` argument gets invoked during each iteration of the loop. The `forEach` function then gets invoked with `['a', 'b', 'c']` and `console.log` as arguments. The `forEach` function will loop through `['a', 'b', 'c']` and invoke the `console.log` function on each element of the array.
