<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Evan Ketchum — Marketing Hub</title>

  <!-- ✅ Link to your CSS -->
  <link rel="stylesheet" href="css/style.css" />

  <!-- ✅ Open Graph Tags (for social media preview) -->
  <meta property="og:title" content="Evan Ketchum — Affiliate Marketer & Creator" />
  <meta property="og:description" content="Affiliate marketing • Art • Digital creativity from Tacoma, WA." />
  <meta property="og:image" content="images/og-image.png" />
  <meta property="og:type" content="website" />
</head>

<body>
  <!-- Navigation -->
  <header>
    <h1>Evan Ketchum</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="hero">
    <img src="images/hero.png" alt="Evan Ketchum Marketing" />
    <h2>Affiliate Marketing • Art • Digital Creativity</h2>
    <p>Helping brands and creators grow through digital innovation and passion.</p>
    <div class="cta-buttons">
      <a href="#services" class="btn">View Services</a>
      <a href="#contact" class="btn ghost">Contact</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Evan</h2>
    <p>Hey! I’m Evan from Tacoma, WA — an affiliate marketer, content creator, and artist who loves helping brands connect with audiences. My goal is to combine creativity with opportunity to help businesses grow online and offline.</p>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Services</h2>
    <div class="cards-container">
      <div class="card">
        <img src="images/product1.jpg" alt="Affiliate Marketing" />
        <h3>Affiliate Marketing</h3>
        <p>Partner with top brands and earn passive income promoting the right products.</p>
        <a href="#" class="btn">Learn More</a>
      </div>

      <div class="card">
        <img src="images/product2.jpg" alt="Content Creation" />
        <h3>Content Creation</h3>
        <p>Custom campaigns and creative storytelling to connect with your ideal audience.</p>
        <a href="#" class="btn">See Examples</a>
      </div>

      <div class="card">
        <img src="images/product3.jpg" alt="Local Services" />
        <h3>Local Promotions</h3>
        <p>Helping Tacoma businesses grow through events, digital listings, and marketing.</p>
        <a href="#" class="btn">Contact Me</a>
      </div>
    </div>
  </section>

  <!-- Newsletter Section -->
  <section id="newsletter">
    <h2>Join My Newsletter</h2>
    <form id="newsletter-form">
      <input type="text" id="name" placeholder="Your Name" required />
      <input type="email" id="email" placeholder="Your Email" required />
      <button type="submit" class="btn">Subscribe</button>
    </form>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Have questions or collaboration ideas? Let’s connect.</p>
    <p><a href="mailto:youremail@example.com" class="btn">Email Me</a></p>
  </section>

  <footer>
    <p>© 2025 Evan Ketchum | Tacoma, WA</p>
  </footer>

  <!-- ✅ Link to your JavaScript -->
  <script src="js/main.js"></script>
</body>
</html>
/* === Global Styles === */
body {
  margin: 0;
  font-family: 'Poppins', Arial, sans-serif;
  background: #0f1724;
  color: #e6eef8;
  scroll-behavior: smooth;
}

/* === Header & Navigation === */
header {
  text-align: center;
  padding: 20px;
  background: #111a2c;
}
header h1 {
  margin: 0;
  font-size: 28px;
  color: #7dd3fc;
}
nav {
  margin-top: 10px;
}
nav a {
  color: #e6eef8;
  text-decoration: none;
  margin: 0 10px;
  font-weight: 500;
}
nav a:hover {
  color: #7dd3fc;
}

/* === Hero Section === */
#hero {
  text-align: center;
  padding: 50px 20px;
}
#hero img {
  width: 160px;
  border-radius: 50%;
  margin-bottom: 15px;
  border: 3px solid rgba(125,211,252,0.3);
}
#hero h2 {
  color: #7dd3fc;
  margin-bottom: 10px;
}
#hero p {
  max-width: 600px;
  margin: 0 auto 20px;
  color: #94a3b8;
}
.cta-buttons {
  display: flex;
  justify-content: center;
  gap: 12px;
}
.btn {
  background-color: #7dd3fc;
  color: #042031;
  padding: 10px 20px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.3s;
}
.btn:hover {
  background-color: #5cb8e3;
}
.btn.ghost {
  background: transparent;
  border: 1px solid #7dd3fc;
  color: #7dd3fc;
}
.btn.ghost:hover {
  background-color: #7dd3fc;
  color: #042031;
}

/* === Section Layouts === */
section {
  padding: 40px 20px;
  text-align: center;
}
h2 {
  color: #7dd3fc;
}

/* === Cards (Services) === */
.cards-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 20px;
}
.card {
  background: #111a2c;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 4px 15px rgba(2,6,23,0.6);
}
.card img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 10px;
}
.card h3 {
  color: #7dd3fc;
  margin-bottom: 10px;
}

/* === Newsletter === */
#newsletter form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
  margin: 0 auto;
}
#newsletter input {
  padding: 10px;
  margin: 8px 0;
  border-radius: 6px;
  border: none;
}
#newsletter button {
  padding: 10px;
  background-color: #7dd3fc;
  color: #042031;
  font-weight: bold;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  transition: 0.3s;
}
#newsletter button:hover {
  background-color: #5cb8e3;
}

/* === Footer === */
footer {
  text-align: center;
  padding: 15px;
  background: #111a2c;
  color: #94a3b8;
  font-size: 14px;
}
// === Smooth Scroll for nav links ===
document.querySelectorAll('nav a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function (e) {
    e.preventDefault();
    document.querySelector(this.getAttribute('href')).scrollIntoView({
      behavior: 'smooth'
    });
  });
});

// === Newsletter popup message ===
const form = document.getElementById('newsletter-form');
form.addEventListener('submit', (event) => {
  event.preventDefault();
  const name = document.getElementById('name').value;
  alert(`Thanks for subscribing${name ? ', ' + name : ''}!`);