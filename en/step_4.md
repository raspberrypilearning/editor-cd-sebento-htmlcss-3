<h2 class="c-project-heading--task">Make your cards clickable</h2>

--- task ---

Turn your homepage cards into clickable links so people can use them to jump straight to the matching bird sections.

--- /task ---

--- task ---

Go to the **index.html** file. 

--- /task ---

--- task ---

Add the code below to wrap your Barn Owl card in a link.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 30
line_highlights: 32, 38
--- 
   <img id="owly" src="barn-owl.jpg" class="topDivider someSpacing mediumPictures" alt="A barn owl" />   
   
    <a href="birds.html#scBarnowl" class="cardLink">
      <article class="card">
        <img src="barn-owl-landing.jpg" class="tinyPicture">
        <h3>Barn Owl</h3>
        <p>Habitat: farmland, grassland</p>
      </article>
    </a>

    </main>
--- /code ---

</div>

--- task ---

In **styles.css** add `cardlink` styles.

--- /task ---


<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 176
line_highlights: 179-182
---
    margin-left: auto;
    margin-right: auto;
}
.cardLink {
  color: inherit;
  text-decoration: none;
}
--- /code ---

</div>


--- task ---

Click **Run** and check that the Barn Owl card is clickable and opens the Barn Owl section on `birds.html`.

--- /task ---

<div class="c-project-output">

![screenshot of output](step4.png)

</div>
