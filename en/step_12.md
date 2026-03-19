<h2 class="c-project-heading--task">Challenge</h2>

--- task ---

Make the website your own by adding one more effect, such as another lightbox, another collage photo, or an animated heading.

--- /task ---

Try extending one of the ideas you have already used so the site feels more personal and creative.

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

<h2 class="c-project-heading--task">Test</h2>

--- task ---

Try your new effect and check that it changes the page in a clear way when the site loads or when you interact with it.

--- /task ---
