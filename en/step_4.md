<h2 class="c-project-heading--task">Style the preview card</h2>

--- task ---

Line numbers are best-effort in this step, and you can add CSS classes for the card thumbnail and card panel to make the new preview look polished.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 163
line_highlights: 163-179
---
.tinyPicture {
    height: 60px;
    border-radius: 10px;
}
.card {
    width: 200px;
    height: 200px;
    border: 2px solid #F0FFFF;
    border-radius: 10px;
    box-sizing: border-box;
    padding: 10px;
    margin-top: 10px;
    font-family: "Trebuchet MS", sans-serif;
    margin-left: auto;
    margin-right: auto;
}
--- /code ---

</div>



--- task ---

Click **Run**. The card now has a border, rounded corners, and a small rounded thumbnail image.

--- /task ---

<div class="c-project-output">

![screenshot of output](step*.png)

</div>
