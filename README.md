<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Movera Photobooth</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      color: #333;
      line-height: 1.6;
    }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
      background: #222;
      color: #fff;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header .logo-img {
      height: 60px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
    }

    nav a:hover {
      color: #ff4081;
    }

    /* Hero */
    .hero {
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(to right, #ff4081, #ff6f61);
      color: white;
    }

    .hero h1 span {
      color: #fff;
      font-style: italic;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 25px;
      background: #fff;
      color: #ff4081;
      font-weight: bold;
      border-radius: 5px;
      text-decoration: none;
    }

    .btn:hover {
      background: #222;
      color: #fff;
    }

    /* Sections */
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }

    h2 {
      margin-bottom: 20px;
      color: #ff4081;
    }

    /* Packages */
    .package-list {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .package {
      border: 1px solid #eee;
      padding: 20px;
      border-radius: 8px;
      background: #fff;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      flex: 1 1 250px;
    }

    .package h3 {
      color: #ff4081;
      margin-bottom: 10px;
    }

    .package p {
      margin-bottom: 8px;
    }

    /* Gallery */
    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 10px;
    }

    .gallery-grid img {
      width: 100%;
      border-radius: 8px;
    }

    /* Contact */
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin: 20px 0;
    }

    form input, form textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    form button {
      background: #ff4081;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 5px;
      cursor: pointer;
    }

    form button:hover {
      background: #ff6f61;
    }

    #contact p {
      margin: 10px 0;
      font-size: 1.1em;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <img src="images/movera-logo.png" alt="Movera Logo" class="logo-img">
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#gallery">Gallery</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Make Your Event Unforgettable with <span>Movera</span></h1>
    <p>Modern photobooth fun, unlimited memories.</p>
    <a href="#contact" class="btn">Book Now</a>
  </section>

  <!-- About -->
  <section id="about">
    <h2>About Us</h2>
    <p>
      Movera Photobooth brings energy and excitement to every event —
      from weddings and birthdays to corporate celebrations. With instant
      prints, unlimited digital sharing, and inflatable booth options, we make
      every moment worth remembering.
    </p>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Our Packages</h2>
    <div class="package-list">
      <div class="package">
        <h3>1st Package</h3>
        <p>$100 per hour</p>
        <p>Perfect for small events</p>
      </div>
      <div class="package">
        <h3>2nd Package</h3>
        <p>$150 per hour</p>
        <p>Includes unlimited printing<br>(3 hr minimum)</p>
      </div>
      <div class="package">
        <h3>Inflatable Photobooth</h3>
        <p>Only $200 extra</p>
        <p>Add the wow factor to your event</p>
      </div>
    </div>
  </section>

  <!-- Gallery -->
  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery-grid">
      <img src="images/sample1.jpg" alt="Guests using photobooth" />
      <img src="images/sample2.jpg" alt="Inflatable booth setup" />
      <img src="images/sample3.jpg" alt="Event photo" />
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>📧 Email: <a href="mailto:info@movera.com">info@movera.com</a></p>
    <p>📞 Phone: (224) 413-4829 | (551) 303-9257</p>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Movera Photobooth. All rights reserved.</p>
  </footer>
</body>
</html>
