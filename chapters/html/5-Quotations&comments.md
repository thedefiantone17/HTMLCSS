# 5. HTML: QUOATATIONS & COMMENTS


In this chapter, we will understand the `<blockquote>`,`<q>`, `<abbr>`, `<address>`, `<cite>`, and `<bdo>` HTML elements.

### `<blockquote>` for Quotations

The HTML `<blockquote>` element defines a section that is quoted from another source.

Browsers usually indent `<blockquote>` elements.

### `<q>` Short Quotations

The HTML `<q>` tag defines a short quotation.

Browsers normally insert quotation marks around the quotation.

**Example;**

```
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```

### `<abbr>` abbreviations 

The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".

Marking abbreviations can give useful information to browsers, translation systems and search-engines.

Tip: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element. 

**Example;**

```
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```

### `<address>` contact information quotation

The HTML `<address>` tag defines the contact information for the author/owner of a document or an article.

The contact information can be an email address, URL, physical address, phone number, social media handle, etc.

The text in the `<address>` element usually renders in italic, and browsers will always add a line break before and after the `<address>` element.

**Example;**

```
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

### `<cite>` for work title

The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).

Note: A person's name is not the title of a work.

The text in the `<cite>` element usually renders in italic.

**Example;**

```
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```

### Bi-Directional Override `<bdo>`
BDO stands for Bi-Directional Override.

The HTML `<bdo>` tag is used to override the current text direction.

**Example;**

```
<bdo dir="rtl">This text will be written from right to left</bdo>
```

----

## HTML COMMENT

HTML comments are not displayed in the browser, but they can help document your HTML source code.

**syntax:**

```
<!-- Write your comments here -->
```