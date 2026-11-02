# Ex02 Commercial Website
## Date: 02-11-2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
about.html

<!DOCTYPE html>
<html>
<head>
    <title>LUXE MART | About Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1 class="logo">LUXE MART</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="categories.html">Categories</a>
        <a href="shop.html">Shop</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="about-section">
    <div class="about-image">
        <img src="https://images.unsplash.com/photo-1441986300917-64674bd600d8?w=900" alt="Our store">
    </div>

    <div class="about-content">
        <h2>About LUXE MART</h2>
        <p>
            LUXE MART is an online shopping destination
            created to make shopping simple, stylish and enjoyable.
        </p>

        <p>
            We offer a wide range of products including fashion,
            electronics, beauty and home accessories.
        </p>

        <p>
            Our mission is to provide quality products,
            affordable prices and a wonderful shopping experience.
        </p>

        <a href="shop.html" class="btn">Start Shopping</a>
    </div>
</section>

<footer>
    <p>© 2026 LUXE MART | Designed by ASIN RENIX V</p>
    <p>Register Number: YOUR REGISTER NUMBER</p>
</footer>

</body>
</html>

categories.html

<!DOCTYPE html>
<html>
<head>
    <title>LUXE MART | Categories</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1 class="logo">LUXE MART</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="categories.html">Categories</a>
        <a href="shop.html">Shop</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="section">
    <h2>Explore Our Categories</h2>

    <div class="flex-container">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1483985988355-763728e1935b?w=600" alt="Fashion">
            <h3>Fashion</h3>
            <p>Discover trendy outfits and accessories.</p>
            <a href="shop.html" class="btn">Explore</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1546435770-a3e426bf472b?w=600" alt="Electronics">
            <h3>Electronics</h3>
            <p>Explore modern gadgets and technology.</p>
            <a href="shop.html" class="btn">Explore</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1608571423902-eed4a5ad8108?w=600" alt="Beauty">
            <h3>Beauty</h3>
            <p>Find beauty and skincare essentials.</p>
            <a href="shop.html" class="btn">Explore</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1616486338812-3dadae4b4ace?w=600" alt="Home Decor">
            <h3>Home Decor</h3>
            <p>Make your home beautiful and comfortable.</p>
            <a href="shop.html" class="btn">Explore</a>
        </div>

    </div>
</section>

<footer>
    <p>© 2026 LUXE MART | Designed by ASIN RENIX V</p>
    <p>Register Number: YOUR REGISTER NUMBER</p>
</footer>

</body>
</html>

contact.html


<!DOCTYPE html>
<html>
<head>
    <title>LUXE MART | Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1 class="logo">LUXE MART</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="categories.html">Categories</a>
        <a href="shop.html">Shop</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="contact-section">
    <h2>Contact Us</h2>
    <p>We would love to hear from you!</p>

    <div class="contact-container">

        <div class="contact-info">
            <h3>Get In Touch</h3>
            <p>Email: support@luxemart.com</p>
            <p>Phone: +91 98765 43210</p>
            <p>Location: Chennai, Tamil Nadu</p>
        </div>

        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="text" placeholder="Subject">
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>

    </div>
</section>

<footer>
    <p>© 2026 LUXE MART | Designed by ASIN RENIX V</p>
    <p>Register Number: YOUR REGISTER NUMBER</p>
</footer>

</body>
</html>

index.html


<!DOCTYPE html>
<html>
<head>
    <title>LUXE MART | Home</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1 class="logo">LUXE MART</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="categories.html">Categories</a>
        <a href="shop.html">Shop</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h2>Discover Your Style</h2>
        <p>Explore the latest trends and upgrade your lifestyle.</p>
        <a href="shop.html" class="btn">Shop Now</a>
    </div>
</section>

<section class="section">
    <h2>Welcome to LUXE MART</h2>
    <p>Your destination for fashion, beauty and lifestyle products.</p>
</section>

<section class="banner">
    <h2>Special Sale!</h2>
    <p>Get up to 50% OFF on selected products.</p>
    <a href="shop.html" class="btn">Explore Offers</a>
</section>

<footer>
    <p>© 2026 LUXE MART | Designed by ASIN RENIX V</p>
    <p>Register Number: YOUR REGISTER NUMBER</p>
</footer>

</body>
</html>

shop.html


<!DOCTYPE html>
<html>
<head>
    <title>LUXE MART | Shop</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1 class="logo">LUXE MART</h1>
    <nav>
        <a href="index.html">Home</a>
        <a href="categories.html">Categories</a>
        <a href="shop.html">Shop</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
</header>

<section class="section">
    <h2>Our Featured Products</h2>

    <div class="flex-container">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff?w=600" alt="Shoes">
            <h3>Sports Shoes</h3>
            <p>₹1,499</p>
            <a href="contact.html" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1548036328-c9fa89d128fa?w=600" alt="Handbag">
            <h3>Premium Handbag</h3>
            <p>₹1,999</p>
            <a href="contact.html" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?w=600" alt="Headphones">
            <h3>Wireless Headphones</h3>
            <p>₹2,499</p>
            <a href="contact.html" class="btn">Buy Now</a>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?w=600" alt="Watch">
            <h3>Classic Watch</h3>
            <p>₹1,799</p>
            <a href="contact.html" class="btn">Buy Now</a>
        </div>

    </div>
</section>

<footer>
    <p>© 2026 LUXE MART | Designed by ASIN RENIX V</p>
    <p>Register Number: YOUR REGISTER NUMBER</p>
</footer>

</body>
</html>

```

## OUTPUT
![alt text](image.png)
![alt text](image-1.png)
![alt text](image-2.png)
![alt text](image-3.png)
![alt text](image-4.png)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
