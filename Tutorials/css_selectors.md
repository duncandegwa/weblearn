### What are selectors in CSS
Selectors are used to locate or find HTML elements based on their name, id, class, attributes, and many more.

### Prerequisites
To follow along with this tutorial it is assumed that you have a basic knowledge of HTML.

Install a text editor such as Vs Code, Sublime text, notepad, or any other text editor you are comfortable width.

### CSS selectors
To understand what selectors are, first, let`s look at the syntax of `CSS`:

```css
p {
    text-align: center;
}
```
In the above `css` syntax `p` is the selector. The braces `{}` defines the declaration block. Inside the braces is the name of the property and its value separated by a colon. In CSS each declaration is ended using a semicolon.

### The `element` Selector
For example, you can select all `<h1>` in a `HTML` page to have a text color `red` and be aligned at the center using the following code:

```css
h1 {
    text-align: center;
    color: black;
}
```
In the above, all headers using the tag `<h1>` will be colored black and center-aligned.

### The `id` Selector
This selector is used to select a specific element based on the `id` attribute of a `HTML` element. Changes will only occur on the element with the `id`.
The hash character (#) followed by the `id` name of the element is used to select the specific element.
Let`s have a look at the code below:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- insert CSS code here -->
    <style> 
        #line1{
            color: blue;
            text-align: center;
        }
    </style><!-- end of CSS code -->
</head>
<body>
<p id="line1">This is a css selector</p> <!-- The css style will on apply to this line -->
<p>Only the paragraph with the id is selected</p>    
</body>
</html>
```
If you run the above code, you will notice that the `css style` will on apply to the paragraph with the `id` `#line1`.

### The `class` Selector
This selector locates `HTML` element with specific class attributes. The dot(.) character followed by the `class` name of the element is used to find elements with a certain class. To understand this better let us examine the code below when run:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- insert CSS code here -->
    <style> 
        .line1{
            color: green;
            text-align: center;
        }
    </style><!-- end of css code -->
</head>
<body>
   <h1 class="line1"> CLASS SELECTOR</h1>

   <p>This selector locates HTML elements with specific class attributes.</p>

   <p class="line1">This is a css selector</p> <!-- The css style will on apply to this line -->


   <h1>CSS style will only affect the named class</h1>    
</body>
</html>
```
When you run the above code, you will find that only specific elements are affected by the `class` selector.

### Grouping selectors
In case you have similar styles defined using different selectors like the one below:
```css
h1 {
    text-align: center;
    color: black;
}
div {
    text-align: center;
    color: black;
}
p {
    text-align: center;
    color: black;
}
```
It is always better to group them to reduce the size of your code. To group them use a comma to separate the selectors as illustrated below:

```css
h1, div, p {
    text-align: center;
    color: black;
}
```
>**NOTE**: The `id` and `class` names should never start with a number.

### Conclusion
In this article we have learned the following:
 - What are selectors?
 - Different types of selectors.
 - How to group selectors

### Further reading
See the following sources for more details on CSS:
 - [CSS for beginners](https://www.w3schools.com/css/)
 - [CSS selectors explained](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Thanks for Reading
Let us connect on [Twitter](https://twitter.com/NdegwaKimunya) and [LinkedIn](https://www.linkedin.com/mwlite/in/duncan-ndegwa-15019021b)
Want to see what I am working on? Check out my [GitHub](https://github.com/duncandegwa)

