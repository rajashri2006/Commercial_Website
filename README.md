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

index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navbar -->
    <header class="navbar">
        <div class="logo">MyShop</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Products</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Welcome to MyShop</h1>
        <p>Best products at affordable prices</p>
    </section>

    <!-- Product Section -->
    <section class="products">
        <div class="card">Product 1</div>
        <div class="card">Product 2</div>
        <div class="card">Product 3</div>
        <div class="card">Product 4</div>
    </section>

    <!-- Footer -->
    <footer>
        <p>Name: RAJASHRI I | Reg No: 212224040261</p>
    </footer>

</body>
</html>
```
style.css
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}


.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: #333;
    color: white;
    padding: 15px;
}

.navbar nav a {
    color: white;
    margin-left: 15px;
    text-decoration: none;
}


.hero {
    text-align: center;
    padding: 50px;
    background: #f4f4f4;
}


.products {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 20px;
}

.card {
    background: #ddd;
    margin: 10px;
    padding: 30px;
    width: 200px;
    text-align: center;
    border-radius: 10px;
}


footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
```

## OUTPUT

![image-1](<Screenshot 2026-05-06 142821.png>)

![image-2](<Screenshot 2026-05-06 142808.png>)

![image-3](<Screenshot 2026-05-06 142758.png>)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
