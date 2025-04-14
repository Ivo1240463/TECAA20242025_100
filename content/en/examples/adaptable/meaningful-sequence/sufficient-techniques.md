---
weight: 2
title: "Sufficient Techniques"
date: 2025-04-04
---

## Ordering the content in a meaningful sequence

### Example:

A web page from a museum exhibition contains a navigation bar containing a long list of links. The page also contains an image of one of the pictures from the exhibition, a heading for the picture, and a detailed description of the picture. The links in the navigation bar form a meaningful sequence. The heading, image, and text of the description also form a meaningful sequence. CSS is used to position the elements on the page.

#### HTML Block:

<pre aria-label="HTML example for ordering content in a meaningful sequence">
&lt;h1&gt;My Museum Page&lt;/h1&gt;
&lt;ul id=&quot;nav&quot;&gt;
  &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 1&lt;/a&gt;&lt;/li&gt;
  &lt;!-- ... --&gt;
  &lt;li&gt;&lt;a href=&quot;#&quot;&gt;Link 10&lt;/a&gt;&lt;/li&gt;
&lt;/ul&gt;
&lt;div id=&quot;description&quot;&gt;
  &lt;h2&gt;Mona Lisa&lt;/h2&gt;
  &lt;div&gt;
    &lt;img src=&quot;img.png&quot; alt=&quot;Mona Lisa&quot;&gt;
  &lt;/div&gt;
  &lt;p&gt;...detailed description of the picture...&lt;/p&gt;
&lt;/div&gt;
</pre>

#### CSS Block:

<pre aria-label="CSS example for styling content in a meaningful sequence">
ul#nav {
  float: left;
  width: 9em;
  list-style-type: none;
  margin: 0;
  padding: 0.5em;
  color: #fff;
  background-color: #063;
}

ul#nav a {
  display: block;
  width: 100%;
  text-decoration: none;
  color: #fff;
  background-color: #063;
}

div#description {
  margin-left: 11em;
}
</pre>

## Making the DOM order match the visual order

### Example:

An online newspaper has placed a navigation bar visually in the top left corner of the page directly below its initial logo. In the source code, the navigation elements appear after the elements encoding the logo.
