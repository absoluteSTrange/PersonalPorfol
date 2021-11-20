- {
  margin: 0;
  padding: 0;
  }

body {
font-family: "Raleway", sans-serif;
background-color: #f15d4e;
}

/_ TOP WAVE START _/
.custom-shape-divider-top-1637304860 {
position: absolute;
top: 0;
left: 0;
width: 100%;
overflow: hidden;
line-height: 0;
transform: rotate(180deg);
}

.custom-shape-divider-top-1637304860 svg {
position: relative;
display: block;
width: calc(148% + 1.3px);
height: 138px;
}

.custom-shape-divider-top-1637304860 .shape-fill {
fill: #000000;
}
/_ TOP WAVE END _/

/_ RESP HEADER START _/

- {
  box-sizing: border-box;
  }

body {
margin: 0;
}

/_ Style the header with a grey background and some padding _/
.header {
overflow: hidden;
background-color: #f1f1f1;
padding: 20px 10px;
}

/_ Style the header links _/
.header a {
float: left;
color: black;
text-align: center;
padding: 12px;
text-decoration: none;
font-size: 18px;
line-height: 25px;
border-radius: 4px;
}

/_ Style the logo link (notice that we set the same value of line-height and font-size to prevent the header to increase when the font gets bigger _/
.header a.logo {
font-size: 25px;
font-weight: bold;
margin-left: 20px;
}

/_ Change the background color on mouse-over _/
.header a:hover {
background-color: #ddd;
color: black;
}

/_ Style the active/current link_/
.header a.active {
background-color: dodgerblue;
color: white;
}

/_ Float the link section to the right _/
.header-right {
float: right;
}

/_ Add media queries for responsiveness - when the screen is 500px wide or less, stack the links on top of each other _/
@media screen and (max-width: 500px) {
.header a {
float: none;
display: block;
text-align: left;
}
.header-right {
float: none;
}
}
/_ RESP HEADER END --------------------------------------------------------------------_/

/_ HOME SEC START --------------------------------------------------------------------_/
.titletxt {
padding-top: 80px;
margin-left: 40px;
font-size: 100px;
color: white;
}

.para1 {
padding-top: 80px;
margin-left: 40px;
font-size: 30px;
color: white;
}

ion-icon {
font-size: 34px;
padding-left: 5px;
}

.zoom {
transition: transform 0.2s; /_ Animation _/
}

.zoom:hover {
transform: scale(
1.5
); /_ (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) _/
}

/_ #1 SEC END --------------------------------------------------------------------_/
/_ #2 SEC START --------------------------------------------------------------------_/
.sec2acht {
color: white;
}

- {
  box-sizing: border-box;
  }

.mySlides {
display: none;
}
img {
vertical-align: middle;
}

/_ Slideshow container _/
.slideshow-container {
max-width: 1000px;
position: relative;
margin: auto;
}

/_ Next & previous buttons _/
.prev,
.next {
cursor: pointer;
position: absolute;
top: 50%;
width: auto;
padding: 16px;
margin-top: -22px;
color: white;
font-weight: bold;
font-size: 18px;
transition: 0.6s ease;
border-radius: 0 3px 3px 0;
user-select: none;
}

/_ Position the "next button" to the right _/
.next {
right: 0;
border-radius: 3px 0 0 3px;
}

/_ On hover, add a black background color with a little bit see-through _/
.prev:hover,
.next:hover {
background-color: rgba(0, 0, 0, 0.8);
}

/_ Caption text _/
.text {
color: #f2f2f2;
font-size: 15px;
padding: 8px 12px;
position: absolute;
bottom: 8px;
width: 100%;
text-align: center;
}

/_ Number text (1/3 etc) _/
.numbertext {
color: #f2f2f2;
font-size: 12px;
padding: 8px 12px;
position: absolute;
top: 0;
}

/_ The dots/bullets/indicators _/
.dot {
cursor: pointer;
height: 15px;
width: 15px;
margin: 0 2px;
background-color: #bbb;
border-radius: 50%;
display: inline-block;
transition: background-color 0.6s ease;
}

.active,
.dot:hover {
background-color: #717171;
}

/_ Fading animation _/
.fade {
-webkit-animation-name: fade;
-webkit-animation-duration: 1.5s;
animation-name: fade;
animation-duration: 1.5s;
}

@-webkit-keyframes fade {
from {
opacity: 0.4;
}
to {
opacity: 1;
}
}

@keyframes fade {
from {
opacity: 0.4;
}
to {
opacity: 1;
}
}

/_ On smaller screens, decrease text size _/
@media only screen and (max-width: 300px) {
.prev,
.next,
.text {
font-size: 11px;
}
}
/_ #1 SEC END --------------------------------------------------------------------_/
.section1 {
padding-bottom: 400px;
}

/_ Prev_/
.homeimgholder {
float: right;
padding-right: 50px;
padding-top: 20px;
}

.nametag {
float: right;
padding-top: 340px;
margin-right: -218px; /_ 220 works too _/
}

.homemeimg {
width: 300px; /_ width of container _/
height: 300px; /_ height of container _/
object-fit: cover;
border: 2px solid black;
object-position: 50% 20%; /_ try 20px 10px _/ /_<----- idk_/
}

.homemeimg:hover {
box-shadow: 0 0 10px 5px rgba(0, 140, 186, 0.5);
}
