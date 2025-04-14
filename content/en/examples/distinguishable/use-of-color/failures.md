---
weight: 1
title: "Failures"
date: 2025-04-04
---

## Failure due to having a text alternative that does not include information that is conveyed by color differences in the image

### Example:

A bar chart of sales data is provided as an image. The chart includes yearly sales figures for four employees in the Sales Department. The text alternative for the image says, "The following bar chart displays the yearly sales figures for the Sales Department. Mary sold 3.1 Million; Fred, 2.6 Million; Bob, 2.2 Million; and Andrew, 3.4 Million. The red bars indicate sales that were below the yearly quota." This text alternative fails to provide the information which is conveyed by the color red in the image. The alternative should indicate which people did not meet the sales quota rather than relying on color.

## Failure due to creating links that are not visually evident without color vision

### Example: Links with no underlines and similar contrast to body text

<pre aria-label="Code Example in HTML"><code>&lt;head&gt;
  &lt;style&gt;
    p a:link {text-decoration: none}
    p a:visited {text-decoration: none}
    p a:active {text-decoration: none}
    p a:hover {text-decoration: underline; color: red;}
  &lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;
  &lt;p&gt;There are many resources to find out more about the 
     &lt;a href=&quot;rain-in-spain.html&quot;&gt;rain in Spain&lt;/a&gt;.
  &lt;/p&gt;
&lt;/body&gt;</code></pre>
