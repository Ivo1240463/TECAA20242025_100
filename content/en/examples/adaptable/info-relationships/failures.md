---
weight: 1
title: "Failures"
date: 2025-04-04
---

## Failure due to using changes in text presentation to convey information without using the appropriate markup or text

### Example: Using CSS to style the p element to look like a heading

The author intended to make a heading but didn't want the look of the default HTML heading. So they used CSS to style the `P` element to look like a heading and they called it a heading. But they failed to use the proper HTML heading element. Therefore, the Assistive Technology could not distinguish it as a heading.

<pre aria-label="Code example showing CSS styling a paragraph to look like a heading">
&lt;style&gt;
.heading1{
  font-family: Times, serif;
  font-size:200%;
  font-weight:bold;
}
&lt;/style&gt;

&lt;p class=&quot;heading1&quot;&gt;Introduction&lt;/p&gt;
&lt;p&gt;This introduction provides detailed information about how to use this ...&lt;/p&gt;
</pre>

## Failure due to using structural markup in a way that does not represent relationships in the content

### Example: A heading used only for visual effect

In this example, a heading element is used to display an address in a large, bold font. The address does not identify a new section of the document, however, so it should not be marked as a heading.

<pre aria-label="Code example showing a heading used for visual effect to display an address">
&lt;p&gt;Interested in learning more? Write to us at&lt;/p&gt; 
&lt;h4&gt;3333 Third Avenue, Suite 300 · New York City&lt;/h4&gt;
&lt;p&gt;And we'll send you the complete informational packet absolutely Free!&lt;/p&gt;
</pre>
