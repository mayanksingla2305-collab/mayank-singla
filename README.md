<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Shri Krishna Jewellers</title>

    <!-- Bootstrap CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            background: #faf8f5;
        }
        header {
            background: #d4af37;
            padding: 15px;
            color: #fff;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
        nav a {
            margin: 0 10px;
            color: #fff;
            font-weight: 600;
            text-decoration: none;
        }
        .hero {
            padding: 80px 20px;
            text-align: center;
            background: linear-gradient(135deg, #fff0c2, #f2d16b);
        }
        .product-card {
            background: #fff;
            border-radius: 10px;
            padding: 25px;
            text-align: center;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 15px rgba(0,0,0,0.15);
        }
        footer {
            background: #333;
            color: #fff;
            padding: 15px;
            text-align: center;
            margin-top: 30px;
        }
    .product-card {
            background-size: cover;
            background-position: center;
            color: #fff;
            font-weight: bold;
            height: 180px;
            display: flex;
            align-items: center;
            justify-content: center;
            border-radius: 10px;
            text-shadow: 0 2px 5px rgba(0,0,0,0.7);
            cursor: pointer
        }
        .necklace { background-image: url('necklace.png'); }
        .ring { background-image: url('ring.png'); }
        .bangle { background-image: url('bangles.png'); }
        .silver { background-image: url('silver.png'); }
    </style>
</head>
<body>

<header>
    <h1>Shri Krishna Jewellers</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home" class="hero">
    <h2 class="fw-bold">Premium Gold & Silver Jewellery</h2>
    <p class="lead">Elegant. Traditional. Handcrafted with Love.</p>
</section>

<section id="about" class="container py-5">
    <h2 class="text-center mb-4">About Us</h2>
    <p class="text-center">Shri Krishna Jewellers brings you the finest handcrafted gold, silver, and diamond jewellery with decades of trust and craftsmanship.</p>
</section>

<section id="products" class="container py-5">
    <h2 class="text-center mb-4">Our Products</h2>
    <div class="row g-4">
        <div class="col-md-3 col-6">
            <div class="product-card necklace">Necklaces</div>
        </div>
        <div class="col-md-3 col-6">
            <div class="product-card ring">Rings</div>
        </div>
        <div class="col-md-3 col-6">
            <div class="product-card bangle">Bangles</div>
        </div>
        <div class="col-md-3 col-6">
            <div class="product-card silver">Silver Items</div>
        </div>
    </div>
</section>

<section id="contact" class="container py-5">
    <h2 class="text-center mb-4">Contact Us</h2>
    <div class="text-center">
        <p><strong>Phone:</strong> +91 98765 43210</p>
        <p><strong>Address:</strong> Main Market, Your City</p>
    </div>
</section>

<footer>
    <p>© 2025 Shri Krishna Jewellers | All Rights Reserved</p>
</footer>

<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
