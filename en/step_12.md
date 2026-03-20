<h2 class="c-project-heading--task">Build a page grid</h2>

--- task ---

Use a grid layout to organise the **birds.html** page so the main article and side notes sit in a cleaner, more interesting arrangement.

--- /task ---

--- task ---

First, add `class="myPageLayoutGrid"` to the existing `main` element.

--- /task ---

--- task ---

Then add classes to the existing content elements:

- add `class="myGridArticle"` to the existing `article`
- add `class="sideNoteStyle myGridAside1"` to the first existing `aside`
- add `class="sideNoteStyle myGridAside2"` to the second existing `aside`

--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: birds.html
line_numbers: true
line_number_start: 20
line_highlights: 20,49,118,131
---
  <main class="myPageLayoutGrid">
    
    <article class="myGridArticle">
      <h1>Birds of conservation concern in Ireland</h1>
    </article>
    
    <aside class="sideNoteStyle myGridAside1">
      <h3>Threats to birds</h3>
    </aside>
    
    <aside class="sideNoteStyle myGridAside2">
      <h3>Useful links</h3>
    </aside>
  </main>
--- /code ---

</div>

--- task ---

In `styles.css`, add the grid rules.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 212
line_highlights: 212-231
---
.myPageLayoutGrid {
    display: grid;
    grid-column-gap: 0.5em;
    grid-row-gap: 1em;
    grid-template-rows: auto;
    grid-template-columns: 2fr 1fr;
    grid-template-areas:
        "egArticle egAside1"
        "egArticle egAside2"
        "egArticle .";
}
.myGridArticle {
    grid-area: egArticle;
}
.myGridAside1 {
    grid-area: egAside1;
}
.myGridAside2 {
    grid-area: egAside2;
}
--- /code ---

</div>
--- task ---

Click **Run** and check that the main article takes the wider column while the two side notes sit in a narrower column on the right.

--- /task ---

<div class="c-project-output">

![screenshot of output](step12.png)

</div>
