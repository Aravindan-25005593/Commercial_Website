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
```
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #7bb303;
            color: white;
            padding: 1rem 0;
        }
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 90%;
            margin: 0 auto;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        .nav-links {
            list-style: none;
            display: flex;
        }
        .nav-links li {
            margin-left: 20px;
        }
        .nav-links a {
            text-decoration: none;
            color: white;
            transition: color 0.3s;
        }
        .nav-links a:hover {
            color: #e67e22;
        }

        .hero {
            background-color: #ecf0f1;
            height: 300px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #e67e22;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px;
        }

        .container {
            width: 90%;
            margin: 40px auto;
        }
        h2.section-title {
            text-align: center;
            margin-bottom: 30px;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }
        .product-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            width: 300px;
            padding: 15px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .product-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        footer {
            background-color: #34495e;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="logo">Laptop Accessories World</div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Accessories World</h1>
        <a href="#" class="btn">Shop Now</a>
    </section>

    <div class="container">
        <h2 class="section-title">Products list</h2>
        <div class="product-list">
            <div class="product-card">
                <img src="gamingmouse.jpg" alt="Product 1">
                <h3>Gaming Mouse</h3>
                <p>Rs.1500</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
            <div class="product-card">
                <img src="rgbkeyboard.jpg" alt="Product 2">
                <h3>RGB keyboard</h3>
                <p>Rs.2000</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
            <div class="product-card">
                <img src="cooling.jpg" alt="Product 3">
                <h3>Laptop Cooling pad</h3>
                <p>Rs.1600</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Laptop Accessories World. All rights reserved.</p>
    </footer>
</body>
</html>
```

## OUTPUT

<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/25e4444d-a882-4a3b-a3f6-24c7e90d9898" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
