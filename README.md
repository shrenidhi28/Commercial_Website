# Ex02 Commercial Website
## Date: 25-05-26

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
<!DOCTYPE html>
<html>
<head>
  <title>Commercial Website</title>

  <style>
    body {
      margin: 0;
      font-family: Arial;
    }

    .navbar {
      background: black;
      color: white;
      display: flex;
      justify-content: space-between;
      padding: 15px;
    }

    .menu {
      display: flex;
      gap: 20px;
    }

    .hero {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 50px;
      background: lightgray;
    }

    .products {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 30px;
    }

    .card {
      border: 1px solid black;
      padding: 20px;
      width: 150px;
      text-align: center;
    }

    .footer {
      background: black;
      color: white;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>

<body>

  <div class="navbar">
    <h2>MyShop</h2>

    <div class="menu">
      <p>Home</p>
      <p>Products</p>
      <p>Contact</p>
    </div>
  </div>

  <div class="hero">
    <div>
      <h1>Welcome to MyShop</h1>
      <p>Best products at low prices</p>
      <button>Shop Now</button>
    </div>

    <img src="https://picsum.photos/300/200" />
  </div>

  <div class="products">

    <div class="card">
      <h3>Shoes</h3>
      <p>$50</p>
    </div>

    <div class="card">
      <h3>Watch</h3>
      <p>$80</p>
    </div>

    <div class="card">
      <h3>Bag</h3>
      <p>$40</p>
    </div>

  </div>

  <div class="footer">
    <p>© 2026 MyShop</p>
  </div>

</body>
</html>

```

## OUTPUT
<img width="1910" height="942" alt="image" src="https://github.com/user-attachments/assets/7932aab1-d55e-496f-8032-6a86ed02f911" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
