
<!DOCTYPE html>
<html lang="en" >

<head>

  <meta charset="UTF-8">
  
  <link rel="apple-touch-icon" type="image/png" href="https://cpwebassets.codepen.io/assets/favicon/apple-touch-icon-5ae1a0698dcc2402e9712f7d01ed509a57814f994c660df9f7a952f3060705ee.png" />

  <meta name="apple-mobile-web-app-title" content="CodePen">

  <link rel="shortcut icon" type="image/x-icon" href="https://cpwebassets.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" />

  <link rel="mask-icon" type="image/x-icon" href="https://cpwebassets.codepen.io/assets/favicon/logo-pin-b4b4269c16397ad2f0f7a01bcdf513a1994f4c94b8af2f191c09eb0d601762b1.svg" color="#111" />


  
  <title>CodePen - Website Project</title>
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">

  
  
<style>
header{
  padding-left: 10px;
  padding-right: 10px;
}





.skip-link screen-reader-text{
  display: flex;
}

h1{
  z-index: 2;
  font-size: 2.3em;
}
.header-wrapper {
	background-color: purple;
  padding-left: 10px;
  padding-right: 10px;
}

.brand {
	display: flex;
  transition: 0.55s all ease;
  transform-origin: left bottom;
}
.brand{
  transition: 0.4s all ease;
}
.brand:hover {
  transform:scale(1.05);
  background-color: rgb(0, 0, 0, 0.2);
}

nav ul li{
  transition: 0.3s all ease;
}
.nb:hover{
  background-color: rgb(0, 0, 0, 0.1);
}
nav ul li:hover{
  transform:scale(1.08);
}


h1 {
	font-weight: 100;
}

.#{ background-color: none; }

.paladin {
  font-weight: 900;
	display: flex;
	letter-spacing: 2px;
	float: left;
  left: 14px;
  font-family: 'Lato', sans-serif;
}

.webgroup {
	display: flex;
	font-family: "Arial", Helvetica, Sans-serif;
	font-size: 23px;
	float: left;
  position: absolute;
  top: 65px;
  left: 14px;
}

.wordmark {
	display: flex;
	flex-direction: column;
  float: left;
}

header {
	text-decoration: none;
	display: flex;
	text-align: center;
}

.container {
	font-family: "Arial", Helvetica, serif;
	display: flex;
	background: purple;
	align-items: center;
	text-decoration: none;
	color: white;
	align-items: center;
}

div a {
	font-family: "Arial", Helvetica, serif;
	display: flex;
	align-items: center;
	text-decoration: none;
	color: white;
}

.brand {
	text-decoration: none;
	font-family: "Times New Roman", Times, serif;
	color: white;
	background: purple;
	display: flex;
	justify-content: flex-start;
}

nav ul {
	text-decoration: none;
	display: flex;
	float: right;
	position: absolute;
	background-color: purple;
	right: 10px;
  top: 25px;
}

.header {
	display: flex;
	position: absolute;
	left: 1px;
	right: 1px;
	top: 10px;
	height: 100px;
	text-align: center;
}

primary-nav-mobile {
	display: flex;
	position: absolute;
	right: 10px;
}

li {
	display: flex;
	text-decoration: none;
	list-style: none;
	padding-right: 10px;
  padding-left: 10px;
	flex-direction: row-reverse;
	right: 0;
	color: white;
}

.primary-nav__cta {
	background-color: red;
	border: none;
	color: white;
	padding: 15px 15px;
	text-decoration: none;
	display: inline-block;
	font-size: 16px;
	border-radius: 15px;
}



@media screen and (max-width: 650px) {
	li a {
		display: none;
  }
  #menu-button {
		display: inline-block;
    position: relative;
    right: 0px;
    float: right;
    align-self: end;
	}
  #menu{
    display: block;
  }
}
  
  


@media screen and (max-width: 650px) {
	.primary-nav__cta {
		visibility: hidden;
    display: none;
	}

}

@media screen and (min-width: 650px) {
  #menu-button {
		display: none;
	}
  #menu{
    display: none;
  }
}



a:hover {
	color: orange;
}





.top{
  text-align: center;
  padding: 20px;
}




.header1{
  padding: 10px;
  font-size: 2em;
}

p{
  font-family: 'Lato', sans-serif;
  line-height: 1.5em;
  text-indent: 75px;
  padding: 10px;
  font-size: 1.4em;
}


.first{
  background: purple;
}
#menu-button{
  
  float: right;
  background: indigo;
  width: 50px;
  border-radius: 5px;
  position: absolute;
  right: 0;
  float: right;
  cursor: pointer;
  transition: all linear .3s;
  padding: 4px;
  margin: 35px;
  z-index: 1;
}

#menu-button.active{
  background: blueviolet;
  position: absolute;
  right: 0;
  top: 0;
}
#line-1,#line-2,#line-3{
  
  width: 90%;
  background: #fff;
  height: 8px;
  margin: 4px auto;
  border-radius: 2px;
  transition: all linear .3s;
}

#line-1.active{
-webkit-transform: translate(0px,12px) rotate(45deg);
transform: translate(0px,12px) rotate(45deg);
}

#line-2.active{
opacity: 0;
}

#line-3.active{
-webkit-transform: translate(0px, -12px) rotate(-45deg);
transform: translate(0px, -12px) rotate(-45deg);
}

#menu{
  background: indigo;
  width: 150px;
  padding: 10px;
  padding-top: 30px;
  color: #fff;
  font-family: arial;
  font-size: 1.5rem;
  display: none;
  position: absolute;
  right: 33px;
  top: 110px;
  border-radius: 5px;
  margin-top: 20px;
}

#menu ul{
  list-style: none;
}

#menu ul li{
  margin: 8px 0;
}

html {
  scroll-behavior: smooth;
}
.parallax-item:nth-child(2) {
  background-image: linear-gradient(rgba(255, 255, 255, 0.5), rgba(255, 255, 255, 0.5)), url("https://images.rawpixel.com/image_social_landscape/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvcGYtYWtlMTI4MC1ha2UuanBn.jpg?s=795ZOA5Hr3TFT6WCrot49CdKWBlSq7uhZXm8h8rRbFg");
  background-size: cover;
}
.parallax-item:nth-child(4) {
  background-image: linear-gradient(rgba(255, 255, 255, 0.7), rgba(255, 255, 255, 0.7)), url("https://i.ibb.co/McZZhWk/wild-corn-grass-closeup-barley-260nw-2172525525-1.png");
  background-size: cover;
}
.parallax-item:nth-child(6) {
  background-image: linear-gradient(rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0.6)), url("https://i.ibb.co/RvvCP3h/image.png");
  background-size: cover;
}
.parallax-item:nth-child(8) {
  background-image: linear-gradient(rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8)), url("https://i.ibb.co/vVsqWkg/image-1.png");
  background-size: fit;
}
.parallax-item{
  margin: 25px;
  padding-top: 1px;
  padding-bottom: 1px;
}





















        footer section {
            padding: 60px 0;
           /* min-height: 100vh;*/
        }
 footer ul {
            margin: 0;
            padding: 0;
            list-style: none;
        }
footer .contact-area {
    border-bottom: 1px solid #353C46;
}

.contact-content p {
    font-size: 15px;
    margin: 30px 0 60px;
    position: relative;
}

.contact-content p::after {
    background: #353C46;
    bottom: -30px;
    content: "";
    height: 1px;
    left: 50%;
    position: absolute;
    transform: translate(-50%);
    width: 80%;
}

.contact-content h6 {
    color: #8b9199;
    font-size: 15px;
    font-weight: 400;
    margin-bottom: 10px;
}

.contact-content span {
    color: #353c47;
    margin: 0 10px;
}

.contact-social {
    margin-top: 30px;
}

.contact-social > ul {
    display: inline-flex;
}

.contact-social ul li a {
    border: 1px solid #8b9199;
    color: #8b9199;
    display: inline-block;
    height: 40px;
    margin: 0 10px;
    padding-top: 7px;
    transition: all 0.4s ease 0s;
    width: 40px;
}

.contact-social ul li a:hover {
    border: 1px solid #FAB702;
    color: #FAB702;
}

.contact-content img {
    max-width: 210px;
}

footer section, footer {
    background: #1A1E25;
    color: #868c96;
}

footer p {
    padding: 40px 0;
    text-align: center;
}

footer img {
    width: 44px;
}
</style>

  
  
  
  

</head>

<body translate="no" >
  <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lato&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lato&display=swap" rel="stylesheet">

<div class="header-wrapper">
   <header class="site-header">
      <!-- <a class="skip-link screen-reader-text" href="#primary">Skip to content</a> -->
     
      <div class="container" >
         <a href="https://cdpn.io/pen/debug/VwGMKVb" class="brand">
           
            <h1 class="wordmark">
              <div class = "paladin" style = "padding: 20px;"><strong>CORN</strong></div>
            </h1>
              
            </a>
            <nav class="primary-nav-mobile" media="screen and (max-width: 650px)">
               <ul>
                  <li class = "nb"><a href = "https://cdpn.io/pen/debug/VwGMKVb" media="screen and (max-width: 650px)">Corn</a></li>
                 <li class = "nb"><a href="https://cdpn.io/pen/debug/oNPyWjQ" media="screen and (max-width: 650px)">Corndogs</a></li>
                 <li class = "nb"><a href="https://cdpn.io/pen/debug/oNPyWZV" media="screen and (max-width: 650px)">Contact</a></li>
                 <li class = "nb"><a href="https://cdpn.io/pen/debug/RwYJVQN" media="screen and (max-width: 650px)">About</a></li>
                 <li class="primary-nav__cta"><a href="https://stopandshop.com/groceries/produce/fresh-vegetables/corn.html" media="screen and (max-width: 650px)"><strong>Buy</strong></a></li> </ul> 
           </nav></ul>
       
           
      </div>

  <div media="screen and (max-width: 650px)">
            <div id="menu-button">
             <div id="line-1"></div>
              <div id="line-2"></div>
              <div id="line-3"></div>
              </div>
                <div id="menu">
                <ul>
                  <a href="https://cdpn.io/pen/debug/VwGMKVb"><li>Corn</li></a>
                  <a href="https://cdpn.io/pen/debug/oNPyWjQ"><li>Corndogs</li></a>
                <a href="https://cdpn.io/pen/debug/oNPyWZV"><li>Contact</li></a>
                  <a href="https://cdpn.io/pen/debug/RwYJVQN"><li>About</li></a>
                  <a href="https://stopandshop.com/groceries/produce/fresh-vegetables/corn.html"><li>Buy</li></ul></a>
</div></div>
  <div media="screen and (max-width: 650px)" class  = "search">
  </div>
   </header>
</div>  
<p style = "font-size: 8px; padding: 0px; ">(these links all work)</p>
<h1 class = "top">Corn/Maize</h1>
<section>
  <div class="parallax-item">
<br>
    <h2 class = "header1">A quick description</h2></div>
  <div id="parallax" class="parallax-item">
<p>Maize, also known as corn in North American and Australian English, is a cereal grain first domesticated by indigenous peoples in southern Mexico about 10,000 years ago. The leafy stalk of the plant produces pollen inflorescences (or "tassels") and separate ovuliferous inflorescences called ears that when fertilized yield kernels or seeds, which are fruits. The term maize is preferred in formal, scientific, and international usage as the common name because this refers specifically to this one grain whereas corn refers to any principal cereal crop cultivated in a country. For example, in North America and Australia corn is often used for maize, but in England and Wales it can refer to wheat or barley, and in Scotland and Ireland to oats. Though it is a major food in many parts of the world, it is inferior to other cereals in nutritional value. In addition to its use as a fresh and processed food for human consumption, corn is an important livestock feed and is used as raw material in industry. American Indians taught colonists to grow corn, including some varieties of yellow corn that are still popular as food, as well as varieties with red, blue, pink, and black kernels, often banded, spotted, or striped, that today are typically regarded as ornamental. The tall annual grass has a stout, erect, solid stem and large narrow leaves with wavy margins. Inedible parts of the plant are used in industry—stalks for paper and wallboard; husks for filling material; and cobs for fuel, to make charcoal, and in the preparation of industrial solvents. Corn husks also have a long history of use in the folk arts for objects such as woven amulets and corn husk dolls. In the U.S. corn is the most important crop, but slightly more acres of soybeans are planted.</p>
  </div>
  <div class = "parallax-item">
    <h2 class = "header1">History</h2>
      
    </div>
  <div id = "parallax1" class = "parallax-item">
<p>Corn was first domesticated by native peoples in southern Mexico about 10,000 years ago. Modern corn is believed to have been derived from the Balsas teosinte, a wild grass. Its culture had spread as far north as southern Maine by the time of European settlement of North America, and Native Americans taught European colonists to grow the indigenous grains. Since its introduction into Europe by Christopher Columbus and other explorers and colonizers, corn has spread to all areas of the world suitable to its cultivation. It is grown from 58° N latitude in Canada and Russia to 40° S latitude in South America, with a corn crop maturing somewhere in the world nearly every month of the year. It is the most important crop in the United States and is a staple food in many places. Ancient farmers in what is now Mexico took the first steps in domesticating maize when they simply chose which kernels (seeds) to plant. These farmers noticed that not all plants were the same. Some plants may have grown larger than others, or maybe some kernels tasted better or were easier to grind. The farmers saved kernels from plants with desirable characteristics and planted them for the next season's harvest. This process is known as selective breeding or artificial selection. Maize cobs became larger over time, with more rows of kernels, eventually taking on the form of modern maize.</p>
  </div>
  <div class = "parallax-item">
    <h2 class = "header1">Today</h2></div><div id = "parallax2"class = "parallax-item">
  <p>Today, corn is the third largest plant-based food source in the world. Despite its importance as a major food in many parts of the world, corn is inferior to other cereals in nutritional value. Its protein is of poor quality, and it is deficient in niacin. Diets in which it predominates often result in pellagra (niacin-deficiency disease). Corn is high in dietary fibre and rich in antioxidants. Unlike many other cereal grains, corn flour is gluten-free and cannot be used alone to make rising breads. It is widely used, however, in Latin American cuisine to make masa, a kind of dough used in such staple foods as tortillas, arepas, and tamales. In the United States and many other places, sweet corn is boiled or roasted on the cob, creamed, converted into hominy (hulled kernels) or meal, and cooked in corn puddings, mush, polenta, griddle cakes, cornbread, and scrapple. It is also used for popcorn, confections, and various manufactured breakfast cereal preparations.</p>
  </div>  
  <div id = "parallax" class = "parallax-item">
    <h2 class = "header1">Corn Biofuel</h2></div><div id = "parallax3" class = "parallax-item">
  <p>Corn is also used to produce ethanol (ethyl alcohol), a first-generation liquid biofuel. In the United States corn ethanol is typically blended with gasoline to produce “gasohol,” an automotive fuel that is 10 percent ethanol. Although corn-based biofuels were initially touted as environmentally friendly alternatives to petroleum, their production diverts arable land and feedstock from the human food chain, sparking a “food versus fuel” debate. In addition, crops grown for biofuel can compete for the world’s natural habitats, and the emphasis on ethanol derived from corn has shifted grasslands and brushlands to corn monocultures in some places, impacting biodiversity. Beyond land-use changes, the process of growing corn to produce ethanol consumes fossil fuels in farming equipment, in fertilizer manufacturing, in corn transportation, and in ethanol distillation. In this respect, ethanol made from corn represents a relatively small energy gain; the energy gain from sugarcane is greater and that from cellulosic ethanol (made from nonedible plant parts such as agricultural waste) or algae biodiesel could be even greater, though the conversion technology is generally less efficient than that of first-generation biofuels.</p>
  </div>
  
  </section>




 <footer>
        <p>Copyright &copy; CORN All Rights Reserved.</p>
   <br>
    </footer>
  
  <script src='//cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js'></script>
      <script id="rendered-js" >
$("#menu-button").click(function(){
  $(this).toggleClass("active");
  $("#line-1").toggleClass("active");
  $("#line-2").toggleClass("active");
  $("#line-3").toggleClass("active");
  $("#menu").slideToggle("slow");
});




















const parallax = document.getElementById("parallax");

// Parallax Effect for DIV 1
window.addEventListener("scroll", function () {
  let offset = window.pageYOffset;
  parallax.style.backgroundPositionY = offset * -0.4 + "px";});

const parallax1 = document.getElementById("parallax1");

// Parallax Effect for DIV 2
window.addEventListener("scroll", function () {
  let offset = window.pageYOffset;
  parallax1.style.backgroundPositionY = offset * -0.4 + "px";});


const parallax2 = document.getElementById("parallax2");

// Parallax Effect for DIV 3
window.addEventListener("scroll", function () {
  let offset = window.pageYOffset;
  parallax2.style.backgroundPositionY = offset * -0.4 + "px";});

const parallax3 = document.getElementById("parallax3");

// Parallax Effect for DIV 4
window.addEventListener("scroll", function () {
  let offset = window.pageYOffset;
  parallax3.style.backgroundPositionY = offset * -0.4 + "px";});
    </script>

  

</body>

</html>
 
