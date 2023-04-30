# 4. HTML: STYLES & FORMATTING 


## HTML Styles

A `style=""` attribute in an element is used to add styles to an element like font, size, color, etc.

**syntax**

```
<tagname style="property:value;">
```
The property here, is a CSS property (which we will study later), the value is a CSS value.

### Background color `background-color:`

this property basicall helps in defining the background color for an HTML element.

**Example**

```
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>

//Here, we're changing the background color of the body to "Powder blue".
```

### Text color `color:`

The CSS `color` property defines the text color for an HTML element.

**Example**

```
<h1 style="color:blue;">This is a heading</h1>
```

### Fonts `font-family:`

This element defines the font to be used for an HTML element.

**Example**

```
<p style="font-family:courier;">This is a paragraph.</p>
```

### Text Size `font-size:`

the `font-size:` property defines the text size for an HTML element.

```
<h1 style="font-size:300%;">This is a heading</h1>
```

### Text alignment `text-align:`
The CSS text-align property defines the horizontal text alignment for an HTML element.

**Example**

```
<h1 style="text-align:center;">Centered Heading</h1>
<p style="text-align:center;">Centered paragraph.</p>
```

---

## HTML Formatting

HTML contains several elements for defining text with a special meaning and display special types of text such as:

* `<b>` - bold text
* `<strong>` - Important text
* `<em>` - Emphasized text
* `<mark>` - Marked text
* `<small>` - Smaller text
* `<del>` - Deleted text
* `<ins>` - Inserted text
* `<sub>` - Subscript text
* `<sup>` - Superscript text

**Example**

```
<!-- bold text -->
<b>This text is bold</b>

<!-- important text -->
<strong>This text is important!</strong>
<!-- italics / alternate voice or mood -->
<i>This text is italic</i>

<!-- emphasised text -->
<em>This text is emphasized</em>

<!-- smaller text -->
<small>This is some smaller text.</small>

<!-- marked text -->
<p>Do not forget to buy <mark>milk</mark> today.</p>

<!-- deleted text -->
<p>My favorite color is <del>blue</del> red.</p>

<!-- inserted text -->
<p>My favorite color is <del>blue</del> <ins>red</ins>.</p>

<!-- Subscript -->
<p>This is <sub>subscripted</sub> text.</p>

<!-- Superscript -->
<p>This is <sup>superscripted</sup> text.</p>
```
