<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>KAMVEXO — Everything You Need, In One Place</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:Arial,sans-serif;
background:#f5f6fa;
color:#17172b;
}

header{
background:#fff;
padding:15px 5%;
box-shadow:0 2px 10px #ddd;
position:sticky;
top:0;
z-index:100;
}

.top{
display:flex;
align-items:center;
gap:20px;
}

.logo{
font-size:30px;
font-weight:900;
white-space:nowrap;
}

.logo span{
color:#673cff;
}

.search{
flex:1;
display:flex;
}

.search input{
width:100%;
padding:14px 18px;
border:1px solid #ddd;
border-radius:25px 0 0 25px;
font-size:16px;
}

.search button{
padding:0 20px;
border:0;
background:#11143d;
color:white;
border-radius:0 25px 25px 0;
font-size:20px;
}

.account{
font-weight:bold;
white-space:nowrap;
}

nav{
display:flex;
gap:28px;
padding-top:18px;
overflow:auto;
white-space:nowrap;
}

nav a{
text-decoration:none;
color:#17172b;
font-weight:bold;
}

.hero{
width:90%;
max-width:1200px;
margin:25px auto;
padding:55px;
border-radius:28px;
background:linear-gradient(120deg,#11143d,#713cff);
color:white;
display:flex;
align-items:center;
justify-content:space-between;
}

.hero h1{
font-size:48px;
margin:12px 0;
}

.hero p{
font-size:21px;
line-height:1.5;
}

.shop{
margin-top:22px;
padding:15px 28px;
border:0;
border-radius:12px;
font-weight:bold;
font-size:16px;
}

.hero-image{
width:300px;
height:220px;
object-fit:cover;
border-radius:20px;
}

section{
width:90%;
max-width:1200px;
margin:45px auto;
}

h2{
font-size:30px;
margin-bottom:20px;
}

.categories{
display:grid;
grid-template-columns:repeat(6,1fr);
gap:15px;
}

.category{
background:white;
padding:22px 10px;
border-radius:18px;
text-align:center;
box-shadow:0 2px 8px #ddd;
}

.category img{
width:70px;
height:70px;
object-fit:cover;
border-radius:50%;
margin-bottom:10px;
}

.products{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
}

.product{
background:white;
border-radius:18px;
overflow:hidden;
box-shadow:0 2px 10px #ddd;
}

.product img{
width:100%;
height:190px;
object-fit:cover;
}

.info{
padding:15px;
}

.info h3{
margin-bottom:8px;
}

.price{
color:#673cff;
font-size:21px;
font-weight:bold;
margin:10px 0;
}

.add{
width:100%;
padding:12px;
border:0;
border-radius:10px;
background:#11143d;
color:white;
font-weight:bold;
}

.features{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:15px;
}

.feature{
background:white;
padding:25px;
text-align:center;
border-radius:18px;
}

.feature-icon{
font-size:35px;
margin-bottom:10px;
}

footer{
background:#11143d;
color:white;
text-align:center;
padding:40px 5%;
margin-top:50px;
}

@media(max-width:800px){

.top{
flex-wrap:wrap;
}

.search{
order:3;
flex-basis:100%;
}

.hero{
padding:35px 25px;
}

.hero h1{
font-size:36px;
}

.hero-image{
width:180px;
height:160px;
}

.categories{
grid-template-columns:repeat(3,1fr);
}

.products{
grid-template-columns:repeat(2,1fr);
}

.features{
grid-template-columns:repeat(2,1fr);
}

}

@media(max-width:500px){

.hero{
width:94%;
}

.hero-image{
display:none;
}

section{
width:94%;
}

.categories{
grid-template-columns:repeat(2,1fr);
}

.products{
gap:10px;
}

.product img{
height:145px;
}

.features{
gap:10px;
}

}

</style>
</head>

<body>

<header>

<div class="top">

<div class="logo">
KAM<span>VEXO</span>
</div>

<div class="search">
<input type="text" placeholder="পণ্য, ব্র্যান্ড বা ক্যাটাগরি খুঁজুন...">
<button>🔍</button>
</div>

<div class="account">
👤 Account<br>
🛒 Cart
</div>

</div>

<nav>

<a href="#home">Home</a>
<a href="#categories">Categories</a>
<a href="#sale">Flash Sale 🔥</a>
<a href="#new">New Arrivals</a>
<a href="#products">Best Sellers</a>

</nav>

</header>


<div class="hero" id="home">

<div>

<p>WELCOME TO</p>

<h1>KAMVEXO</h1>

<p>
Everything You Need,<br>
In One Place.
</p>

<button class="shop">
SHOP NOW →
</button>

</div>

<img
class="hero-image"
src="https://images.unsplash.com/photo-1556742049-0cfed4f6a45d
