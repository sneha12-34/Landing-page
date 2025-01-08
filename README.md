<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShopMate | Your Shopping Partner</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header a {
            color: #fff;
            text-decoration: none;
            margin: 0 0.5rem;
        }
        header a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 4rem 2rem;
            background: url('https://via.placeholder.com/1500x800') no-repeat center center/cover;
            color: #fff;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
        }
        .hero button {
            background: #ff5722;
            color: #fff;
            border: none;
            padding: 0.8rem 1.5rem;
            font-size: 1rem;
            cursor: pointer;
        }
        .hero button:hover {
            background: #e64a19;
        }
        .offers {
            background: #f4f4f4;
            padding: 2rem;
            text-align: center;
        }
        .offers h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }
        .offers p {
            font-size: 1.1rem;
            margin-bottom: 1rem;
        }
        .offers span {
            background: #ff5722;
            color: #fff;
            padding: 0.5rem 1rem;
            font-size: 1.2rem;
            border-radius: 5px;
        }
        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
            padding: 2rem;
            background: #fff;
        }
        .product {
            background: #f9f9f9;
            padding: 1rem;
            border: 1px solid #ddd;
            text-align: center;
            transition: transform 0.2s;
        }
        .product img {
            width: 100%;
            height: auto;
            margin-bottom: 1rem;
        }
        .product h3 {
            font-size: 1.2rem;
            margin-bottom: 0.5rem;
        }
        .product p {
            font-size: 0.9rem;
            margin-bottom: 1rem;
            color: #555;
        }
        .product .offer {
            color: #ff5722;
            font-weight: bold;
            margin-bottom: 1rem;
        }
        .product button {
            background: #4CAF50;
            color: #fff;
            border: none;
            padding: 0.5rem 1rem;
            font-size: 1rem;
            cursor: pointer;
        }
        .product button:hover {
            background: #45a049;
        }
        .product:hover {
            transform: scale(1.05);
        }
        footer {
            background: #333;
            color: #fff;
            padding: 1.5rem 2rem;
            text-align: center;
        }
        footer a {
            color: #ff5722;
            text-decoration: none;
            margin: 0 0.5rem;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">ShopMate</div>
        <nav>
            <a href="#offers">Offers</a>
            <a href="#products">Products</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <section class="hero">
        <h1>Welcome to ShopMate</h1>
        <p>Discover amazing deals and shop your favorite products now!</p>
        <button>Start Shopping</button>
    </section>
    <section id="offers" class="offers">
        <h2>Exclusive Offers & Coupons</h2>
        <p>Don't miss out on our latest deals:</p>
        <span>20% OFF on your first purchase! Use code: FIRST20</span>
    </section>
    <section id="products" class="products">
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Product 1">
            <h3>Product 1</h3>
            <p class="offer">50% OFF</p>
            <p>Stylish and affordable. Perfect for everyone!</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Product 2">
            <h3>Product 2</h3>
            <p class="offer">Buy 1 Get 1 Free</p>
            <p>Grab this deal before it's gone!</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Product 3">
            <h3>Product 3</h3>
            <p class="offer">Save $10</p>
            <p>The best quality at unbeatable prices.</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Product 4">
            <h3>Product 4</h3>
            <p class="offer">Limited Time Offer</p>
            <p>Experience luxury at an affordable price.</p>
            <button>Add to Cart</button>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 ShopMate | <a href="#privacy">Privacy Policy</a> | <a href="#terms">Terms of Service</a></p>
        <p>Follow us on 
            <a href="#facebook">Facebook</a>, 
            <a href="#twitter">Twitter</a>, 
            <a href="#instagram">Instagram</a>
        </p>
    </footer>
</body>
</html>
