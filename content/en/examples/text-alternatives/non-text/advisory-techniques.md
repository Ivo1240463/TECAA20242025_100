---
weight: 2
title: "Advisory Techniques"
date: 2025-04-04
---


## Using CSS margin and padding rules instead of spacer images for layout design

### Example: Distinguishing navigation landmarks

The following example consists of two parts: the CSS code, which specifies a margin on all sides of the table, and padding for the table cells; and the HTML code for the table, which does not contain spacer images and is not nested inside another table.

### CSS Block:

<pre aria-label="Code Example on CSS"><code>table { margin: .5em; border-collapse: collapse; } 
td, th { padding: .4em; border: 1px solid #000; }
</code></pre>
### HTML Block:
<pre aria-label="Code Example in HTML"><code>&lt;table&gt;
  &lt;caption&gt;Books in the category 'Web development'&lt;/caption&gt;
  &lt;thead&gt;
    &lt;tr&gt;
      &lt;th&gt;Title&lt;/th&gt;
      &lt;th&gt;Author&lt;/th&gt;
      &lt;th&gt;Date&lt;/th&gt;
    &lt;/tr&gt;
  &lt;/thead&gt;
  &lt;tbody&gt;
    &lt;tr&gt;
      &lt;td&gt;How to Think Straight About Web Standards&lt;/td&gt;
      &lt;td&gt;Andrew Stanovich&lt;/td&gt;
      &lt;td&gt;1 April 2007&lt;/td&gt;
    &lt;/tr&gt;
  &lt;/tbody&gt;
&lt;/table&gt;
</code></pre>