## Operators and loops

### Comparison operators

* Used to compare a value in the script to what you expect
* The result is a Boolean: true or false
* It's preferable to use the strict method.

    * Comparison == compares the characters '3' == 3 is true
    * Comparison === compares the characters and data type (strict method) '3' === 3 is false
* Used to evaluate the condition

### Logical operators

* Allow you to compare the results of more than one comparison operator
* Logical And (&&) tests more than one condition - true if both are true, false if either is false
* Logical Or (||) tests at least one condition - true if either is true, false if both are false
* Logical Not (!) takes a single Boolean value and inverts it - reverses the state of an expression
* Logical expressions are evaluated left to right. If evaluation of first condition provides enough info, it doesn't evaluate the second one.

### Loops

* Checks a condition, if true, the code block runs. Then checks the condition again, if it's still true, it runs the code block again. This continues until the condition is false.
* For loop - use if you need to run code a specific number of times

    * Uses a counter as a condition which tells the code how many times to run
    * The counter is made up of three statements: 
    
        * Initialization: `var i = 0;`
        * Condition `i < 10;`
        * Update `i++`
* While loop - use if you don't know how many times the code should run
* Do While loop - similar to the While loop; however it will run the code block at least once even if the condition is false




---
[Home page](https://marlene-rinker.github.io/learning-journal/)