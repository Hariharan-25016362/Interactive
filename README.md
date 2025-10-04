# Ex.08 Design of Interactive Image Gallery
## Date:4.10.2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
ex8.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Interactive Image Gallery</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <h2>Interactive Image Gallery</h2>
  <div class="gallery">
    <img src="1.png" alt="Image 1">
    <img src="2.png" alt="Image 2">
    <img src="3.png" alt="Image 3">
    <img src="4.png" alt="Image 4">
  </div>

</body>
</html>


style.css
/* style.css */
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #f8f9fa;
  margin: 0;
  padding: 20px;
}

h2 {
  text-align: center;
  color: #333;
  margin-bottom: 30px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  max-width: 1200px;
  margin: auto;
}

.gallery img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  cursor: pointer;
}

.gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 12px rgba(0,0,0,0.2);
}
```

## OUTPUT:
Screenshot 2025-10-04 154838.png

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
