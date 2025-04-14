---
title: Meaningful Sequence
linkTitle: 6- Meaningful Sequence
---

## Meaningful Sequence

In some web content, the order in which information is presented is essential for understanding its meaning. This is especially important for users relying on screen readers, who experience content linearly.

If the visual layout of a page suggests a specific reading sequence, that same sequence must be programmatically determinable so it can be conveyed accurately by assistive technologies.

## General Rule

When the sequence of content affects its meaning, a correct reading order must be:

- Programmatically determined, so it can be accessed by screen readers and other assistive tools.

This ensures that users can perceive the content in the intended order, maintaining clarity and comprehension.

## Specific Situations

### Multi-Column Layouts
If content is presented in multiple columns (side-by-side text), ensure that the HTML source order reflects the intended reading sequence. Do not rely solely on CSS for layout if it changes the logical order.

### Step-by-Step Instructions
For ordered steps or instructions, use semantic HTML elements like `<ol>` to preserve the correct sequence. Avoid placing steps out of order visually or in the code.

### Tables
Ensure that the reading order within tables matches the logical flow of data, left to right, top to bottom, unless a different order is intentional and clear.

### Screen Readers and Source Order
Use ARIA landmarks and HTML elements carefully so that screen readers follow the correct reading path. Avoid placing key content out of sequence in the DOM, even if it appears in the right place visually.

### Responsive Layouts
On smaller screens or when content reflows, ensure that the reading order still makes sense and reflects the intended sequence.

## Examples
{{< cards >}}
  {{< card url="../../../../examples/adaptable/meaningful-sequence" title="Meaningful Sequence Examples" icon="chevron-right" >}}
{{< /cards >}}