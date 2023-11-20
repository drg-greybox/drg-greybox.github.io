---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# <img style="float: left;" src="images/drglogo.png"> <img style="float: middle;" src="images/sheffieldlogo.jpg">

#<br>

#<p align="center">
 # <img  src="images/sheffieldgrouplogo.jpg">
#</p>

layout: page
title: Physics-informed machine learning for structural dynamics 
show_sidebar: true
#hero_image: /path/to/DRG-logo.jpg
hero_height: is-small
#darken( $base-color, 10% )
background-color: rgba($hero-darken, 0.3);
#hero_darken: true

---

Physics-informed machine learning is a fast growing area of interest. Our team in the Dynamics Research Group at the University of Sheffield are looking at its use in structural dynamics, for structural health monitoring and system identification. These pages introduce the team and give a bit of background on our research with links to papers and presentations. 

<br>

<!-- <p align="center">
<img  src="https://raw.githubusercontent.com/drg-greybox/drg-greybox.github.io/master/docs/images/elizabeth_cross_group.jpg">
</p> -->

<!-- <p align="center">
<img  src="images/surfaces.png">
<img  src="images/spectrum.png">
</p>  -->

<!-- <img  src="images/plane_resize.png"> -->

<!-- <img  src="images/wave.png"> -->

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box;}
body {font-family: Ubuntu, sans-serif;}
.mySlides {display: none;}
img {vertical-align: middle;}
/* Slideshow container */
.slideshow-container {
  max-width: 350px;
  position: relative;
  margin: auto;
}
/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}
/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}
/* The dots/bullets/indicators */
.dot {
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}
.active {
  background-color: #717171;
}
/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1s;
}
@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}
/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>
</head>
<body>

<!-- <h2>Automatic Slideshow</h2> -->
<!-- <p>Change image every 2 seconds:</p> -->

<div class="slideshow-container">

<div class="mySlides fade">
  <!-- <div class="numbertext">1 / 3</div> -->
  <p align="center">
  <img src="images/spectrum.png">
  </p>
  <!-- <div class="text">test1</div> -->
</div>

<div class="mySlides fade">
  <!-- <div class="numbertext">2 / 3</div> -->
  <p align="center">
  <img src="images/wave.png">
  </p>
  <!-- <div class="text">test2</div> -->
</div>

<div class="mySlides fade">
  <!-- <div class="numbertext">3 / 3</div> -->
  <p align="center">
  <img src="images/plane.png">
  </p>
  <!-- <div class="text">test3</div> -->
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 5000); // Change image every 2 seconds
}
</script>

</body>
</html> 

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>





<p align="center">
<img  src="images/drg-logo.png">
<img  src="images/sheffieldlogo.png">
</p> 

