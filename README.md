# index.html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beyezy - Explore Latest Apparel</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <div class="logo">
        <h1>Beyezy</h1>
    </div>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#offers">Latest Offers</a></li>
            <li><a href="#login">Login</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <h2>Welcome to Beyezy</h2>
    <p>Discover the latest styles in T-shirts, Hoodies, and Shirts!</p>
</section>

<section id="offers">
    <h2>Latest Offers</h2>
    <div class="product-list">
        <!-- Product Item 1 -->
        <div class="product">
            <h3>T-shirt</h3>
            <p>Price: $19.99</p>
            <p>Size: M, L, XL</p>
            <p>Description: Comfortable and stylish T-shirt.</p>
            <button onclick="redirectToOrder()">Order Now</button>
        </div>
        <!-- Product Item 2 -->
        <div class="product">
            <h3>Hoodie</h3>
            <p>Price: $39.99</p>
            <p>Size: M, L, XL</p>
            <p>Description: Cozy and warm hoodie for all seasons.</p>
            <button onclick="redirectToOrder()">Order Now</button>
        </div>
        <!-- Product Item 3 -->
        <div class="product">
            <h3>Shirt</h3>
            <p>Price: $29.99</p>
            <p>Size: M, L, XL</p>
            <p>Description: Formal shirt for a sharp look.</p>
            <button onclick="redirectToOrder()">Order Now</button>
        </div>
    </div>
</section>

<section id="login">
    <h2>Login/Signup</h2>
    <form>
        <input type="email" placeholder="Email" required>
        <input type="password" placeholder="Password" required>
        <button type="submit">Login</button>
        <p>Or login with:</p>
        <button onclick="socialLogin('google')">Google</button>
        <button onclick="socialLogin('facebook')">Facebook</button>
        <button onclick="socialLogin('twitter')">Twitter</button>
        <button onclick="socialLogin('mobile')">Mobile Number</button>
    </form>
</section>

<footer>
    <p>&copy; 2024 Beyezy. All rights reserved.</p>
</footer>

<script>
    // Function to handle "Order Now" button redirection
    function redirectToOrder() {
        window.location.href = "https://yoursite.com";  // Replace with your external order URL
    }

    // Function for social login (placeholder for now)
    function socialLogin(platform) {
        alert('Logging in with ' + platform);
    }
</script>

</body>
</html>
