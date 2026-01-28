# ci-cd
#html.sibika_project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShoeStore - Premium Shoes Collection</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #000;
            color: white;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        nav {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }
        .logo {
            font-size: 1.8rem;
            font-weight: bold;
        }
        .nav-links {
            display: flex;
            list-style: none;
            gap: 2rem;
        }
        .nav-links a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            background: url('https://via.placeholder.com/1920x600/000/fff?text=Premium+Shoes') no-repeat center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            margin-top: 80px;
        }
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }
        .products {
            max-width: 1200px;
            margin: 4rem auto;
            padding: 0 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }
        .product-card {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-card img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }
        .product-info h3 {
            padding: 1rem;
            font-size: 1.2rem;
        }
        .price {
            padding: 0 1rem 1rem;
            font-size: 1.5rem;
            color: #e74c3c;
        }
        .btn {
            display: inline-block;
            background: #000;
            color: white;
            padding: 0.8rem 2rem;
            text-decoration: none;
            border-radius: 25px;
            margin-bottom: 1rem;
        }
        footer {
            background: #000;
            color: white;
            text-align: center;
            padding: 2rem;
        }
        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }
            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">ShoeStore</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#shop">Shop</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero" id="home">
        <div>
            <h1>Discover Premium Shoes</h1>
            <p>Style meets comfort. Shop now!</p>
            <a href="#shop" class="btn">Explore Collection</a>
        </div>
    </section>

    <section class="products" id="shop">
        <div class="product-card">
            <img src="https://via.placeholder.com/300x250/ccc?text=Running+Shoes" alt="Running Shoes">
            <div class="product-info">
                <h3>Running Shoes Pro</h3>
            </div>
            <div class="price">$59.99 <strike>$79.99</strike></div>
            <a href="#" class="btn">Add to Cart</a>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300x250/ccc?text=Casual+Shoes" alt="Casual Shoes">
            <div class="product-info">
                <h3>Casual Sneakers</h3>
            </div>
            <div class="price">$49.99 <strike>$69.99</strike></div>
            <a href="#" class="btn">Add to Cart</a>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300x250/ccc?text=Leather+Boots" alt="Leather Boots">
            <div class="product-info">
                <h3>Leather Boots</h3>
            </div>
            <div class="price">$89.99 <strike>$109.99</strike></div>
            <a href="#" class="btn">Add to Cart</a>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/300x250/ccc?text=Sports+Shoes" alt="Sports Shoes">
            <div class="product-info">
                <h3>Sports Edition</h3>
            </div>
            <div class="price">$69.99 <strike>$89.99</strike></div>
            <a href="#" class="btn">Add to Cart</a>
        </div>
    </section>

    <footer id="contact">
        <p>&copy; 2026 ShoeStore. All rights reserved. | Delhi, India</p>
    </footer>
</body>
</html>
