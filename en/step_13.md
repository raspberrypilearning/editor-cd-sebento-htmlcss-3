<h2 class="c-project-heading--task">Test the character form check</h2>

--- task ---

Add a JavaScript check for your character details form so you can test how the page responds when fields are left empty.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: js
filename: scripts.js
line_numbers: true
line_number_start: 31
line_highlights: 32-34,36,38-44,46-52
---
// Function to check the character details form
const alertBox = document.querySelector("#alert");

function checkForm() {

  var alertMessage = "";

  if (characterName.value == "") {
    alertMessage = "Please enter a name";
  } else if (characterAbility.value == "") {
    alertMessage = "Please choose an ability";
  } else if (characterOrigin.value == "") {
    alertMessage = "Please write the origin story";
  }

  if (alertMessage != "") {
    alertBox.innerText = alertMessage;
    alertBox.style.display = "block";
  } else {
    alertBox.style.display = "none";
    displaySummary();
  }
}
--- /code ---

</div>

--- task ---

Click **Run** and test the form with missing fields to check that the correct warning appears.

--- /task ---

<div class="c-project-output">

![screenshot of output](step13.png)

</div>
