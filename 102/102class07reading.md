[Johnston - Reading Notes - Home](https://chrisjohnston1986.github.io/reading-notes/)

# Code 102, _Intro to Software Development_ 
**Class 07 - Reading Notes**

&nbsp;
&nbsp;

# Programming with JavaScript
  
[What is Javascript?](https://developer.mozilla.org/en-US/docs/Web/JavaScript)


&nbsp;


## Control Flow

[MDN Web Docs](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

&nbsp;

> **Control flow:** the order in which the computer executes statememts in a script. Generally, code executes from top to bottom unless the code encounters a structure that changes the control flow, such as a conditional or a loop.

&nbsp;

_Reminder:_ _**Conditional Structures** include `if`...`else`_

&nbsp;

## JavaScript Functions
Summarized from [W3Schools](https://www.w3schools.com/js/js_functions.asp)

&nbsp;

>A function is a block of code designed to perform a particular task. A JS function is executed when "something" calls it.

**For example:**

> `function myFunction(p1, p2) {`
  `return p1 * p2;   // The function returns the product of p1 and p2`
`}`

&nbsp;

## JavaScript Function Syntax

&nbsp;

> JS functions are defined with the `function` keyword, followed by a name (you choose the name), followed by parentheses `()`. 

> Function names can contain letters, digits, underscores, and `$` signs. Parentheses *may* include parameter names separated by commas: `(parameter1,parameter2)`. The code to be executed by the function is placed inside curly brackets.

> Function **arguments** are the values received by the function when it is invoked.

> In other programming languages, **function** is much the same as **procedure** or **subroutine**

&nbsp;

**Function Invocation**

_The code inside the function will execute when "something" **invokes** the function:_

> When an event occurs (user clicks a button)

> When it is invoked from JS code

> Automatically (self-invoked)

&nbsp;

**Function Return**

>When JS reaches a `return` statement, the function will stop executing. If the function was invoked from a statement, JS will "return" to execute the code after the invoking statement. Functions often compute a **return value**. The return value is "returned" back to the caller
> `let x = myFunction(4, 3);   // Function is called, return value will end up in x`
`function myFunction(a, b) {`
  `return a * b;             // Function returns the product of a and b`
`}`

&nbsp;

### The `()` Operator

> _Accessing a function without () will return the function definition (object) instead of the function result._

&nbsp;

### Local Variables

> _Variables declared within a JS function become **local** to the function, and can only be accessed from within the function. Since local variables are only recognized inside their functions, variables with the same name can be used in different functions. They are created when a function starts, and deleted when the function is complete._

&nbsp;

## JavaScript Operators

More on operators at [W3Schools](https://www.w3schools.com/js/js_operators.asp)

&nbsp;

`=` is the **assignment** operator, _it assignes a value to a variable._

`+`  is the **addition** operator, _it adds numbers._

`*`  is the **multiplication** operator, _it multiplies numbers._

&nbsp;

The `+` operator can also be used to add or "concatenate" strings.



> `let text1 = "John";  let text2 = "Doe";  let text3 = text1 " " + text 2;`

> Result will be `John Doe`


&nbsp;
&nbsp;

[https://chrisjohnston1986.github.io/reading-notes/102class07reading](https://chrisjohnston1986.github.io/reading-notes/102/102class07reading.html)
