<!--<script>
    import { onMount, onDestroy } from 'svelte';
  
    // Import Pico.css styles
    import 'pico.css';
    import omalako from '$lib/images/omalako.jpeg';
    import prayer from '$lib/images/prayer.jpg';
    import Spear from '$lib/images/Spear.jpg';
  
    // Define the images for the slider
    let images = [
        { src : {omalako}, caption: ''},
        { src :{prayer}, caption: ''},
        { src : {Spear}, caption: ''}
    ];
  
    // Initialize the index of the currently displayed image
    let currentIndex = 0;
  
    // Set the interval (in milliseconds) between automatic transitions
    const interval = 3000;
  
    // Function to navigate to the next image
    function nextImage() {
      currentIndex = (currentIndex + 1) % images.length;
    }
  
    // Function to navigate to the previous image
    function previousImage() {
      currentIndex = (currentIndex - 1 + images.length) % images.length;
    }
  
    // Automatically transition to the next image at the specified interval
    let timer;
    onMount(() => {
      timer = setInterval(nextImage, interval);
    });
  
    // Clear the timer on component destruction to prevent memory leaks
    onDestroy(() => {
      clearInterval(timer);
    });
  </script>
  
  <style>
    /* Add custom styling for the image slider if needed */
  </style>
  

-->
<h2>Office Of the National Chairman</h2>
<p>Changing the state of the Nation for good:</p>

  <!--div class="slider">
    <img src={images[currentIndex]} alt="Slider Image" />
  </!--div>
  
<style>
* {box-sizing: border-box;}
/* body {font-family: Verdana, sans-serif;} */
.mySlides {display: none;}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 1000px;
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

/* .active {
  background-color: #717171;
} */

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
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



<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 3</div>
  <img src={omalako} alt="omalako" style="width:100%">
  <div class="text">Ku ballot 2026-2031</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 3</div>
  <img src={Spear} alt="Jajja's spear" style="width:100%">
  <div class="text">Magulu nnyondo</div>
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 3</div>
  <img src={prayer} alt="prayers" style="width:100%">
  <div class="text">Prayers held at Kyambogo for the president when he was diagnosed</div>
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
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>
-->