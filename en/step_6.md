<h2 class="c-project-heading--task">Make the menu responsive</h2>

--- task ---

Line numbers are best-effort in this step, and you can switch the navigation to a mobile-first flex layout that rearranges itself on wider screens.

--- /task ---

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
--- /code ---

</div>


<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run** to test. Make the browser narrow and wide, and confirm the menu stacks on smaller screens before spreading into a row on larger screens.

--- /task ---

<div class="c-project-output">

![screenshot of output](step*.png)

</div>
