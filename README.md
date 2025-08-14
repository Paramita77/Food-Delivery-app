# Food-Delivery-app
using html,css,javascript
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Food App</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #fff8f0;
      color: #333;
    }

    header {
      background: #ff5722;
      color: white;
      padding: 1rem;
      text-align: center;
    }

    .banner img {
      width: 100%;
      height: auto;
      display: block;
    }

    .about-section {
      padding: 2rem;
      background: #fff;
      text-align: center;
    }

    .aboutcontent {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1rem;
    }

    .aboutcontent img {
      max-width: 300px;
      border-radius: 10px;
    }

    .menu-section {
      padding: 2rem;
      background: #fff4e3;
    }

    .menu-section h2 {
      text-align: center;
      margin-bottom: 1.5rem;
    }

    .menu-item {
      display: inline-block;
      width: 200px;
      margin: 1rem;
      text-align: center;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      padding: 1rem;
    }

    .menu-img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 8px;
    }

    button {
      background: #ff5722;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
      transition: background 0.3s;
    }

    button:hover {
      background: #e64a19;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #333;
      color: white;
      margin-top: 2rem;
    }

    footer a {
      color: white;
      margin: 0 0.5rem;
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <header>
    <h1>Tasty Bite</h1>
  </header>

  <section class="banner">
    <img src="IMAGE GREAT/banner.jpg" alt="Tasty bite image"/>
  </section>

  <section class="about-section">
    <h2>About Us</h2>
    <div class="aboutcontent">
      <p>We are here to serve you the most delicious food.</p>
      <img src="IMAGE GREAT/noodle.jpg" class="img-hold" alt="Noodles">
    </div>
  </section>

  <section class="menu-section">
    <h2>Our Menu</h2>
    <div class="menu-item">
      <img src="IMAGE GREAT/margarita pizza.jpg" class="menu-img" alt="Margarita Pizza">
      <span>Margarita Pizza</span>
      <button onclick="orderNow('Margarita Pizza')">Order Now</button>
    </div>
    <div class="menu-item">
      <img src="IMAGE GREAT/burger.jpg" class="menu-img" alt="Burger">
      <span>Burger</span>
      <button onclick="orderNow('Burger')">Order Now</button>
    </div>
    <div class="menu-item">
      <img src="IMAGE GREAT/lemon chiken.jpg" class="menu-img" alt="Lemon Chicken">
      <span>Lemon Chicken</span>
      <button onclick="orderNow('Lemon Chicken')">Order Now</button>
    </div>
    <div class="menu-item">
      <img src="IMAGE GREAT/gulab jamun.jpeg" class="menu-img" alt="Gulab Jamun">
      <span>Gulab Jamun</span>
      <button onclick="orderNow('Gulab Jamun')">Order Now</button>
    </div>
    <div class="menu-item">
      <img src="IMAGE GREAT/maharaja thali.jpg" class="menu-img" alt="Maharaja Thali">
      <span>Maharaja Thali</span>
      <button onclick="orderNow('Maharaja Thali')">Order Now</button>
    </div>
  </section>

  <footer>
    <p>
      <a href="#">Contact</a> |
      <a href="#">Privacy</a> |
      <a href="#">Feedback</a>
    </p>
    <p>@2023, Tasty Bite</p>
  </footer>

  <script>
    function orderNow(itemName) {
      alert("Thank you for ordering: " + itemName + "!");
    }
  </script>

</body>
</html>
