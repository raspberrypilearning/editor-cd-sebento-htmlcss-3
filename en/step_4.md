<h2 class="c-project-heading--task">Make your cards clickable</h2>

--- task ---
Turn your homepage cards into clickable links so people can use them to jump straight to the matching bird sections.

--- /task ---

This is a neat way to turn your homepage into a simple shortcut to another part of the site. The `href` uses a page anchor such as `birds.html#scBarnowl`, so clicking the card opens the correct section on the birds page.

Start by wrapping your Barn Owl card in a link. Once that works, you can repeat the same pattern for more cards later.

**Code snippet 1: Wrap the Barn Owl card in a link.**

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 36
line_highlights: 36-44
---
    <a href="birds.html#scBarnowl" class="cardLink">
      <article class="card">
        <img src="barn-owl-landing.jpg" class="tinyPicture">
        <h3>Barn Owl</h3>
        <p>Habitat: farmland, grassland</p>
      </article>
    </a>
--- /code ---

</div>

**Code snippet 2: Reset the default link styling so the card still looks like a card.**

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 167
line_highlights: 185-188
---
.cardLink {
  color: inherit;
  text-decoration: none;
}
--- /code ---

</div>


<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run** and check that the Barn Owl card is clickable and opens the Barn Owl section on `birds.html`.

--- /task ---
