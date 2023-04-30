# 7. HTML: Styling

CSS stands for Cascading Style Sheets. It saves a lot of work and can control the layout of multiple web pages all at once.

It is used to format the layout of a webpage. With it, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, etc.

## Using CSS

CSS can be added to HTML documents in 3 ways:

* Inline - by using the style attribute inside HTML elements
* Internal - by using a `<style>` element in the `<head>` section
* External - by using a `<link>` element to link to an external CSS file

### Inline CSS

An inline CSS uses the style attribute of an HTML element.
Example:

```
<h1 style="color:blue;">A Blue Heading</h1>
```

### Internal CSS

An internal CSS is defined in the `<head>` section of an HTML page, within a `<style>` element.

Example:

```
<head>
    <style>
        body {
            background-color: powderblue;
            }

        h1   {
            color: blue;
            }

        p    {
            color: red;
            }

    </style>
</head>
```

### External CSS

An external style sheet is used to define the style for many HTML pages.

To use an external style sheet, add a link to it in the `<head>` section of each HTML page.

Example:

```
// inside html file.
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <h1>This is a heading</h1>
    <p>This is a paragraph.</p>

</body>
</html>
```


```
// inside styles.css

body {
    background-color: powderblue;
}

h1 {
    color: blue;
}

p {
    color: red;
}
```


## CSS properties

Some commonly used CSS properties are as follows:

### CSS color
The CSS `color:` property defines the text color to be used.

Example:
```
color: blue;
```

### Font family
`font-family:` property defines the font to be used.

Example:
```
font-family: verdana;
```

### Font size
In CSS `font-size:` property defines the text size to be used.

Example:
```
font-size: 300%;
```

### border
The `border:` property defines a border around an HTML element.

Example:
```
border: 2px solid powderblue;
```

### Padding
`padding:` defines a padding (space) between the text and the border.

Example:
```
padding: 30px;
```

### Margin
The CSS `margin:` property defines a margin (space) outside the border.

Example:
```
margin: 50px;
```