# cafe-yours
a simple cafe website built using HTML and CSS
<!-- ===================== index.html ===================== -->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Urban Bites Cafe</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
<style>
body{margin:0;font-family:Poppins;background:#0f0f0f;color:white}
header{display:flex;justify-content:space-between;padding:20px;background:#111}
a{color:white;text-decoration:none;margin:0 10px}
.hero{height:90vh;background:url('https://images.unsplash.com/photo-1504674900247-0877df9cc836') center/cover no-repeat;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center}
.hero h1{font-size:60px}
.btn{padding:12px 25px;background:#ff4d6d;border:none;border-radius:25px;color:white;cursor:pointer}
.section{padding:40px;text-align:center}
.card{background:#1a1a1a;padding:20px;border-radius:20px;margin:10px;display:inline-block;width:250px}
footer{background:#111;padding:20px;text-align:center}
</style>
</head>
<body>
<header>
<h2>Urban Bites</h2>
<nav>
<a href="index.html">Home</a>
<a href="menu.html">Menu</a>
<a href="about.html">About</a>
</nav>
</header>

<div class="hero">
<h1>Fresh Nepali Fast Food</h1>
<p>Affordable • Hygienic • Tasty</p>
<a href="menu.html"><button class="btn">Explore Menu</button></a>
</div>

<div class="section">
<h2>Popular Items</h2>
<div class="card">Momo - Rs. 80</div>
<div class="card">Chowmein - Rs. 50</div>
<div class="card">Milk Tea - Rs. 20</div>
</div>

<footer>
<p>butwal, nepal | 9800000000</p>
</footer>
</body>
</html>


<!-- ===================== menu.html ===================== -->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Menu - Urban Bites</title>
<style>
body{font-family:Poppins;background:#0f0f0f;color:white;text-align:center}
h1{padding:20px}
.grid{display:flex;flex-wrap:wrap;justify-content:center}
.item{background:#1a1a1a;margin:10px;padding:20px;border-radius:15px;width:200px}
img{width:100%;border-radius:10px}
</style>
</head>
<body>
<h1>Our Menu</h1>

<h2>Momo</h2>
<div class="grid">
<div class="item"><img src="https://images.unsplash.com/photo-1604908176997-125f25cc6f3d"><p>Veg Momo - Rs. 70</p></div>
<div class="item"><img src="https://images.unsplash.com/photo-1604908176997-125f25cc6f3d"><p>Buff Momo - Rs. 80</p></div>
</div>

<h2>Chowmein</h2>
<div class="grid">
<div class="item"><img src="https://images.unsplash.com/photo-1589302168068-964664d93dc0"><p>Veg Chowmein - Rs. 50</p></div>
<div class="item"><img src="https://images.unsplash.com/photo-1589302168068-964664d93dc0"><p>Chicken Chowmein - Rs. 90</p></div>
</div>

<h2>Drinks</h2>
<div class="grid">
<div class="item"><img src="https://images.unsplash.com/photo-1544148103-0773bf10d330"><p>Milk Tea - Rs. 20</p></div>
<div class="item"><img src="https://images.unsplash.com/photo-1544148103-0773bf10d330"><p>Cold Coffee - Rs. 120</p></div>
</div>

<a href="index.html">Back Home</a>
</body>
</html>


<!-- ===================== about.html ===================== -->
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>About - Urban Bites</title>
<style>
body{font-family:Poppins;background:#0f0f0f;color:white;text-align:center}
.section{padding:40px}
input,textarea{padding:10px;margin:10px;width:250px;border-radius:10px;border:none}
button{padding:10px 20px;background:#ff4d6d;border:none;border-radius:20px;color:white}
</style>
</head>
<body>
<h1>About Us</h1>
<div class="section">
<p>Urban Bites is a small Nepali cafe focused on fast, tasty and hygienic food. We serve fresh momo, chowmein and local snacks at affordable prices.</p>

<h2>Opening Hours</h2>
<p>7 AM - 9 PM (Everyday)</p>

<h2>Location</h2>
<p>Lamachaur, Pokhara</p>

<h2>Reserve a Table</h2>
<input type="text" placeholder="Your Name"><br>
<input type="number" placeholder="Phone"><br>
<textarea placeholder="Message"></textarea><br>
<button>Book Now</button>

<h2>Customer Reviews</h2>
<p>⭐ "Best momo in town!"</p>
<p>⭐ "Affordable and hygienic."</p>
</div>

<a href="index.html">Back Home</a>
</body>
</html>
