# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Styling Demo</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h1 id="main-heading">Welcome to My Page</h1>

  <p class="intro-text">This is a styled paragraph to demonstrate font, color, and spacing.</p>

  <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Beautiful Scenery" class="styled-image">

  <div class="card">
    <h2>Contact Info</h2>
    <p>Name: Alex</p>
    <p>Email: alex@example.com</p>
  </div>

</body>
</html>

/* ID Selector */
#main-heading {
  color: teal;
  font-family: 'Georgia', serif;
  text-align: center;
}

/* Class Selector */
.intro-text {
  font-family: 'Arial', sans-serif;
  color: #333;
  margin: 20px;
  padding: 10px;
  border: 2px solid #ccc;
  background-color: #f9f9f9;
}

/* Element Selector */
body {
  background-color: #f0f8ff;
  margin: 0;
  padding: 20px;
}

/* Image Styling */
.styled-image {
  display: block;
  width: 100%;
  max-width: 500px;
  border: 5px solid #008080;
  border-radius: 10px;
  margin: 20px auto;
}

/* Additional styling for div */
.card {
  padding: 15px;
  border: 1px solid #999;
  background-color: #ffffff;
  width: fit-content;
  margin: auto;
  font-family: 'Courier New', monospace;
}

   

Happy Coding! 💻✨
