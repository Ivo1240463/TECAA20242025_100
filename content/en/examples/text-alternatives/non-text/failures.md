---
weight: 1
title: "Failures"
date: 2025-04-04
---

## Failure due to using CSS to include images that convey important information

### Example:

In the following example, part of the content is contained in an image that is presented by CSS alone. In this example, the image `TopRate.png` is a 180 by 200 pixel image that contains the text, "19.3% APR Typical Variable."

### CSS Block
<pre aria-label="Code Example in CSS"><code>p#bestinterest {
   padding-left: 200px;
   background: transparent url(/images/TopRate.png) no-repeat top left;
}
</code></pre>
### When used on this HTML Block
<pre aria-label="Code Example in HTML"><code>&lt;p id="bestinterest"&gt;Where else would you find a better interest rate?&lt;/p&gt;
</code></pre>
## Failure due to having a text alternative that does not include information that is conveyed by color differences in the image
### Example:
A bar chart of sales data is provided as an image. The chart includes yearly sales figures for four employees in the Sales Department. The text alternative for the image says, "The following bar chart displays the yearly sales figures for the Sales Department. Mary sold 3.1 Million; Fred, 2.6 Million; Bob, 2.2 Million; and Andrew, 3.4 Million. The red bars indicate sales that were below the yearly quota". This text alternative fails to provide the information which is conveyed by the color red in the image. The alternative should indicate which people did not meet the sales quota rather than relying on color.