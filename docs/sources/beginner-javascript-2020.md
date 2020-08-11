# Beginner Javascript (2020)

_Tags: #website_

## Info

- Source: https://beginnerjavascript.com/
- Author: Wes Bos
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
    - It is also possible to create variables on the fly by having \`Hello ${newVariableName};\`
  - Parameteres and arguments
    - [Cheat sheet](https://github.com/wesbos/beginner-javascript/blob/master/function-definition.jpg)
    - *Parameters* are the placeholders of the function
      - Parameters from different functions can use the same name, they won't overwrite each other.
      - Default value of a parameter: `function hey(name = 'Clara') { ... }`
        - If there are multiple default parameters in one function, the argument that have to default must be marked `undefined`
    - *Arguments* are actual values replacing the parameters when the function is invoked

