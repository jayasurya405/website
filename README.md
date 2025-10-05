# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CR7-cafe | Home</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">CR7-cafe</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="index.html" class="active">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h2>Welcome to CR7-cafe</h2>
      <p>For the Love of Football & Flavor.</p>
      <a href="menu.html" class="btn">Explore Menu</a>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 CR7-cafe. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>

menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CR7-cafe | Menu</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">CR7-cafe</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html" class="active">Menu</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="menu-section">
    <div class="container">
      <h2>Our Popular Dishes</h2>
      <div class="menu-items">
        <div class="menu-item">
          <img src="a.png" alt="Dish 1">
          <h3>🥘 Bacalhau Power Bowl</h3>
          <p>Inspired by Ronaldo’s favorite Bacalhau à Brás — a café twist with golden potato crisps and fresh greens.</p>
        </div>
        <div class="menu-item">
          <img src="b.png" alt="Dish 2">
          <h3>🐟 Champion’s Grilled Fish Platter</h3>
          <p>Ronaldo-style grilled sea bass with lemon herb dressing and quinoa.</p>
        </div>
        <div class="menu-item">
          <img src="c.png" alt="Dish 3">
          <h3>🥗 GOAT’s Chicken Salad</h3>
          <p>Grilled chicken breast tossed with crisp veggies and olive oil vinaigrette.</p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 CR7-cafe. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>

about.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CR7-cafe | About</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">CR7-cafe</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="about.html" class="active">About</a></li>
          <li><a href="contact.html">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="about-section">
    <div class="container">
      <h2>About Us</h2>
      <p>Welcome to CR7 Café, where football passion meets flavorful perfection!  
      Inspired by the legendary Cristiano Ronaldo, our café is more than just a place to eat — it’s a lifestyle.  
      Our goal is to serve nutritious, tasty meals that match the energy and dedication of the GOAT himself!</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 CR7-cafe. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>CR7-cafe | Contact</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <div class="container">
      <h1 class="logo">CR7-cafe</h1>
      <nav>
        <ul class="nav-links">
          <li><a href="index.html">Home</a></li>
          <li><a href="menu.html">Menu</a></li>
          <li><a href="about.html">About</a></li>
          <li><a href="contact.html" class="active">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="contact-section">
    <div class="container">
      <h2>Contact Us</h2>
      <p>Email: CR7-cafe@ucl.com</p>
      <p>Phone: (123) 456-7890</p>
      <p>Address: 123 Flavor Street, Foodville</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 CR7-cafe. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>

styles.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: linear-gradient(to right, #f4f1f3, #e994c7);
  color: #333;
}

header {
  background: linear-gradient(90deg, #430121d1, #570234);
  padding: 15px;
  text-align: center;
  color: white;
}

header h1 {
  margin: 0;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 0 15px;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  text-align: center;
  padding: 50px;
  background: linear-gradient(120deg, #d3ebef, #f59ce7);
  color: white;
}

.dishes {
  padding: 20px;
  text-align: center;
}

.dish-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 15px;
  margin-top: 20px;
}

.dish-grid img {
  width: 100%;
  border-radius: 10px;
  box-shadow: 0px 4px 6px rgba(0,0,0,0.2);
}

.menu ul, .dashboard ul {
  list-style: none;
  padding: 0;
}

.menu li, .dashboard li {
  background: #fff;
  margin: 8px;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.contact {
  text-align: center;
  padding: 40px;
  background: linear-gradient(135deg, #c3cfe2, #e2ebf0);
  border-radius: 10px;
  margin: 30px;
}

.login, .dashboard {
  width: 60%;
  margin: auto;
  padding: 20px;
  background: #ffffffdd;
  border-radius: 12px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.2);
}

form input, form button {
  display: block;
  width: 100%;
  padding: 12px;
  margin: 10px 0;
  border-radius: 8px;
  border: 1px solid #ccc;
}

form button {
  background: #66a6ff;
  color: white;
  border: none;
  font-weight: bold;
}

form button:hover {
  background: #558de8;
}

footer {
  text-align: center;
  padding: 15px;
  margin-top: 20px;
  background: #66a6ff;
  color:white;
}

```
# OUTPUT:
![alt text](<Screenshot 2025-10-05 183720.png>)
![alt text](<Screenshot 2025-10-05 183736.png>)
![alt text](<Screenshot 2025-10-05 183752.png>)
![alt text](<Screenshot 2025-10-05 183811.png>)
![alt text](<Screenshot 2025-10-05 183819.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
