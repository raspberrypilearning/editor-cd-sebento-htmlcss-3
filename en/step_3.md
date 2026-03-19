<h2 class="c-project-heading--task">Style the preview card</h2>

--- task ---

Style your preview card so it looks more like a polished feature on your homepage, with a neat thumbnail and a clear card shape.

--- /task ---


--- task ---

Click on the project file tab and select **styles.css**

--- /task ---


--- task ---

Add the highlighted CSS below to create a small card with a rounded picture.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 105
line_highlights: 109-125
---
.niceLinks:hover {
  color: #00FF7F;
}

.tinyPicture {
    height: 60px;
    border-radius: 10px;
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
}
.card:hover {
    border-color: #1E90FF;
}

/**********************************
This section is for styling tables
--- /code ---

</div>
--- task ---

Click **Run** and check that the card now has a border, rounded corners, and a small rounded thumbnail image.

--- /task ---

<div class="c-project-output">

![screenshot of output](step3.png)

</div>
