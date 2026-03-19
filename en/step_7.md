<h2 class="c-project-heading--task">Add side notes to the birds page</h2>

--- task ---

Add side notes to your birds page so you can include extra facts and useful links without crowding the main article.

--- /task ---

This is a good job for `aside` elements, because the information is useful but does not belong inside the main list of birds.

<div class="c-project-code">

--- code ---
---
language: html
filename: birds.html
line_numbers: true
line_number_start: 114
line_highlights: 118-138
---
      </article>
      
      <aside>
        <h3>Threats to birds</h3>
        <p>
          Some of the main reasons you might observe declining numbers are:
        </p>
        <ol>
          <li>Habitat destruction</li>
          <li>Pollution</li>
          <li>Climate change</li>
        </ol>
      </aside>

      <aside>
        <h3>Useful links</h3>
        <p>See the complete published <span class="warnOrange">amber</span> and <span class="warnRed">red</span> lists
          <a href="https://www.birdwatchireland.ie/LinkClick.aspx?fileticket=VcYOTGOjNbA%3d&tabid=178">here</a>.</p>
        <p>Check out the Wikipedia <a href="https://en.wikipedia.org/wiki/Bird_conservation">article</a>.</p>
      </aside>
      
    </main>
    <footer>
--- /code ---

</div>

<h2 class="c-project-heading--task">Test</h2>

--- task ---

Click **Run** and check that the extra notes appear outside the main bird list on the birds page.

--- /task ---
