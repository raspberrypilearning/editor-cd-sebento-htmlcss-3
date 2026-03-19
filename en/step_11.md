<h2 class="c-project-heading--task">Challenge</h2>

--- task ---

Make the website feel more personal by inventing one more effect, such as another lightbox, another collage photo, or an animated heading.

<h2 class="c-project-heading--task">Test</h2>


<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 6
line_highlights: 9,117-133
---
h1 {
    color: Azure;
    font-family: "Times New Roman", serif;
    animation: rainbowGlow 3s infinite;
}

@keyframes rainbowGlow {
    0% {
        color: #00BFFF;
    }
    25% {
        color: #00FF7F;
    }
    50% {
        color: #eeeeaf;
    }
    75% {
        color: #eeafee;
    }
    100% {
        color: #00BFFF;
    }
}
--- /code ---

</div>



