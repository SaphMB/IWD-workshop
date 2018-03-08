---
layout: post
title: Fonts and text formatting
---

During this workshop, you'll be updating and formatting a webpage about [Dorothy Vaughan](https://www.nasa.gov/content/dorothy-vaughan-biography). The basic text you'll be editing can be found [here](https://saphmb.github.io/iwd-workshop/dorothy/).

# Headings
Headings are used to style and format text in web pages and come in six sizes and are declared using `<h#>` `</h#>` tags that wrap around the text of the heading.

# `<h1>Heading</h1>`

## `<h2>Heading</h2>`

### `<h3>Heading</h3>`

#### `<h4>Heading</h4>`

##### `<h5>Heading</h5>`

###### `<h6>Heading</h6>`

A `h1` defines the most important heading whereas a `h6` defines the least important.

## Exercise

In your HTML Editor, within the `<body> </body>` tags add a title to your website about Dorothy Vaughan and wrap it in an appropriate heading. Below your new heading, copy Dorothy's bio from [here](https://saphmb.github.io/iwd-workshop/dorothy/).

This should give something that isn't that easy to read. To make it easier on the eye, add appropriate headings to each sub-heading about Dorothy's life.

# Paragraphs

Although the Headings have helped, there are still large chunks of text that aren't nice to look at or pleasant to read. Putting content into a `<p>` tag will break your text up into paragraphs, making the content of your page easier to read for the user. For example:

```
<p>Vaughan was born September 20, 1910 in Kansas City, Missouri, the daughter of Annie and Leonard Johnson. Her family moved to Morgantown, West Virginia, where she graduated from Beechurst High School in 1925. Receiving a full-tuition scholarship, she graduated at the age of 19 with a B.A. in mathematics in 1929 from Wilberforce University, a historically black college located in Wilberforce, Ohio. In 1932 she married Howard Vaughan. The couple moved to Newport News, Virginia where they had six children; Ann, Maida, Leonard, Kenneth, Michael and Donald.</p>
```

## Exercise
Use `<p> </p>` tags break the text down into paragraphs.

# Lists
There are two types of lists that can included on a webpage, ordered and unordered. An unordered list `<ul>` is defined with bullets whilst an ordered list `<ol>` uses a numbered sequence.

In our section on FORTRAN, Let’s create a new `<h4>` and list some of the other programming languages FORTRAN went on to influnce:

```
<h4>FORTRAN influenced</h4>
<ol>
  <li>ALGOL 58</li>
  <li>BASIC</li>
  <li>Chapel</li>
  <li>CMS-2</li>
  <li>PL/I</li>
  <li>PACT I</li>
  <li>MUMPS and Ratfor.</li>
  <li>Ratfor</li>
</ol>
```

If you wanted to make this an unordered list, what would you change? How could you check it worked? Try it, then change your list back to an ordered list.

# Formatting text

We can also emphasise or make text important. For emphasis we use `<em>` and for importance `<strong>`

Let's add some emphasis to Dorothy's quote about working at Langley during the Space Age.

Up next: [Images and Styling]()
