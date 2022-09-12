[Johnston - Reading Notes - Home](https://chrisjohnston1986.github.io/reading-notes/)

# Code 201, _Foundations of Software Development_ 
**Class 01 - Reading Notes**

&nbsp;
&nbsp;

# Getting Started
[Getting Started with the Web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web)

&nbsp;
&nbsp;

# Overview

> _Getting acclimated with all things HTML, JS, and CSS._

&nbsp;
&nbsp;

## How the Web Works
[How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

&nbsp;

> **Clients and Servers**

&nbsp;

_**Clients** are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome)._

_**Servers** are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser._

&nbsp;

> _Imagine that the web is a road. On one end of the road is the client, which is like your house. On the other end of the road is the server, which is a shop you want to buy something from. In addition to the client and the server, we also need to say hello to:_

&nbsp;

-   **Your internet connection:** Allows you to send and receive data on the web. It's basically like the street between your house and the shop.

-   **TCP/IP:** Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet. This is like the transport mechanisms that let you place an order, go to the shop, and buy your goods. In our example, this is like a car or a bike (or however else you might get around).

-   **DNS:** Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place (see below). This is like looking up the address of the shop so you can access it.

-   **HTTP:** Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other. This is like the language you use to order your goods.

-   **Component files:** A website is made up of many different files, which are like the different parts of the goods you buy from the shop. These files come in two main types:

    -   **Code files:** Websites are built primarily from HTML, CSS, and JavaScript, though you'll meet other technologies a bit later.

    -   **Assets:** This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.

&nbsp;
&nbsp;

## Website Design and Process
[Website Design and Process.](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

&nbsp;
&nbsp;

***Planning, Sketching, Choosing Your Assets***

&nbsp;
&nbsp;

## JavaScript Basics
[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

&nbsp;
&nbsp;

> _**JavaScript** is a powerful programming language that can add interactivity to a website. It was invented by Brendan Eich._

&nbsp;
&nbsp;

JavaScript itself is relatively compact, yet very flexible. Developers have written a variety of tools on top of the core JavaScript language, unlocking a vast amount of functionality with minimum effort. 

&nbsp;

**These include:**

-   Browser Application Programming Interfaces (APIs) built into web browsers, providing functionality such as dynamically creating HTML and setting CSS styles; collecting and manipulating a video stream from a user's webcam, or generating 3D graphics and audio samples.

-   Third-party APIs that allow developers to incorporate functionality in sites from other content providers, such as Twitter or Facebook.

-   Third-party frameworks and libraries that you can apply to HTML to accelerate the work of building sites and applications.

&nbsp;

## Language Basics Crash Course

&nbsp;

**Variables:** containers that store values.

&nbsp;

- **String:** This is a sequence of text known as a string. To signify that the value is a string, enclose it in single quote marks.

- **Number:** This is a number. Numbers don't have quotes around them.

- **Boolean:** This is a True/False value. The words true and false are special keywords that don't need quote marks.

- **Array:** This is a structure that allows you to store multiple values in a single reference.

- **Object:** This can be anything. Everything in JavaScript is an object and can be stored in a variable. Keep this in mind as you learn.

&nbsp;

**Comments:** snippets of text that can be added along with code. The browser ignores text marked as comments.

&nbsp;
&nbsp;

_**Compose a short poem describing how HTTP sends data between computers.**_

    -   Hello There! I see you! I want to understand you! Password barrier unlocked and now I can step through the door and hear your sweet melody of information. 

_**Describe how HTML, CSS, and JS files are “parsed” in the browser.**_

    -  The browser parses the HTML file first, and that leads to the browser recognizing any <link>-element references to external CSS stylesheets and any <script>-element references to scripts.

    -   As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from <link> elements, and any JavaScript files it has found from <script> elements, and from those, then parses the CSS and JavaScript.

    -   The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.

    -   As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.
 

_**How can you find images to add to a Website?**_

    -   To choose an image, go to Google Images and search for something suitable. Note that most images on the web, including in Google Images, are copyrighted. To reduce your likelihood of violating copyright, you can use Google's license filter. Click on the Tools button, then on the resulting Usage rights option that appears below. You should choose the option Creative Commons licenses.

_**How do you create a String vs a Number in JavaScript?**_

    -   To signify that the value is a string, enclose it in single quote marks. Numbers don't have quotes around them.

_**What is a Variable and why are they important in JavaScript?**_

    -   Variables are containers that store values. Variables are necessary to do anything interesting in programming. If values couldn't change, then you couldn't do anything dynamic, like personalize a greeting message or change an image displayed in an image gallery.

&nbsp;
&nbsp;

# Introduction to HTML
[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

&nbsp;
&nbsp;

## Getting Started with HTML
[Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)

&nbsp;
&nbsp;

## HTML Document Structure
[HTML Document Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)

&nbsp;
&nbsp;

## Metadata in HTML
[Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

&nbsp;
&nbsp;

_**What is an HTML attribute?**_

    -   Attributes contain extra information about the element that won't appear in the content.

_**Describe the Anatomy of an HTMl element.**_

    HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way. 
    
    The anatomy of our element is:

        -   The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.

        -   The content: This is the content of the element. In this example, it is the paragraph text.

        -   The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

_**What is the Difference between article and section element tags?**_

    -   <article> encloses a block of related content that makes sense on its own without the rest of the page (e.g., a single blog post).

    -   <section> is similar to <article>, but it is more for grouping together a single part of the page that constitutes one single piece of functionality (e.g., a mini map, or a set of article headlines and summaries), or a theme.

_**What Elements does a “typical” website include?**_

    -   header: Usually a big strip across the top with a big heading, logo, and perhaps a tagline. This usually stays the same from one webpage to another.

    -   navigation bar: Links to the site's main sections; usually represented by menu buttons, links, or tabs. Like the header, this content usually remains consistent from one webpage to another — having inconsistent navigation on your website will just lead to confused, frustrated users. Many web designers consider the navigation bar to be part of the header rather than an individual component, but that's not a requirement; in fact, some also argue that having the two separate is better for accessibility, as screen readers can read the two features better if they are separate.

    -   main content: A big area in the center that contains most of the unique content of a given webpage, for example, the video you want to watch, or the main story you're reading, or the map you want to view, or the news headlines, etc. This is the one part of the website that definitely will vary from page to page!

    -   sidebar: Some peripheral info, links, quotes, ads, etc. Usually, this is contextual to what is contained in the main content (for example on a news article page, the sidebar might contain the author's bio, or links to related articles) but there are also cases where you'll find some recurring elements like a secondary navigation system.

    -   footer: A strip across the bottom of the page that generally contains fine print, copyright notices, or contact info. It's a place to put common information (like the header) but usually, that information is not critical or secondary to the website itself. The footer is also sometimes used for SEO purposes, by providing links for quick access to popular content.

_**How does metadata influence Search Engine Optimization?**_

    -   Specifying a description that includes keywords relating to the content of your page is useful as it has the potential to make your page appear higher in relevant searches performed in search engines

_**How is the meta HTML tag used when specifying metadata?**_

    -   Metadata is data that describes data. Many <meta> elements include name and content attributes. Two such meta elements that are useful to include on your page define the author of the page, and provide a concise description of the page. As you travel around the web, you'll find other types of metadata, too. A lot of the features you'll see on websites are proprietary creations, designed to provide certain sites (such as social networking sites) with specific pieces of information they can use.


&nbsp;
&nbsp;

# Miscellaneous

&nbsp;
&nbsp;

## How to Start to Design a Website
[How to Start to Design a Website](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding)

&nbsp;
&nbsp;

_**What is the first step to designing a website?**_

    -   project ideation

_**What is the most important question to answer when designing a website?**_

    -   What exactly do I want to accomplish?

&nbsp;
&nbsp;

## Semantics
[Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics)

&nbsp;
&nbsp;

_**Why should you use an h1 element over a span element to display a top level heading?**_

    -   In HTML, for example, the <h1> element is a semantic element, which gives the text it wraps around the role (or meaning) of "a top level heading on your page." Using span will render it to look like a top level heading, but it has no semantic value, so it will not get any extra benefits as described above. It is therefore a good idea to use the right HTML element for the right job.

_**What are the benefits of using semantic tags in our HTML?**_

    -   Search engines will consider its contents as important keywords to influence the page's search rankings (see SEO)

    -   Screen readers can use it as a signpost to help visually impaired users navigate a page

    -   Finding blocks of meaningful code is significantly easier than searching through endless divs with or without semantic or namespaced classes

    -   Suggests to the developer the type of data that will be populated

    -   Semantic naming mirrors proper custom element/component naming


&nbsp;
&nbsp;

## What is JavaScript?
[What is JavaScript?](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

&nbsp;
&nbsp;

_**Describe 2 things that require JavaScript in the Browser?**_

    -   Zooming in or zooming out on an image
    -   Playing audio and video in a web page

_**How can you add JavaScript to an HTML document?**_

    -   You can add JavaScript code in an HTML document by employing the dedicated HTML tag <script> that wraps around JavaScript code. The <script> tag can be placed in the <head> section of your HTML or in the <body> section, depending on when you want the JavaScript to load.


&nbsp;
&nbsp;

# _Things I want to know more about:_

&nbsp;
&nbsp;

[https://chrisjohnston1986.github.io/reading-notes/201class01reading](https://chrisjohnston1986.github.io/reading-notes/201/201class01reading.html)