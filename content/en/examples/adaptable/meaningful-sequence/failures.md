---
weight: 1
title: "Failures"
date: 2025-04-04
---

## Failure due to using white space characters to format tables in plain text content

### Example:

<table aria-label="Table with white space characters">
  <thead>
    <tr>
      <th>Menu</th>
      <th>Breakfast</th>
      <th>Lunch</th>
      <th>Dinner</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Monday</td>
      <td>2 fried eggs<br>bacon<br>toast</td>
      <td>tomato soup<br>hamburger<br>onion rings</td>
      <td>garden salad<br>Fried Chicken<br>green beans</td>
    </tr>
    <tr>
      <td></td>
      <td>Oatmeal cookie</td>
      <td></td>
      <td>mashed potatoes</td>
    </tr>
    <tr>
      <td>Tuesday</td>
      <td>Pancakes<br>sausage<br>orange juice</td>
      <td>vegetable soup<br>hot dogs<br>potato salad</td>
      <td>Caesar salad<br>Spaghetti with meatballs<br>Italian bread</td>
    </tr>
    <tr>
      <td></td>
      <td>brownie</td>
      <td></td>
      <td>ice cream</td>
    </tr>
  </tbody>
</table>

## Failure due to using white space characters to control spacing within a word

### Example: Failure due to adding white space in the middle of a word

This example has white spaces within a word to space out the letters in a heading. Screen readers may read each letter individually instead of the word "Welcome."

<pre aria-label="Code example showing a heading with spaces between letters">
&lt;h1&gt;W e l c o m e&lt;/h1&gt;
</pre>

&nbsp; can also be used to add white space, producing similar failures:

<pre aria-label="Code example showing a heading with non-breaking spaces between letters">
&lt;h1&gt;H&amp;nbsp;E&amp;nbsp;L&amp;nbsp;L&amp;nbsp;O&lt;/h1&gt;
</pre>
