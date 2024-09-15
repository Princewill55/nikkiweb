<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nikki&Gov Essentials</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <img src="logo.png" alt="Nikki&Gov Essentials Logo" class="logo">
    <nav>
      <ul>
        <li><a href="#about">About Us</a></li>
        <li><a href="#products">Products</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="about">
      <h1>About Us</h1>
      <p>Welcome to Nikki&Gov Essentials, your go-to for premium candles and wax products.</p>
    </section>

    <section id="products">
      <h2>Our Products</h2>
      <div class="product-grid">
        <div class="product">
          <img src="candle1.jpg" alt="Candle Product 1">
          <h3>Scented Candle</h3>
        </div>
        <!-- Add more products here -->
      </div>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required>

        <button type="submit">Submit</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Nikki&Gov Essentials</p>
  </footer>
</body>
</html>
