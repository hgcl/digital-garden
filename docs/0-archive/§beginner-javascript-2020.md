---
tags: [archive, reference, class]
source: https://beginnerjavascript.coos
author: Wes Bos
dateretrieved:
---

# Beginner Javascript (2020)

## Info

- Topics:
- Synopsis: Learn Javascript basics

## Notes

- Module 1
  - How to comment out?
    - alt + shift + a
    - cmd + /
  - Where run javascript?
    - In `<body><script src="./functionfile.js"></script></body>`
  - 3 types of variables
    - `var first = "cl";` variable declaration statement (function scoped)
    - `let age = 300;` (block scoped)
    - `const cool = true;` use first, constant variable that cannot be changed -> ex: API key (block scoped)
    - It is also possible to create variables on the fly by having \`Hello \${newVariableName};\`
- Module 2
  - Parameteres and arguments
    - [Cheat sheet](https://github.com/wesbos/beginner-javascript/blob/master/function-definition.jpg)
    - _Parameters_ are the placeholders of the function
      - Parameters from different functions can use the same name, they won‘t overwrite each other.
      - Default value of a parameter: `function hey(name = 'Clara') { ... }`
        - If there are multiple default parameters in one function, the argument that have to default must be marked `undefined`
    - _Arguments_ are actual values replacing the parameters when the function is invoked
  - How to declare a function
    - Regular way: `function helloYay(hey) { ... };`
    - Function expression: `const helloYay = function (hey) { ... };`
      - Uses the anonymous function: `function (hey) { ... };`
      - These functions are not hoisted (brought to the top)
    - Arrow function: `const inchToCm = (inches) => inches * 2.54;`
      - Uses a shortened anon function, `=>` replaces `function`
      - Implicit return to fit one line
      - `()` of parameters can be removed if only one parameter
    - IIFE (Immediately Invoked Function Expression)
      - `(function() { console.log('Hello there'); }) ();`
    - Methods
      - Function that lives inside of an object
      - e.g. console.log(‘hey’)
        - log is a function
        - console is an object
      - `const wes = { name: 'Bos', sayHi: function() { ... } }`
        - I can call the method `wes.sayHi()`
        - Usually use method shorthand: `sayHi()` instead of `sayHi: function()`
    - Callback function
      - “When someone clicks something, run this” or “When duration passed, run this”.
