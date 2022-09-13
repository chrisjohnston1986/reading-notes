[Johnston - Reading Notes - Home](https://chrisjohnston1986.github.io/reading-notes/)

# Code 201, _Foundations of Software Development_ 
**Class 03 - Reading Notes**

&nbsp;
&nbsp;

# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

&nbsp;
&nbsp;

## Learn HTML
[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

&nbsp;
&nbsp;

**Ordered** and **Unordered**

&nbsp;
&nbsp;

_**When should you use an unordered list in your HTML document?**_

    -  The <ul> element is for grouping a collection of items that do not have a numerical ordering, and their order in the list is meaningless. 

_**How do you change the bullet style of unordered list items?**_

    -  Typically, unordered-list items are displayed with a bullet, which can be of several forms, like a dot, a circle, or a square. The bullet style is not defined in the HTML description of the page, but in its associated CSS, using the list-style-type property.
 
_**When should you use an ordered list vs an unordered list in your HTML document?**_

    -   The <ol> and <ul> elements both represent a list of items. They differ in that, with the <ol> element, the order is meaningful. To determine which one to use, try changing the order of the list items; if the meaning is changed, the <ol> element should be used, otherwise you can use <ul>.

_**Describe two ways you can change the numbers on list items provided by an ordered list?**_

    Sets the numbering type:
        -   a, for lowercase letters
        -   A, for uppercase letters
        -   i, for lowercase Roman numerals
        -   I, for uppercase Roman numerals
        -   1, for numbers (default)

The specified type is used for the entire list unless a different type attribute is used on an enclosed `<li>` element..

## Learn CSS
[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

&nbsp;
&nbsp;

**The Box Model**

&nbsp;
&nbsp;

_**Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?**_

    -   There once was a young element named Content, Content had 3 friends, Padding, Border, and Margin.  Element and Padding were the closest while border always remain neutral in arguments.  Then there was Margin.  Margin was jealous because she was always on the outside and felt like she could never get close to content because padding was always in the way.  She was cool with border though.  He was a bit of an outsider himself but he never got jealous of padding. Content was content with being the center of attention but was always with Padding there is no where that Content would go that Padding wouldn't.  Margin vehemently hated Padding for this reason. Border would never allow Margin and Padding to fight, he was always there keeping the peace.  To this day if you look at the box model you will see that they have never changed.. 

_**List and describe the four parts of an HTML elements box as referred to by the box model.**_

    -  Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.

    -   Padding box: The padding sits around the content as white space; size it using padding and related properties.

    -   Border box: The border box wraps the content and any padding; size it using border and related properties.

    -   Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.

&nbsp;
&nbsp;

## Learn JS
[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

&nbsp;
&nbsp;

**Arrays**, **Operators and Expressions**, **Conditionals**, **Loops**

&nbsp;
&nbsp;

_**What data types can you store inside of an Array?**_

    - Arrays are basically single objects that contain multiple values, stored in a list, under a singular variable. 

_**Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?**_

    -  You can access individual items in the array using bracket notation and supplying the item's index, in the same way that you accessed the letters in a string.
 
_**List five shorthand operators for assignment in javascript and describe what they do.**_

    -   x = f() Assignment
    
    -   x += f() Addition assignment

    -   x -= f() Subtraction assignment

    -   x *= f() Multiplication assignment

    -   x /= f() Division assignment

_**Read the code below and evaluate the last expression and explain what the result would be and why.**_

    -  when you declare the variable (c) as false, it's a boolean and will result in the entire expression reading false .

_**Describe a real world example of when a conditional statement should be used in a JavaScript program.**_

    - Conditional statements are used to decide the flow of execution based on different conditions. So, if you needed data input to diverge, dependent on user input, conditional statements would facilitate by directing the varying answers into the correct path.

_**Give an example of when a Loop is useful in JavaScript.**_

    -  they repeat an action some number of times and the various loop mechanisms offer different ways to determine the start and end points of the loop.

&nbsp;
&nbsp;

# _Things I want to know more about:_

&nbsp;
&nbsp;

[https://chrisjohnston1986.github.io/reading-notes/201class03reading](https://chrisjohnston1986.github.io/reading-notes/201/201class03reading.html)