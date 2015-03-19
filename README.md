## Quick and Easy JavaScript Testing with “Assert”

### Introduction
- There is no assert in JavaScript. 
- Perhaps you're using some library that provides one. 
- Usually assertions are used only in "testing" builds and stripped out of production code.
- There's [talk](http://wiki.ecmascript.org/doku.php?id=strawman:assert) of adding one, but it's at an early stage. 

### Code

- The assert function accepts two parameters:
    - _outcome_: A boolean, which references whether your test passed or failed
    - _description_: A short description of your test.
    


            var assert = function (outcome, description) {
                // code
            };


### References:
1. [stackoverflow - Javascript Assert ](http://stackoverflow.com/questions/15313418/javascript-assert)
2. http://wiki.ecmascript.org/doku.php?id=strawman:assert
