# Introductory HTML and JavaScript

## Getting Started

1. HTTP poem

        When a browser has a destination in mind
        It tells DNS "I'm looking for this store"
        DNS says "Of course, here's the address.
        Just talk to the server, he's on the first floor."
        Then the server says "Sure, I've got what you need.
        It's all right here - some assembly required."
        So the browser gets to work, building piece by piece,
        Until the page is complete, just as desired.

2. The browser reads the HTML first, at which point it will notice the references to linked CSS files or scripts. It requests the server for these files, then parses and builds a local version of the DOM tree and the CSSOM structure along with compiling and executing the JavaScript code.

3. Any image can be added to a website if you have the file. To avoid copywrite issues, you can use the usage rights tool in Google's image search to filter by license types.

4. Strings are contained between quotes. Numbers are assigned without the use of quotes

5. A variable is a container that stores data; the fact that they can change means that programs can adapt their outcomes to a variety of inputs.

## Introduction to HTML

1. Attributes are extra information about an html element that is not content

2. An HTML element begins with an opening tag that consists of the name (i.e. type) of element being described and any attributes it has, all contained in angle brackets. Following this is the content and finally a closing tag contained in angle brackets with a slash before the element name.

3. The `<article>` tag is for content that can stand alone, while `<section>` is used to organize a page into sections of similar functionality.

4. Most (if not all) websites will include the tags: `<html>`,  `<head>`, `<title>`, `<meta>`, `<body>`, `<header>`, `<nav>`, `<main>`, `<footer>`, etc.

5. Metadata can give information to help a search engine identify what the page is about. Further, attributes like title and description can be read and displayed by the search engine to help users know what the search result they have been given is before they click on it.

6. The `<meta>` tag is used for any metadata that does not have an appropriate tag. As it is a empty tag, any data must be included as an attribute.

## Miscellaneous

### How to Design a Website

1. The first step to designing a website is planning: defining your goals and determining what steps are needed in order to accomplish them.

2. The most important design question is:

    >[What exactly do I want to accomplish?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Thinking_before_coding#what_exactly_do_i_want_to_accomplish)

### Semantics

1. Using `<h1>` is a semantic tag, whereas `<span>` has no semantic value.

2. Using semantic tags makes it much easier for developers, search engines, and accessibility tools to read what the html is actually doing. It also helps make clear associations with other files, e.g. your CSS stylesheet.

### What is JavaScript?

1. JavaScript is required whenever a site is receiving input from a user to change how the site acts, whether that be storing information they input or reacting to events they perform in the page. Also, it is necessary for other applications to interface with a site through the use of APIs.

2. JavaScript is added to an html document through the use of the `<script>` tag. This can either contain the code that is being run (please no) or a link to a separate `.js` file that contains the code (much preferred).
