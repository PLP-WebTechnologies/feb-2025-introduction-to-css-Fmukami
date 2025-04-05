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

Happy Coding! 💻✨




<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Styled Page</title>
  <!-- Link to External CSS File -->
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header Section -->
  <header class="header">
    <h1>Welcome to My Styled Page!</h1>
    <p>This is a sample page styled using CSS.</p>
  </header>

  <!-- Image Section -->
  <section class="image-section">
    <img src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg" alt="Nature Landscape" />
  </section>

  <!-- Content Section -->
  <section class="content">
    <h2>About this Page</h2>
    <p>This page demonstrates the use of CSS selectors, margin, padding, and borders.</p>
  </section>

  <footer>
    <p>&copy; 2025 My Styled Page</p>
  </footer>

</body>
</html>



/* 1. General Body Styling */
body {
  font-family: 'Arial', sans-serif;
  background-color: #f4f4f4;
  margin: 0;
  padding: 0;
  color: #333;
}

/* 2. Header Styling with Class Selector */
.header {
  background-color: #4CAF50;
  color: white;
  text-align: center;
  padding: 20px;
  border-bottom: 5px solid #333;
}

.header h1 {
  font-size: 2.5rem;
}

.header p {
  font-size: 1.2rem;
}

/* 3. Image Section Styling with Class Selector */
.image-section img {
  width: 100%;
  height: auto;
  border: 3px solid #ddd;
  border-radius: 10px;
  padding: 5px;
  margin-top: 20px;
}

/* 4. Content Section Styling with Class Selector */
.content {
  padding: 20px;
  margin: 20px auto;
  max-width: 800px;
  background-color: white;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
}

.content h2 {
  font-size: 2rem;
  color: #333;
}

.content p {
  font-size: 1rem;
  line-height: 1.6;
}

/* 5. Footer Styling with ID Selector */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
  position: fixed;
  width: 100%;
  bottom: 0;
}

/* 6. Link Styling (Example of a Selector) */
a {
  color: #4CAF50;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

