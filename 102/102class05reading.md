[Johnston - Reading Notes - Home](https://chrisjohnston1986.github.io/reading-notes/)

# Code 102, _Intro to Software Development_ 
**Class 05 - Reading Notes**

&nbsp;
&nbsp;

# What is CSS?
  
[What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

&nbsp;

> _CSS stands for "Cascading Style Sheets", and is used to style websites with such functions as font sizing and coloring, backgrounds, color and sizing of headings and links, sidebars, and animations._

&nbsp;

## CSS Syntax

&nbsp;

> _CSS rules open with a **selector** from the HTML being styled. For example: headers, paragraphs, and images. The selector is followed by a set of curly braces `{ }`. Inside the braces there are one or more **declarations**. Declarations come as a pair - a **property** and a **value**, separated by a colon followed by a space. The declaration is closed with a semicolon._

h1 { 

    color: red;
    
    font-size: 5em;
    
}

&nbsp;

## CSS Modules and Specifications

&nbsp;

> _CSS has such a large variety of uses that the language is broken into *modules*. Find a list of modules [here](https://developer.mozilla.org/en-US/docs/Web/CSS)._

&nbsp;

**Specifications for different versions of CSS are maintained by the CSS Working Group to ensure that while new features are added, older versions used on older websites still function.**

&nbsp;

## How to Add CSS

&nbsp;

***There are three ways of inserting a style sheet:***


> _External CSS_

> _Internal CSS_

> _Inline CSS_

&nbsp;

**External CSS**

> _External CSS allows the user to keep a separate file for styling which is referenced inside the HTML page in the head section, inside the `<link>` element. An external style sheet can be created in any text editor, and must be saved with a .css extension._

**Internal CSS**

> _Internal CSS is usually used if only one HTML page has a unique style. In this case, the style is defined inside the `<style>` element, inside the head section._

**Inline CSS**

> _An inline style can be used to style a single element, and is added as an attribute to that element in the HTML page. It can contain any CSS property._

&nbsp;

## Cascading Order

&nbsp;

***What happens when there is more than one style specified for an HTML element?***

> _Styles will "cascade" using the following rules, from highest priority to lowest._

&nbsp;

1. Inline style
2. External and internal style (in head section)
3. Browser default

&nbsp;

## Color in CSS

&nbsp;

> _Colors can be added to HTML elements in three different ways:_ 

> _The color name, if it is a fairly common color name._

> _HTML color codes: [Color Picker](https://htmlcolorcodes.com/color-picker/)_

> _RGB values_

&nbsp;
&nbsp;

[https://chrisjohnston1986.github.io/reading-notes/102class05reading](https://chrisjohnston1986.github.io/reading-notes/102/102class05reading.html)
