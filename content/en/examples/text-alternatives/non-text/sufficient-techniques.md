---
weight: 3
title: "Sufficient Techniques"
date: 2025-04-04
---


## Situation A:
If a short description can serve the same purpose and present the same information as the non-text content

### Short text alternative technique - Using aria-label to provide labels for objects

#### Example: Distinguishing navigation landmarks

The following example shows how `aria-label` could be used to distinguish two navigation landmarks in an HTML document, where there are more than two of the same type of landmark on the same page, and there is no existing text on the page that can be referenced as the label.
<pre aria-label="Code Example in HTML"><code>&lt;div role="navigation" aria-label="Primary"&gt;
  &lt;ul&gt;
    &lt;li&gt;...a list of links here ...&lt;/li&gt;
  &lt;/ul&gt;
&lt;/div&gt;
&lt;div role="navigation" aria-label="Secondary"&gt;
  &lt;ul&gt;
    &lt;li&gt;...a list of links here ...&lt;/li&gt;
  &lt;/ul&gt;
&lt;/div&gt;
</code></pre>
## Situation B:
If a short description can not serve the same purpose and present the same information as the non-text content (e.g., a chart or diagram)
### Short text alternative technique - Using aria-labelledby to provide a text alternative for non-text content
#### Example: Providing a short description for a complex graphic
This example shows how to use the aria-labelledby attribute to provide a short text description for a read-only complex graphic of an star rating pattern; the graphic is composed of several image elements. The text alternative for the graphic is the label, visible on the page beneath the star pattern.
<pre aria-label="Code Example in HTML"><code>&lt;div role="img" aria-labelledby="star-id"&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="fullstar.png" alt=""&gt;
  &lt;img src="emptystar.png" alt=""&gt;
&lt;/div&gt;
&lt;div id="star-id"&gt;4 of 5&lt;/div&gt;
</code></pre>

 