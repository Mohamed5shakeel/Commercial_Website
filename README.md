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

##STYLE.CSS
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    background: #f8f8f8;
}

/* Header */
header {
    background: #222;
    color: #d7cbcb;
    padding: 15px 0;
}

.container {
    width: 90%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

h1 {
    font-size: 24px;
}

/* Navigation */
nav ul {
    list-style: none;
    display: flex;
    padding: 0;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    text-decoration: none;
    color: #bc4343;
    font-weight: bold;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ff9800;
}

/* Hero Section */
.hero {
    background: url('mobile banner.jpg') no-repeat center center/cover;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: #fff;
    padding: 20px;
}

.hero-text h2 {
    font-size: 2.5rem;
    color: #ff5733; /* Updated color for "Latest Smartphones at Best Prices" */
}

.hero .btn {
    display: inline-block;
    background: #ff9800;
    padding: 12px 25px;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    margin-top: 15px;
    border-radius: 5px;
    transition: 0.3s;
}

.hero .btn:hover {
    background: #e68900;
}

/* Products Section */
.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 50px 0;
}

.product {
    background: #fff;
    margin: 15px;
    padding: 20px;
    width: 250px;
    text-align: center;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

.product img {
    width: 100px;
    height: 100px;
}

.product h3 {
    font-size: 1.2rem;
    margin: 10px 0;
}

.product p {
    font-size: 0.9rem;
    color: #666;
}

.product .btn {
    display: inline-block;
    background: #28a745;
    padding: 10px 20px;
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    margin-top: 10px;
    border-radius: 5px;
    transition: 0.3s;
}

.product .btn:hover {
    background: #218838;
}

/* Footer */
footer {
    background: #222;
    color: #fff;
    text-align: center;
    padding: 15px;
    margin-top: 20px;
}



## OUTPUT
![image](https://github.com/user-attachments/assets/2fe1e7ee-e7af-4eb3-93c9-a20e36eea96b)




## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
