<h2 class="c-project-heading--task">Add a featured image caption</h2>

--- task ---

Wrap the featured owl image on the homepage and its caption in a `figure` element so the picture has a clear label.

--- /task ---


<div class="c-project-code">
--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 26
line_highlights: 30-33
---
    <p>
	    Explore the links above to learn more.
    </p>

    <figure>
      <img id="owly" src="barn-owl.jpg" class="topDivider someSpacing mediumPictures" alt="A barn owl" />
      <figcaption>Owly the barn owl</figcaption>
    </figure>

    <div class="cardContainer">
--- /code ---

</div>


--- task ---

Click **Run** and check that the owl image now has a caption directly below it.

--- /task ---

<div class="c-project-output">

![screenshot of output](step9.png)

</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

`figure` and `figcaption` are useful when a picture and its text belong together and should be treated as one part of the page.


</div>
