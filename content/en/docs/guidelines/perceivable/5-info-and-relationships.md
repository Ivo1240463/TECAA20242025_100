---
title: Info and Relationships
linkTitle: 5- Info and Relationships
---

## Info and Relationships

When designing web content, it's not enough to focus only on visual presentation, the underlying structure and meaning must also be clear to assistive technologies. This ensures that users who rely on screen readers or other tools can understand how information is organized and how different elements relate to each other.

This guideline supports users with visual, cognitive, and learning disabilities by making content more predictable and easier to navigate.

## General Rule

Information, structure, and relationships conveyed through visual presentation must also be:

- Programmatically determined 
- Available in text.

This allows users with disabilities to perceive and interact with content in a meaningful and efficient way.

## Specific Situations

### Headings and Labels
Use proper HTML tags (`<h1>` to `<h6>`) to indicate headings. This helps screen reader users understand the hierarchy and organization of content. Avoid using visual styling alone (like bold text or large fonts) to indicate headings.

### Lists and Groupings
Ensure that lists are marked up using semantic HTML tags like `<ul>`, `<ol>`, and `<li>`. Group related form fields using `<fieldset>` and `<legend>` to convey relationships.

### Tables
Use appropriate table markup (`<table>`, `<thead>`, `<tbody>`, `<th>`, and `<td>`) to indicate data relationships. Provide table headers to explain how data is organized.

## Exemplos
{{< cards >}}
  {{< card url="../../../../examples/adaptable/info-relationships" title="Info and Relationships Exemplos" icon="chevron-right" >}}
{{< /cards >}}