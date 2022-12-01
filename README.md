# Debugging in JavaScript
## Learn
- https://www.w3schools.com/js
- https://launchschool.com/exercises#js210_javascript_language_fundamentals
- https://gist.github.com/MarkBennett/1629116
- https://www.dummies.com/article/technology/programming-web-design/javascript/10-common-javascript-bugs-and-how-to-avoid-them-142585/
- https://www.dummies.com/article/technology/programming-web-design/general-programming-web-design/top-10-common-javascript-error-messages-254151/
- https://www.programiz.com/javascript/examples/simple-calculator

## Practice
- https://github.com/BurlingtonCodeAcademy/bug-hunts
- https://github.com/codefellows/debugging-js
- https://github.com/DevMountain/debugging-exercises
- https://github.com/CodeYourFuture/debugging-js-exercises REF: [CodeYourFuture - Debugging](https://codeyourfuture.github.io/syllabus-london/js-core-2/debugging.html)
- https://github.com/jrmykolyn/debugging-practice
- https://app.testgorilla.com/preview/730715

## Tools
- [ESLint for VSCode](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) | https://eslint.org/

## Extra
- [How to use the Debugger in VSCode to debug Node.js Applications - YouTube](https://youtube.com/watch?v=qz68RsESlp8)

## Be careful
| DON'T                         | DO                                            |
| -----------                   | -----------                                   |
| `[1,2,3] === [1,2,3]`         | `JSON.stringify(a1) === JSON.stringify(a2)`   |
| `"Hey ${name}, how are you?"` | `` Hey ${name}, how are you? ``               |
| `arr1 = arr2`                 | `arr1 = arr2.slice()`                         |
- https://davidwalsh.name/multiline-javascript-strings
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Logical_NOT
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals
- https://www.geeksforgeeks.org/reference-and-copy-variables-in-javascript/
- https://www.freecodecamp.org/news/how-to-compare-arrays-in-javascript/
- https://www.w3schools.com/js/js_objects.asp
- https://www.w3schools.com/js/js_function_parameters.asp#:~:text=Try%20it%20Yourself%20%C2%BB-,The%20Arguments%20Object,-JavaScript%20functions%20have
