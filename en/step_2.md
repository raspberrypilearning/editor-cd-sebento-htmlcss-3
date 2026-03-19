<h2 class="c-project-heading--task">Add a preview card</h2>

--- task ---

Add a preview card to your homepage so visitors can quickly spot one of your featured birds and click through to learn more.

--- /task ---

Preview cards are a handy way to show off different parts of your site. Start by adding one card for the Barn Owl.

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 32-36 
---
    <p>
      Explore the links above to learn more.
    </p>
    
    <img id="owly" src="barn-owl.jpg" class="topDivider someSpacing mediumPictures" alt="A barn owl" />

    <article class="card">
      <img src="barn-owl-landing.jpg" class="tinyPicture">
      <h3>Barn Owl</h3>
      <p>Habitat: farmland, grassland</p>
    </article>
    
  </main>
  <footer>
--- /code ---

</div>


<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run** and check that a new Barn Owl card appears on your homepage under the featured image.

--- /task ---
