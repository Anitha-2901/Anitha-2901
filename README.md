<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spice Delight - Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Spice Delight</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <h2>Premium Masalas for Authentic Taste</h2>
        <p>Experience the richness of pure and organic spices.</p>
        <a href="products.html" class="btn">Shop Now</a>
    </section>

    <footer>
        <p>&copy; 2025 Spice Delight. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Products - Spice Delight</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Masala Collection</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="products">
        <div class="product">
            <img src="images/turmeric.jpg" alt="Turmeric Powder">
            <h3>Turmeric Powder</h3>
            <p>100% pure and organic.</p>
            <span>$5.99</span>
        </div>
        <div class="product">
            <img src="images/chili.jpg" alt="Red Chili Powder">
            <h3>Red Chili Powder</h3>
            <p>Spicy and flavorful.</p>
            <span>$6.99</span>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Spice Delight. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Spice Delight</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Spice Delight</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="about">
        <p>We are a family-owned business dedicated to providing high-quality, organic masalas sourced from the finest farms.</p>
    </section>

    <footer>
        <p>&copy; 2025 Spice Delight. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Spice Delight</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <form>
            <label>Name:</label>
            <input type="text" required>
            
            <label>Email:</label>
            <input type="email" required>
            
            <label>Message:</label>
            <textarea required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Spice Delight. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #fff5e1;
}

header {
    background: #c0392b;
    color: white;
    text-align: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.banner {
    text-align: center;
    padding: 50px;
}

.btn {
    background: #e67e22;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.products {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

.product {
    border: 1px solid #ccc;
    padding: 10px;
    text-align: center;
}

.contact form {
    display: flex;
    flex-direction: column;
    max-width: 300px;
    margin: auto;
}

.contact form input, .contact form textarea {
    margin: 10px 0;
    padding: 10px;
}

.contact form button {
    background: #c0392b;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
}
