<h2 class="c-project-heading--task">Add more bird cards</h2>

--- task ---

Now that the Barn Owl card works, add more cards so your homepage links to the other bird sections too.

--- /task ---

The sections on `birds.html` already give you useful names and anchor IDs to link to:

--- task ---

Make cards for these birds from `birds.html`:
- Curlew links to `#scCurlew`
- Yellowhammer links to `#scYellowh`
- Lapwing links to `#scLapwing`
- You can also add one for `#scOther` if you want an extra card

--- /task ---

Each new card follows the same pattern as the Barn Owl card. Change the picture, heading text, habitat text, and the `href` value so they match the bird you are linking to.

--- task ---

In **index.html**, add another linked card. For example, here is one for Curlew:

--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 36
line_highlights: 37-44
---
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
--- /code ---

</div>

--- task ---

Click **Run** and check that you now have more than one card on the homepage, with each card linking to the matching bird section.

--- /task ---

<div class="c-project-output">

![screenshot of output](step5.png)

</div>
