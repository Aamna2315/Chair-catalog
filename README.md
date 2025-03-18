<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ruby Traders - Premium Seating</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header class="sticky-header">
    <img src="IMG-20250313-WA0028.jpg" alt="Ruby Traders Logo" class="logo">
    <nav>
        <a href="index.html">Home</a>
        <a href="chairs.html">Chairs</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="banner">
    <h1>Premium Seating for Every Space</h1>
</section>

<section class="categories">
    <h2>Our Chair Categories</h2>
    <div class="category-grid">
        <div class="category">
            <a href="chairs.html#office"><img src="office-chairs.jpg" alt="Office Chairs"></a>
            <h3>Office Chairs</h3>
        </div>
        <div class="category">
            <a href="chairs.html#lounge"><img src="lounge-chairs.jpg" alt="Lounge Chairs"></a>
            <h3>Lounge Chairs</h3>
        </div>
        <div class="category">
            <a href="chairs.html#cafe"><img src="cafe-chairs.jpg" alt="Café Chairs"></a>
            <h3>Café Chairs</h3>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2025 Ruby Traders | Premium Seating for Every Space</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Chairs - Ruby Traders</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header class="sticky-header">
    <img src="IMG-20250313-WA0028.jpg" alt="Ruby Traders Logo" class="logo">
    <nav>
        <a href="index.html">Home</a>
        <a href="chairs.html">Chairs</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="chair-category" id="office">
    <h2>Office Chairs</h2>
    <div class="chair-grid">
        <div class="chair">
            <img src="high-back.jpg" alt="High Back Chair">
            <h3>High Back Chair</h3>
            <p>Luxury and ergonomic comfort.</p>
        </div>
        <div class="chair">
            <img src="low-back.jpg" alt="Low Back Chair">
            <h3>Low Back Chair</h3>
            <p>Compact and stylish for offices.</p>
        </div>
    </div>
</section>

<section class="chair-category" id="lounge">
    <h2>Lounge Chairs</h2>
    <div class="chair-grid">
        <div class="chair">
            <img src="lounge1.jpg" alt="Luxury Lounge Chair">
            <h3>Luxury Lounge Chair</h3>
            <p>Perfect for relaxation.</p>
        </div>
    </div>
</section>

<section class="chair-category" id="cafe">
    <h2>Café Chairs</h2>
    <div class="chair-grid">
        <div class="chair">
            <img src="cafe1.jpg" alt="Modern Café Chair">
            <h3>Modern Café Chair</h3>
            <p>Elegant and durable for cafés.</p>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2025 Ruby Traders | Premium Seating for Every Space</p>
</footer>

</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: white;
}

.sticky-header {
    position: fixed;
    width: 100%;
    top: 0;
    background-color: white;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 30px;
    border-bottom: 2px solid #900; /* Ruby Red Accent */
}

.logo {
    height: 50px;
}

nav a {
    text-decoration: none;
    color: #900; /* Ruby Red */
    font-weight: bold;
    margin: 0 15px;
}

.banner {
    margin-top: 80px;
    background: #900;
    color: white;
    padding: 50px;
    font-size: 24px;
}

.categories, .chair-category {
    padding: 30px;
}

.category-grid, .chair-grid {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.category, .chair {
    border: 2px solid #900;
    padding: 15px;
    width: 250px;
    transition: transform 0.3s ease-in-out;
}

.category img, .chair img {
    width: 100%;
    height: auto;
}

.category:hover, .chair:hover {
    transform: scale(1.05);
}

footer {
    background-color: #900;
    color: white;
    padding: 10px;
    margin-top: 20px;
}
