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
    <title>Commercial Website</title>
    <style>
        
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #6cd3d8;
        }

        
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 2rem;
            background-color: #333;
            color: rgb(229, 232, 235);
        }

        .header .logo {
            font-size: 1.8rem;
            font-weight: bold;
        }

        .header .nav ul {
            display: flex;
            list-style: none;
        }

        .header .nav ul li {
            margin-left: 2rem;
        }

        .header .nav ul li a {
            color: rgb(237, 231, 231);
            text-decoration: none;
            font-size: 1rem;
        }

        
        .main {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 2rem 0;
        }

        
        .hero {
            text-align: center;
            margin-bottom: 2rem;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
        }

        .cta-button {
            padding: 10px 20px;
            background-color: #333;
            color: rgb(246, 242, 242);
            text-decoration: none;
            border-radius: 5px;
        }

        
        .features {
            display: flex;
            justify-content: space-around;
            width: 80%;
            margin-top: 3rem;
        }

        .feature {
            text-align: center;
            padding: 1rem;
            background-color: #7cadd6;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 30%;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .feature h2 {
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }

        
        .feature:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
        }

        
        .about-us {
            background-color: #75a9e8;
            width: 80%;
            padding: 2rem;
            margin-top: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .about-us h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .about-us p {
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

    
        .contact {
            background-color: #78a6e3;
            width: 80%;
            padding: 2rem;
            margin-top: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .contact h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .contact p {
            font-size: 1.2rem;
            margin-bottom: 1rem;
        }

        
        .login-form {
            background-color: #739ad5;
            width: 80%;
            padding: 2rem;
            margin-top: 2rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .login-form h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .login-form input {
            width: 100%;
            padding: 10px;
            margin: 0.5rem 0;
            font-size: 1rem;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .login-form button {
            width: 100%;
            padding: 10px;
            background-color: #333;
            color: white;
            font-size: 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .login-form button:hover {
            background-color: #444;
        }

        
        .footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #333;
            color: white;
        }

        
        @media (max-width: 768px) {
            .features {
                flex-direction: column;
                align-items: center;
            }

            .feature {
                width: 80%;
                margin-bottom: 2rem;
            }

            .about-us, .contact, .login-form {
                width: 90%;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <div class="logo">My Company</div>
        <nav class="nav">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#about-us">About</a></li>
                <li><a href="#contact">Contact</a></li>
                <li><a href="#login">Login</a></li>
            </ul>
        </nav>
    </header>

    <main class="main">
        <section class="hero">
            <h1>Welcome to Our Company</h1>
            <p>We provide amazing services to make your life better.</p>
            <a href="#" class="cta-button">Learn More</a>
        </section>

        <section class="features">
            <div class="feature">
                <h2>Feature 1</h2>
                <p>High-quality services.</p>
            </div>
            <div class="feature">
                <h2>Feature 2</h2>
                <p>Affordable prices.</p>
            </div>
            <div class="feature">
                <h2>Feature 3</h2>
                <p>Customer satisfaction guaranteed.</p>
            </div>
            
            <div class="feature">
                <h2>Feature 4</h2>
                <p>Fast and reliable support.</p>
            </div>
            <div class="feature">
                <h2>Feature 5</h2>
                <p>Secure transactions with encryption.</p>
            </div>
            <div class="feature">
                <h2>Feature 6</h2>
                <p>Global reach, services available worldwide.</p>
            </div>
        </section>

        
        <section id="about-us" class="about-us">
            <h2>About Us</h2>
            <p>We are a leading company providing high-quality services for over 10 years. Our mission is to make life better for our customers through innovation and dedication.</p>
        </section>

        
        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <p>Email: support@mycompany.com</p>
            <p>Phone: +123 456 7890</p>
            <p>Address: 123 Main Street, City, Country</p>
        </section>

        
        <section id="login" class="login-form">
            <h2>Login</h2>
            <form action="#" method="post">
                <input type="email" placeholder="Email" required>
                <input type="password" placeholder="Password" required>
                <button type="submit">Login</button>
            </form>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2025 My Company. All rights reserved.</p>
    </footer>
</body>
</html>

## OUTPUT


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
