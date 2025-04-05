# my-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Christine Kabuga | Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <script defer src="script.js"></script>
</head>
<body>
  <!-- Header Section -->
  <header id="home">
    <div class="hero">
      <h1>Welcome to My Portfolio</h1>
      <p>I'm Christine Kabuga, a Software Developer and Graphic Designer.</p>
    </div>
  </header>

  <!-- About Section -->
  <section id="about">
    <h2>About Me</h2>
    <div class="about-content">
      <img src="https://images.pexels.com/photos/1181376/pexels-photo-1181376.jpeg" alt="Christine Profile" />
      <p>I am passionate about creating innovative software solutions and stunning design projects.</p>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services">
    <h2>Services</h2>
    <div class="service-cards">
      <div class="service-card">
        <h3>Software Development</h3>
        <p>Building reliable, scalable software to meet your business needs.</p>
      </div>
      <div class="service-card">
        <h3>Graphic Design</h3>
        <p>Creating beautiful, user-friendly designs that tell your story.</p>
      </div>
      <div class="service-card">
        <h3>Branding & Content Creation</h3>
        <p>Helping businesses develop strong identities through branding and content.</p>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-gallery">
      <img src="https://images.pexels.com/photos/1181376/pexels-photo-1181376.jpeg" alt="Portfolio 1">
      <img src="https://images.pexels.com/photos/1181376/pexels-photo-1181376.jpeg" alt="Portfolio 2">
      <img src="https://images.pexels.com/photos/1181376/pexels-photo-1181376.jpeg" alt="Portfolio 3">
    </div>
  </section>

  <!-- Client Remarks Section -->
  <section id="testimonials">
    <h2>Client Remarks</h2>
    <div class="testimonials-slider">
      <div class="testimonial">
        <p>"Christine's designs transformed our brand image. Highly recommend!"</p>
        <footer>— Client 1</footer>
      </div>
      <div class="testimonial">
        <p>"Her software solutions made our operations more efficient. Excellent work!"</p>
        <footer>— Client 2</footer>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:kabugachristine4@gmail.com">kabugachristine4@gmail.com</a></p>
    <p>Phone: <a href="tel:+254795215071">0795215071</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Christine Kabuga | All rights reserved</p>
  </footer>
</body>
</html>
***style.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #f4f4f9;
  color: #333;
}

header {
  background-image: url('https://images.pexels.com/photos/1181376/pexels-photo-1181376.jpeg');
  background-size: cover;
  text-align: center;
  padding: 60px 20px;
  color: white;
}

h1 {
  font-size: 3rem;
}

h2 {
  color: #444;
}

#about {
  padding: 40px 20px;
}

.about-content {
  display: flex;
  justify-content: space-between;
}

.about-content img {
  width: 200px;
  border-radius: 50%;
}

#services {
  background: #e1e1e1;
  padding: 40px 20px;
}

.service-cards {
  display: flex;
  justify-content: space-around;
}

.service-card {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  width: 30%;
}

#portfolio {
  padding: 40px 20px;
}

.portfolio-gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}

.portfolio-gallery img {
  width: 100%;
  border-radius: 8px;
}

#testimonials {
  background: #f4f4f9;
  padding: 40px 20px;
}

.testimonials-slider {
  display: flex;
  justify-content: space-around;
  gap: 20px;
}

.testimonial {
  background: white;
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  width: 45%;
}

#contact {
  padding: 40px 20px;
  text-align: center;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 20px;
}
