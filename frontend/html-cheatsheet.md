# HTML Cheatsheet

- [HTML Cheatsheet](#html-cheatsheet)
  - [HTML Basics](#html-basics)
    - [Boilerplate Code](#boilerplate-code)
    - [HTML Comments](#html-comments)
    - [Headings Tag `<h1>` `<h6>`](#headings-tag-h1-h6)
    - [Paragraph Tag `<p>`](#paragraph-tag-p)
    - [Pre-Formatted Text Tag `<pre>`](#pre-formatted-text-tag-pre)
    - [Code Tag `<code>`](#code-tag-code)
    - [Division Tag `<div>`](#division-tag-div)
    - [Span Tag `<span>`](#span-tag-span)
  - [Text Formatting](#text-formatting)
    - [Bold Text Tag `<b>`](#bold-text-tag-b)
    - [Italic Text Tag `<i>`](#italic-text-tag-i)
    - [Subscript Text Tag `<sub>`](#subscript-text-tag-sub)
    - [Superscript Text Tag `<sup>`](#superscript-text-tag-sup)
    - [Ordered List](#ordered-list)
  - [HTML Hyperlinks](#html-hyperlinks)
  - [HTML Media](#html-media)
    - [Image Tag `<img>`](#image-tag-img)
    - [Video Tag `<video>`](#video-tag-video)
    - [Audio Tag `<audio>`](#audio-tag-audio)
  - [HTML Table](#html-table)
  - [HTML Forms](#html-forms)
    - [Form Tag `<form>`](#form-tag-form)
    - [Input Tag `<input>`](#input-tag-input)
    - [Radio Buttons](#radio-buttons)
    - [Checkbox Buttons](#checkbox-buttons)
    - [Buttons](#buttons)
  - [HTML Classes & ID](#html-classes--id)
    - [HTML Class Attribute](#html-class-attribute)
    - [HTML ID Attribute](#html-id-attribute)


## HTML Basics

**HTML** stands for *Hyper Text Markup Language*
**HTML** is used for creating web pages and websites.

### Boilerplate Code

```html
<html>
    <head>
        <title> Hello </title>
    </head>
    <body>
    </body>
</html>
```

The `<html>` tag is used to define an HTML document.
The `head` tag contains meta information about HTML page.
The `<title>` tag is used to define Title for HTML page.
The `<body>` tag everything we need in html page like images, text, links, tables and many more.

---

### HTML Comments
Comments are piece of code ignored by browsers. Comments are used to indicate sections or to keep notes.

```html
<!-- This is comment and will be ignored by browser -->

<h1> Hello </h1>

<!-- This is the example of 
     multi line comment
     Multiple line comment 2 -->
```
---

### Headings Tag `<h1>` `<h6>`

HTML heading ranges from `<h1>` to `<h6>` tags.

**Live Example**
```html
    <h1>Level 1 Heading</h1>
    <h2>Level 2 Heading</h2>
    <h3>Level 3 Heading</h3>
    <h4>Level 4 Heading</h4>
    <h5>Level 5 Heading</h5>
    <h6>Level 6 Heading</h6>
```
<h1>Level 1 Heading</h1>
<h2>Level 2 Heading</h2>
<h3>Level 3 Heading</h3>
<h4>Level 4 Heading</h4>
<h5>Level 5 Heading</h5>
<h6>Level 6 Heading</h6>

---

### Paragraph Tag `<p>`

`<p>` tag is used to structure your text into different paragraphs.

```html
<p> This is the paragraph </p>
<p> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque </p>
```
---

### Pre-Formatted Text Tag `<pre>`

`<pre>` tag is defines pre-formatted text.

```html
<pre> Hello World </pre>
<pre> This is pre-formatted text example </pre>
```
**OUTPUT**
<pre>Hello World 
This is pre-formatted text example </pre>

---

### Code Tag `<code>`

Code tag is used to define code block.

```html
<code>
    print("Hacking NASA using HTML...")
    print("Hacking Failed Successfully")
</code>
```
**OUTPUT**

```py
print("Hacking NASA using HTML...")
print("Hacking Failed Successfully")
```
----

### Division Tag `<div>`

`<div>` tag is used to make division or block in document.

```html
<div>
    <p> This is example of div tag</p>
</div>
```

---

### Span Tag `<span>`
`<span>` tag is used to define inline block.

```html
<span> Inline block example </span>
```
## Text Formatting

### Bold Text Tag `<b>`

`<b>` tag is used to bold the text.

```html
<b> This text is bold </b>
```

### Italic Text Tag `<i>`

```html
<i> This text is Italic </i>
```

### Subscript Text Tag `<sub>`
`<sub>` tag is used to define subscript text. Subscript text appears half a character below the normal line

```html
CO<sub>2</sub>
H<sub>2</sub>O
This is <sub>Subscript</sub>Text
```
**OUTPUT**

CO<sub>2</sub>
H <sub>2</sub>O
This is <sub>Subscript</sub>Text

---

### Superscript Text Tag `<sup>`

`<sup>` tag is used to define text in power position.Superscript text appears half a character above the normal line.

```html
x<sup>2</sup>
x<sup>a+b</sup>
````
**OUTPUT**

x<sup>2</sup>
x<sup>a+b</sup>

---

## List
### Unordered List


Unordered list are declared using `<ul>` tag.

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ul>
```

**OUTPUT**
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
</ul>


### Ordered List
Ordered list are declared using `<ol>` tag.
```html
<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JS</li>
</ol>
```
**OUTPUT**
<ol>
    <li>HTML</li>
    <li>CSS</li>
    <li>JS</li>
</ol>

---

## HTML Hyperlinks

`<a>` tag used to define a hyperlink. 

```html
<a href="https://github.com">Link to GitHub</a>
```
`href` specifies the path/link to website or another page.

**OUTPUT**
<a href="https://github.com">Link to GitHub</a>

---

## HTML Media

### Image Tag `<img>`

`<img>` tag is used to embed image in document.

```html
<img src="dummy.jpg" alt="This is Image">
```
`src` specifies the path of image.

<br>

### Video Tag `<video>`
`<video>` tag is used to embed video in document.

```html
<video width="300" height="400" controls>
    <source src="dummy.mp4" type="video/mp4">
    Video Not Supported!
</video>
```

Text between Tag is only displayed when video is not supported in the document.

### Audio Tag `<audio>`
`<audio>` tag is used to embed audio in document.

```html
<audio>
    <source src="dummy.mp3" type="audio/mpeg">
    Audio Not Supported!
</audio>
```
---

## HTML Table

Table is used to represent data in tabular form. Table consist of rows and columns.

```html
<table border="2">
        <thead>
            <tr>
                <th>Sr No.</th>
                <th>Name</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>ABC</td>
            </tr>
            <tr>
                <td>2</td>
                <td>XYZ</td>
            </tr>
            <tr>
                <td>3</td>
                <td>PQR</td>
            </tr>
        </tbody>
    </table>
```

- `<th>` is used to give heading to column (TH stands for Table Heading).
- `<tr>` is used to define row in table (TR stands for Table Row).
- `<td>` is used to enter data in row/column.

OUTPUT:

| Sr No. | Name |
| ------ | ---- |
| 1      | ABC  |
| 2      | XYZ  |
| 3      | PQR  |


---

## HTML Forms
HTML forms are used to collect the user input. 

### Form Tag `<form>`

To create form we use the `<form>` tag.

```html
<form>
    <!-- Another form tags -->
</form>
```

### Input Tag `<input>`

```html
<input type="text">         <!-- Displays a single line text input field -->
<input type="radio">        <!-- Displays a radio button -->
<input type="checkbox">     <!-- Displays a checkbox button -->
<input type="button">       <!-- Displays a Simple Clickable button -->
<input type="submit">       <!-- Displays a button to submit form-->
```

### Radio Buttons
Radio buttons are used to choose one options out of many.

```html
Choose Age:
<input type="radio" name="age" value="0-18"> 0 - 18
<input type="radio" name="age" value="19-40"> 19 - 40
<input type="radio" name="age" value=">= 41"> >= 41
```
Choose Age:
<input type="radio" name="age" value="0-18"> 0 - 18
<input type="radio" name="age" value="19-40"> 19 - 40
<input type="radio" name="age" value=">= 41"> >= 41

### Checkbox Buttons
Checkbox buttons are used to choose many options together.

```html
Choose Something:
<input type="checkbox" name="something" value="Data 1"> Data 1
<input type="checkbox" name="something" value="Data 2"> Data 2
<input type="checkbox" name="something" value="Data 3"> Data 3
```
<input type="checkbox" name="something" value="Data 1"> Data 1
<input type="checkbox" name="something" value="Data 2"> Data 2
<input type="checkbox" name="something" value="Data 3"> Data 3

### Buttons

```html
<input type="button" value="Click Me">
```
<input type="button" value="Click Me">

---

## HTML Classes & ID

### HTML Class Attribute
The `class` attribute is used to point a class name in a CSS style and JavaScript. Using class name we can add our own custom CSS style like changing font, colors and many more.

```html

<div class="vehicles">
    <p> This is Bike </p>
</div>

<div class="vehicles">
    <p> This is Car </p>
</div>

<div class="vehicles">
    <p> This is Bus </p>
</div>
```

Applying Our own CSS:
```css
.vehicles{
    color: red;
    font-size: 20px;
}
```

*Note:*
- Class name is case sensitive.
- Class attribute can be used on any HTML tag.
- Classes are used by CSS and JS to access specific element.

### HTML ID Attribute
The HTML `id` attribute is used to specify a unique id for an HTML element.

```html
<div id="text">This is Text </p>
```
Own CSS:
```css
#text{
    font-size: 15px;
    color: blue;
}
```