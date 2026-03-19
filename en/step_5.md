<h2 class="c-project-heading--task">Arrange the cards in a row</h2>

--- task ---

Centre your preview card and place it inside a flex container so the homepage is ready for a neat row of cards.

--- /task ---

`margin-left: auto;` and `margin-right: auto;` centre a fixed-width block. A flex container can then lay cards out side by side when you add more of them later.

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

In **index.html**, wrap the card link in a new `div` with the class `cardContainer`.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 30
line_highlights: 32,39
---
    <img id="owly" src="barn-owl.jpg" class="topDivider someSpacing mediumPictures" alt="A barn owl" />

    <div class="cardContainer">
      <a href="birds.html#scBarnowl" class="cardLink">
        <article class="card">
          <img src="barn-owl-landing.jpg" class="tinyPicture">
          <h3>Barn Owl</h3>
          <p>Habitat: farmland, grassland</p>
        </article>
      </a>
    </div>

    </main>
--- /code ---

</div>

--- task ---

Still in **styles.css**, add a flex rule for `.cardContainer`.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 185
line_highlights: 190-194
---
.cardLink {
  color: inherit;
  text-decoration: none;
}
.cardContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 10px;
}
--- /code ---

</div>

--- task ---

Click **Run** and check that the card stays centred. The new flex container will also let extra cards sit side by side when you add more later.

--- /task ---

<div class="c-project-output">

![screenshot of output](step5.png)

</div>
