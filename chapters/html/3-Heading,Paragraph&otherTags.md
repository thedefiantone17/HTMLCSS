# 3. HTML: HEADING, PARAGRAPH AND OTHER TAGS 


### Why are Headings important?

Search engines use the headings to index the structure and content of your web pages. Users often skim a page by its headings, so, it is important to use headings to show the document structure.

**Note:** Html Headings are used for headings only and not for decorations(like big, bolde, etc.). Each heading has a default size, However, heading size can be specified with `<style>` attribute using `font-size:` property.

**Example:**

```
<h1>This is heading 1</h1> //most importance
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 3</h4>
<h5>This is heading 3</h5>
<h6>This is heading 3</h6> //least importance
```

### PARAGRAPH `<p>`

`<p>` element efines a paragraph. It always starts on a new line and browsers add white space (margin) before and after a paragraph automatically.



### HTML Display
there are different screen sizes, we can't be sure how the html will be displayed.

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.

The browser will automatically remove any extra spaces and lines when the page is displayed:

**Example:**

```
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>

// will be displayed in a single line.
```

### Horizontal lines `<hr>`

the `<hr>` tag defines a break with a line in an HTML page, aka the horizontal rule line. It is used to separate content (or define a change) in an HTML page.


**Example**

```
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```

### Line break `<br>`

The `<br>` tag defines a line break between the elements in an HTML page. We use `<br>` if we want a line break (a new line) without starting a new paragraph.

**Example**

```
<p>This is<br>a paragraph<br>with line breaks.</p>
```

### Preformatted Text `<pre>`

the `<pre>` tag defines the preformatted text in a web page.  

The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks.

**Example**

```
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```