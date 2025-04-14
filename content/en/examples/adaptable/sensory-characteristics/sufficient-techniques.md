---
weight: 2
title: "Sufficient Techniques"
date: 2025-04-04
---

## Providing textual identification of items that otherwise rely only on sensory information to be understood

### Example 1: Button referenced by shape and accessible name
A round button is provided on a form to submit the form and move onto the next step in a progression. The button is labeled with the text "go". The instructions state, "To submit the form, press the round button labeled 'go'." This includes both shape and textual information to locate the button.

### Example 2: A section of navigation links referenced by location and heading
Instructions for a web page providing online training state, "Use the list of links to the right with the heading, 'Class Listing' to navigate to the desired online course." This description provides location as well as textual clues to help find the correct list of links.

### Example 3: Button referenced by position and accessible name
The following layout places a button in the lower right corner and indicates it by position. An indication of the text label clarifies which button to use for users for whom position is not meaningful.

#### HTML Block:
<pre aria-label="Example code of a form in HTML"><code>&lt;form class=&quot;wrapper&quot;&gt;
  &lt;h1&gt;Sign up to our mailing list&lt;/h1&gt;
    &lt;div role=&quot;note&quot;&gt;
      Complete the form and then press the lower-right (&lt;i&gt;sign up&lt;/i&gt;) button.
    &lt;/div&gt;
  &lt;div class=&quot;form-group&quot;&gt;
    &lt;label for=&quot;full-name&quot;&gt;Your name&lt;/label&gt;
    &lt;input autocomplete=&quot;name&quot; id=&quot;full-name&quot; type=&quot;text&quot;&gt;
  &lt;/div&gt;
  &lt;div class=&quot;form-group&quot;&gt;
    &lt;label for=&quot;email&quot;&gt;Your email address&lt;/label&gt;
    &lt;input autocomplete=&quot;email&quot; id=&quot;email&quot; type=&quot;text&quot;&gt;
  &lt;/div&gt;
  &lt;button type=&quot;reset&quot;&gt;Cancel&lt;/button&gt;
  &lt;button type=&quot;submit&quot;&gt;Sign up&lt;/button&gt;
&lt;/form&gt;</code></pre>
#### CSS Block:
<pre aria-label="Example code on CSS"><code>
.wrapper{
  border: 1px solid #aeaeae;
  display: grid;
  gap: 1rem;
  grid-template-columns: 1fr 1fr;
  padding: 1rem;
  width: 50vw;
}

label{
  display: block;
}

input, button{
  font: inherit;
}

h1, [role="note"]{
  grid-column: 1 / -1;
}

.form-group{
  grid-column: 1;
}

input{
  width: 100%;
}

button[type="reset"]{
  grid-column: 1;
}

button[type="submit"]{
  grid-column: 2;
}
</code></pre>