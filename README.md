# Project Responsive Web Design using Bootstrap
## Date:

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Tech Hub</title>
    <link rel="stylesheet" href="MAIN.CSS">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <!-- Navigation Bar -->
    <header class="header">
        <div class="logo">
            <h1>Tech Hub</h1>
        </div>
        <nav class="nav">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#deals">Deals</a></li>
                <li><a href="#brands">Brands</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section (Featured Image) -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h2>Welcome to Tech Hub</h2>
            <p>Your one-stop shop for all the latest gadgets!</p>
            <button><a href="#products">Shop Now</a></button>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="products">
        <h2>Latest Technology Products</h2>
        <div class="product-grid">
            <article class="product-item">
                <img src="https://in-exstatic-vivofs.vivo.com/gdHFRinHEMrj3yPG/1707995273516/451c30b0f972851219b58e6c304334f1.png" alt="Product 1">
                <h3>New Smartphone</h3>
                <p>Experience cutting-edge performance and sleek design with our latest smartphones.</p>
                <a href="#">Learn More</a>
            </article>
            <article class="product-item">
                <img src="https://encrypted-tbn0.gstatic.com/shopping?q=tbn:ANd9GcSedFKb3o0i-8j7iEd7f328Hf63MtEJAeVSxTSV0HcZuX4y4y8LJJsccriEJufhmmTYUnt-__MHrNta2WdnRmGZXQqeDQgse9t8D6ZcoTkuGevPwPEj6Zj5Xw" alt="Product 2">
                <h3>Gaming Laptop</h3>
                <p>High-performance laptops for immersive gaming experiences.</p>
                <a href="#">Learn More</a>
            </article>
            <article class="product-item">
                <img src="https://m.media-amazon.com/images/I/41OjI3aJguL._AC_.jpg" alt="Product 3">
                <h3>Ultra-HD Monitor</h3>
                <p>Get stunning visuals with our range of high-definition monitors.</p>
                <a href="#">Learn More</a>
            </article>
        </div>
    </section>

    <!-- Deals Section -->
    <section id="deals" class="deals">
        <h2>Exclusive Deals</h2>
        <div class="deal-grid">
            <div class="deal-item">
                <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcS6yPS07bnZTTztgAZfohiGHZQ27EQtTcXVcadKX42v91KyGyzcpBJIz5K10YROEf8uLjD-8IloyHS01GqbgIjTOJO3hkqSIyohPo4XWfh3Ze0gRr0JEXSWFQ" alt="Product 3">
                <h3>50% Off on Smartwatches</h3>
                <p>Limited time offer on selected models.</p>
            </div>
            <div class="deal-item">
                <img src="https://encrypted-tbn3.gstatic.com/shopping?q=tbn:ANd9GcSP7ZtzS1yGTyIInysMJEfySMtGD1QKoIEmJ5u_KWc-CWt_JW6PZgSdXq7fu-cOa5z2kkJLvqnMLMCto3nohxgNazRZiw3mA6F3Rayq1AhYQWKkNJ0N5p-PSw" alt="Product 3">
                <h3>Discounts on Laptops</h3>
                <p>Save up to $200 on our latest laptops.</p>
            </div>
            <div class="deal-item">
                <img src="https://m.media-amazon.com/images/I/61dBheO1mFL._AC_UL480_QL65_.jpg" alt="Product 3">
                <h3>Accessories Bundle</h3>
                <p>Buy more, save more on all accessories.</p>
            </div>
        </div>
    </section>

    <!-- Brands Section -->
    <section id="brands" class="brands">
        <h2>Featured Brands</h2>
        <div class="brands-grid">
            <div class="brand">
                <img src="https://www.apple.com/v/iphone/home/bx/images/overview/select/iphone_16pro__erw9alves2qa_xlarge.png" alt="Brand 1">
                <h3>Apple</h3>
            </div>
            <div class="brand">
                <img src="image.png" alt="Brand 2">
                <h3>Samsung</h3>
            </div>
            <div class="brand">
                <img src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcTY4j130BMJLGqQLKDmQgzy9DQbbNsKM0WUR_iEVJo1vIdXQsJN9WkgzyfS_yQrmj73tkr2ZmxEaTA8_wV5Sj7gthKwjvfokW6kE3wKQyr528ZVVGRVdWrRhA" alt="Brand 3">
                <h3>Dell</h3>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Have questions? Reach out to us:</p>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
        <p>&copy; 2024 Tech Hub | All Rights Reserved</p>
    </footer>
</body>
</html>
```
```
MAIN.CSS
/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    background-color: #f0f4f8;
    color: #333;
}

a {
    text-decoration: none;
    color: inherit;
}

ul {
    list-style: none;
}

/* Header Styles */
.header {
    display: flex;
    justify-content: space-between;
    padding: 20px 50px;
    background-color: #2d3e50;
    color: white;
}

.header .logo h1 {
    font-size: 28px;
}

.nav ul {
    display: flex;
    gap: 20px;
}

.nav li a {
    color: white;
    font-weight: bold;
    font-size: 16px;
}

.nav li a:hover {
    color: #0dbd8b;
}

/* Hero Section */
.hero {
    background-color: #0dbd8b;
    color: white;
    text-align: center;
    padding: 80px 20px;
}

.hero h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.hero button {
    padding: 12px 30px;
    background-color: white;
    color: #0dbd8b;
    font-weight: bold;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

.hero button:hover {
    background-color: #e0f7e9;
}

/* Products Section */
.products {
    padding: 50px 20px;
}

.products h2 {
    text-align: center;
    font-size: 36px;
    margin-bottom: 20px;
}

.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 500px; /* Increased gap for more space between images */
}

.product-item img {
    width: 100%;
    border-radius: 10px;
}

.product-item h3 {
    margin-top: 10px;
    font-size: 20px;
}

.product-item a {
    color: #0dbd8b;
    font-weight: bold;
}

/* Deals Section */
.deals {
    padding: 50px 20px;
    background-color: #f8f9fa;
}

.deal-grid {
    display: flex;
    justify-content: space-around;
}

.deal-item {
    text-align: center;
    padding: 20px;
    background-color: white;
    border-radius: 10px;
    width: 250px;
}

/* Brands Section */
.brands {
    padding: 50px 20px;
}

.brands-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    gap: 500px;
}

.brand img {
    width: 100%;
    border-radius: 10px;
}

/* Contact Section */
.contact {
    padding: 50px 20px;
    background-color: #0dbd8b;
    color: white;
    text-align: center;
}

.contact form {
    max-width: 500px;
    margin: 0 auto;
}

.contact input, .contact textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
    border: 1px solid #ddd;
}

.contact button {
    padding: 12px 30px;
    background-color: white;
    color: #0dbd8b;
    font-weight: bold;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

.contact button:hover {
    background-color: #e0f7e9;
}

/* Footer Section */
.footer {
    background-color: #2d3e50;
    color: white;
    text-align: center;
    padding: 20px;
}

```


## OUTPUT:
![Screenshot 2024-11-14 122336](https://github.com/user-attachments/assets/ffb3ab5c-4dd2-4e0e-8850-e8ff47c6f274)

![Screenshot 2024-11-14 122644](https://github.com/user-attachments/assets/5aecce1e-7b3c-4a09-b7e8-5299cbbd6b34)




## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
