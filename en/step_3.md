<h2 class="c-project-heading--task">Style the preview card</h2>

--- task ---

Style your preview card by making the image into a thumbnail and a clear card shape.

--- /task ---

<div class="c-project-callout c-project-callout--tip">

### Tip

A thumbnail is a small picture that shows a preview of something bigger. It is used so you can quickly see what something is without opening it.

</div>

--- task ---

Click on the project file tab and select **styles.css**

--- /task ---


--- task ---

Add the highlighted CSS below to create a small card with a rounded picture. You can experiment with the border and colour setting to look how you want it.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 105
line_highlights: 109-132
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

.cardLink {
  color: inherit;
  text-decoration: none;
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
