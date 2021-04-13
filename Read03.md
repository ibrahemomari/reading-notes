# EXTRA MARKUP 

>

**different versions of HTML:**

|HTML4|HTML5|
|---|---|
|a few elements added in HTML5 |web page authors do not need to close all tags, and new elements and attributes will be introduced|
|had some presentational elements to control the appearance of pages|ensure that users with older browsers will be able to view your pages|


>There are many HTML elements which have been modified or removed from HTML5. Some of them are listed below:

|Element|	In HTML5|
|---|---|
|<applet>|Changed to <object>|
|<acronym>|Changed to <abbr>|
|<dir>|	Changed to <ul>|
|<frameset>|Removed|
|<frame>|Removed|
|<noframes>|Removed|
|<strike>|	No new tag. CSS is used for this|
|<big>|	No new tag. CSS is used for this|
|<basefont>|	No new tag. CSS is used for this|
|<font>|	No new tag. CSS is used for this|
|<center>|	No new tag. CSS is used for this|
|<tt>|	No new tag. CSS is used for this|


>DOCTYPES tell browsers which version of HTML you
are using.
>You can add comments to your code between the
 < !-- and --> markers.
 The id and class attributes allow you to identify
particular elements.
The id and class attributes allow you to identify
particular elements.
The id and class attributes allow you to identify
particular elements.
< meta> tag allows you to supply all kinds of
information about your web page.
Escape characters are used to include special
characters in your pages such as <, >, and ©.

>_
>_

# HTML5 Layout

>HTML5 is introducing a new set of elements that help define the structure of a page.



### Headers & Footers
<header> <footer> 

` <header> <h1>Yoko's Kitchen</h1> <nav> <ul>`
`<li><a href="" class="current">home</a></li>`
`<li><a href="">classes</a></li>`
`<li><a href="">catering</a></li>`
`<li><a href="">about</a></li>`
`<li><a href="">contact</a></li>`
`</ul>`
`</nav>`
`</header>`


> ----------------------------
### Navigation
<nav>

`<nav>`
`<ul>`
`<li><a href="" class="current">home</a></li>`
`<li><a href="">classes</a></li>`
`<li><a href="">catering</a></li>`
`<li><a href="">about</a></li>`
`<li><a href="">contact</a></li>`
`</ul>`
`</nav>`
> ----------------------------
### Articles
<article>

`<article>`
`<figure>`
`<img src="images/bok-choi.jpg" alt="Bok Choi" />`
`<figcaption>Bok Choi</figcaption>`
`</figure>`
`<hgroup>`
`<h2>Japanese Vegetarian</h2>`
`<h3>Five week course in London</h3>`
`</hgroup>`
`<p>A five week introduction to traditional`
`Japanese vegetarian meals, teaching you a`
`selection of rice and noodle dishes.</p>`
`</article>`
`<article>`
`<figure>`
`<img src="images/teriyaki.jpg"`
`alt="Teriyaki sauce" />`
`<figcaption>Teriyaki Sauce</figcaption>`
`</figure>`
`<hgroup>`
`<h2>Sauces Masterclass</h2>`
`<h3>One day workshop</h3>`
`</hgroup>`
`<p>An intensive one-day course looking at how to`
`create the most delicious sauces for use in a`
`range of Japanese cookery.</p>`
`</article>`

> ----------------------------
### Article
<aside>

`<aside>`
`<section class="popular-recipes">`
`<h2>Popular Recipes</h2>`
`<a href="">Yakitori (grilled chicken)</a>`
`<a href="">Tsukune (minced chicken patties)</a>`
`<a href="">Okonomiyaki (savory pancakes)</a>`
`<a href="">Mizutaki (chicken stew)</a`>
`</section>`
`<section class="contact-details">`
`<h2>Contact</h2>`
`<p>Yoko's Kitchen<br />`
`27 Redchurch Street<br />`
`Shoreditch<br />`
`London E2 7DP</p>`
`</section>`
`</aside>`

> ----------------------------
### Sections
<section>

`<section class="popular-recipes">`
`<h2>Popular Recipes</h2>`
`<a href="">Yakitori (grilled chicken)</a>`
`<a href="">Tsukune (minced chicken patties)</a>`
`<a href="">Okonomiyaki (savory pancakes)</a>`
`<a href="">Mizutaki (chicken stew)</a>`
`</section>`
`<section class="contact-details">`
`<h2>Contact</h2>`
`<p>Yoko's Kitchen<br />`
`27 Redchurch Street<br />`
`Shoreditch<br />`
`London E2 7DP</p>`
`</section>`

> ----------------------------
### Heading Groups
<hgroup>


`<hgroup>`
`<h2>Japanese Vegetarian</h2>`
`<h3>Five week course in London</h3>`
`</hgroup>`


> ----------------------------
### Figures
<figure> <figcaption>

`<figure>`
`<img src="images/bok-choi.jpg" alt="Bok Choi" />`
`<figcaption>Bok Choi</figcaption>`
`</figure>`

> ----------------------------
### Sectioning El ements
<div>


`<div class="wrapper">`
`<header>`
`<h1>Yoko's Kitchen</h1>`
`<nav>`
`<!-- nav content here -->`
`</nav>`
`</header>`
`<section class="courses">`
`<!-- section content here -->`
`</section>`
`<aside>`
`<!-- aside content here -->`
`</aside>`
`<footer>`
`<!-- footer content here -->`
`</footer>`
`</div><!-- .wrapper -->`

> ----------------------------
* The new HTML5 elements indicate the purpose of
different parts of a web page and help to describe
its structure.
* The new elements provide clearer code (compared
with using multiple <div> elements).
* Older browsers that do not understand HTML5
elements need to be told which elements are
block-level elements.
* To make HTML5 elements work in Internet Explorer 8
(and older versions of IE), extra JavaScript is needed,
which is available free from Google.
