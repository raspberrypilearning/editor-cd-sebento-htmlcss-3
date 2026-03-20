<h2 class="c-project-heading--task">Make the menu responsive</h2>

--- task ---

Make your navigation menu responsive so it works neatly on small screens first and then spreads out on larger screens.

--- /task ---

You will start with the menu stacked for smaller screens, then use media queries to adjust the layout when there is more space.

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 14
line_highlights: 19,21-23,32-35,44-55
---
nav ul {
    background-color: tomato;
    border-style: solid;
    border-color: MediumVioletRed;
    border-width: 2px;
    padding: 0.5em;
    border-radius: 10px;
    display: flex;
    flex-direction: column;
}

nav ul li {
    color: PapayaWhip;
    text-align: center;
    list-style-type: none;
    margin-right: 0.5em;
    margin-left: 0.5em;
}
nav ul li a {
  text-decoration: none;
  color: indigo;
}

@media all and (min-width: 400px) {
    nav ul {
        flex-direction: row;
        justify-content: space-around;
    }
}

@media all and (min-width: 1600px) {
    nav ul {
        flex-direction: row;
        justify-content: flex-end;
    }
}
.darkerBackground {
  background-color: #99bbff;
}
--- /code ---

</div>
--- task ---

Click **Run**, make the browser narrow and wide, and check that the menu stacks on smaller screens before spreading into a row on larger screens.

--- /task ---

<div class="c-project-output">

![screenshot of output](step10.png)

</div>
