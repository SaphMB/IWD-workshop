---
layout: post
title: Getting Started
---

# What is HTML?

HTML (**H**ypertext **M**arkup **L**anguage) is a a basic building block used to build websites. All text and content that you see on the internet is built using HTML.

##  HTML Elements

An element is an HTML building block. There are paragraphs, headings, links, lists, and many more.

HTML elements are usually made up of an opening tag, followed by content then the closing tag.

<tagname>some content</tagname>

# And CSS?
CSS is used alongside HTML to style webpages.

# Webpage structure
The doctype is the first thing that must be defined in an HTML page. It tells the browser which version of HTML the page is using.

<!DOCTYPE html>
The doctype is always followed by the <html> tag, which contains the contents of your page.

<!DOCTYPE html>
<html>
</html>

# HEAD and BODY tags
A HTML page is split into two parts. The head and the body.

The head contains important webpage information like the page title (the text in the browser tab), stylesheets, scripts and meta information.

The body contains webpage content that is visible to the user.

# Exercise
Open the [Online HTML Editor](http://htmleditor.tools/) to a new HTML file. In your new HTML file:

* declare the doctype to be HTML
* open and close a set of `<html></html>` tags
* Within this, create the head and body tags
* Inside your head tag create a `<title>` tag with `Dorothy Vaughn` title.

You should have something that looks like this

```
<!DOCTYPE html>
<html>
  <head>
    <title>Dorothy Vaughn</title>
  </head>
  <body>
  </body>
</html>
```

You shouldn't see anything on your page but this basic configurations will make a huge impact on how information and stying appear on your page.

Up next: [Fonts and text formatting](https://saphmb.github.io/iwd-workshop/2016/05/07/fonts-and-text-formatting.html)