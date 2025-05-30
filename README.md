<!DOCTYPE html>
<html lang="en">
<head>https://github.com/VelvetBoutiqueAndGifts/VelvetBoutiqueAndGifts/settings
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Velvet Boutique And Gifts</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Velvet Boutique And Gifts</h1>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Shop</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h2>Jewelry With Heart & Heritage</h2>
      <p>Handcrafted by Doña Rosa, inspired by tradition and love.</p>
      <a href="#" class="btn">Shop Now</a>
    </section>

    <section class="about">
      <h2>About Doña Rosa</h2>
      <p>Doña Rosa brings the soul of Mexico into every handmade piece. Velvet Boutique is her tribute to beauty, tradition, and family.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Velvet Boutique And Gifts. All rights reserved.</p>
  </footer>
</body>
</html>
/* Reset some default styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Georgia', serif;
  background-color: #fdf6f2;
  color: #3a1f1a;
  line-height: 1.6;
}

header {
  background-color: #6b0f1a;
  color: white;
  padding: 20px 0;
  text-align: center;
}

header h1 {
  font-size: 2rem;
  margin-bottom: 10px;
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  gap: 20px;
}

nav a {
  color: #fbe4d8;
  text-decoration: none;
  font-weight: bold;
}

nav a:hover {
  text-decoration: underline;
}

.hero {
  background: url('https://source.unsplash.com/1600x900/?jewelry,mexico') no-repeat center center/cover;
  color: white;
  padding: 100px 20px;
  text-align: center;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.btn {
  background-color: #b03060;
  color: white;
  padding: 10px 20px;
  text-decoration: none;
  font-weight: bold;
  border-radius: 5px;
}

.btn:hover {
  background-color: #8b1c4a;
}

.about {
  padding: 40px 20px;
  text-align: center;
}

.about h2 {
  margin-bottom: 10px;
  font-size: 2rem;
}

footer {
  background-color: #6b0f1a;
  color: white;
  text-align: center;
  padding: 10px 0;
}
