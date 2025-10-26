# directweave.com<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DirectWeave Co. | Sustainable Fashion</title>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
<style>
* { margin:0; padding:0; box-sizing:border-box; font-family:'Roboto',sans-serif;}
body {background:#fdfdfd; color:#333;}
header {display:flex; justify-content:space-between; align-items:center; padding:1rem 2rem; background:#2a2a2a; color:#fff; position:sticky; top:0; z-index:1000;}
header nav a {margin-left:1.5rem; color:#fff; font-weight:500; transition:0.3s;}
header nav a:hover {color:#ff6f61;}
.hero {position:relative; height:90vh; overflow:hidden;}
.hero img{width:100%; height:100%; object-fit:cover; animation:fade 15s infinite;}
.hero .overlay {position:absolute; top:0; left:0; width:100%; height:100%; background:rgba(0,0,0,0.4); display:flex; flex-direction:column; justify-content:center; align-items:center; text-align:center; color:#fff;}
.hero h1{font-size:3rem; margin-bottom:1rem; text-shadow:2px 2px 8px rgba(0,0,0,0.5);}
.hero p{font-size:1.2rem; margin-bottom:2rem; text-shadow:1px 1px 5px rgba(0,0,0,0.5);}
.cta{background:#ff6f61; color:#fff; padding:.8rem 2rem; border-radius:5px; font-weight:600; transition:.3s; cursor:pointer;}
.cta:hover{background:#ff3b2e;}
section{padding:4rem 2rem; max-width:1400px; margin:auto;}
h2{text-align:center; margin-bottom:2rem; font-size:2.5rem; color:#2a2a2a;}
.products{display:grid; grid-template-columns:repeat(auto-fit,minmax(280px,1fr)); gap:2rem;}
.product-card{background:#fff; border-radius:10px; overflow:hidden; box-shadow:0 5px 20px rgba(0,0,0,0.1); transition: transform .3s;}
.product-card:hover{transform:translateY(-5px);}
.product-card img{width:100%; height:300px; object-fit:cover; transition:.3s;}
.product-card:hover img{transform:scale(1.05);}
.product-card .info{padding:1rem;}
.product-card .info h3{margin-bottom:.5rem;}
.product-card .info p{color:#777; margin-bottom:1rem;}
.product-card .info span{font-weight:bold; color:#2a2a2a;}
.btn{display:inline-block; padding:.6rem 1.5rem; background:#ff6f61; color:#fff; border-radius:5px; font-weight:500; transition:.3s; cursor:pointer;}
.btn:hover{background:#ff3b2e;}
.grid-2{display:grid; grid-template-columns:repeat(auto-fit,minmax(300px,1fr)); gap:2rem; align-items:center;}
.contact-form{max-width:600px; margin:auto;}
.contact-form input, .contact-form textarea{width:100%; padding:.8rem; margin-bottom:1rem; border-radius:5px; border:1px solid #ccc;}
.contact-form button{width:100%; padding:.8rem; border:none; border-radius:5px; background:#ff6f61; color:#fff; font-weight:600; cursor:pointer;}
.testimonials{display:grid; grid-template-columns:repeat(auto-fit,minmax(300px,1fr)); gap:2rem;}
.testimonial-card{background:#fff; padding:2rem; border-radius:10px; box-shadow:0 5px 20px rgba(0,0,0,0.1);}
footer{background:#2a2a2a; color:#fff; text-align:center; padding:2rem; margin-top:2rem;}
@keyframes fade{0%,33%{opacity:1;}33.33%,66.66%{opacity:0;}66.66%,100%{opacity:1;}}
</style>
</head>
<body>

<header>
  <h2>DirectWeave Co.</h2>
  <nav>
    <a href="#home">Home</a>
    <a href="#products">Shop</a>
    <a href="#how">How It Works</a>
    <a href="#makers">Makers</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">
  <img src="https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb?auto=format&fit=crop&w=1470&q=80" alt="Hero Image">
  <div class="overlay">
    <h1>Affordable, Sustainable Fashion</h1>
    <p>Connecting consumers directly with skilled artisans worldwide.</p>
    <div class="cta" onclick="scrollToProducts()">Shop Now</div>
  </div>
</section>

<section id="products">
  <h2>Featured Products</h2>
  <div class="products" id="productGrid">
    <!-- Products dynamically loaded here -->
  </div>
</section>

<section id="how">
  <h2>How It Works</h2>
  <div class="grid-2">
    <div>
      <img src="https://images.unsplash.com/photo-1581091012184-3c71fcf0f6da?auto=format&fit=crop&w=600&q=80" style="width:100%; border-radius:10px;">
    </div>
    <div>
      <h3>Step 1: Browse Products</h3>
      <p>Explore unique, handcrafted clothing directly from artisans.</p>
      <h3>Step 2: Place Order</h3>
      <p>Add items to cart and checkout securely with easy payment options.</p>
      <h3>Step 3: Direct Delivery</h3>
      <p>Receive your order shipped directly from the artisan to your doorstep.</p>
      <h3>Step 4: Track Your Order</h3>
      <p>Stay updated with real-time tracking and notifications.</p>
    </div>
  </div>
</section>

<section id="makers">
  <h2>Meet Our Artisans</h2>
  <div class="grid-2">
    <div><img src="https://images.unsplash.com/photo-1512436991641-6745cdb1723f?auto=format&fit=crop&w=600&q=80" style="width:100%; border-radius:10px;"></div>
    <div>
      <p>Our skilled artisans create every piece with love, ensuring fair wages and sustainable practices. Each product tells a story and supports a community.</p>
    </div>
  </div>
</section>

<section id="testimonials">
  <h2>What Customers Say</h2>
  <div class="testimonials">
    <div class="testimonial-card">
      <p>"I love the unique designs and the ethical sourcing. Every purchase feels meaningful!"</p>
      <strong>- Aditi R.</strong>
    </div>
    <div class="testimonial-card">
      <p>"High-quality clothes that are sustainable and affordable. Truly a game-changer!"</p>
      <strong>- Rahul K.</strong>
    </div>
    <div class="testimonial-card">
      <p>"DirectWeave connects me with the artisans. It's not just shopping, it's supporting real people."</p>
      <strong>- Priya S.</strong>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <form class="contact-form">
    <input type="text" placeholder="Your Name" required>
    <input type="email" placeholder="Your Email" required>
    <textarea rows="5" placeholder="Message" required></textarea>
    <button type="submit">Send Message</button>
  </form>
</section>

<footer>
  &copy; 2025 DirectWeave Co. All Rights Reserved.
</footer>

<script>
const products = [
  {name:'Handwoven Top', desc:'Eco-friendly cotton, ethically made.', price:799, img:'https://images.unsplash.com/photo-1520974735194-5f3642c2e8f2?auto=format&fit=crop&w=700&q=80'},
  {name:'Sustainable Dress', desc:'Handcrafted, unique designs.', price:999, img:'https://images.unsplash.com/photo-1580396427302-3e995f14c5c0?auto=format&fit=crop&w=700&q=80'},
  {name:'Artisan Skirt', desc:'Fair-trade weaving with love.', price:850, img:'https://images.unsplash.com/photo-1562158073-8e7e7c0db184?auto=format&fit=crop&w=700&q=80'},
  {name:'Handmade Jacket', desc:'Warm, cozy, and ethical.', price:1200, img:'https://images.unsplash.com/photo-1593032465179-1f8c688fd9f8?auto=format&fit=crop&w=700&q=80'},
  {name:'Ethnic Shawl', desc:'Traditional weaving, modern touch.', price:650, img:'https://images.unsplash.com/photo-1598970434795-0c54fe7c0642?auto=format&fit=crop&w=700&q=80'},
];

const productGrid = document.getElementById('productGrid');
function renderProducts() {
  productGrid.innerHTML = '';
  products.forEach(p=>{
    const card = document.createElement('div');
    card.className = 'product-card';
    card.innerHTML = `
      <img src="${p.img}" alt="${p.name}">
      <div class="info">
        <h3>${p.name}</h3>
        <p>${p.desc}</p>
        <span>₹${p.price}</span><br><br>
        <div class="btn" onclick="addToCart('${p.name}')">Add to Cart</div>
      </div>
    `;
    productGrid.appendChild(card);
  });
}
renderProducts();

function scrollToProducts() {
  document.getElementById('products').scrollIntoView({behavior:'smooth'});
}

function addToCart(name){
  alert(name+' added to cart!');
}
</script>

</body>
</html>
