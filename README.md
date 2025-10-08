# Ex.08 Design of Interactive Image Gallery
## Date:8/10/2025

## AIM:8/10/2025
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
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Multiple Images Enlarge on Click</title>
<style>
  .clickable-image {
    width: 150px;
    height: auto;
    margin: 10px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .enlarged {
    transform: scale(2);
    z-index: 10;
    position: relative;
  }
</style>
</head>
<body>

<img class="clickable-image" src="https://www.uws.ac.uk/media/1105/edinburgh-1969709_1920.jpg?cc=0.34179384741129043,0,0.1489106845917536,0.23902933964657158&width=650&height=650&v=1dada051d07e800" alt="Image 1" />
<img class="clickable-image" src="https://di-uploads-development.dealerinspire.com/bmwofsandiego/uploads/2023/05/BMW-Mobile-1.png" alt="Image 2" />
<img class="clickable-image" src="https://www.theamericanacademy.com/cdn/shop/products/art212_3024x.jpg?v=1566336034" alt="Image 3" />
<img class="clickable-image" src="https://images.pexels.com/photos/2747446/pexels-photo-2747446.jpeg?cs=srgb&dl=pexels-wolfgang-1002140-2747446.jpg&fm=jpg" alt="Image 4" />

<script>
  const images = document.querySelectorAll('.clickable-image');

  images.forEach(img => {
    img.addEventListener('click', () => {
      img.classList.toggle('enlarged');
    });
  });
</script>

</body>
</html>

```
## OUTPUT:
<<<<<<< HEAD
![alt text](gallery.png.png)



## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
