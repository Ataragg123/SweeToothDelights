# SweeToothDelights<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SweeToothDelights</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>SweeToothDelights</h1>
    <nav>
      <a href="#menu">Menu</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Baking Smiles Since 2025</h2>
    <p>Sweet treats made with love and a dash of magic.</p>
  </section>

  <section id="menu" class="menu">
    <h2>Menu</h2>
    <ul>
      <li><strong>Pastries:</strong> Macarons, Cupcakes, Eclairs</li>
      <li><strong>Cakes:</strong> Red Velvet, Fudge, Strawberry Shortcake</li>
      <li><strong>Drinks:</strong> Iced Coffee, Chai Latte, Hot Chocolate</li>
    </ul>
  </section>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>At SweeToothDelights, we’re all about sugar, smiles, and handmade happiness. Since 2025, we’ve crafted each treat with a sprinkle of love and a whole lot of flavor!</p>
  </section>

  <section id="contact" class="contact">
    <h2>Contact</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 SweeToothDelights</p>
  </footer>
</body>
</html>body {
  font-family: 'Comic Sans MS', cursive;
  margin: 0;
  background: #fffafc;
  color: #4a2c2a;
}

header {
  background: #ffe0e9;
  padding: 1em;
  text-align: center;
}

nav a {
  margin: 0 15px;
  color: #d76f85;
  text-decoration: none;
}

.hero {
  background: #fff0f5;
  padding: 3em 1em;
  text-align: center;
}

.menu, .about, .contact {
  padding: 2em;
}

form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
  margin: auto;
}

form input, form textarea {
  margin: 10px 0;
  padding: 10px;
}

button {
  background: #d76f85;
  color: white;
  padding: 10px;
  border: none;
  border-radius: 5px;
}

footer {
  background: #ffe0e9;
  text-align: center;
  padding: 1em;
}