<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="BATHORA - Live the Better Way. Premium faucets, showers, washbasins and commodes.">
<title>BATHORA | Live the Better Way</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Playfair+Display:wght@500;600;700&display=swap" rel="stylesheet">

<style>
:root {
--dark:#172522;--gold:#bd9b69;--cream:#f7f5f0;
--green:#52685b;--text:#333b37;
}
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{font-family:'DM Sans',sans-serif;color:var(--text)}
a{text-decoration:none;color:inherit}
.topbar{background:var(--dark);color:white;text-align:center;padding:10px;font-size:12px;letter-spacing:2px}
header{height:85px;padding:0 7%;display:flex;justify-content:space-between;align-items:center;background:white;position:sticky;top:0;z-index:100;box-shadow:0 2px 15px #0000000c}
.logo,.footer-logo{font-family:'Playfair Display',serif;font-size:34px;letter-spacing:3px;color:var(--dark);font-weight:bold}
.logo span,.footer-logo span{color:var(--gold)}
.nav{display:flex;align-items:center;gap:30px}
.nav a{font-size:13px;font-weight:600;letter-spacing:1px}
.nav a:hover{color:var(--gold)}
.contact-btn{background:var(--dark);color:white!important;padding:14px 22px}
.menu-toggle{display:none;border:0;background:none;font-size:25px}
.hero{min-height:600px;display:flex;align-items:center;padding:80px 9%;background:linear-gradient(90deg,#101d1bd9,#101d1b20),url('https://images.unsplash.com/photo-1600607687939-ce8a6c25118c?auto=format&fit=crop&w=2000&q=85') center/cover;color:white}
.hero-content{max-width:620px}
.eyebrow{color:var(--gold);font-size:12px;letter-spacing:4px;font-weight:bold;margin-bottom:20px}
.hero h1{font:500 clamp(44px,6vw,76px)/1.12 'Playfair Display';margin-bottom:22px}
.hero p{line-height:1.9;color:#eee;margin-bottom:32px;max-width:480px}
.primary-btn{display:inline-block;background:var(--gold);color:var(--dark);padding:16px 28px;font-size:12px;font-weight:bold;letter-spacing:1px}
.primary-btn:hover{background:white}
.section{padding:90px 8%}
.heading{text-align:center;max-width:650px;margin:0 auto 45px}
.heading h2,.about h2{font:500 clamp(32px,4vw,47px) 'Playfair Display';color:var(--dark);margin-bottom:15px}
.heading p{color:#777;line-height:1.8;font-size:14px}
.products{display:grid;grid-template-columns:repeat(4,1fr);gap:22px}
.product-card{background:var(--cream);overflow:hidden;transition:.3s}
.product-card:hover{transform:translateY(-6px);box-shadow:0 12px 30px #0002}
.product-card img{width:100%;height:270px;object-fit:cover;display:block}
.product-info{text-align:center;padding:22px 12px}
.product-info h3{font:23px 'Playfair Display';color:var(--dark);margin-bottom:10px}
.product-info p{font-size:13px;color:#777;line-height:1.7}
.product-info a{display:inline-block;margin-top:17px;font-size:11px;font-weight:bold;letter-spacing:1px;border-bottom:1px solid var(--gold);padding-bottom:5px}
.about{background:var(--cream);display:grid;grid-template-columns:1fr 1fr;gap:55px;align-items:center}
.about img{width:100%;height:450px;object-fit:cover}
.about p{font-size:14px;line-height:1.9;color:#666;margin:18px 0}
.features{display:grid;grid-template-columns:repeat(3,1fr);gap:22px}
.feature{text-align:center;border:1px solid #e9e5dd;padding:30px 20px}
.feature .symbol{font-size:30px;color:var(--gold);margin-bottom:15px}
.feature h3{font:22px 'Playfair Display';color:var(--dark);margin-bottom:10px}
.feature p{font-size:13px;color:#777;line-height:1.8}
.cta{text-align:center;padding:85px 8%;background:linear-gradient(#172522df,#172522df),url('https://images.unsplash.com/photo-1600566753086-00f18fb6b3ea?auto=format&fit=crop&w=1800&q=85') center/cover;color:white}
.cta h2{font:48px 'Playfair Display';margin-bottom:15px}
.cta p{font-size:14px;line-height:1.8;margin-bottom:28px;color:#ddd}
.contact{background:var(--cream);text-align:center}
.contact-details{display:flex;justify-content:center;gap:45px;flex-wrap:wrap;margin-top:35px}
.contact-details div{font-size:14px;line-height:2}
.contact-details a:hover{color:var(--gold)}
footer{background:#101b18;color:white;padding:55px 8% 20px}
.footer-content{display:grid;grid-template-columns:2fr 1fr 1fr;gap:40px;padding-bottom:40px}
.footer-logo{color:white;margin-bottom:12px}
.footer-content p{font-size:13px;color:#b9c1bd;line-height:1.9;max-width:350px}
.footer-content h3{color:var(--gold);font-size:13px;letter-spacing:2px;margin-bottom:18px}
.footer-links a{display:block;color:#b9c1bd;font-size:13px;margin-bottom:12px}
.footer-links a:hover{color:var(--gold)}
.copyright{border-top:1px solid #33413b;padding-top:20px;text-align:center;color:#9aa49f;font-size:12px}
.whatsapp{position:fixed;right:22px;bottom:22px;width:56px;height:56px;border-radius:50%;background:#25D366;color:white;display:grid;place-items:center;font-size:27px;z-index:200}
@media(max-width:950px){.products{grid-template-columns:repeat(2,1fr)}}
@media(max-width:650px){
header{height:75px;padding:0 6%}.logo{font-size:28px}
.menu-toggle{display:block}
.nav{display:none;position:absolute;top:75px;left:0;right:0;background:white;flex-direction:column;padding:25px;gap:22px}
.nav.active{display:flex}
.hero{min-height:530px;padding:60px 7%}
.section{padding:65px 6%}
.products{grid-template-columns:1fr 1fr;gap:12px}
.product-card img{height:190px}
.product-info{padding:17px 8px}
.product-info h3{font-size:18px}
.product-info p{font-size:11px}
.about{grid-template-columns:1fr;gap:30px}
.about img{height:300px}
.features{grid-template-columns:1fr}
.cta h2{font-size:35px}
.footer-content{grid-template-columns:1fr;gap:30px}
.contact-details{flex-direction:column;gap:20px}
}
</style>
</head>

<body>
<div class="topbar">ELEVATE YOUR SPACE. LIVE THE BETTER WAY.</div>

<header>
<a href="#home" class="logo">BATH<span>ORA</span></a>
<button class="menu-toggle" onclick="toggleMenu()" aria-label="Open menu">☰</button>
<nav class="nav" id="navigation">
<a href="#home" onclick="closeMenu()">HOME</a>
<a href="#products" onclick="closeMenu()">PRODUCTS</a>
<a href="#about" onclick="closeMenu()">ABOUT US</a>
<a href="#contact" class="contact-btn" onclick="closeMenu()">CONTACT US</a>
</nav>
</header>

<main>
<section class="hero" id="home">
<div class="hero-content">
<div class="eyebrow">WELCOME TO BATHORA</div>
<h1>Redefining the Art of Modern Living.</h1>
<p>Discover thoughtfully selected bathroom essentials that bring elegance, comfort and functionality into your everyday spaces.</p>
<a href="#products" class="primary-btn">EXPLORE COLLECTION</a>
</div>
</section>

<section class="section" id="products">
<div class="heading">
<div class="eyebrow">OUR COLLECTION</div>
<h2>Designed for Better Living</h2>
<p>Explore our range of sanitary ware and bathroom solutions.</p>
</div>

<div class="products">

<div class="product-card">
<img src="https://images.unsplash.com/photo-1620626011761-996317b8d101?auto=format&fit=crop&w=800&q=85" alt="Bathroom faucet and tap">
<div class="product-info">
<h3>Faucets</h3>
<p>Elegant fittings for everyday sophistication.</p>
<a href="#contact">ENQUIRE NOW</a>
</div>
</div>

<div class="product-card">
<img src="https://images.unsplash.com/photo-1620626011761-996317b8d101?auto=format&fit=crop&w=800&q=85&sat=-70" alt="Modern shower fittings">
<div class="product-info">
<h3>Showers</h3>
<p>Modern shower solutions for daily comfort.</p>
<a href="#contact">ENQUIRE NOW</a>
</div>
</div>

<div class="product-card">
<img src="https://images.unsplash.com/photo-1620626011761-996317b8d101?auto=format&fit=crop&w=800&q=85&blur=1" alt="Designer washbasin">
<div class="product-info">
<h3>Washbasins</h3>
<p>Beautiful designs for contemporary bathrooms.</p>
<a href="#contact">ENQUIRE NOW</a>
</div>
</div>

<div class="product-card">
<img src="https://images.unsplash.com/photo-1584622650111-993a426fbf0a?auto=format&fit=crop&w=800&q=85" alt="Modern commode and toilet">
<div class="product-info">
<h3>Commodes</h3>
<p>Practical elegance and everyday comfort.</p>
<a href="#contact">ENQUIRE NOW</a>
</div>
</div>

</div>
</section>

<section class="section about" id="about">
<img src="https://images.unsplash.com/photo-1600607687920-4e2a09cf159d?auto=format&fit=crop&w=1000&q=85" alt="Elegant bathroom interior">
<div>
<div class="eyebrow">ABOUT BATHORA</div>
<h2>Where Style Meets Everyday Comfort.</h2>
<p>At BATHORA, we believe every space deserves thoughtful design. Our aim is to bring together style, functionality and quality through a carefully selected range of sanitary ware.</p>
<p>From elegant faucets to contemporary showers, washbasins and commodes, we help you explore solutions that make everyday living better.</p>
<a href="#contact" class="primary-btn">CONNECT WITH US</a>
</div>
</section>

<section class="section">
<div class="heading">
<div class="eyebrow">THE BATHORA DIFFERENCE</div>
<h2>More Than Just Bathroom Essentials</h2>
<p>We focus on making your product selection simple and convenient.</p>
</div>
<div class="features">
<div class="feature"><div class="symbol">✧</div><h3>Modern Designs</h3><p>Explore stylish products for contemporary spaces.</p></div>
<div class="feature"><div class="symbol">◇</div><h3>Curated Selection</h3><p>Discover options suited to different preferences and needs.</p></div>
<div class="feature"><div class="symbol">⌂</div><h3>Customer Focus</h3><p>Personal assistance to help you choose the right products.</p></div>
</div>
</section>

<section class="cta">
<h2>Let's Create Your Dream Bathroom.</h2>
<p>Looking for the right sanitary ware for your home or project?<br>Connect with BATHORA and explore your options.</p>
<a href="#contact" class="primary-btn">GET IN TOUCH</a>
</section>

<section class="section contact" id="contact">
<div class="heading">
<div class="eyebrow">GET IN TOUCH</div>
<h2>Let's Talk About Your Space.</h2>
<p>For product enquiries, pricing and business collaborations, contact us.</p>
</div>
<div class="contact-details">
<div><strong>EMAIL</strong><br><a href="mailto:Bathoraofficia@gmail.com">Bathoraofficia@gmail.com</a></div>
<div><strong>CONTACT NUMBER</strong><br><a href="tel:+919211690811">+91 92116 90811</a></div>
<div><strong>PRODUCTS</strong><br>Faucets | Showers | Washbasins | Commodes</div>
</div>
<p style="margin-top:30px">
<a class="primary-btn" href="https://wa.me/919211690811?text=Hello%20BATHORA%2C%20I%20would%20like%20to%20enquire%20about%20your%20products." target="_blank">SEND AN ENQUIRY</a>
</p>
</section>
</main>

<footer>
<div class="footer-content">
<div>
<div class="footer-logo">BATH<span>ORA</span></div>
<p>LIVE THE BETTER WAY.</p>
<p>Bringing style, comfort and functionality together for better everyday living.</p>
</div>
<div class="footer-links">
<h3>QUICK LINKS</h3>
<a href="#home">Home</a><a href="#products">Our Products</a><a href="#about">About Us</a><a href="#contact">Contact</a>
</div>
<div class="footer-links">
<h3>CONTACT</h3>
<a href="mailto:Bathoraofficia@gmail.com">Bathoraofficia@gmail.com</a>
<a href="tel:+919211690811">+91 92116 90811</a>
</div>
</div>
<div class="copyright">© <span id="year"></span> BATHORA. All Rights Reserved.<br><br>LIVE THE BETTER WAY.</div>
</footer>

<a class="whatsapp" href="https://wa.me/919211690811?text=Hello%20BATHORA" target="_blank" rel="noopener noreferrer" aria-label="WhatsApp">☏</a>

<script>
function toggleMenu(){
document.getElementById('navigation').classList.toggle('active');
}
function closeMenu(){
document.getElementById('navigation').classList.remove('active');
}
document.getElementById('year').textContent=new Date().getFullYear();
</script>
</body>
</html>

