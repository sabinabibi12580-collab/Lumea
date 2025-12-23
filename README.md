<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxe Wardrobe - Modern Clothing Brand</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Lato:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <div class="logo">Luxe Wardrobe</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#categories">Categories</a></li>
                <li><a href="#featured">Featured</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Elevate Your Style</h1>
            <p>Discover timeless pieces crafted for the modern wardrobe.</p>
            <a href="#featured" class="cta-button">Shop Now</a>
        </div>
        <div class="hero-image">
            <img src="https://images.unsplash.com/photo-1441986300917-64674bd600d8?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Fashion model">
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Luxe Wardrobe</h2>
            <p>Luxe Wardrobe is a fashion-forward brand dedicated to creating chic, minimal clothing that blends comfort with elegance. Our collections feature soft neutrals accented with bold shades, perfect for the discerning individual who values quality and style.</p>
            <img src="https://images.unsplash.com/photo-1556742049-0cfed4f6a45d?ixlib=rb-4.0.3&auto=format&fit=crop&w=600&q=80" alt="Brand story image">
        </div>
    </section>

    <section id="categories" class="categories">
        <div class="container">
            <h2>Product Categories</h2>
            <div class="grid">
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1591047139829-d91aecb6caea?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Dresses">
                    <h3>Dresses</h3>
                    <p>Elegant and versatile dresses for every occasion.</p>
                </div>
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Tops">
                    <h3>Tops</h3>
                    <p>Chic tops in soft fabrics and modern cuts.</p>
                </div>
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1542272604-787c3835535d?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Bottoms">
                    <h3>Bottoms</h3>
                    <p>Comfortable pants and skirts with a minimalist edge.</p>
                </div>
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1553062407-98eeb64c6a62?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Accessories">
                    <h3>Accessories</h3>
                    <p>Subtle accents to complete your look.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="featured" class="featured">
        <div class="container">
            <h2>Featured Products</h2>
            <div class="grid">
                <div class="product-card">
                    <img src="https://images.unsplash.com/photo-1595777457583-95e059d581b8?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Product 1">
                    <h3>Minimalist Dress</h3>
                    <p>$89.99</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
                <div class="product-card">
                    <img src="https://images.unsplash.com/photo-1582418702059-97ebafb35d09?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Product 2">
                    <h3>Chic Blouse</h3>
                    <p>$59.99</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
                <div class="product-card">
                    <img src="https://images.unsplash.com/photo-1544966503-7cc5ac882d5f?ixlib=rb-4.0.3&auto=format&fit=crop&w=400&q=80" alt="Product 3">
                    <h3>Sleek Pants</h3>
                    <p>$79.99</p>
                    <button class="add-to-cart">Add to Cart</button>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form>
                <input type="text" placeholder="Name" required>
                <input type="email" placeholder="Email" required>
                <textarea placeholder="Message" required></textarea>
                <button type="submit">Send Message</button>
            </form>
            <div class="social-links">
                <a href="#" class="social-icon">Instagram</a>
                <a href="#" class="social-icon">Facebook</a>
                <a href="#" class="social-icon">Twitter</a>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2023 Luxe Wardrobe. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Lato', sans-serif;
    line-height: 1.6;
    color: #333;
    background-color: #f5f5f5;
}

h1, h2, h3 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Header */
header {
    position: fixed;
    top: 0;
    width: 100%;
    background-color: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    z-index: 1000;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem 2rem;
}

.logo {
    font-size: 1.5rem;
    font-weight: 700;
    color: #e91e63;
}

.nav-links {
    display: flex;
    list-style: none;
}

.nav-links li {
    margin-left: 2rem;
}

.nav-links a {
    text-decoration: none;
    color: #333;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #2196f3;
}

.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
}

.hamburger span {
    width: 25px;
    height: 3px;
    background-color: #333;
    margin: 3px 0;
    transition: 0.3s;
}

/* Hero Section */
.hero {
    display: flex;
    align-items: center;
    min-height: 100vh;
    background-color: #fff;
    padding: 0 2rem;
}

.hero-content {
    flex: 1;
    padding-right: 2rem;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    color: #333;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
    color: #666;
}

.cta-button {
    display: inline-block;
    padding: 0.8rem 2rem;
    background-color: #e91e63;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s;
}

.cta-button:hover {
    background-color: #d81b60;
}

.hero-image {
    flex: 1;
}

.hero-image img {
    width: 100%;
    border-radius: 10px;
}

/* About Section */
.about {
    padding: 5rem 0;
    background-color: #f9f9f9;
    text-align: center;
}

.about h2 {
    margin-bottom: 2rem;
    color: #333;
}

.about p {
    max-width: 600px;
    margin: 0 auto 2rem;
    color: #666;
}

.about img {
    width: 100%;
    max-width: 600px;
    border-radius: 10px;
}

/* Categories Section */
.categories {
    padding: 5rem 0;
    background-color: #fff;
}

.categories h2 {
    text-align: center;
    margin-bottom: 3rem;
    color: #333;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.card {
    background-color: #f9f9f9;
    border-radius: 10px;
    overflow: hidden;
    transition: transform 0.3s, box-shadow 0.3s;
}

.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card h3 {
    padding: 1rem;
    color: #333;
}

.card p {
    padding: 0 1rem 1rem;
    color: #666;
}

/* Featured Section */
.featured {
    padding: 5rem 0;
    background-color: #f9f9f9;
}

.featured h2 {
    text-align: center;
    margin-bottom: 3rem;
    color: #333;
}

.product-card {
    background-color: #fff;
    border-radius: 10px;
    overflow: hidden;
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
}

.product-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.product-card img {
    width: 100%;
    height: 250px;
    object-fit: cover;
}

.product-card h3 {
    padding: 1rem;
    color: #333;
}

.product-card p {
    color: #e91e63;
    font-weight: 700;
}

.add-to-cart {
    display: block;
    width: 100%;
    padding: 0.8rem;
    background-color: #2196f3;
    color: #fff;
    border: none;
    border-radius: 0 0 10px 10px;
    cursor: pointer;
    transition: background-color 0.3s;
}

.add-to-cart:hover {
    background-color: #1976d2;
}

/* Contact Section */
.contact {
    padding: 5rem 0;
    background-color: #fff;
    text-align: center;
}

.contact h2 {
    margin-bottom: 2rem;
    color: #333;
}

form {
    max-width: 500px;
    margin: 0 auto 3rem;
}

input, textarea {
    width: 100%;
    padding: 1rem;
    margin-bottom: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-family: 'Lato', sans-serif;
}

button[type="submit"] {
    width: 100%;
    padding: 1rem;
    background-color: #e91e63;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
}

button[type="submit"]:hover {
    background-color: #d81b60;
}

.social-links {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.social-icon {
    text-decoration: none;
    color: #2196f3;
    font-weight: 700;
    transition: color 0.3s;
}

.social-icon:hover {
    color: #1976d2;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}

/* Animations */
.fade-in {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s, transform 0.6s;
}

.fade-in.visible {
    opacity: 1;
    transform: translateY(0);
}

/* Mobile Responsiveness */
@media (max-width: 768px) {
    nav {
        padding: 1rem;
    }

    .nav-links {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 100%;
        left: 0;
        width: 100%;
        background-color: #fff;
        box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .nav-links.active {
        display: flex;
    }

    .nav-links li {
        margin: 1rem 0;
    }

    .hamburger {
        display: flex;
    }

    .hero {
        flex-direction: column;
        text-align: center;
        padding: 2rem 1rem;
    }

    .hero-content {
        padding-right: 0;
    }

    .hero h1 {
        font-size: 2rem;
    }

    .grid {
        grid-template-columns: 1fr;
    }

    .social-links {
        flex-direction: column;
    }
}// Smooth scrolling for navigation links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Mobile menu toggle
const hamburger = document.querySelector('.hamburger');
const navLinks = document.querySelector('.nav-links');
hamburger.addEventListener('click', () => {
    navLinks.classList.toggle('active');
});

// Fade-in animation on scroll
const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('visible');
        }
    });
});

document.querySelectorAll('.card, .product-card, .about img').forEach(el => {
    el.classList.add('fade-in');
    observer.observe(el);
});
