# Main html  
  
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Shoot Gallery</title>  
  
<!-- Google Font -->  
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">  
  
<style>  
*{  
  margin:0;  
  padding:0;  
  box-sizing:border-box;  
  font-family:'Poppins',sans-serif;  
}  
  
body{  
  background:#000;  
  color:#fff;  
  scroll-behavior:smooth;  
}  
  
header{  
  position:sticky;  
  top:0;  
  background:#000;  
  padding:15px 30px;  
  display:flex;  
  justify-content:space-between;  
  align-items:center;  
  z-index:1000;  
}  
  
header h1{  
  color:gold;  
}  
  
nav a{  
  color:#fff;  
  margin-left:20px;  
  text-decoration:none;  
}  
  
.hero{  
  height:100vh;  
  display:flex;  
  flex-direction:column;  
  justify-content:center;  
  align-items:center;  
  text-align:center;  
  padding:20px;  
}  
  
.hero h2{  
  font-size:40px;  
  color:gold;  
}  
  
.hero p{  
  margin:10px 0;  
}  
  
.btn{  
  margin:10px;  
  padding:12px 25px;  
  border:none;  
  cursor:pointer;  
  font-weight:600;  
}  
  
.btn-gold{  
  background:gold;  
  color:black;  
}  
  
.btn-outline{  
  border:1px solid gold;  
  color:gold;  
  background:none;  
}  
  
section{  
  padding:60px 20px;  
  text-align:center;  
}  
  
.cards{  
  display:flex;  
  flex-wrap:wrap;  
  justify-content:center;  
  gap:20px;  
}  
  
.card{  
  background:#111;  
  padding:20px;  
  border-radius:10px;  
  width:300px;  
  transition:0.3s;  
}  
  
.card:hover{  
  transform:scale(1.05);  
  border:1px solid gold;  
}  
  
.gallery{  
  display:grid;  
  grid-template-columns:repeat(auto-fit,minmax(150px,1fr));  
  gap:10px;  
}  
  
.gallery img{  
  width:100%;  
  border-radius:10px;  
}  
  
footer{  
  background:#111;  
  padding:20px;  
}  
  
.whatsapp{  
  position:fixed;  
  bottom:20px;  
  right:20px;  
  background:green;  
  padding:15px;  
  border-radius:50%;  
}  
  
@media(max-width:768px){  
  .hero h2{  
    font-size:28px;  
  }  
}  
</style>  
</head>  
  
<body>  
  
<header>  
<h1>Shoot Gallery</h1>  
<nav>  
<a href="#about">About</a>  
<a href="#services">Packages</a>  
<a href="#contact">Contact</a>  
</nav>  
</header>  
  
<!-- HERO -->  
<section class="hero">  
<h2>Shoot Gallery</h2>  
<p>Premium Reels. Instant Delivery.</p>  
<p>Shot on iPhone | Cinematic Quality | Affordable Pricing</p>  
  
<button class="btn btn-gold">Book Now</button>  
  
<a href="https://wa.me/918639535739">  
<button class="btn btn-outline">Chat on WhatsApp</button>  
</a>  
</section>  
  
<!-- ABOUT -->  
<section id="about">  
<h2>About Us</h2>  
<p>  
Shoot Gallery specializes in creating premium-quality reels with fast delivery.  
We capture your best moments using high-end iPhone cinematography techniques,  
ensuring stunning visuals at unbeatable prices.  
</p>  
</section>  
  
<!-- SERVICES -->  
<section id="services">  
<h2>Packages</h2>  
  
<div class="cards">  
  
<div class="card">  
<h3>Starter Reel</h3>  
<p>₹1699 + GST</p>  
<p>1 Hour | 1 Reel</p>  
<ul>  
<li>Instant Delivery</li>  
<li>Shot on iPhone</li>  
<li>Premium Editing</li>  
</ul>  
</div>  
  
<div class="card">  
<h3>Creator Pack</h3>  
<p>₹2499 + GST</p>  
<p>2 Hours | 2 Reels</p>  
<ul>  
<li>Instant Delivery</li>  
<li>Cinematic Shots</li>  
<li>Smooth Transitions</li>  
</ul>  
</div>  
  
<div class="card">  
<h3>Half Day Shoot</h3>  
<p>₹3999 + GST</p>  
<p>Half Day | Multiple Reels</p>  
<ul>  
<li>Premium Coverage</li>  
<li>Best Packaging</li>  
<li>High-End Editing</li>  
</ul>  
</div>  
  
</div>  
</section>  
  
<!-- SPECIAL -->  
<section>  
<h2>Special Services</h2>  
<p>  
We also undertake wedding shoots, functions, events, and special occasions with premium quality coverage.  
</p>  
</section>  
  
<!-- WHY -->  
<section>  
<h2>Why Choose Us</h2>  
<ul>  
<li>Instant Delivery</li>  
<li>Shot on iPhone (Cinematic Quality)</li>  
<li>Affordable Pricing</li>  
<li>Professional Editing</li>  
<li>Best Packaging Ever</li>  
</ul>  
</section>  
  
<!-- GALLERY -->  
<section>  
<h2>Gallery</h2>  
<div class="gallery">  
<img src="https://via.placeholder.com/300">  
<img src="https://via.placeholder.com/300">  
<img src="https://via.placeholder.com/300">  
<img src="https://via.placeholder.com/300">  
</div>  
</section>  
  
<!-- CONTACT -->  
<section id="contact">  
<h2>Contact</h2>  
  
<p>Email: charantejchary@gmail.com</p>  
<p>Phone: +91 86395 35739</p>  
<p>Phone: +91 99485 74474</p>  
  
<a href="tel:+918639535739">  
<button class="btn btn-gold">Call Now</button>  
</a>  
  
<a href="https://wa.me/918639535739">  
<button class="btn btn-outline">Chat on WhatsApp</button>  
</a>  
  
</section>  
  
<footer>  
<p>Shoot Gallery</p>  
<p>Capture. Create. Deliver.</p>  
</footer>  
  
<!-- Floating WhatsApp -->  
<a href="https://wa.me/918639535739" class="whatsapp">  
💬  
</a>  
  
</body>  
</html>  
