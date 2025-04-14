---
weight: 2
title: "Advisory Techniques"
date: 2025-04-04
---

## Using CSS to control visual presentation of text

### Example: Using CSS font-family to control the font family for text

**The HTML Component:**
<pre aria-label="Code example demonstrating how to use the font-family property in CSS to set the font for text.">
<code>&lt;p&gt;The JavaScript method to convert a string to uppercase is &lt;code&gt;toUpperCase()&lt;/code&gt;.&lt;/p&gt;</code>
</pre>

**The CSS component:**
<pre aria-label="Code example showing how to apply a font-family in CSS.">
<code>&lt;code&gt; { font-family:&quot;Courier New&quot;, Courier, monospace }&lt;/code&gt;</code>
</pre>

### Using the aria-describedby property to provide a descriptive label for user interface controls

**Example: Using aria-describedby to associate instructions with form fields**

Sample form field using `aria-describedby` to associate instructions with form fields while there is a form label.

<pre aria-label="Code example demonstrating the use of aria-describedby to associate instructions with a form field.">
<code>&lt;form&gt;
  &lt;label for=&quot;fname&quot;&gt;First name&lt;/label&gt;
  &lt;input aria-describedby=&quot;int2&quot; autocomplete=&quot;given-name&quot; id=&quot;fname&quot; type=&quot;text&quot;&gt;
  &lt;p id=&quot;int2&quot;&gt;Your first name is sometimes called your &quot;given name&quot;.&lt;/p&gt;
&lt;/form&gt;</code>
</pre>
