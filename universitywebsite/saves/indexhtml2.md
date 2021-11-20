<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="index.css">

    <!-- GOOGLE FONTS STUFF -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@600&display=swap" rel="stylesheet">


    <title>University of monkeys</title>

</head>
<body>
    <!-- RESP HEADER START -->
    <div class="header">
        <a href="#default" class="logo">Naveen Ramanthan</a>
        <div class="header-right">
          <a class="active" href="#home">Home</a>
          <a href="#contact">Achievements</a>
          <a href="#about">About</a>
          <a href="#about">Socials</a>
          <a href="#about">Contact Me</a>
        </div>
      </div>
      <!-- RESP HEADER END -->

<!-- SECTION 1 START -->
<div class="section1">
  <h1 class="titletxt">Hello!</h1>
  <h1 class="para1">I'm Naveen,<br>
  I am a game developer, app developer, web developer, <br>
  I specialize in programming.
  </h1>
</div>
<!-- SECTION 1 END -->

<!-- SECTION 2 START -->
<h1 class="sec2acht" style="text-align: center; padding-bottom: 20px;">About me!</h1>

<div class="section 2">

  <div class="slideshow-container">
  
  <div class="mySlides fade">
    <div class="numbertext">1 / 3</div>
    <img src="https://picsum.photos/seed/picsum/1000/350" style="width:100%">
    <div class="text">Caption Text</div>
  </div>
  
  <div class="mySlides fade">
    <div class="numbertext">2 / 3</div>
    <img src="https://picsum.photos/seed/picsum/1000/350" style="width:100%">
    <div class="text">Caption Two</div>
  </div>
  
  <div class="mySlides fade">
    <div class="numbertext">3 / 3</div>
    <img src="https://picsum.photos/seed/picsum/1000/350" style="width:100%">
    <div class="text">Caption Three</div>
  </div>
  
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
  
  </div>
  <br>
  
  <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span> 
    <span class="dot" onclick="currentSlide(2)"></span> 
    <span class="dot" onclick="currentSlide(3)"></span> 
  </div>
  
  <script>
    var slideIndex = 1;
  showSlides(slideIndex);
  
  // Next/previous controls
  function plusSlides(n) {
    showSlides(slideIndex += n);
  }
  
  // Thumbnail image controls
  function currentSlide(n) {
    showSlides(slideIndex = n);
  }
  
  function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    if (n > slides.length) {slideIndex = 1}
    if (n < 1) {slideIndex = slides.length}
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";
    }
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";
    dots[slideIndex-1].className += " active";
  }
  </script>
</div>
<!-- SECTION 2 END -->

      <!-- WAVE START -->
    <!-- <div class="custom-shape-divider-top-1637304860">
        <svg data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 120" preserveAspectRatio="none">
            <path d="M985.66,92.83C906.67,72,823.78,31,743.84,14.19c-82.26-17.34-168.06-16.33-250.45.39-57.84,11.73-114,31.07-172,41.86A600.21,600.21,0,0,1,0,27.35V120H1200V95.8C1132.19,118.92,1055.71,111.31,985.66,92.83Z" class="shape-fill"></path>
        </svg>
    </div> -->
      <!-- WAVE END -->


    <!-- ION ICONS STUFF -->
      <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
      <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>

</body>
</html>
