<h2 class="c-project-heading--task">Challenge: Create a photo collage</h2>

Build a photo collage on your homepage so the site feels richer and more eye-catching.

<h2 class="c-project-heading--explainer">Follow these instructions</h2>

## Step 1

### Tip

<div class="c-project-callout c-project-callout--tip">

Exact positioning lets you place images wherever you want instead of leaving them in a simple row. That makes it ideal for building a collage.

</div>



<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 68
line_highlights: 77-84
---
      <a href="birds.html" class="cardLink">
        <article class="card">
          <img src="hen-harrier.jpg" class="tinyPicture">
          <h3>Hen Harrier</h3>
          <p>Habitat: moorlands</p>
        </article>
      </a>
    </div>


    <div id="photoBox" class="relPos">
      <img id="imgYoungKestrel" class="collagePhoto absPos" src="young-kestrel.jpg" alt="A young kestrel" />
      <img id="imgYoungKestrelTree" class="collagePhoto absPos" src="baby-kestrel.jpg"
        alt="A young kestrel on a branch" />
      <img id="imgKestrelSky" class="collagePhoto absPos" src="kestrel-flying.jpg" alt="A kestrel flying" />
      <img id="imgHello" class="collagePhoto absPos" src="bird-kestrel.jpg" alt="Closeup of a kestrel's face" />
      <img id="imgKestrel" class="collagePhoto absPos" src="kestrel-mirror.jpg" alt="A kestrel perched by a mirror" />
      <p id="photoText" class="absPos"><em>The Kestrel</em></p>
    </div>

  </main>
--- /code ---

</div>

## Step 2

Click **Run** and check that the collage images and text appear on the homepage ready to be styled.

<div class="c-project-output">

![screenshot of output](images/step14-output.png)

</div>

## Now run your code

Confirm the observable result.
