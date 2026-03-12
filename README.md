# Ex02- Commercial Website
## Name: Sivaprasath R
## Reg No: 212224243007

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
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Commercial Website</title>
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
            background-color: #2c3e50;
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
            <div class="logo">Face 2 Face</div>
            <ul class="nav-links">
                <li><a href="#">Home</a></li>
                <li><a href="#">Shop</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Summer Collection 2026</h1>
        <p>Discover the best trends for this season.</p>
        <a href="#" class="btn">Shop Now</a>
    </section>

    <div class="container">
        <h2 class="section-title">Featured Products</h2>
        <div class="product-list">
            <div class="product-card">
                <img src="download.jpg" alt="Product 1">
                <h3>Classic Watch</h3>
                <p>Rs/1500</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
            <div class="product-card">
                <img src="leather-pouch-bag-in-tan-esmerelda-bicyclistshop-leather-goods-102104.webp" alt="Product 2">
                <h3>Leather Bag</h3>
                <p>Rs/2500</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
            <div class="product-card">
                <img src="51wwVl2r-WL.jpg" alt="Product 3">
                <h3>Sunglasses</h3>
                <p>Rs/600</p>
                <a href="#" class="btn">Add to Cart</a>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2026 Face 2 Face Commercial Website. All rights reserved.</p>
    </footer>
</body>
</html>
```

## OUTPUT

<img width="1917" height="677" alt="image" src="https://github.com/user-attachments/assets/e2ee7baf-2e9a-4131-8adf-52ff9d569ec3" />


<img width="1910" height="686" alt="image" src="https://github.com/user-attachments/assets/523d43fe-36d6-4211-a30b-4ca873d380bb" />



## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
