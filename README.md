# Ex.08 Design of Interactive Image Gallery
# Date:13.12.2025
# AIM:
To design a web application for an inteactive image gallery with minimum five images.

# DESIGN STEPS:
## Step 1:
Clone the github repository and create Django admin interface.

## Step 2:
Change settings.py file to allow request from all hosts.

## Step 3:
Use CSS for positioning and styling.

## Step 4:
Write JavaScript program for implementing interactivity.

## Step 5:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# PROGRAM :
'''
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Image Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background: #f4f4f4;
    }

    h1 {
      text-align: center;
      margin-bottom: 20px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 15px;
      max-width: 1200px;
      margin: auto;
    }

    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 8px;
      cursor: pointer;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>

  <h1>My Image Gallery</h1>

  <div class="gallery">
    <img src="images/image1.jpg" alt="Image 1">
    <img src="images/image2.jpg" alt="Image 2">
    <img src="images/image3.jpg" alt="Image 3">
    <img src="images/image4.jpg" alt="Image 4">
    <img src="images/image5.jpg" alt="Image 5">
    <img src="images/image6.jpg" alt="Image 6">
  </div>

</body>
</html>
'''
# OUTPUT:
# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
