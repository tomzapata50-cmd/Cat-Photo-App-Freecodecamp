# 🐾 CatPhotoApp

A playful HTML demo project showcasing semantic structure, image embedding, and list formatting — all wrapped in a cat-themed layout. Built as part of a FreeCodeCamp module.

---

## 📸 Overview

CatPhotoApp is a simple webpage that celebrates the internet’s favorite animal — cats! It demonstrates core HTML elements including:

- Headings (`<h1>`, `<h2>`, `<h3>`)
- Paragraphs and hyperlinks
- Images with `alt` text
- Unordered and ordered lists
- Semantic tags like `<main>`, `<section>`, `<figure>`, and `<footer>`

---

## 🧱 HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>CatPhotoApp</title>
  </head>
  <body>
    <main>
      <!-- Cat Photos Section -->
      <section>
        <h2>Cat Photos</h2>
        <p>Everyone loves <a href="https://freecatphotoapp.com">cute cats</a> online!</p>
        <p>See more <a target="_blank" href="https://freecatphotoapp.com">cat photos</a> in our gallery.</p>
        <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">

      </section>

      <!-- Cat Lists Section -->
      <section>
        <h2>Cat Lists</h2>
        <h3>Things cats love:</h3>
        <ul>
          <li>catnip</li>
          <li>laser pointers</li>
          <li>lasagna</li>
        </ul>

       
         <figure>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
  <figcaption>Cats <em>love</em> lasagna.</figcaption>
</figure>

          <figcaption>Cats <em>love</em> lasagna.</figcaption>
        </figure>

        <h3>Top 3 things cats hate:</h3>
        <ol>
          <li>flea treatment</li>
          <li>thunder</li>
          <li>other cats</li>
        </ol>
        <figure>
          <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Two tabby kittens sleeping together on a couch">

          <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
        </figure>
      </section>
    </main>

    <footer>
      <p>No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a></p>
    </footer>
  </body>
</html>



