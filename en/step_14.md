## Challenge: Style the photo collage

Use CSS to position the collage images so they overlap in an eye-catching layout on the homepage.

> [!TIP]
>
> Use `position: absolute;` on the collage items and `position: relative;` on the container so you can place each image exactly where you want it.

In `styles.css`, add the collage positioning rules.

```css filename="styles.css" line_numbers="true" line_number_start="235" line_highlights="235-288"
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
```

## Now run your code

Click **Run** and check that the kestrel images overlap inside one collage with the text sitting on top.


![screenshot of output](images/photoCollageExample.png)


