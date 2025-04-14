---
weight: 3
title: "Sufficient Techniques"
date: 2025-04-04
---

## Situation A: 
The technology provides semantic structure to make information and relationships conveyed through presentation programmatically determinable.

### Using ARIA landmarks to identify regions of a page
#### Example: Simple landmarks
The following example shows how landmarks might be added to an HTML document:

<pre aria-label="Code example showing simple ARIA landmarks for identifying regions">
&lt;div role=&quot;banner&quot;&gt;site logo and name, etc. here&lt;/div&gt;
&lt;div role=&quot;search&quot;&gt;search functionality here&lt;/div&gt;
&lt;div role=&quot;navigation&quot;&gt;a list of navigation links here&lt;/div&gt;
&lt;div role=&quot;form&quot;&gt;a sign-up form here&lt;/div&gt;
&lt;div role=&quot;main&quot;&gt;the page&apos;s main content here&lt;/div&gt;
&lt;div role=&quot;region&quot;&gt;a sponsor&apos;s promotion here&lt;/div&gt;
&lt;div role=&quot;complementary&quot;&gt;sidebar content here&lt;/div&gt;
&lt;div role=&quot;contentinfo&quot;&gt;site contact details, copyright information, etc. here&lt;/div&gt;
</pre>

## Situation B: 
The technology in use does NOT provide the semantic structure to make the information and relationships conveyed through presentation programmatically determinable.

### Using text to convey information that is conveyed by variations in presentation of text
#### Example: Indicating new content with boldface and a text indicator
The following example shows a list of accessibility standards. WCAG 2.2 is new, so it is indicated in boldface. To avoid conveying information solely by presentation, the word "(new)" is included after it as well.

<pre aria-label="Code example showing accessibility standards with boldface and text indicator for new content">
&lt;h2&gt;Web Accessibility Guidelines&lt;/h2&gt;
&lt;ul&gt;
  &lt;li&gt;&lt;strong&gt;WCAG 2.2 (New)&lt;/strong&gt;&lt;/li&gt;
  &lt;li&gt;WCAG 2.1&lt;/li&gt;
  &lt;li&gt;WCAG 2.0&lt;/li&gt;
  &lt;li&gt;Section 508&lt;/li&gt;
  &lt;li&gt;JIS X 8341-3&lt;/li&gt;
  &lt;li&gt;...&lt;/li&gt;
&lt;/ul&gt;
</pre>
