# 8. HTML: Linking Attributes

We know that HTML links are hyperlinks, we click on them and jump to another document.
A link isn't always texts, it can be an image or any other HTML document.

## HTML links - syntax

`<a>` tag defines the the hyperlinks.
`syntax:`
```
<a hrf="url">Link text</a>
```
Here, `href` is an attribute which indicates the link's destination.

By default, links will appear as follows in all browsers:

* An unvisited link is underlined and blue
* A visited link is underlined and purple
* An active link is underlined and red

with CSS links can also be styled.

## HTML links - Target Attribute

The target attribute specifies where to open the linked document, it's syntax is as follows:

```
<a href="https://www.google.com/" target="_blank">Visit google!</a>

```

### target attribute values

The target attribute can have one of the following values:


* `_self` - Default. Opens the document in the same window/tab as it was clicked

* `_blank` - Opens the document in a new window or tab

* `_parent` - Opens the document in the parent frame

* `_top` - Opens the document in the full body of the window

## Absolute and Relative URLs

A local link (a link to a page within the same website) is specified with a Relative URL, whereas, a link with a full URL to a web page is absolute URL.

#### Example:

```
// absolute URL
<a href="https://www.w3schools.com/html/default.asp">HTML tutorial</a>

// relative URL
<a href="default.asp">HTML tutorial</a>
```

## Email Link
Use mailto: `inside` the `href` attribute to create a link for mailing.

```
<a href="mailto:someone@example.com">Send email</a>
```
note in a similar way we can link phone numbers.

## images with link

```
    <a href="default.asp">
        <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
    </a>
```
## Link Colors 

By default, a link will appear like this (in all browsers):

* An unvisited link is underlined and blue
* A visited link is underlined and purple
* An active link is underlined and red

```

<!-- Example:  -->

<style>
a:link {
  color: green;
  background-color: transparent;
  text-decoration: none;
}

a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}

a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}

a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>

```

## link bookmarks

with link we can also create bookmarks, To create a bookmark - first create the bookmark, then add a link to it. When the link is clicked, the page will scroll down or up to the location with the bookmark.

`Process:`
* First, use the `id` (read more about it later) attribute to create a bookmark.

```
<h2 id="C4">Chapter 4</h2>
```
* add link to the bookmark within the same page:
```
<h2 id="#C4">Jump to Chapter 4</h2>
```
* we can also add link to a bookmark on another page:

```
<a href="html_demo.html#C4">Jump to Chapter 4</a>
```

