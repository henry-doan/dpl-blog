![Image of DevPoint Labs Logo](https://lh6.googleusercontent.com/oV1O0DyTmC0F1k-6DgyrVy2vLjLnEjZC3wN6sNtwrp8lp313Dt5aOCcl93ENEJ4rYbTCqCmvY27e8D4=w2880-h1312)

# [DevPoint Labs](http://www.devpointlabs.com/) Intro to HTML & CSS

Here are additional resource links

>Link to the [Presentation](https://docs.google.com/presentation/d/1m35mab5hIrNYBk2jVSQr31v7mTb30Sb3A5jWpHb6sjQ/edit?usp=sharing)
>
>Link to the [CodePen](https://codepen.io/nightwing891/pen/mmoJQe?editors=1100)

<br>

## HTML
HTML, or Hyper Text Markup Language, is a programming language that is used to display content for web pages. It is sometimes referred to the skeletons of web pages, providing the foundation of the content for web pages.

### Syntax
Every programming language has different ways to write in the language, this is called **Syntax**. The **Syntax** for the HTML language has and opening and closing tag, with content in between. Opening tags in HTML starts with a less than symbol < then the tag keyword and finally a less than symbol >. Closing tags have the same format but a / before the tag keyword to show that it is an ending tag.

```HTML

<!-- 
    this is a opening tag: 
        <p> 
    
    this is a closing tag:
        </p>
-->

<p>Content goes here</p>

```

Here is a resource that shows all the HTML tags

>Link to the [HTML Tags](https://www.w3schools.com/tags/ref_byfunc.asp)

### HTML Attributes 
HTML elements has many attributes and each element has there own specific attribute. But the most common attributes for HTML elements are Class and Id. 

```HTML
<h1 class="name_of_the_class" id="name_of_the_id"></h1>
```

Classes and ids can be named anything but it can't start with a symbol or a number. The purpose of these attributes is for giving specific classification for elements to be referenced to in another language such as styling, and behavior. 

Classes and ids are not required in writing elements and you can have one or the other or none, it is just best practice to have them and are needed in styling and behaviors.

### HTML Comment
This is an example of a HTML comment:

```HTML
<!-- This is a HTML comment -->
```

Everything in the comment will not run or show up in the browser. Developers uses code comments to take notes on certain pieces of code, or have TODOS, or even to not show a block of code without deleting it. Every programming language has its own commenting syntax.You can also do single line comments or multi-line comments as well.

This is an example of a single line html comment:

```HTML
<!-- This is a single line HTML comment -->
```

This is an example of a multi-line html comment:

```HTML
<!-- 
    This is a 
    multi-line 
    HTML comment 
-->
```

### Header
Anything that is inside of a **Header** tags goes on top of the page and this is usually used for the nav bar for the pages' logo and links to other pages.

```HTML
<header></header>
```

### Footer
Like the Header tag anything that is inside of the **Footer** tags, it will show up on the bottom of the web page. This is used primarily for web pages' footers. 

```HTML
<footer></footer>
```

<br>

## CSS
CSS or Cascading Style Sheet is allows us to style our html elements using rules. CSS can style the sizing, typography, colors and positioning content on the page.

### Syntax
The **Syntax** for the CSS language is a very different than the HTML **Syntax** and it has two parts a **Selector** and a **Declaration**. **Selectors** are used to select elements that you want to manipulate.**Declarations** is how you want to manipulate the element and is encased in { } brackets. Declarations have a **Property** and a **Value** to manipulate the element and ends each manipulation with a semicolon ; .

```CSS

p {
    color: red;
}

/* 
    - p is the selector
    - everything in the { } is the declaration
    - color is a property
    - red is the value
    - ; ends the line of the what you want to declare

    You can have multiple declarations such as below.
 */

h1 {
    padding: 10px;
    color: green;
    font-size: 32px;
}

```

Here is a resource of all the properties you can use on an element:

>Link to the [CSS Properties](https://www.w3schools.com/cssref/)

### CSS Selectors
In CSS, Selectors really depend on what you want to change. 

```CSS
h1 {

}

#id_Name {

}

.class_name {

}
```

You can select certain HTML elements by their class, id or by the element itself. Also be aware that if you select a certain selector in the CSS, all of the elements that the selector will share all the styles. For example, if you have a selector of h1 that means all of the h1 on the page will have the style specified in the CSS. Sometimes you might not want all the h1 ones to have the styles that are why using classes and ids are recommended in for selectors in CSS.

### CSS Comment
This is an example of a CSS comment:

```CSS
/* This is a CSS comment */
```

Like HTMl comment and every comment everything in the comment will not run or show up in the browser. The same purposes as a HTML comments. You can also do single line comments or multi-line comments as well.

This is an example of a single line css comment:

```CSS
/* This is a single line CSS comment */
```

This is an example of a multi-line css comment:

```CSS
/* 
    This is a 
    multi-line CSS 
    comment. 
*/
```

<br>

##TODOS
* [ ] Info on how to use selectors in css
* [ ] Inline styling, styling tags, best practice
* [ ] CSS units of measurements, px, rem, em, %, etc.
* [ ] CSS Colors
* [ ] Explain how files are in a certain language, .html, .css etc.
* [ ] Link live Project
* [ ] Box Model
* [ ] How Pages Connects
* [ ] Have examples of all of the elements
* [ ] Have examples of all of the properties
* [ ] Fonts / Typography
* [ ] HTML Attributes
* [ ] Separators, divs, aside, section etc. 
* [ ] Advance sections of events with css, hover etc.
    