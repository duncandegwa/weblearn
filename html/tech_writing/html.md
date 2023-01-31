### Getting started with HTML forms
### Prerequisites
 - Have a text editor installed such as notepad, vs code or sublime text.
 - Have some basic concepts of `HTML`.

### Defining HTML Forms
As a developer, you use forms to collect user input data. Forms in `HTML` are defined using the ``<form>` element as illustrated below:

```html
<form>
    form elements
</form>
```

**Form elements** - this is what is contained in a form, for example, input values, checkboxes, radio buttons, submit option, and many others.

### How to accept user input in a HTML form
User input can be of various types such as text, numbers, passwords,email, gender etc. For a `HTML` for to accept user input as text the input element must be defined together with the type attribute.

To accept text as user input the attribute `type=text is used`. Below is an example illustrating text as user input being collected by a HTML Form:

```html
<form>
    Best Car:
    <input type="text">
</form>
```
