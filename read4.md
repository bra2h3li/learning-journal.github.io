
HTML Layout Elements
Websites often display content in multiple columns (like a magazine or newspaper).

HTML offers several semantic elements
that define the different parts of a web page:

<header> - Defines a header for a document or a section
<nav> - Defines a container for navigation links
<section> - Defines a section in a document
<article> - Defines an independent self-contained article
<aside> - Defines content aside from the content (like a sidebar)
<footer> - Defines a footer for a document or a section
<details> - Defines additional details
<summary> - Defines a heading for the <details> element

HTML Tables
The <table> element was not designed to be a
layout tool! The purpose of the <table> element is to displa
y tabular data. So, do not use tables for your page layout! They will bring a mess
into your code. And imagine how hard it will be to redesign your site after a couple of months.


css color
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>

CSS Color Values
In CSS, colors can also be specified using
RGB values, HEX values, HSL values, RGBA values, and HSLA values:

Same as color name "Tomato":

rgb(255, 99, 71)
#ff6347
hsl(9, 100%, 64%)

Styling Links
Links can be styled with any CSS property (e.g. color, font-family, background, etc.).

Example
a {
  color: hotpink;
}


