The new **HTML5** elements indicate the purpose of
different parts of a web page and help to describe
its structure.

You can see the **HTML** code for this page below. Don't worry about what
the code means yet. We start to look at it in more detail on the next
page. Note that the HTML code is in blue, and the text you see on screen
is in black.

```
<html>
<body>
<h1>This is the Main Heading</h1>
<p>This text might be an introduction to the rest of
the page. And if the page is a long one it might
be split up into several sub-headings.<p>
<h2>This is a Sub-Heading</h2>
<p>Many long articles have sub-headings so to help
you follow the structure of what is being written.
There may even be sub-sub-headings (or lower-level
headings).</p>
<h2>Another Sub-Heading</h2>
<p>Here you can see another sub-heading.</p>
</body>
</html>
````
## DOCTYPEs
Because there have been
several versions of HTML, each
web page should begin with a
**DOCTYPE** declaration to tell a
browser which version of HTML
the page is using (although
browsers usually display the
page even if it is not included).
We will therefore be including
one in each example for the rest
of the book.

``<!DOCTYPE html>``
## Comments in HTML
``<!-- start of introduction -->``
## ID Attribute
The id attribute is known as a
global attribute because it can
be used on any element.
```
<p id="pullquote">Every time I view the sea I feel
a calming sense of security, as if visiting my
ancestral home; I embark on a voyage of seeing.
</p>
```
## Class Attribute
The class attribute on any
element can share the same
value. So, in this example, the
value of important could be
used on headings and links, too.
```
<p class="important">For a one-year period from
November 2010, the Marugame Genichiro-Inokuma
Museum of Contemporary Art (MIMOCA) will host a
cycle of four Hiroshi Sugimoto exhibitions.</p>
```
## Block Elements
```
<ul>
<li>Science: 21 Nov - 20 Feb 2010/11</li>
<li>Architecture: 6 Mar - 15 May 2011</li>
<li>History: 29 May - 21 Aug 2011</li>
<li>Religion: 28 Aug - 6 Nov 2011</li>
</ul>
```
## The `<div>`element 

The `<div>` element allows you to
group a set of elements together
in one block-level box
## summery
* DOCTYPES tell browsers which version of HTML you
are using.
* You can add comments to your code between the
`<!-- and -->` markers.
* The id and class attributes allow you to identify
particular elements.
* The `<div>` and `<span>` elements allow you to group
block-level and inline elements together.

* The `<meta>` tag allows you to supply all kinds of
information about your web page.
* Escape characters are used to include special
characters in your pages such as <, >, and ©.

## Figures
The `<figure>` element should
also contain a `<figcaption>`
element which provides a text
decription for the content of
the `<figure>` element. In
this example, you can see a
`<figure>` has been added inside
the `<article>` element.
```
<figure>
<img src="images/bok-choi.jpg" alt="Bok Choi" />
<figcaption>Bok Choi</figcaption>
</figure>
```
## Process& Design
* SIZE
Larger elements will grab users'
attention first. For this reason it
is a good idea to make headings
and key points relatively large
* COLOR
Foreground and background
color can draw attention to key
messages. Brighter sections tend
to draw users' attention first.
* Style
An element may be the same
size and color as surrounding
content but have a different style
applied to it to make it stand out.

+ You can differentiate between pieces of information
using size, color, and style.
+ You can use grouping and similarity to help simplify
the information you present.

**you can use this website for more infrmation**
[CSS cheat sheet](https://overapi.com/css)