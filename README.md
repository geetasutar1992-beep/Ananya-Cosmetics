<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ananya Cosmetics</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#fffaf6;
    color:#333;
}

header{
    background:linear-gradient(135deg,#ff9eb5,#ffe5b4);
    color:white;
    text-align:center;
    padding:60px 20px;
}

header h1{
    font-size:45px;
}

header p{
    font-size:20px;
    margin-top:10px;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:white;
    color:#ff4d79;
    text-decoration:none;
    border-radius:30px;
    font-weight:bold;
}

section{
    padding:50px 20px;
}

h2{
    text-align:center;
    color:#ff4d79;
    margin-bottom:30px;
}

.products{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:20px;
}

.card{
    width:250px;
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 15px rgba(0,0,0,.15);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card img{
    width:100%;
    height:220px;
    object-fit:cover;
}

.card h3{
    text-align:center;
    padding:10px;
    color:#444;
}

.card p{
    text-align:center;
    color:#777;
    padding-bottom:15px;
}

.contact{
    background:#ffeef3;
    text-align:center;
}

.contact p{
    margin:10px;
    font-size:18px;
}

footer{
    background:#ff4d79;
    color:white;
    text-align:center;
    padding:15px;
}
</style>

</head>
<body>

<header>
    <h1>Ananya Cosmetics</h1>
    <p>Natural Beauty • Premium Quality • Affordable Price</p>
    <a href="tel:9284485735" class="btn">Call Now</a>
</header>

<section>
    <h2>Our Products</h2>

    <div class="products">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?w=500" alt="Lipstick">
            <h3>Lipstick</h3>
            <p>Long Lasting Matte Shades</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1596462502278-27bfdc403348?w=500" alt="Face Cream">
            <h3>Face Cream</h3>
            <p>Natural Skin Glow</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1626784215021-2e39ccf971cd?w=500" alt="Perfume">
            <h3>Perfume</h3>
            <p>Fresh & Elegant Fragrance</p>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1583241800698-9d5d7d62e7f4?w=500" alt="Makeup Kit">
            <h3>Makeup Kit</h3>
            <p>Everything for Beautiful You</p>
        </div>

    </div>
</section>

<section class="contact">
    <h2>Contact Us</h2>

    <p><strong>📍 Address:</strong><br>
    Sai Mandir Samor, Unchgaon</p>

    <p><strong>📞 Contact:</strong><br>
    9284485735</p>

    <p><strong>🌸 Thank You for Visiting Ananya Cosmetics 🌸</strong></p>
</section>

<footer>
    © 2026 Ananya Cosmetics | Beauty Begins Here
</footer>

</body>
</html># Ananya-Cosmetics
Natural, Attractive, Designed
