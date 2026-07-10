## Arrange the cards in a row

Use CSS to style the `cardContainer` so the cards sit side by side and wrap neatly when there is less space.

In **styles.css**, add a flex rule for `.cardContainer`.

```css filename="styles.css" line_numbers="true" line_number_start="131" line_highlights="136-141"
.cardLink {
  color: inherit;
  text-decoration: none;
}

.cardContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 10px;
}
```

## Now run your code

Click **Run** and check that the cards sit in a row when there is space and wrap onto a new line when the window gets narrower.

![screenshot of output](images/flexSideBySide.png)


