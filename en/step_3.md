<h2 class="c-project-heading--task">Style the preview card</h2>

--- task ---

Style your preview card so it looks more like a polished feature on your homepage, with a neat thumbnail and a clear card shape.

--- /task ---

Add the CSS below to create a small card with a rounded picture, ready for the rest of your featured birds.

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 159
line_highlights: 163-179
---
.lightbox:target {
    visibility: visible;
}

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
.cardLink {
  color: inherit;
  text-decoration: none;
}
--- /code ---

</div>


<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run** and check that the card now has a border, rounded corners, and a small rounded thumbnail image.

--- /task ---
