<h2 class="c-project-heading--task">Create a photo collage</h2>

--- task ---
Line numbers are best-effort in this step, and you can position several homepage images inside one container to build a layered collage.

**Code snippet 1: Add the collage container and images to `index.html`.**

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 81
line_highlights: 81-88
---
    <div id="photoBox" class="relPos">
        <img id="imgYoungKestrel" class="collagePhoto absPos" src="young-kestrel.jpg" alt="A young kestrel" />
        <img id="imgYoungKestrelTree" class="collagePhoto absPos" src="baby-kestrel.jpg" alt="A young kestrel on a branch" />
        <img id="imgKestrelSky" class="collagePhoto absPos" src="kestrel-flying.jpg" alt="A kestrel flying" />
        <img id="imgHello" class="collagePhoto absPos" src="bird-kestrel.jpg" alt="Closeup of a kestrel's face" />
        <img id="imgKestrel" class="collagePhoto absPos" src="kestrel-mirror.jpg" alt="A kestrel perched by a mirror" />
        <p id="photoText" class="absPos"><em>The Kestrel</em></p>
    </div>
--- /code ---

</div>

**Code snippet 2: Position each collage item with CSS.**

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 235
line_highlights: 235-288
---
#imgYoungKestrel {
    width: 230px;
    top: 100px;
    left: 20px;
    z-index: 6;
}
#imgYoungKestrelTree {
    width: 250px;
    top: 210px;
    left: 160px;
    z-index: 10;
}
#imgKestrelSky {
    width: 250px;
    top: 65px;
    left: 180px;
    z-index: 8;
}
#imgHello {
    width: 150px;
    top: 10px;
    left: 340px;
    z-index: 9;
}
#imgKestrel {
    width: 200px;
    top: 120px;
    left: 360px;
    z-index: 7;
}
#photoText {
    font-family: "Times New Roman", serif;
    color: #cc6699;
    font-size: 22px;
    left: 185px;
    top: 190px;
    z-index: 20;
}

.collagePhoto {
    border: 1px solid white;
}
.relPos {
    position: relative;
}
.absPos {
    position: absolute;
}

#photoBox {
    width: 800px;
    height: 400px;
}
--- /code ---

</div>
--- /task ---

<h2 class="c-project-heading--task">Test</h2>

--- task ---
Refresh the homepage and confirm the kestrel images overlap inside one collage with the text sitting on top.
--- /task ---
