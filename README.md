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
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Commercial Business</title>
<link rel="stylesheet" href="style.css">
</head>
<body>



<header>
<div class="container">
<h1>AutoCommerial</h1>
<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Services</a></li>
<li><a href="#">Projects</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>

</div>
</header>



<section class="hero">
<div class="hero-text">
<h2>Expert Window Tinting for Any Application</h2>
<p>We offer premium solutions for automotive, commercial, and residential window tinting.</p>
<a href="#" class="btn">Get a Quote</a>
</div>
</section>



<section class="services">
<div class="container">
<div class="service">
<img src="c:\Users\admin\Downloads\auto.jpg" alt="Automotive">
<h3>Automotive</h3>
<p>High-quality tinting for vehicles.</p>
</div>
<div class="service">
<img
src="c:\Users\admin\Downloads\1711738968-maintain-brand-authenticity-build-credibility-g-1469786   852.jpg" alt="Commercial">
<h3>Commercial</h3>
<p>Protect office spaces with superior tinting.</p>
</div>
<div class="service">
<img src="c:\Users\admin\Downloads\res.jpg" alt="Residential">
<h3>Residential</h3>
<p>Enhance privacy and reduce heat in homes.</p>
</div>

<div class="service">
<img src="c:\Users\admin\Downloads\Tinting-Boat-Windows.webp" alt="Marine">
<h3>Marine</h3>
<p>Protect boats with durable tinting solutions.</p>
</div>
</div>
</section>



<footer>
<p>© 2025 Automobiles All Rights Reserved.</p>
</footer>


</body>
</html>


style.css



body {
font-family: Arial, sans-serif; margin: 0;
padding: 0;
color: #333;
}



header {
background: #767f94; padding: 20px;
box-shadow: 0 2px lOpx rgba(0, 0, 0, 0.1);
}

.container { width: 90%; margin: auto; display: flex;
justify-content: space-between; align-items: center;
}


nav ul {
list-style: none; display: flex;
}


nav ul li {
margin: 0 15px;
}


nav ul li a {
text-decoration: none; color: #333;
font-weight: bold;
}



.hero {
background:
url('c:\Users\admin \Downloads\1711738968-maintain-brand-authenticity-build-credibility-g-14697868 52.jpg');
height: 400px; display: flex;
align-items: center; justify-content: center;

text-align: center; color: #0b0b0b;
}


.hero-text h2 {
font-size: 2.5rem;
}


.hero .btn {
display: inline-block; background: #ff9800; padding: 10px 20px; color: #fff;
text-decoration: none; margin-top: 20px; border-radius: 5px;
}
.services { padding: 50px 0;
background: #f9f9f9; text-align: center;
}


.services .container { display: flex;
justify-content: space-between;
}


.service { width: 22%;
padding: 20px; background: #fff;

box-shadow: 0 2px lOpx rgba(0, 0, 0, 0.1); border-radius: 5px;
}


.service img { width: 50px; height: 50px;
}



.projects { padding: 50px 0;
text-align: center;
}
.project-gallery { display: flex;
justify-content: center; gap: 20px;
}
.project img { width: 250px; height: 150px;
border-radius: 5px;
}
footer {
background: #111; color: #fff;
text-align: center; padding: 15px; position: relative; bottom: 0;
width: 100;


## OUTPUT


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
