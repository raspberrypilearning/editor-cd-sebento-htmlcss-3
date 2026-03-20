<h2 class="c-project-heading--task">Add a preview card</h2>

--- task ---

Add a preview card to your homepage so visitors can quickly spot one of your featured birds and click through to learn more.

--- /task ---

--- task ---

Preview cards are a handy way to show off different parts of your site. Start by adding one card for the Barn Owl.

--- /task ---






<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 30
line_highlights: 32-36 
---
<img id="owly" src="barn-owl.jpg" class="topDivider someSpacing mediumPictures" alt="A barn owl" />
    
<article class="card">
<img src="barn-owl-landing.jpg" class="tinyPicture">
<h3>Barn Owl</h3>
<p>Habitat: farmland, grassland</p>
</article>     	    

      <a href="birds.html#scCurlew" class="cardLink">
        <article class="card">
          <img src="curlew2.jpg" class="tinyPicture">
          <h3>Curlew</h3>
          <p>Habitat: wet grasslands</p>
        </article>
      </a>



</main>
--- /code ---

</div>
--- task ---

Click **Run** and check that a new Barn Owl card appears on your homepage under the featured image.

--- /task ---

<div class="c-project-output">

![screenshot of output](step2.png)

</div>
