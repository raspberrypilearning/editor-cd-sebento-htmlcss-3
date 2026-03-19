<h2 class="c-project-heading--task">Add side notes to the birds page</h2>

--- task ---
Line numbers are best-effort in this step, and you can add extra information in `aside` elements so the main article keeps its focus.

**Code snippet 1: Add two side notes after the main article in `birds.html`.**

--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: birds.html
line_numbers: true
line_number_start: 118
line_highlights: 118-138
---
      <aside class="sideNoteStyle">
        <h3>Threats to birds</h3>
        <p>
          Some of the main reasons you might observe declining numbers are:
        </p>
        <ol>
          <li>Habitat destruction</li>
          <li>Pollution</li>
          <li>Climate change</li>
        </ol>
      </aside>

      <aside class="sideNoteStyle">
        <h3>Useful links</h3>
        <p>See the complete published <span class="warnOrange">amber</span> and <span class="warnRed">red</span> lists
          <a href="https://www.birdwatchireland.ie/LinkClick.aspx?fileticket=VcYOTGOjNbA%3d&tabid=178">here</a>.</p>
        <p>Check out the Wikipedia <a href="https://en.wikipedia.org/wiki/Bird_conservation">article</a>.</p>
      </aside>
--- /code ---

</div>

**Code snippet 2: Style the side notes and highlighted words.**

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 197
line_highlights: 197-209
---
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
--- /code ---

</div>


<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run**. The extra notes appear outside the main bird list in their own styled boxes.

--- /task ---

<div class="c-project-output">

![screenshot of output](step*.png)

</div>
