# HTML 5 and CSS 3

## HTML 5

- `<!DOCTYPE html>` is a document type declaration. This tells the browser that it is HTML 5.
- `<html>` tags are used to represent the begging and end of the HTML content.
  - `lang="en"` within `<html>` helps a search engine know what language the page is written in.
- The `<head>` section is used for information that the browser and search engines will find useful, for example, the page title, meta data, stylesheets, javascript.
- The `<body>` section is used for the information that is displayed to the user in the browser.

Think of the HTML as a document object model (DOM) -- The tree of all the elements of the HTML document.

<img src="00%20-%20HTML%20and%20CSS/images/dom.png">

### Some example HTML documents:

- <a href="./00 - HTML and CSS/00 - Hello, world.html">Hello, world!</a>
- <a href="./00 - HTML and CSS/01 - Headings.html">Headings</a>
- <a href="./00 - HTML and CSS/02 - Lists.html">Lists</a>
- <a href="./00 - HTML and CSS/03 - Image.html">Image</a>
- <a href="./00 - HTML and CSS/04 - Link.html">Link</a>
- <a href="./00 - HTML and CSS/05 - Table.html">Table</a>
- <a href="./00 - HTML and CSS/06 - Form.html">Form</a>
- <a href="./00 - HTML and CSS/07 - CSS.html">CSS Basics</a>
- <a href="./00 - HTML and CSS/08 - Size.html">Size</a>
- <a href="./00 - HTML and CSS/09 - Font.html">Font</a>
- <a href="./00 - HTML and CSS/10 - Descendant.html">Descendant</a>
- <a href="./00 - HTML and CSS/11 - Hover.html">Hover</a>
- <a href="./00 - HTML and CSS/12 - Responsive.html">Responsive</a>
- <a href="./00 - HTML and CSS/13 - Flexbox.html">Flexbox</a>
- <a href="./00 - HTML and CSS/14 - Grid.html">Grid</a>
- <a href="./00 - HTML and CSS/15 - Bootstrap.html">Bootstrap example</a>

#### Some info about forms

There are several different types of form inputs, such as:
- Inputs for text, passwords, etc
- Radio buttons for selecting an option from several choices
- Checkboxes for selecting n number of choices
- An input associated with a datalist for selecting an option from a dropdown
- And much more!

## CSS

### CSS Specificity

1. Inline (e.g. `<p style="color: red">`)
2. ID (e.g. `<p id="red">`)
3. Class (e.g. `<p class="red">`)
4. Type (e.g. `<style>p { color: red }</style>`)

### CSS Selectors

<img src="00%20-%20HTML%20and%20CSS/images/selectors.png">

### CSS Pseudo Classes

`div:hover` is an example of a pseudo class and activates on hover.

### CSS Responsiveness

This meta tag will help you determine how your page looks on mobile:
`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

Bootstrap is a great example of a responsive CSS framework -- https://getbootstrap.com

#### Flexbox CSS

Useful for responsive design with multiple elements. For example, you can have them wrap around the screen provided. See <a href="./00 - HTML and CSS/13 - Flexbox.html">Flexbox</a> for an example of Flexbox CSS.

#### Grid CSS
Similar to Flexbox CSS. See <a href="./00 - HTML and CSS/14 - Grid.html">Grid</a> for an example of grid positioning.

## SCSS

The term SCSS is an acronym for Sassy Cascading Style Sheets. It is basically a more advanced and evolved variant of the CSS language. Natalie Weizenbaum and Chris Eppstein created it, and Hampton Catlin designed it. It comes with more advanced features- thus often called Sassy CSS.