---
title: Gavin's Blog Post
published_at: 2024-07-24
snippet: An example of a blog post.
disable_html_sanitization: true
allow_math: true
---

# SCAVANGER HUNT
## An Exploding Coffee 
![image one](photo1.JPG)


This is something that we thought somewhat resemble an exploding coffee. Although we didn't quite get the right object, we still had a good laugh about the coffee machine that we took a picture with.

## A Study Fit for A Sith Lord
![image two](photo2.JPG)


We found this object because one of us had been there, so it was sort of easy to figure out when he saw it on the checklist.

## A Wide Net Strung Above, Bulging Under The Weight of Its Flying Paper Cargo
![image three](photo3.JPG)

We found this thing by coincidence, we were going down the escalator and i spotted something by the window. It looked like it matched the description so we took a picture with it, we're pretty sure it's right.


## A Book Containing Digital Media Wisdom, Found Amongst Many
![image four](photo4.JPG)

We didn't have enough time to find the book so we rushed to the library and found something resembling digital media. A





<iframe id="coding_train_video" src="https://www.youtube.com/embed/rI_y2GAlQFM?si=RDgjkpunxk1mQzMI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<script type="module">

    console.log (`hello world! 🚀`)

    const iframe  = document.getElementById (`coding_train_video`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16

</script>

## Embedding p5 sketches:

<iframe id="falling_falling" src="https://editor.p5js.org/capogreco/full/Fkg05m7aA"></iframe>

<script type="module">

    const iframe  = document.getElementById (`falling_falling`)
    iframe.width  = iframe.parentNode.scrollWidth
    iframe.height = iframe.width * 9 / 16 + 42

</script>

## Canvas API

<canvas id="canvas_example"></canvas>

<script type="module">
    const cnv = document.getElementById (`canvas_example`)
    cnv.width = cnv.parentNode.scrollWidth
    cnv.height = cnv.width * 9 / 16

    const ctx = cnv.getContext (`2d`)
    const pos = {
        x: -100,
        y: cnv.height / 2 - 50
    }
    
    function draw_frame () {
        ctx.fillStyle = `turquoise`
        ctx.fillRect (0, 0, cnv.width, cnv.height)

        ctx.fillStyle = `hotpink`
        ctx.fillRect (pos.x, pos.y, 100, 100)

        pos.x += 2

        if (pos.x > cnv.width) {
            pos.x = -100
        }

        requestAnimationFrame (draw_frame)
    }

    draw_frame ()
</script>


