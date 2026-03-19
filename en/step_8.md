<h2 class="c-project-heading--task">Style the side notes</h2>

--- task ---

Style your side notes so they stand out from the main article and make the extra information easier to spot.

--- /task ---

Add a class to each `aside`, then use CSS to give the notes their own look.

<div class="c-project-code">

--- code ---
---
language: html
filename: birds.html
line_numbers: true
line_number_start: 118
line_highlights: 118,131,133
---
      <aside class="sideNoteStyle">
        <h3>Threats to birds</h3>
        <p>
          Some of the main reasons you might observe declining numbers are:
        </p>
      </aside>

      <aside class="sideNoteStyle">
        <h3>Useful links</h3>
        <p>See the complete published <span class="warnOrange">amber</span> and <span class="warnRed">red</span> lists
          <a href="https://www.birdwatchireland.ie/LinkClick.aspx?fileticket=VcYOTGOjNbA%3d&tabid=178">here</a>.</p>
        <p>Check out the Wikipedia <a href="https://en.wikipedia.org/wiki/Bird_conservation">article</a>.</p>
      </aside>
--- /code ---

</div>

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 190
line_highlights: 197-209
---
.cardContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 10px;
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
    grid-column-gap: 0.5em;
}
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run** and check that the side notes appear in styled boxes and that the words `amber` and `red` stand out.

--- /task ---
