<h2 class="c-project-heading--task">Arrange the cards in a row</h2>

--- task ---

Put your cards inside a flex container so they can sit side by side and wrap neatly when there is less space.

--- /task ---

A flex container can lay cards out side by side and move them onto a new line when needed.

--- task ---

In **index.html**, wrap the card links in a new `div` with the class `cardContainer`.

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

In **styles.css**, add a flex rule for `.cardContainer`.

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

Still in **styles.css**, add a hover effect so each card lifts slightly when you move the pointer over it.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 176
line_highlights: 178,180-184
---
    margin-left: auto;
    margin-right: auto;
    transition: all 0.2s ease-out;
}
.card:hover {
    box-shadow: 0px 2px 2px rgba(0,0,0,0.2);
    transform: translateY(-2px);
}
.cardLink {
--- /code ---

</div>

--- task ---

Click **Run** and check that the cards sit in a row when there is space, wrap onto a new line when the window gets narrower, and lift slightly when you hover over them.

--- /task ---

<div class="c-project-output">

![screenshot of output](step6.png)

</div>
