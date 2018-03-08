---
layout: post
title:  "Styling with CSS"
---

It's time to return to CSS.

# What is CSS?

CSS (**C**ascading **S**tyle **S**heets) is the language used to style websites.

It defines the visual representation of the content. For example colour, margins, borders, backgrounds, position in the page.

CSS works in conjunction with HTML to change website presentation with selectors.

# CSS Selectors

```
body {
  color: hotpink;
}
```

body is a selector

color is a property

hotpink is a value

selector {
  property: value;
}

A group of properties for the given selector is defined within the curly braces

body {
  color: hotpink;
  font-size: 12px;
}

# Getting started with CSS

CSS styling sits within style tags in your code. Add a style tag to the head of your html

```
<head>
  <title>Dorothy Vaughan</title>
  <style type="text/css">

  </style>
</head>
```

Let’s set the font that we want our page to use:

```
body {
   font-family: Helvetica, Arial, sans-serif;
}
```
As we have selected the body element, this change will apply to everything nested within it, the entire contents of our page.

There are a few more properties we can change in the body. Try updating the text `color` and `background-color`.

With CSS, we can update any html element's proprties. Try changing the `list-style` of your `ul` to `none`.

# Using font libraries

The fonts provided by default aren't that exciting, but we can use font libraries to increase our options. Visit Google fonts and choose a font for your page title. Click the `+` icon to select your font. Once selected, open the `Family Selected` window that should have appeared at the bottom of the screen. This provides you with two bits of code, the link to the font library

```
<link href="https://fonts.googleapis.com/css?family=Comfortaa" rel="stylesheet">
``` 

and the CSS properties to update

```
font-family: 'Comfortaa', cursive;
```

Add the link to font library to your `head` outside of the `style` block and update the selcetor for your page title with the new CSS properties.

# Images

Like your text and body, your images `img` can be styled with CSS. 

Try styling your images with `border-radius`.

Checkout what else you can with your images (and other elements) on [w3schools](https://www.w3schools.com/css/css3_images.asp).