<h2 class="c-project-heading--task">Try flex on the menu</h2>

--- task ---

Use flex on the menu so the links line up in a row and you can control how they spread across the page.

--- /task ---

Flex is useful for more than cards. A navigation bar is another good place to practise arranging items horizontally.

--- task ---

In **styles.css**, remove `display: inline;` from `nav ul li`, then add the highlighted CSS to `nav ul`.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 12
line_highlights: 19-20
---
nav ul {
  background-color: tomato;
  border-style: solid;
  border-color: MediumVioletRed;
  border-width: 2px;
  padding: 10px;
  border-radius: 10px;
  display: flex;
  justify-content: flex-start;
}

nav ul li {
  list-style-type: none;
  margin-right: 10px;
  margin-left: 10px;
  color: PapayaWhip;
}
--- /code ---

</div>

`justify-content` controls how items are distributed across the flex container. Try `flex-end` to push the links to the right, or `space-around` to spread them out evenly.

--- task ---

Click **Run** and check that the menu now sits in a row. Experiment with different `justify-content` values to see how the layout changes.

--- /task ---

<div class="c-project-output">

![screenshot of output](step6.png)

</div>
