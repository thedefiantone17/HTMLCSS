# 9. HTML: BLOCK & INLINE



every HTML element consists of a defaul display value depending on the type of element it is. In HTML, there are two display values:
* `block`
* `inline`

## Block-level Elements 

These elements always start on a new line, browsers automatically add space before and after the element.

Block elements take up the full width of the display available.

* Two commonly used block elements: `<p>` and `<div>`

Example of block-level elements:

```
<address> <article> <aside> <blockquote> <canvas> <dd> <div> <dl> <dt> <fieldset> <figcaption>
<figure> <footer> <form> <h1>-<h6> <header> <hr> <li> <main> <nav> <noscript> <ol> <p> <pre> 
<section> <table> <tfoot> <ul> <video>
```

## Inline Elements

An inline element doesn't start from a new line, it only takes up the width/ space that's necessary.

Example: `<span>`

other inline elements:

```
<a> <abbr> <acronym> <b> <bdo> <big> <br> <button> <cite> <code> <dfn> <em> <i> <img>
<input> <kbd> <label> <map> <object> <output> <q> <samp> <script> <select> <small> <span>
<strong> <sub> <sup> <textarea> <time> <tt> <var>
```

`Note:` a block element "CAN" contain an inline element. But!, an inline element can't contain a block element.

### `<div>` Element

The `<div>` element is mostly used as a container for other HTML elements. this element has no required attributes but style, class and id are common.

Example:
```
<div style="background-color:black;color:white;padding:20px;">
  <h2>London</h2>
  <p>London is the capital city of England. It is the most populous city in the United Kingdom, with a metropolitan area of over 13 million inhabitants.</p>
</div>
```

### `<span>` Element

It is an inline container that's used to mark up a part of text or a part of a document. this element also has no required attributes, but style, class and id are common.

Example:
```
<p>My mother has <span style="color:blue;font-weight:bold;">blue</span> eyes and my father has <span style="color:darkolivegreen;font-weight:bold;">dark green</span> eyes.</p>
```
