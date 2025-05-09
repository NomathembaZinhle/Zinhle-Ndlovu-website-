
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zee Hair Products - Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="intro">
            <h1>Welcome to Zee Hair Products</h1>
            <p>Natural hair care for the modern woman. Sulfate-free, eco-friendly products for healthy, beautiful hair.</p>
            <img src="images/product-image.jpg" alt="Zee Hair Products" class="hero-image">
        </section>

        <section class="problem">
            <h2>The Problem</h2>
            <p>75% of women use hair products with harsh chemicals that damage hair, scalp, and the environment. Current natural options are often expensive.</p>
        </section>

        <section class="solution">
            <h2>The Solution</h2>
            <p>Zee Hair Products offers natural, effective, and affordable sulfate-free, eco-friendly formulas with ingredients like coconut oil, shea butter, and argan oil.</p>
        </section>

        <section class="cta">
            <h2>Explore Our Products</h2>
            <a href="about.html" class="button">Learn More</a>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Zee Hair Products | All Rights Reserved</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Zee Hair Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="about">
            <h1>About Zee Hair Products</h1>
            <p>Zee Hair Products offers natural, effective, and affordable hair care solutions for modern women looking for eco-friendly alternatives.</p>
        </section>

        <section class="products">
            <h2>Our Product Line</h2>
            <ul>
                <li>Sulfate-free Shampoos</li>
                <li>Eco-friendly Hair Masks</li>
                <li>Natural Conditioners</li>
            </ul>
        </section>

        <section class="target-market">
            <h2>Target Market</h2>
            <p>Women aged 25-45 who care about health, wellness, and sustainability.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Zee Hair Products | All Rights Reserved</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Zee Hair Products</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="contact-form">
            <h1>Contact Us</h1>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" required><br><br>

                <label for="email">Email:</label>
                <input type="email" id="email" required><br><br>

                <label for="message">Message:</label>
                <textarea id="message" required></textarea><br><br>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Zee Hair Products | All Rights Reserved</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

<link rel="stylesheet" href="style.css">

/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero-image {
    width: 100%;
    height: auto;
}

button {
    background-color: #007BFF;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

/* Responsive Design */
@media (max-width: 768px) {
    nav ul li {
        display: block;
        text-align: center;
        margin: 10px 0;
    }
}

.contact-form {
    width: 60%;
    margin: 0 auto;
}

.contact-form input, .contact-form textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0;
}

.contact-form button {
    width: 100%;
    padding: 15px;
    background-color: #28a745;
}
document.getElementById("contact-form").addEventListener("submit", function (e) {
    e.preventDefault();
    let name = document.getElementById("name").value;
    let email = document.getElementById("email").value;
    let message = document.getElementById("message").value;

    if (name && email && message) {
        alert("Thank you for contacting us, " + name + "!");
    } else {
        alert("Please fill in all fields.");
    }
});

