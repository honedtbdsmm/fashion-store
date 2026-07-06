<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>1SeMail Fashion</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial,sans-serif;
    }

    body{
      background:#fff;
      color:#111;
    }

    header{
      background:#000;
      color:#fff;
      display:flex;
      justify-content:space-between;
      align-items:center;
      padding:20px 8%;
    }

    nav a{
      color:#fff;
      text-decoration:none;
      margin-left:20px;
      font-weight:bold;
    }

    .hero{
      height:85vh;
      display:flex;
      justify-content:center;
      align-items:center;
      flex-direction:column;
      background:linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
      url("https://images.unsplash.com/photo-1523381210434-271e8be1f52b?q=80&w=1600&auto=format&fit=crop");
      background-size:cover;
      background-position:center;
      color:white;
      text-align:center;
    }

    .hero h1{
      font-size:55px;
    }

    .hero p{
      margin:20px 0;
      font-size:20px;
    }

    .btn{
      background:gold;
      color:#000;
      padding:15px 35px;
      text-decoration:none;
      border-radius:40px;
      font-weight:bold;
    }

    .products{
      padding:60px 8%;
    }

    .products h2{
      text-align:center;
      margin-bottom:40px;
    }

    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:25px;
    }

    .card{
      border-radius:15px;
      overflow:hidden;
      box-shadow:0 5px 20px rgba(0,0,0,.1);
      background:white;
    }

    .card img{
      width:100%;
      height:320px;
      object-fit:cover;
    }

    .card h3{
      padding:15px;
    }

    .card p{
      padding:0 15px 20px;
      color:#666;
    }

    footer{
      background:#000;
      color:white;
      text-align:center;
      padding:30px;
      margin-top:60px;
    }

  </style>

</head>
<body>

<header>

<h2>1SeMail Fashion</h2>

<nav>
<a href="#">Home</a>
<a href="#">Men</a>
<a href="#">Women</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Premium Fashion Store</h1>

<p>Discover Your New Style</p>

<a href="#" class="btn">Shop Now</a>

</section>

<section class="products">

<h2>Featured Products</h2>

<div class="grid">

<div class="card">
<img src="https://images.unsplash.com/photo-1521572267360-ee0c2909d518?q=80&w=600&auto=format&fit=crop">
<h3>Men T-Shirt</h3>
<p>$29.99</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c?q=80&w=600&auto=format&fit=crop">
<h3>Women's Dress</h3>
<p>$49.99</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?q=80&w=600&auto=format&fit=crop">
<h3>Sneakers</h3>
<p>$79.99</p>
</div>

</div>

</section>

<footer>

<h3>© 2026 1SeMail Fashion</h3>

<p>Email: honestbdsmm@gmail.com</p>

</footer>

</body>
</html>
