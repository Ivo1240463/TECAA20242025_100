---
weight: 3
title: Non-text Content (Level A)
type: page
date: 2025-04-04

sections:
  - block: collection
    id: examples
    content:
      filters:
        section: examples
      sort: weight
      design:
        view: list
  - block: subtopics
    filters:
      section: examples
      folders: 
        - sufficient-techniques
        - advisory-techniques
        - failures
      sort: weight
      design:
        view: nested_list
---
{{< cards >}}
  {{< card url="../../../../docs/guidelines/perceivable/1-non-text-content/" title="Non-text Content Guidelines" icon="chevron-right" >}}
{{< /cards >}}