<h2 class="c-project-heading--task">Link and arrange your cards</h2>

--- task ---
Line numbers are best-effort in this step, and you can turn the cards into links and place them in a flexible row so the homepage becomes easier to explore.

**Code snippet 1: Replace the single card with a linked card container on the homepage.**

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 36
line_highlights: 36-78
---
    <div class="cardContainer">
      <a href="birds.html#scBarnowl" class="cardLink">
        <article class="card">
          <img src="barn-owl-landing.jpg" class="tinyPicture">
          <h3>Barn Owl</h3>
          <p>Habitat: farmland, grassland</p>
        </article>
      </a>

      <a href="birds.html#scCurlew" class="cardLink">
        <article class="card">
          <img src="curlew2.jpg" class="tinyPicture">
          <h3>Curlew</h3>
          <p>Habitat: wet grasslands</p>
        </article>
      </a>

      <a href="birds.html#scYellowh" class="cardLink">
        <article class="card">
          <img src="yellowhammer.jpg" class="tinyPicture">
          <h3>Yellowhammer</h3>
          <p>Habitat: dry, open country</p>
        </article>
      </a>

      <a href="birds.html#scLapwing" class="cardLink">
        <article class="card">
          <img src="lapwing.jpg" class="tinyPicture">
          <h3>Lapwing</h3>
          <p>Habitat: pasture, wet grassland</p>
        </article>
      </a>

      <a href="birds.html#scOther" class="cardLink">
        <article class="card">
          <img src="hen-harrier.jpg" class="tinyPicture">
          <h3>Hen Harrier</h3>
          <p>Habitat: moorlands</p>
        </article>
      </a>
    </div>
--- /code ---

</div>

**Code snippet 2: Add link-reset and flex layout styles.**

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 167
line_highlights: 176-195
---
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

.cardContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 10px;
}
--- /code ---

</div>
--- /task ---

<h2 class="c-project-heading--task">Test</h2>

--- task ---
Open the homepage and confirm the cards sit in a row or wrap neatly, and that clicking a card jumps to the matching section on `birds.html`.
--- /task ---
