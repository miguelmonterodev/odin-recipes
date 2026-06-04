# odin-recipes
## Description
Basic recipe website of a main index page which will have links to a few recipes.
## HTML Foundations
HTML and CSS are two languages that work together to create everything that you see when you look at something on the web. HTML is the raw data that a webpage is built out of. All the text, links, cards, lists, and buttons are created in HTML. CSS is what adds style to those plain elements. HTML puts information on a webpage, and CSS positions that information, gives it color, changes the font, and makes it look great! JavaScript is a programming language which makes webpages do things.
### Elements and Tags
HTML (HyperText Markup Language) defines the structure and content of webpages. We use HTML elements to create all of the paragraphs, headings, lists, images, and links that make up a typical webpage.
## CSS Foundations
CSS is the language we use to style a Web page.
- CSS stands for Cascading Style Sheets
- CSS describes how HTML elements are to be displayed on screen, paper, or in other media
- CSS saves a lot of work. It can control the layout of multiple web pages all at once
- External stylesheets are stored in CSS files (style.css)
A CSS rule consists of a selector and a declaration block:
- The selector points to the HTML element you want to style.
- The declaration block contains one or more declarations separated by semicolons.
- Each declaration includes a CSS property name and a value, separated by a colon.
- Multiple CSS declarations are separated with semicolons, and declaration blocks are surrounded by curly braces.
### Selectors
The universal selector will select elements of every type (as in the whole document), hence the name “universal”.
A type selector (or element selector) will select all elements of the given element type, and the syntax is just the name of the element.
Class selectors will select all elements with the given class, which is just an attribute you place on an HTML element.
ID selectors are similar to class selectors. They select an element with the given ID, which is another attribute you place on an HTML element. The major difference between classes and IDs is that an element can only have one ID. It cannot be repeated on a single page and should not contain any whitespace.
Grouping selectors is when all the selectors separated by comas share the same declaration.
Chain selectors. Another way to use selectors is to chain them as a list without any separation.
Descendant combinator. A descendant combinator will only cause elements that match the last selector to be selected if they also have an ancestor (parent, grandparent, etc.) that matches the previous selector.
### Properties
Color and background-color.
Typography basics and text-align.
Image height and width.
And more...
### Adding CSS to HTML
External 
```html
<link rel="stylesheet" href="./style.css">
```
Internal
```html
<head>
    <style>
        selector {property: value;}
    </style>
</head> 
```
Inline
```html
<p style="background-color: red; font-size: 16px;">This is a paragraph</p>
```