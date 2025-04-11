# Ex02 Commercial Website
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile Store</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>
    <div class="container">
        <h1>Mobile Store</h1>
        <nav>
            <ul>
                <li><a href="#" onclick="showPage('home')">Home</a></li>
                <li><a href="#" onclick="showPage('shop')">Shop</a></li>
                <li><a href="#" onclick="showPage('brands')">Brands</a></li>
                <li><a href="#" onclick="showPage('offers')">Offers</a></li>
                <li><a href="#" onclick="showPage('contact')">Contact</a></li>
            </ul>
        </nav>
    </div>
</header>

<section id="home">
    <h2>Latest Smartphones at Best Prices</h2>
    <p>Find the perfect mobile phone with unbeatable deals and discounts.</p>
</section>

<section id="shop" style="display: none;">
    <h2>Shop Smartphones</h2>
    <p>Explore our wide range of smartphones.</p>
</section>

<section id="brands" style="display: none;">
    <h2>Popular Mobile Brands</h2>
    <p>Check out the best brands in the market.</p>
</section>

<section id="offers" style="display: none;">
    <h2>🔥 Exclusive Deals & Offers 🔥</h2>
    <p>Find the best deals on smartphones and accessories.</p>
</section>

<section id="contact" style="display: none;">
    <h2>Contact Us</h2>
    <form action="submit_contact.php" method="POST">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>
        
        <label for="message">Your Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>
        
        <button type="submit" class="btn">Send Message</button>
    </form>
</section>

<footer>
    <p>© 2025 Mobile Store. All Rights Reserved. Deepika S</p>
</footer>
</body>
</html>


## OUTPUT


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
