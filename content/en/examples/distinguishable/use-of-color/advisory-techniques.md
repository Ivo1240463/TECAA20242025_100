---
weight: 2
title: "Advisory Techniques"
date: 2025-04-04
---

## Using CSS to change the presentation of a user interface component when it receives focus

### Example: Link elements

In this example, mouse and keyboard focus indicators have been applied to the link elements. CSS has been used to apply a background color when the link elements receive focus.

Here is the content to be displayed:
<pre aria-label="Code Example in HTML"><code>&lt;nav id=&quot;main-nav&quot;&gt;
  &lt;ul&gt;
    &lt;li&gt;Home&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/services&quot;&gt;Services&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/projects&quot;&gt;Projects&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/demos&quot;&gt;Demos&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/about-us&quot;&gt;About us&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/contact-us&quot;&gt;Contact us&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;&lt;a href=&quot;/links&quot;&gt;Links&lt;/a&gt;&lt;/li&gt;
  &lt;/ul&gt;
&lt;/nav&gt;</code></pre>
Here is the CSS that changes the background color for the above elements when they receive mouse or keyboard focus:
<pre aria-label="Code Example in CSS"><code>#main-nav a:hover, #main-nav a:active, #main-nav a:focus-visible {
  background-color: #DCFFFF;
  color: #000066;
}</code></pre>
