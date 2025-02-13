<!DOCTYPE html>
<html lang="en">
<head>
    <title>Famous Composers Throughout the Ages</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <style>
    body {
    height:100%;
    font-family: 'Bookman Old Style',Bookman,'URW Bookman L','Palatino Linotype',serif;
    margin:0;
    }
    body, html{
    background-color: lightgrey;
    height: 100%;
    }
    * {
    box-sizing: border-box;
    }
    .bg-image {
    background-image: url(sheetmusic.jpg);
    filter:blur(5px);
    -webkit-filter: blur(5px);
    height: 100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size:cover;
    }
main{
    border-left: 10px solid #333;
    border-right: 10px solid #333;
}
.bg-text {
    background-color:#333;
    background-color: rgba(0,0,0,0.4);
    color:white;
    font-weight:bold;
    font-size:20px;
    border:3px solid #f1f1f1;
    position:absolute;
    top: 30%;
    left: 10%;
    transform: translate (-50%, -50%);
    z-index: 2;
    width: 80%;
    padding: 10px;
    text-align: center; 
}
h1 {
    background-color:#333;
    color:white;
    padding-top: 30px;
    padding-bottom: 30px;
}
* {
    box-sizing: border-box;
} 
.navbar {
    overflow: hidden;
    background-color: #333;
    position: absolute;
    top:0px;
    width:100%;
}
  .navbar a {
    float: left;
    display:block;
    font-size:20px;
    color: lightgrey;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}
  .dropdown {
    float: left;
    overflow: hidden;
}
.dropdown .dropbtn {
    font-size: 20px;  
    border: none;
    outline: none;
    color: white;
    padding: 00px;
    background-color: inherit;
    font-family: inherit;
    margin: 0;
}
.navbar a:hover, .dropdown:hover .dropbtn {
    background-color: red;
}
  .dropdown-content {
    display: none;
    position: fixed;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 10;
}
.dropdown-content a {
    float: none;
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}
.dropdown-content a:hover {
    background-color: #ddd;
}
  
.dropdown:hover .dropdown-content {
    display: block;
}
/* Create three equal columns that floats next to each other */
.column {
    font-family:'Bookman Old Style',Bookman,'URW Bookman L','Palatino Linotype',serif;
    float: left;
    width: 33.33%;
    padding: 10px;
    background-color: #ccc;
    height: 250px;
}
.column a {
    float: none;
    color: black;
    padding: 16px;
    text-decoration: none;
    display: block;
    text-align: left;
}
.column a:hover {
    background-color: #ddd;
}
  
  /* Clear floats after the columns */
.row:after {
    font-family:'Bookman Old Style',Bookman,'URW Bookman L','Palatino Linotype',serif;
    content: "";
    display: table;
    clear: both;
}
.fa {
  font-size: 30px;
  width: 70px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}

.fa:hover {
    opacity: 0.7;
}

.fa-facebook {
  background: #3B5998;
  color: white;
}
.fa-google {
  background: #dd4b39;
  color: white;
}

.fa-linkedin {
  background: #007bb5;
  color: white;
}
.fa-twitter {
  background: #55ACEE;
  color: white;
}
.fa-instagram {
  background: #125688;
  color: white;
}
/* Full-width input fields */
input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

.mySlides{
    display:none;
}
img {
    vertical-align: middle;
}
/*Slideshow container*/
.slideshow-container {
    max-width: 80%;
    position: relative;
    display:block;
    margin-right:auto;
    margin-left:auto;
}
/* Next & previous buttons */
.prev, .next {
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

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}
/* Caption text */
.text {
  color: #f2f2f2;
  font-weight: bold;
  font-size: 20px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align:end;
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
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
.main {
  padding: 16px;
  height:1500px; 
  border-left: 10px solid #333;
  border-right: 10px solid #333; 
  border-bottom: 30px solid #333;
  height:fit-content;
}
/* Add a background color when the inputs get focus */
input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

/* Set a style for all buttons */
button {
  background-color: #04AA6D;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}

/* Extra styles for the cancel button */
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}

/* Float cancel and signup buttons and add an equal width */
.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}

/* Add padding to container elements */
.container {
  padding: 16px;
}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: #474e5d;
  padding-top: 50px;
}

/* Modal Content/Box */
.modal-content {
  background-color: #fefefe;
  margin: 5% auto 15% auto; /* 5% from the top, 15% from the bottom and centered */
  border: 1px solid #888;
  width: 80%; /* Could be more or less, depending on screen size */
}

/* Style the horizontal ruler */
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}
 
/* The Close Button (x) */
.close {
  position: absolute;
  right: 35px;
  top: 15px;
  font-size: 40px;
  font-weight: bold;
  color: #f1f1f1;
}

.close:hover,
.close:focus {
  color: #f44336;
  cursor: pointer;
}

/* Clear floats */
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

/* Change styles for cancel button and signup button on extra small screens */
@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
     width: 100%;
  }
}
.timeline {
    position:relative;
    max-width:1200px;
    margin: 0 auto;
}
.timeline::after {
  content: '';
  position: absolute;
  width: 6px;
  background-color: white;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -3px;
}
.container {
  padding: 10px 40px;
  position: relative;
  background-color: inherit;
  width: 50%;
}
.container::after {
  content: '';
  position: absolute;
  width: 25px;
  height: 25px;
  right: -17px;
  background-color: white;
  border: 4px solid #FF9F55;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}
.left {
  left: 0;
}
.right {
  left: 50%;
}
.left::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  right: 30px;
  border: medium solid white;
  border-width: 10px 0 10px 10px;
  border-color: transparent transparent transparent white;
}
.right::before {
  content: " ";
  height: 0;
  position: absolute;
  top: 22px;
  width: 0;
  z-index: 1;
  left: 30px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
}
.right::after {
  left: -16px;
}
.content {
  padding: 20px 30px;
  background-color: white;
  position: relative;
  border-radius: 6px;
}
@media screen and (max-width: 600px) {
  /* Place the timelime to the left */
  .timeline::after {
  left: 31px;
  }
  .container {
  width: 100%;
  padding-left: 70px;
  padding-right: 25px;
  }
  .container::before {
  left: 60px;
  border: medium solid white;
  border-width: 10px 10px 10px 0;
  border-color: transparent white transparent transparent;
  }
  .left::after, .right::after {
  left: 15px;
  }
  .right {
  left: 0%;
  }
}
#myBtn {
  display: none;
  position: fixed;
  width: 80px;
  bottom: 100px;
  left: 25px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: red;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}
#myBtn:hover {
  background-color: #555;
}
.footer{
    font-family: Arial, Helvetica, sans-serif;
    position:fixed;
    font-size: 10px;
    right: 8px;
    bottom:0;
    width:40%;
    color:#000;
    text-align:center;
}
</style>
</head>
<body>
    <div class="bg-image"></div>
    <div class="bg-text">
        <h1>Famous Composers <p>Throughout the Ages</p></h1>
    </div>
        <div class="navbar">
            <a href="finalproject2.html"><b>Home</b></a>
            <a href="instruments.html"><b>Instrumentation</b></a>
            <div class="dropdown">
                <button class="dropbtn">Composers
                    <i class="fa fa-caret-down"></i>
                </button>
                <div class="dropdown-content">
                    <div class="row">
                        <div class="column">
                           <a href="bingen.html"><small>Bingen</small></a>
                           <a href="tallis.html"><small>Tallis</small></a>
                           <a href="monteverdi.html"><small>Monteverdi</small></a>
                        </div>
                        <div class="column">
                           <a href="vivaldi.html"><small>Vivaldi</small></a>
                           <a href="handel.html"><small>Handel</small></a>
                           <a href="bach.html"><small>Bach</small></a>
                        </div>
                        <div class="column">
                           <a href="haydn.html"><small>Hadyn</small></a>
                           <a href="mozart.html"><small>Mozart</small></a>
                           <a href="beethoven.html"><small>Beethoven</small></a>
                        </div>
                        <div class="column">
                           <a href="paganini.html"><small>Paganini</small></a>
                           <a href="rossini.html"><small>Rossini</small></a>
                           <a href="schubert.html"><small>Schubert</small></a>
                      </div>
                      <div class="column">
                         <a href="berlioz.html"><small>Berlioz</small></a>
                         <a href="mendelssohn.html"><small>Mendelssohn</small></a>
                         <a href="schumann.html"><small>Schumann</small></a>
                    </div>
                </div>
            </div>
        </div>
<main class="main">
   <div class="slideshow-container">
       <div class="mySlides fade">
           <div class="numbertext">1/10</div>
            <img src="images2.jpeg" style="width:100%">
            <div class="text">Antonio Lucio Vivaldi</div>
       </div>
       <div class="mySlides fade">
            <div class="numbertext">2/10</div>
                <img src="Unknown.jpeg" style="width:100%">
            <div class="text">Johann Sebastian Bach</div>
       </div>
       <div class="mySlides fade">
            <div class="numbertext">3/10</div>
                <img src="Unknown-4.jpeg" style="width:100%">
            <div class="text">Wolfgang Amadeus Mozart</div>
       </div>
       <div class="mySlides fade">
           <div class="numbertext">4/9</div>
                <img src="unknown-7.jpeg" style="width:100%">
            <div class="text">Ludwig Van Beethoven</div>
       </div>
       <div class="mySlides fade">
           <div class="numbertext">5/9</div>
                <img src="Unknown-17.jpeg" style="width:100%">
            <div  class="text">Jakob Ludwig Felix Mendelssohn Bartholdy</div>
       </div>
       <div class="mySlides fade">
           <div class="numbertext">6/9</div>
                <img src="Unknown-13.jpeg" style="width:100%">
            <div class="text">Fryderyk Franciszek Chopin</div>
       </div>
       <div class="mySlides fade">
           <div class="numbertext">7/9</div>
                <img src="Unknown-20.jpeg" style="width:100%">
            <div class="text">Johannes Brahms</div>
       </div>
       <div class="mySlides fade">
           <div class="numbertext">8/9</div>
                <img src="Unknown-23.jpeg" style="width:100%">
            <div class="text">Pyotr Ilych Tchaikovsky</div>
       </div>
       <div class="mySlides fade">
           <div class="numbertext">9/</div>
                <img src="Unknown-28.jpeg" style="width:100%">
            <div class="text">Antonín Leopold Dvorák</div>
       </div>
       <div class="mySlides fade">
        <div class="numbertext">9/10</div>
             <img src="Prokofiev_1.jpg" style="width:100%">
         <div class="text">Sergi Prokofiev</div>
      </div>
       <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
       <a class="next" onclick="plusSlides(1)">&#10095;</a>
   </div>
   <br>
<div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span> 
    <span class="dot" onclick="currentSlide(2)"></span> 
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
    <span class="dot" onclick="currentSlide(5)"></span>
    <span class="dot" onclick="currentSlide(6)"></span>
    <span class="dot" onclick="currentSlide(7)"></span>
    <span class="dot" onclick="currentSlide(8)"></span>
    <span class="dot" onclick="currentSlide(9)"></span>
    <span class="dot" onclick="currentSlide(10)"></span>
</div>
<script>
    var slideIndex = 1;
    showSlides(slideIndex);
    
    function plusSlides(n) {
      showSlides(slideIndex += n);
    }
    
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
<div class="timeline" style="font-family:Arial, Helvetica, sans-serif">
    <div class="container left">
        <div class="content">
            <h2>Vivaldi</h2>
            <p>Born March 4, 1678 in Venice, Italy and died July 28, 1741</p>
        </div>
    </div>
    <div class="container right">
        <div class="content">
            <h2>Bach</h2>
            <p>Born March 21, 1685 in Eisenach, Germany and died July 28, 1750 in Leipzig, Germany</p>
        </div>
    </div>
    <div class="container left">
        <div class="content">
            <h2>Mozart</h2>
            <p>Born January 27, 1756 in Salzburg, Germany and died December 5, 1827 in Vienna, Austria</p>
        </div>
    </div>
    <div class="container right">
        <div class="content">
            <h2>Beethoven</h2>
            <p>Born December 17, 1770 in Bonn, Germany and died December 5, 1791 in Vienna, Austria</p>
        </div>
    </div>
    <div class="container left">
        <div class="content">
            <h2>Mendelssohn</h2>
            <p>Born February 3, 1809 in Hamburg, Germany and died November 4, 1847 in Leipzig, Germany</p>
        </div>
    </div>
    <div class="container right">
        <div class="content">
            <h2>Chopin</h2>
            <p>Born March 1, 1810 in Zelazowa Wola, Poland and died October 17, 1849 in Paris, France</p>
        </div>
    </div>
    <div class="container left">
        <div class="content">
            <h2>Brahms</h2>
            <p>Born May 7, 1833 in Hamburg, Germany and died April 3, 1897 in Vienna, Austria</p>
        </div>
    </div>
    <div class="container right">
        <div class="content">
            <h2>Tchaikovsky</h2>
            <p>Born April 25, 1840 in Votkinsk, Russia and died October 25, 1893 in St. Petersburg, Russia</p>
        </div>
    </div>
    <div class="container left">
        <div class="content">
            <h2>Dvorak</h2>
            <p>Born September 4,1841 in Nelahozeves, Czechia and died May 1, 1904 in Prague, Czechia</p>
        </div>
    </div>
    <div class="container right">
      <div class="content">
          <h2>Prokofiev</h2>
          <p>Born April 23, 1891 in Sontsovka, Ukraine and died March 5, 1953 in Moscow, Russia</p>
      </div>
  </div>
</div>
<button onclick="topFunction()" id="myBtn"
    title="Go to top">Top</button>
    <br>
<h3 style="text-align:center; font-family: Arial, Helvetica, sans-serif;">
    <i>Gabby DePamphilis</i></h3>
<button onclick="document.getElementById('id01').style.display='block'" style="width:auto;">Sign Up</button>
<div id="id01" class="modal">
  <span onclick="document.getElementById('id01').style.display='none'" class="close" title="Close Modal">&times;</span>
  <form class="modal-content" action="/action_page.php">
    <div class="container">
      <h1>Sign Up</h1>
      <p>Please fill in this form to create an account.</p>
      <hr>
      <label for="email"><b>Email</b></label>
      <input type="text" placeholder="Enter Email" name="email" required>
      <label for="psw"><b>Password</b></label>
      <input type="password" placeholder="Enter Password" name="psw" required>
</main>
</body>
<footer class="footer">
    <script>
        var date1= new Date();
        var date2= date1.toDateString();
            document.write("<p>Today's date is: "+date2)
        var mybutton=document.getElementById ("myBtn");
        window.onscroll=function(){scrollFunction()};
        function scrollFunction() {
        if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
            mybutton.style.display = "block";
            } 
        else {
            mybutton.style.display = "none";
            }
        }
    function topFunction() {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
        }
    </script>
    <br>
      <a href="google.com" class="fa fa-google"></a>
      <a href="https://www.facebook.com/baldwinwallaceuniversity/" class="fa fa-facebook"></a>
      <a href="https://www.linkedin.com/school/baldwin-wallace-university/" class="fa fa-linkedin"></a>
      <a href="https://twitter.com/BaldwinWallace?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor" class="fa fa-twitter"></a>
      <a href="https://www.instagram.com/baldwinwallace/?hl=en" class="fa fa-instagram"></a>
</footer>
</html>
