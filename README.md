# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
/* style.css */

/* Selectors */
body {
    background-color: #f0f8ff; /* Light blue background */
    font-family: 'Arial', sans-serif; /* Font for the body */
    margin: 0;
    padding: 0;
}

/* Class selector for paragraph */
.text-container {
    font-size: 18px; /* Text size */
    color: #333333; /* Dark grey text color */
    line-height: 1.6; /* Spacing between lines */
    margin: 20px; /* Margin around the paragraph */
    padding: 15px; /* Padding inside the paragraph */
    border: 2px solid #007bff; /* Blue border around paragraph */
    border-radius: 8px; /* Rounded corners */
}

/* ID selector for heading */
#main-heading {
    text-align: center; /* Center the heading */
    color: #2c3e50; /* Dark color for the heading */
    font-family: 'Verdana', sans-serif; /* Different font for the heading */
    margin-top: 50px; /* Top margin for spacing */
}

/* Style for image */
#featured-image {
    display: block;
    max-width: 100%;
    height: auto;
    border-radius: 8px; /* Rounded corners for the image */
    margin: 20px auto; /* Center the image */
}

/* Class selector for button */
.btn {
    display: inline-block;
    background-color: #28a745; /* Green background for button */
    color: white; /* White text color */
    padding: 10px 20px;
    text-align: center;
    border-radius: 5px; /* Rounded button corners */
    text-decoration: none; /* Remove underline */
    margin-top: 20px;
}

.btn:hover {
    background-color: #218838; /* Darker green when hovered */
}

Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment Page</title>
    <!-- Link to the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1 id="main-heading">Welcome to My Styled Page</h1>

    <div class="text-container">
        <p>
            This is a simple HTML page styled with an external CSS file. We are using different selectors such as classes, IDs, and more. The design focuses on readability and aesthetic appearance using margins, padding, borders, colors, and typography.
        </p>
    </div>

    <!-- Image styled with ID selector -->
    <img id="featured-image" src="https://via.placeholder.com/600x400" alt="Sample Image">

    <!-- Button styled with a class -->
    <a href="#" class="btn">Click Me</a>

</body>
</html>


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
