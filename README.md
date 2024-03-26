<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Orifier website design - original verifier</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.2/css/fontawesome.min.css">
</head>
<body>
<section class="header">
    <nav>
        <a href="index.html"><img src="images/logo.png"></a>
        <div class="nav-links">
            <i class="fa fa-times" onclick="hidemenu()"></i>
            <ul>
                <li><a href="">PROFILE</a></li>
                <li><a href="">ABOUT</a></li>
                <li><a href="">CONTACT</a></li>
            </ul>
        </div>
        <i class="fa-solid fa-bars" onclick="showmenu()"></i>
    </nav>
    <div class="text-box">
        <h1>Original Product Verfier</h1>
        <p>Verify your purchased product is original or fake branded</p>
        <a href="" class="hero-btn">Visit to verify</a>
    </div>
</section>
<!---------javascript for toggle menu------->
<script>
var navLinks = document.getElementById("navLinks");
function showmenu(){
    navLinks.style.right = "0";
}
function hidemenu(){
    navLinks.style.right = "-200px";
}
</script>
<section class="testimonials">
    <h1>What our user says</h1>
    <div class="row">
        <div class="testimonial-col">
            <img src="image/user1.jpg">
            <div>
                <p>This webstie helps me to purchasing.<br>
                     It verifies that product designed by original company or not.
                </p>
                <h3>Bob Kane</h3>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star-o"></i>
            </div>
        </div>
        <div class="testimonial-col">
            <img src="image/user3.jpg">
            <div>
                <p>The website helps to identify fake product.This helped me a lot.
                </p>
                <h3>Baalu</h3>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star"></i>
                <i class="fa-solid fa-star-o"></i>
        </div>
    </div>
</section>
<section>
    <h1>Any query or suggestions</h1>
    <a href="" class="hero-btn">CONTACT US</a>
</section>
</body>
</html>
