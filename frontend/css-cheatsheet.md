## CSS Basics
CSS Stands for **Cascading Style Sheets**.
It is used to style the different HTML elements or HTML pages.

### CSS Syntax

```css
p{
    font-size: 20px;    /*Changes font to 20px size*/
    color: blue;        /*Changes font color to blue*/
}
```
`p` is a selector. A selector targets specific HTML element to apply styles to content.

`font-size` and `color` are properties and `20px` and `blue` are values of that properties respectively.

### Adding CSS to HTML

#### Internal CSS
Internal CSS are defined within the `<style>` tag, inside `<head>` tag in an HTML page.

**Example Code :**
```html
<html>
    <head>
        <!-- Internal CSS -->
        <style>
            p{
                font-size: 20px;
                color: red;
            }
            h1{
                color: blue;
                background-color: yellow;
            }
        </style>
    </head>
    <body>
        <h1> This is Heading with blue color</h1>
        <p> This is Paragraph with red color</p>
    </body>
</html>
```

#### External CSS
You can define CSS in different file but should be saved with extension `.css`.
