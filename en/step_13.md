<h2 class="c-project-heading--task">Style the side notes</h2>

--- task ---

Style your side notes so they stand out from the main article and make the extra information easier to spot.

--- /task ---

The `sideNoteStyle` class was added in the previous step. In this step, use CSS to give those side notes their own look.

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 196
line_highlights: 197-209
---
}

.sideNoteStyle {
  border: dotted 1px purple;
  background-color: #cddffe;
  padding: 0.5em;
  margin: 0.5em;
}
.warnOrange {
    background-color: #ffa500;
}
.warnRed {
    color: #FF4500;
    font-size: larger;
}
.myPageLayoutGrid {
    display: grid;
--- /code ---

</div>
--- task ---

Click **Run** and check that the side notes appear in styled boxes and that the words `amber` and `red` stand out.

--- /task ---

<div class="c-project-output">

![screenshot of output](step13.png)

</div>
