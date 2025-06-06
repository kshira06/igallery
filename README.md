# Ex.08 Design of Interactive Image Gallery
## Date: 04-05-2025

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
<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: beige;


}
div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: 700px;
}

div.desc {
  padding: 15px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.responsive {
  padding: 0 6px;
  float: left;
  width: 24.99999%;
}

@media only screen and (max-width: 700px) {
  .responsive {
    width: 49.99999%;
    margin: 6px 0;
  }
}

@media only screen and (max-width: 500px) {
  .responsive {
    width: 100%;
  }
}

.clearfix:after {
  content: "";
  display: table;
  clear: both;
}
</style>
</head>
<body>

<h1 style="text-align: center; background-color:plum;">Interactive Image Gallery</h1>
<center>
  <h2 >Kshira K- 212224040166</h2>
</center>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img1.jpg">
      <img src="img1.jpg" alt="Giraffe" height="250px"  >
    </a>
  </div>
</div>


<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img2.jpg">
      <img src="img2.jpg" alt="deer" height="250px">
    </a>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img3.jpg">
      <img src="img3.jpg" alt="boat" height="250px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img4.jpg">
      <img src="img4.jpg" alt="bridge" height="250px" >
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img5.jpg">
      <img src="img5.jpg" alt="tree" height="250px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img6.jpg">
      <img src="img6.jpg" alt="birds" height="250px">
    </a>

  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img7.jpg">
      <img src="img7.jpg" alt="sunset" height="250px">
    </a>

  </div>
</div>



<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="img8.jpg">
      <img src="img8.jpg" alt="elephant" height="250px">
    </a>

  </div>
</div>



</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot (74).png>)
![alt text](<Screenshot (75).png>)

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
