# Sona-Mall
A Java Console Based Project for the e commerce mall
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Sona Mall</title>
</head>

<body>

    <h1>Sona Mall</h1>
    <h2>Login</h2>

    <form>
        <label>Email:</label><br>
        <input type="email" placeholder="Enter your email" required><br><br>

        <label>Password:</label><br>
        <input type="password" placeholder="Enter your password" required><br><br>

        <button type="submit">Login</button>
    </form>

    <p>Don't have an account?</p>
    <a href="register.html">Create Account</a>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sona Mall - Online Shopping</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
        }

        header {
            background-color: #2e7d32;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: white;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px gray;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 20px;
            font-weight: bold;
        }

        .welcome {
            text-align: center;
            padding: 50px 20px;
        }

        .welcome h2 {
            color: #2e7d32;
            font-size: 32px;
        }

        .products {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            padding: 20px;
        }

        .product {
            background-color: white;
            width: 220px;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 2px 8px #ccc;
        }

        .product h3 {
            color: #333;
        }

        .product button {
            background-color: #2e7d32;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

    <header>
        <h1>🛍️ Sona Mall</h1>
        <p>Your Online Shopping Destination</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="login.html">Login</a>
        <a href="register.html">Register</a>
        <a href="cart.html">Cart 🛒</a>
    </nav>

    <section class="welcome">
        <h2>Welcome to Sona Mall</h2>
        <p>Shop your favorite products online!</p>
    </section>

    <section class="products">

        <div class="product">
            <h3>Fashion</h3>
            <p>Latest fashion products</p>
            <button>Shop Now</button>
        </div>

        <div class="product">
            <h3>Jewellery</h3>
            <p>Beautiful jewellery collections</p>
            <button>Shop Now</button>
        </div>

        <div class="product">
            <h3>Electronics</h3>
            <p>Latest electronic products</p>
            <button>Shop Now</button>
        </div>

        <div class="product">
            <h3>Beauty</h3>
            <p>Beauty and skincare products</p>
            <button>Shop Now</button>
        </div>

    </section>

    <footer>
        <p>© 2026 Sona Mall | Online Shopping Website</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register - Sona Mall</title>
</head>

<body>

    <h1>🛍️ Sona Mall</h1>
    <h2>Create Account</h2>

    <form>
        <label>Full Name:</label><br>
        <input type="text" placeholder="Enter your name" required><br><br>

        <label>Email:</label><br>
        <input type="email" placeholder="Enter your email" required><br><br>

        <label>Password:</label><br>
        <input type="password" placeholder="Create a password" required><br><br>

        <label>Confirm Password:</label><br>
        <input type="password" placeholder="Confirm your password" required><br><br>

        <button type="submit">Register</button>
    </form>

    <p>Already have an account?</p>
    <a href="login.html">Login</a>

    <br><br>
    <a href="index.html">Back to Home</a>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sona Mall - Products</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
        }

        /* Header */
        header {
            background-color: #1f4d3a;
            color: white;
            padding: 15px 30px;
            display: flex;
            align-items: center;
            gap: 25px;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
            white-space: nowrap;
        }

        .tagline {
            font-size: 12px;
        }

        /* Search */
        .search {
            flex: 1;
            display: flex;
        }

        .search input {
            width: 100%;
            padding: 12px;
            border: none;
            font-size: 16px;
        }

        .search button {
            padding: 12px 20px;
            border: none;
            background-color: #f5a623;
            cursor: pointer;
        }

        /* Navigation */
        nav {
            background-color: white;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px #ccc;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 18px;
            font-weight: bold;
        }

        /* Welcome */
        .welcome {
            text-align: center;
            padding: 25px;
        }

        .welcome h1 {
            color: #1f4d3a;
        }

        /* Categories */
        .categories {
            text-align: center;
            margin-bottom: 20px;
        }

        .categories button {
            padding: 10px 18px;
            margin: 5px;
            border: 1px solid #1f4d3a;
            background-color: white;
            border-radius: 20px;
            cursor: pointer;
        }

        /* Products */
        .products {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            padding: 20px;
        }

        .product {
            background-color: white;
            width: 230px;
            padding: 20px;
            text-align: center;
            border-radius: 10px;
            box-shadow: 0 2px 8px #ccc;
        }

        .product-image {
            font-size: 70px;
            padding: 20px;
        }

        .product h3 {
            margin: 10px 0;
        }

        .price {
            color: #d35400;
            font-size: 20px;
            font-weight: bold;
        }

        .product button {
            background-color: #1f4d3a;
            color: white;
            border: none;
            padding: 11px 20px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }

        .product button:hover {
            background-color: #143528;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 30px;
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>

        <div class="logo">
            🛍️ RM | Sona Mall
            <div class="tagline">Shop Smart. Live Better.</div>
        </div>

        <div class="search">
            <input type="text" placeholder="Search products...">
            <button>🔍 Search</button>
        </div>

    </header>

    <!-- Navigation -->
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="login.html">Login</a>
        <a href="register.html">Register</a>
        <a href="cart.html">🛒 Cart</a>
    </nav>

    <!-- Welcome -->
    <section class="welcome">
        <h1>Welcome to Sona Mall</h1>
        <p>Discover amazing products at great prices.</p>
    </section>

    <!-- Categories -->
    <div class="categories">

        <button>All</button>
        <button>Fashion</button>
        <button>Jewellery</button>
        <button>Electronics</button>
        <button>Beauty</button>

    </div>

    <!-- Products -->
    <section class="products">

        <div class="product">

            <div class="product-image">👗</div>

            <h3>Fashion Dress</h3>

            <p>Beautiful latest fashion dress</p>

            <div class="price">₹799</div>

            <button>Add to Cart</button>

        </div>


        <div class="product">

            <div class="product-image">💍</div>

            <h3>Fashion Jewellery</h3>

            <p>Elegant jewellery collection</p>

            <div class="price">₹499</div>

            <button>Add to Cart</button>

        </div>


        <div class="product">

            <div class="product-image">🎧</div>

            <h3>Wireless Headphones</h3>

            <p>High quality wireless headphones</p>

            <div class="price">₹1,299</div>

            <button>Add to Cart</button>

        </div>


        <div class="product">

            <div class="product-image">💄</div>

            <h3>Beauty Kit</h3>

            <p>Complete beauty care kit</p>

            <div class="price">₹699</div>

            <button>Add to Cart</button>

        </div>

    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Sona Mall</p>
        <p>Shop Smart. Live Better.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sona Mall - Cart</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f3f3f3;
        }

        header {
            background-color: #1f4d3a;
            color: white;
            text-align: center;
            padding: 25px;
        }

        nav {
            background-color: white;
            padding: 15px;
            text-align: center;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 15px;
            font-weight: bold;
        }

        .cart {
            background-color: white;
            width: 80%;
            max-width: 700px;
            margin: 40px auto;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 8px #ccc;
        }

        .cart h2 {
            color: #1f4d3a;
        }

        .item {
            border-bottom: 1px solid #ddd;
            padding: 20px 0;
        }

        .price {
            font-weight: bold;
            color: #d35400;
        }

        .checkout {
            background-color: #1f4d3a;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 5px;
            cursor: pointer;
        }

        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>🛍️ RM | Sona Mall</h1>
        <p>Shopping Cart</p>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="login.html">Login</a>
        <a href="register.html">Register</a>
        <a href="cart.html">🛒 Cart</a>
    </nav>

    <div class="cart">

        <h2>🛒 Your Shopping Cart</h2>

        <div class="item">
            <h3>Fashion Dress</h3>
            <p>Quantity: 1</p>
            <p class="price">₹799</p>
        </div>

        <div class="item">
            <h3>Fashion Jewellery</h3>
            <p>Quantity: 1</p>
            <p class="price">₹499</p>
        </div>

        <h2>Total: ₹1,298</h2>

        <button class="checkout">Proceed to Checkout</button>

    </div>

    <footer>
        <p>© 2026 Sona Mall</p>
        <p>Shop Smart. Live Better.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Sona Mall - Checkout</title>

    <style>
        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f4f6f5;
        }

        /* Header */
        header {
            background: #1f4d3a;
            color: white;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        .logo span {
            display: block;
            font-size: 12px;
            font-weight: normal;
            margin-top: 4px;
        }

        /* Navigation */
        nav {
            background: white;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px #ddd;
        }

        nav a {
            text-decoration: none;
            color: #333;
            margin: 0 18px;
            font-weight: bold;
        }

        /* Main */
        .container {
            width: 90%;
            max-width: 900px;
            margin: 30px auto;
        }

        .container h1 {
            color: #1f4d3a;
        }

        .checkout-box {
            background: white;
            padding: 25px;
            margin-top: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px #ddd;
        }

        /* Form */
        label {
            font-weight: bold;
            display: block;
            margin-top: 15px;
        }

        input,
        select {
            width: 100%;
            padding: 12px;
            margin-top: 7px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* Order Summary */
        .summary {
            background: #f8f8f8;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
        }

        .summary p {
            display: flex;
            justify-content: space-between;
        }

        .total {
            font-size: 20px;
            font-weight: bold;
            color: #d35400;
        }

        /* Button */
        .place-order {
            width: 100%;
            margin-top: 25px;
            padding: 15px;
            background: #f5a623;
            color: #222;
            border: none;
            border-radius: 6px;
            font-size: 17px;
            font-weight: bold;
            cursor: pointer;
        }

        .place-order:hover {
            background: #e39412;
        }

        /* Footer */
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>

<body>

    <!-- Header -->
    <header>
        <div class="logo">
            🛍️ RM | Sona Mall
            <span>Shop Smart. Live Better.</span>
        </div>

        <div>
            🛒 Checkout
        </div>
    </header>


    <!-- Navigation -->
    <nav>
        <a href="index.html">Home</a>
        <a href="products.html">Products</a>
        <a href="cart.html">Cart</a>
        <a href="login.html">Login</a>
    </nav>


    <!-- Checkout -->
    <div class="container">

        <h1>Checkout</h1>

        <div class="checkout-box">

            <h2>📦 Delivery Details</h2>

            <label>Full Name</label>
            <input type="text" placeholder="Enter your full name">

            <label>Mobile Number</label>
            <input type="tel" placeholder="Enter your mobile number">

            <label>Address</label>
            <input type="text" placeholder="Enter your delivery address">

            <label>City</label>
            <input type="text" placeholder="Enter your city">

            <label>PIN Code</label>
            <input type="text" placeholder="Enter PIN code">

        </div>


        <div class="checkout-box">

            <h2>💳 Payment Method</h2>

            <label>Select Payment Method</label>

            <select>
                <option>Cash on Delivery</option>
                <option>UPI</option>
                <option>Credit / Debit Card</option>
            </select>

        </div>


        <div class="checkout-box">

            <h2>🧾 Order Summary</h2>

            <div class="summary">

                <p>
                    <span>Fashion Dress</span>
                    <span>₹799</span>
                </p>

                <p>
                    <span>Fashion Jewellery</span>
                    <span>₹499</span>
                </p>

                <hr>

                <p class="total">
                    <span>Total</span>
                    <span>₹1,298</span>
                </p>

            </div>

            <button class="place-order">
                Place Order
            </button>

        </div>

    </div>


    <!-- Footer -->
    <footer>
        <p>© 2026 Sona Mall</p>
        <p>Shop Smart. Live Better.</p>
    </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Order Successful - Sona Mall</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f6f5;
            text-align: center;
        }

        header {
            background-color: #1f4d3a;
            color: white;
            padding: 25px;
        }

        .logo {
            font-size: 26px;
            font-weight: bold;
        }

        .success-box {
            background-color: white;
            width: 90%;
            max-width: 600px;
            margin: 60px auto;
            padding: 40px 20px;
            border-radius: 12px;
            box-shadow: 0 2px 10px #ccc;
        }

        .success-icon {
            font-size: 70px;
        }

        h1 {
            color: #1f4d3a;
        }

        .order-number {
            background-color: #f3f3f3;
            padding: 15px;
            margin: 20px 0;
            border-radius: 8px;
        }

        .home-button,
        .products-button {
            display: inline-block;
            text-decoration: none;
            padding: 13px 25px;
            border-radius: 6px;
            margin-top: 15px;
        }

        .home-button {
            background-color: #1f4d3a;
            color: white;
        }

        .products-button {
            background-color: #f5a623;
            color: #222;
        }

        footer {
            background-color: #222;
            color: white;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>

<body>

    <header>
        <div class="logo">🛍️ RM | Sona Mall</div>
        <p>Shop Smart. Live Better.</p>
    </header>

    <div class="success-box">

        <div class="success-icon">✅</div>

        <h1>Order Placed Successfully!</h1>

        <p>Thank you for shopping with Sona Mall.</p>

        <p>Your order has been successfully placed.</p>

        <div class="order-number">
            <strong>Order ID:</strong> RM20260001
        </div>

        <p>📦 Your order will be delivered soon.</p>

        <a href="products.html" class="products-button">
            Continue Shopping
        </a>

        <br>

        <a href="index.html" class="home-button">
            Back to Home
        </a>

    </div>

    <footer>
        <p>© 2026 Sona Mall</p>
        <p>Shop Smart. Live Better.</p>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    color: #333;
}

header {
    background-color: #2874f0;
    color: white;
    padding: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 28px;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-size: 16px;
}

nav a:hover {
    text-decoration: underline;
}

main {
    text-align: center;
    padding: 100px 20px;
}

main h2 {
    font-size: 40px;
    margin-bottom: 20px;
}

main p {
    font-size: 20px;
    margin-bottom: 30px;
}

button {
    background-color: #fb641b;
    color: white;
    border: none;
    padding: 12px 30px;
    font-size: 18px;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #e85b18;
}

footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 100px;
}
console.log("SonaMart website loaded successfully!");

function addToCart(productName, price) {
    alert(productName + " added to cart!");
}
