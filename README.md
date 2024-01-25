# Mongolian Realty
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mongolian Realty</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>Property Marketplace</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#rent">Rent Properties</a></li>
            <li><a href="#sell">Sell Properties</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home">
    <h2>Welcome to our Property Marketplace</h2>
    <p>Find your dream home or sell your property with us!</p>
</section>

<section id="rent">
    <h2>Properties for Rent</h2>
    <div class="property-list">
        <!-- Display rental property listings here -->
    </div>
</section>

<section id="sell">
    <h2>Properties for Sale</h2>
    <div class="property-list">
        <!-- Display properties for sale listings here -->
    </div>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Have questions or want to list your property? Reach out to us!</p>
    <!-- Add a contact form or contact information here -->
</section>

<footer>
    <p>&copy; 2024 Property Marketplace</p>
</footer>

</body>
</html>

/* styles.css */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

section {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
