<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Madina Sweets | Kanpur Ahmednagar</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#fff9f2;
color:#333;
}

/* NAVBAR */
nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 20px;
background:#ffffff;
box-shadow:0 4px 15px rgba(0,0,0,0.08);
position:sticky;
top:0;
z-index:1000;
}

.logo{
font-size:20px;
font-weight:700;
color:#c46a1b;
}

.location{
font-size:12px;
color:#777;
}

/* HERO */
.hero{
text-align:center;
padding:40px 20px;
}

.hero h1{
font-size:28px;
margin-bottom:10px;
}

.hero p{
color:#666;
margin-bottom:20px;
}

.hero img{
width:100%;
max-width:350px;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,0.1);
}

/* BUTTON */
.btn{
display:inline-block;
padding:12px 25px;
background:#c46a1b;
color:white;
border-radius:30px;
text-decoration:none;
font-weight:600;
margin-top:15px;
transition:0.3s;
}

.btn:hover{
background:#a65314;
}

/* PRODUCTS */
.products{
padding:30px 20px;
}

.products h2{
text-align:center;
margin-bottom:25px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:15px;
}

.card{
background:white;
padding:15px;
border-radius:15px;
box-shadow:0 5px 20px rgba(0,0,0,0.08);
text-align:center;
transition:0.3s;
}

.card:hover{
transform:translateY(-5px);
}

.card img{
width:100%;
height:120px;
object-fit:cover;
border-radius:10px;
margin-bottom:10px;
}

.price{
color:#c46a1b;
font-weight:600;
margin-top:5px;
}

/* FOOTER */
footer{
background:#c46a1b;
color:white;
text-align:center;
padding:15px;
margin-top:30px;
font-size:14px;
}
</style>
</head>
<body>

<nav>
<div>
<div class="logo">Madina Sweets</div>
<div class="location">Chacha Bahu, Kanpur - Ahmednagar</div>
</div>
</nav>

<section class="hero">
<h1>Fresh & Pure Indian Mithai</h1>
<p>Premium quality sweets made with love & tradition.</p>
<img src="https://images.unsplash.com/photo-1604908177522-0403b1b4f66e" alt="Mithai">
<br>
<a href="https://wa.me/91XXXXXXXXXX" class="btn">Order on WhatsApp</a>
</section>

<section class="products">
<h2>Our Special Sweets</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1631452180519-c014fe946bc7">
<h3>Gulab Jamun</h3>
<p class="price">₹250/kg</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1617093727343-374698b1b08d">
<h3>Kaju Barfi</h3>
<p class="price">₹900/kg</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1625944236116-8a7a28ed5c82">
<h3>Besan Laddu</h3>
<p class="price">₹400/kg</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1601050690597-df0568f70950">
<h3>Rasgulla</h3>
<p class="price">₹300/kg</p>
</div>

</div>
</section>

<footer>
© 2026 Madina Sweets | All Rights Reserved
</footer>

</body>
</html>
