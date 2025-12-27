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


    <style>
        body {
            margin: 0;
            font-family: Georgia, serif;
            background: #dff7f4;
            text-align: center;
        }

        h1 {
            margin: 30px 0;
            letter-spacing: 3px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 30px;
            padding: 40px;
            max-width: 1100px;
            margin: auto;
        }

        .gallery img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }
    </style>
</head>

<body>

    <h1>IMAGE GALLERY</h1>

    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470" alt="Nature">
        <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee" alt="Waterfall">
        <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e" alt="Backwater">
        <img src="https://images.unsplash.com/photo-1524492412937-b28074a5d7da" alt="Temple">
        <img src="https://images.unsplash.com/photo-1501973801540-537f08ccae7b" alt="Beach">
    </div>

</body>
</html>


   
'''
# OUTPUT:![](gallery.png)
# RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
