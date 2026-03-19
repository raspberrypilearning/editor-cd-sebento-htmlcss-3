<h2 class="c-project-heading--task">Centre the cards</h2>

--- task ---

Move your cards into the centre of the page so they feel more polished and are ready for a larger card layout.

--- /task ---

`margin-left: auto;` and `margin-right: auto;` centre a fixed-width block.

--- task ---

Once the Barn Owl card is working, repeat the same card pattern for the other birds you want to feature on the homepage.

--- /task ---

--- task ---

In **styles.css**, add the highlighted lines to the `.card` rule.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 174
line_highlights: 176-177
---
    margin-top: 10px;
    font-family: "Trebuchet MS", sans-serif;
    margin-left: auto;
    margin-right: auto;
}
.card:hover {
--- /code ---

</div>

--- task ---

Click **Run** and check that each card stays centred, even when you make the browser wider and narrower.

--- /task ---

<div class="c-project-output">

![screenshot of output](step5.png)

</div>
