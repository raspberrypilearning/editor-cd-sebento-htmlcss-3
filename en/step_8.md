<h2 class="c-project-heading--task">Improve the card hover effect</h2>

--- task ---

Add a smoother hover effect so each card feels more lively when you move the pointer over it.

--- /task ---

--- task ---

In **styles.css**, update the card styles with the highlighted lines below to add a transition, a shadow, and a slight lift.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: styles.css
line_numbers: true
line_number_start: 127
line_highlights: 129-131
---
.card:hover {
    border-color: #1E90FF;
    box-shadow: 0px 4px 4px rgba(0,0,139,0.5);
    transform: translateY(-2px);
}
.cardLink {
--- /code ---

</div>

--- task ---

Click **Run** and check that the cards still sit in a row and now lift when you hover over them. Experiment with colours and translate values to change the effect.

--- /task ---

<div class="c-project-output">

![screenshot of output](step8.gif)

</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

- `rgba` is a way to set a colour using red, green, blue, and alpha. `rgba(0,0,139,0.5)` means a dark blue with some see-through opacity.
- `translateY` moves an element up or down.

</div>
