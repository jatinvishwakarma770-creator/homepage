<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="project.css">
</head>
<body>
    <header  class="head">
       <div class="navbar">

<img src="C:\Users\HP\Downloads\index2\piccom.jpg" class="logo">

<div class="menu-icon" onclick="toggleMenu()">☰</div>

<div class="nav-links">

<a href="#">Home</a>
<a href="C:\Users\HP\OneDrive\Desktop\coding\c+code\h.html">About</a>
<a href="#">Careers</a>
<a href="C:\Users\HP\OneDrive\Desktop\coding\c+code\contact.html">Contact</a>

</div>

</div>
        
         <div class="v"><video src="C:\Users\HP\Downloads\2802271-hd_1920_1080_30fps.mp4" height="50" width="100%" autoplay loop muted allowfullscreen type="video/ogg"></video> 
        <h1 class="line1"><bold>AJWS Enviorment Water Solution</bold></h1>
     <h1 ><bold class="line2"> Treating</bold><bold class="line3"> Water</bold><bold class="line4"> Diffrently</bold>
        </h1></div>
       <a class="two"  href="#">Learn More</a> 
       <a class="one" href="#">See all service</a>
       </header>
       
    <main>
        <div class="plant"></div>
        <div class="para"><h1 class="welcom">Welcome TO AJWS</h1>
            <h1 class="pioneers">Pioneers in Water Management</h1>
            <p class="topic">At Doshion Environment Water Solutions (DEWS), 
                we are pioneers in delivering innovative and sustainable water management solutions.</hr> 
                Founded over four decades ago, we have grown into a trusted name for industries across the globe,
                 offering end-to-end water treatment services tailored to diverse needs.</p>
                 <a class="s" href="">segment we offer</a>
        </div>
        <h1 class="sol"># Solution We offer</h1>
        <div class="plant2">
        <div class="pic1"></div>
         <div class="pic2"></div>
         <div class="pic3"></div>  
         <div class="pic4"></div> 
        </div>
    </main>
    <footer class="footer">

<div class="footer-container">

<!-- LEFT SECTION -->
<div class="footer-box">
<img src="logo.png" class="logo">

<p><i class="fa-solid fa-phone"></i> +91 9327036101</p>
<p><i class="fa-solid fa-envelope"></i> contact@dews.co.in</p>
<p><i class="fa-solid fa-location-dot"></i>
10, Sigma Corporates Off Sindhu Bhavan Road Bh,
Rajpath Rangoli Rd, Ahmedabad, Gujarat 380054
</p>
</div>

<!-- QUICK LINKS -->
<div class="footer-box">
<h3>Quick Links</h3>
<ul>
<li><a href="#">About Us</a></li>
<li><a href="#">Segments We Serve</a></li>
<li><a href="#">Solutions We Offer</a></li>
<li><a href="#">Careers</a></li>
<li><a href="#">Contact Us</a></li>
</ul>
</div>

<!-- POPULAR SERVICE -->
<div class="footer-box">
<h3>Popular Service</h3>
<ul>
<li><a href="#">High Purity Water</a></li>
<li><a href="#">Utility Water</a></li>
<li><a href="#">Process Water</a></li>
<li><a href="#">Effluent Water</a></li>
</ul>
</div>

</div>

<!-- COPYRIGHT -->
<div class="footer-bottom">

<p>Copyright © 2026 Doshion Environment Water Solutions</p>

<div class="social">
<i class="fab fa-facebook"></i>
<i class="fab fa-x-twitter"></i>
<i class="fab fa-youtube"></i>
<i class="fab fa-instagram"></i>
</div>

</div>

</footer>
    <script>

function toggleMenu(){
document.querySelector(".nav-links").classList.toggle("active");
}

</script>
    <style>
   *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* NAVBAR */

.logo{
    width: 120px;
    height: 60px;
    background-color: white;
    position: relative;
    left: 5%;
    border: 2px solid #2a836f;
    transform-style: preserve-3d;
    box-shadow: 0 0 5px rgba(0,0,0,0.3);
}

.navbar{
height:90px;
background:#47b49a;
display:flex;
align-items:center;
justify-content:space-between;
padding:0 60px;
}

/* LOGO */

.logo{
height:45px;
}

/* NAV LINKS */

.nav-links{
display:flex;
gap:80px;
}

.nav-links a{
text-decoration:none;
color:white;
font-size:20px;
font-weight:600;
}
.nav-links a:hover{
    text-decoration:none;
color:white;
font-size:20px;
font-weight:600;
text-decoration: underline;
}

/* HAMBURGER */

.menu-icon{
display:none;
font-size:30px;
color:white;
cursor:pointer;
}
/* NAV LINKS */


/* VIDEO */

video{
    height: 100%;
    width: 100%;
}

.j{
    position: relative;
    bottom: 300px;
}

.v{
    z-index: -1;
}

/* TEXT LINES */

.line1{
   color: #ffff;
   position: relative;
   bottom: 60vh;
   left: 7%;
}

.line2,.line3,.line4{
   position: relative;
   bottom: 60vh;
   left: 7%;
   font-weight: bolder;
   font-size: 70px;
}

.line2{color:#fff;}
.line3{color:#47b49a;}
.line4{color:#fff;}

/* BUTTONS */

.one,.two{
    background-color: #47b49a;
    height: 70px;
    width: 300px;
    position: relative;
    bottom: 55vh;
    left: 8%;
    border: 10px solid #47b49a;
    text-align: center;
    color: white;
    text-decoration: none;
    font-weight: bold;
    border-radius: 20px;
}

.two{
    left: 10%;
}

/* IMAGE + TEXT SECTION */

.plant{
    height: 450px;
    width: 50%;
    background-image: url(https://i0.wp.com/dews.co.in/wp-content/uploads/2024/12/treatment-plant-wastewater-2826986_1280.jpg?resize=1024%2C682&ssl=1);
    background-size: cover;
    position: relative;
    left: 5%;
    bottom: 100px;
    border-radius: 10px;
}

.para{
    position: relative;
    left: 60%;
    bottom: 450px;
    width: 35%;
}

/* SERVICES SECTION */

.plant2{
    height: auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: center;
    background-color: #47b49a;
    border-radius: 25px;
    position: relative;
    bottom: 80px;
    padding: 40px;
    gap: 30px;
}

/* CARDS */

.pic1,.pic2,.pic3,.pic4{
    height: 250px;
    width: 350px;
    background-size: cover;
    border: 5px solid #2a836f;
}

.pic1{background-image:url(https://www.kelvinindia.in/blog/wp-content/uploads/2024/09/sewage-treatment-plant-3.jpg);}
.pic2{background-image:url(https://cpimg.tistatic.com/03423100/b/4/STP-PLANT.jpg);}
.pic3{background-image:url(https://www.netsolwater.com/netsol-water/assets/img/product-images/What_are_the_advantages_of_installing_Industrial_RO_plants.jpg);}
.pic4{background-image:url(https://as2.ftcdn.net/v2/jpg/05/10/78/53/1000_F_510785343_YCAbyguyR6xlqfeT6RJIL4WmweoQXkiz.jpg);}

.pic1:hover,
.pic2:hover,
.pic3:hover,
.pic4:hover{
    height: 280px;
    width: 380px;
    transition-duration: 0.6s;
}

/* FOOTER */

footer{
    height: auto;
    padding: 40px;
    background-color:black;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.piccom2{
    width: 120px;
    height: 40px;
    background-color: white;
    position: relative;
    left: -500px;
    bottom: -20px;
}

.bang1{
    height: auto;
    color: white;
    font-weight: bolder;
    font-size: large;
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
   
}

.footer{
background:#48a896;
color:white;
padding-top:50px;
}

/* MAIN CONTAINER */

.footer-container{
display:flex;
justify-content:space-between;
flex-wrap:wrap;
width:90%;
margin:auto;
gap:40px;
}

.footer-box{
flex:1;
min-width:250px;
}

/* LOGO */

.logo{
width:150px;
margin-bottom:20px;
}

/* TEXT */

.footer-box p{
margin:10px 0;
line-height:1.6;
}

.footer-box i{
margin-right:10px;
}

/* LINKS */

.footer-box h3{
margin-bottom:15px;
}

.footer-box ul{
list-style:none;
}

.footer-box ul li{
margin:10px 0;
}

.footer-box ul li a{
text-decoration:none;
color:white;
transition:0.3s;
}

.footer-box ul li a:hover{
color:#e2e2e2;
}

/* BOTTOM */

.footer-bottom{
display:flex;
justify-content:space-between;
align-items:center;
flex-wrap:wrap;
border-top:1px solid rgba(255,255,255,0.3);
margin-top:40px;
padding:15px 5%;
font-size:14px;
}

/* SOCIAL ICONS */

.social i{
margin-left:15px;
cursor:pointer;
font-size:18px;
}

.social i:hover{
opacity:0.7;
}

/* ANIMATION */

@keyframes showoff{
    from{opacity: 0;}
    to{opacity: 1;}
}

/* =========================
   MOBILE RESPONSIVE
   ========================= */

@media (max-width: 768px){
    html,body{
        overflow-x: hidden;
        flex-wrap: wrap;
    }
.navbar{
padding:0 20px;
}

.menu-icon{
display:block;
}

.nav-links{
position:absolute;
top:90px;
left:0;
width:100%;
background:#47b49a;
flex-direction:column;
align-items:center;
gap:0;
display:none;
z-index: 1;
}

.nav-links a{
padding:18px;
width:100%;
text-align:center;
border-top:1px solid rgba(255,255,255,0.4);
z-index: 1;
}

.nav-links.active{
display:flex;
}

.line2,.line3,.line4{
    font-size: 25px;
    position: relative;
    bottom:175px;
}
.one,.two{
    position: relative;
    bottom: 150px;
    width: 20px;
    height: auto;
}

.plant{
    width: 90%;
    left: 5%;
}

.para{
    width: 90%;
    left: 5%;
    bottom: 110px;
    margin-top: 10px;
    
} 
.topic{
    text-align: left;
}
.s{
    height: 10px;
    transform-style: preserve-3d;
    box-shadow:(0,0,5px rgba(0,0,0,0.3))
    position: relative;
    left: 80px;
    
}
.sol{
 font-size: larger;
 position: relative;
 left: 4px;
 
}

.one,.two{
    width: 200px;
    height: 50px;
}

.pic1,.pic2,.pic3,.pic4{
    width: 90%;
}
.piccom2{
    position: relative;
    left: -75px;
    bottom: 35px;
}
.bang1{
    font-size: medium;
}

.footer-bottom{
flex-direction:column;
gap:10px;
text-align:center;
}

.social i{
margin:10px;
}

}
    </style>
</body>
</html>
