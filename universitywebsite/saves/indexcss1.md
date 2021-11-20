- {
  margin: 0;
  padding: 0;
  }

body {
font-family: "Raleway", sans-serif;
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

.header {
overflow: hidden;
background-color: black; /_f1f1f1_/
padding: 20px 10px;
box-shadow: black;
}

.header a {
float: left;
color: white;
text-align: center;
padding: 12px;
text-decoration: none;
font-size: 18px;
line-height: 25px;
border-radius: 4px;
}

.header a.logo {
font-size: 25px;
font-weight: bold;
}

.header a:hover {
background-color: dodgerblue;
color: white;
}

.header a.active {
background-color: dodgerblue;
color: white;
}

.header-right {
float: right;
}

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
/_ RESP HEADER END _/

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
