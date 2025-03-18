# Chair-catalog
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chair Collection</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Our Chair Collection</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="chairs.html">Chairs</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section>
        <h2>Explore Our Stylish Chairs</h2>
        <p>Browse our exclusive collection of high-quality chairs.</p>
        <a href="chairs.html" class="btn">View Chairs</a>
    </section>
    <footer>
        <p>&copy; 2025 Chair Collection</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Chairs</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Chair Models</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="chairs.html">Chairs</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>
    <section class="chair-gallery">
        <div class="chair">
            <img src="chair1.jpg" alt="Modern Chair">
            <h3>Modern Chair</h3>
            <p>$120</p>
        </div>
        <div class="chair">
            <img src="chair2.jpg" alt="Classic Wooden Chair">
            <h3>Classic Wooden Chair</h3>
            <p>$150</p>
        </div>
        <div class="chair">
            <img src="chair3.jpg" alt="Luxury Lounge Chair">
            <h3>Luxury Lounge Chair</h3>
            <p>$250</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Chair Collection</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background-color: #333;
    color: white;
    padding: 15px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
}

.chair-gallery {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
    flex-wrap: wrap;
}

.chair {
    border: 1px solid #ddd;
    padding: 10px;
    width: 250px;
}

.chair img {
    width: 100%;
    height: auto;
}

.btn {
    display: inline-block;
    background: #444;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    margin-top: 10px;
}
