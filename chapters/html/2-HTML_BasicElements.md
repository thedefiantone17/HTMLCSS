
# 2. HTML BASIC ELEMENTS



All HTML documents must start with a document type declaration: **`<!DOCTYPE html>`**

The HTML document itself begins with **`<html>`** and ends with **`</html>`**

the basic elements in a HTML document are:

* HTML Headings `<h>`
* HTML Paragraphs `<p>`
* HTML Links `<a>`
* HTML Images `<img>`


## Headings 
HTML headings are defined with `<h1>` to `<h6>` tags, where `<h1>` tag determines the most important Heading and `<h6>` tag dwfinws the least important Heading.

Example:

```
<h1>This is heading 1</h1> //most importance
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 3</h4>
<h5>This is heading 3</h5>
<h6>This is heading 3</h6> //least importance
```

## Paragraphs
They're defined by `<p>` tags.

Example:

```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

## Links
HTML links are defined with the `<a>` tag, it also has a few components like `href` which determines the path where the user is redirected.

Example:

```
<a href="https://www.google.com">This is a link</a>
```

## Images

HTML images are defined with the `<img>` tag.

It's components are:
* Source file`(src)` : shows the source / path of image
* Alternate text`(alt)` : displays the alternate text that's going to appear when image isn't visible
* Width`(width)` : sets width of image
* Height`(height)` : sets height of image

Example:

```
<img src="https://cdp.azureedge.net/products/USA/SU/2022/MC/SUPERSPORT/HAYABUSA/50/ETALLIC_MATTE_SWORD_SILVER_-_CANDY_DARING_RED/2000000001.jpg" alt="Hayabusa.com" width="150" height="100">
```

## HTML Source Code

View HTML Source Code:
* Right-click in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

Inspect an HTML Element:
* Right-click on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.