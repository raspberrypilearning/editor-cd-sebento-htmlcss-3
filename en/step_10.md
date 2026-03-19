<h2 class="c-project-heading--task">Add hover and lightbox effects</h2>

--- task ---
Line numbers are best-effort in this step, and you can make your cards lift on hover while bird images open in a full-page lightbox when clicked.

**Code snippet 1: Add lightbox links and wrap bird images so they open the matching popup.**

<div class="c-project-code">

--- code ---
---
language: html
filename: birds.html
line_numbers: true
line_number_start: 22
line_highlights: 22-46,61-62,70-71,75-76,85-86,94-95
---
    <a href="#_" class="lightbox" id="boxBarnowl">
      <h3>Hi there!</h3>
      <img src="barn-owl-landing.jpg" alt="Picture of a barn owl" />
      <p>Owly the barn owl dropping in for lunch</p>
    </a>

    <a href="#_" class="lightbox" id="boxCurlew1">
      <h3>Curlew</h3>
      <img src="curlew.jpg" alt="A curlew on the sand" />
    </a>

    <a href="#_" class="lightbox" id="boxCurlew2">
      <h3>Curlew</h3>
      <img src="curlew2.jpg" alt="A curlew facing the camera" />
    </a>

    <a href="#_" class="lightbox" id="boxYellowh">
      <h3>Yellowhammer</h3>
      <img src="yellowhammer.jpg" alt="A yellowhammer in a tree" />
    </a>

    <a href="#_" class="lightbox" id="boxLapwing">
      <h3>Lapwing</h3>
      <img src="lapwing.jpg" alt="Picture of a lapwing" />
    </a>

    <a href="#boxBarnowl"><img src="barn-owl-landing.jpg" alt="Barn owl landing on a branch" class="mediumPictures" /></a>
    <a href="#boxCurlew1"><img src="curlew.jpg" class="smallPictures" /></a>
    <a href="#boxCurlew2"><img src="curlew2.jpg" class="smallPictures" /></a>
    <a href="#boxYellowh"><img src="yellowhammer.jpg" width="200px" /></a>
    <a href="#boxLapwing"><img src="lapwing.jpg" width="200px" /></a>
--- /code ---

</div>

**Code snippet 2: Add the lightbox styles and hover animation.**

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 146
line_highlights: 146-160,178,180-184
---
.lightbox{
    background: rgba(0,0,0,0.8);
    color: #ffffff;
    text-align: center;
    text-decoration: none;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    position: fixed;
    visibility: hidden;
    z-index: 999;
}
.lightbox:target {
    visibility: visible;
}

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
    transition: all 0.2s ease-out;
}
.card:hover {
    box-shadow: 0px 2px 2px rgba(0,0,0,0.2);
    transform: translateY(-2px);
}
--- /code ---

</div>
--- /task ---

<h2 class="c-project-heading--task">Test</h2>

--- task ---
Hover over a homepage card to check it lifts slightly, then open `birds.html` and click a bird image to confirm the lightbox appears and closes when you click away.
--- /task ---
