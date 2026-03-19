<h2 class="c-project-heading--task">Add a featured image caption</h2>

--- task ---

Group the owl image and its caption together so the homepage feels more finished and the picture has a clear label.

--- /task ---

`figure` and `figcaption` are useful when a picture and its text belong together and should be treated as one part of the page.

<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 27
line_highlights: 31-34
---
    <p>
      Explore the links above to learn more.
    </p>
    
    <figure>
      <img id="owly" src="barn-owl.jpg" class="topDivider someSpacing mediumPictures" alt="A barn owl" />
      <figcaption>Owly the barn owl</figcaption>
    </figure>
    
    <a href="birds.html#scBarnowl" class="cardLink">
--- /code ---

</div>


<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run** and check that the owl image now has a caption directly below it.

--- /task ---
