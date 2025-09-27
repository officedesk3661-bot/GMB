<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>GMB Entertainment Group</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #0e0e0e;
      color: #fff;
      line-height: 1.6;
    }

    header {
      background: #111;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 { font-size: 1.5rem; color: #f8d23c; }

    nav a {
      color: #fff;
      margin-left: 1.2rem;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover { color: #f8d23c; }

    .hero {
      background: url('https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4') center/cover no-repeat;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }

    .hero h2 {
      font-size: 3rem;
      background: rgba(0,0,0,0.6);
      padding: 1rem 2rem;
      border-radius: 8px;
    }

    section {
      padding: 4rem 2rem;
      max-width: 1100px;
      margin: auto;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      color: #f8d23c;
      text-align: center;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .service {
      background: #1c1c1c;
      padding: 2rem;
      border-radius: 10px;
      text-align: center;
      transition: transform 0.3s ease;
    }

    .service:hover {
      transform: translateY(-5px);
    }

    footer {
      background: #111;
      text-align: center;
      padding: 2rem;
      margin-top: 2rem;
      font-size: 0.9rem;
    }

    footer a {
      color: #f8d23c;
      margin: 0 0.5rem;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>GMB Entertainment Group</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero -->
  <div class="hero">
    <h2>Shaping the Future of Music & Entertainment</h2>
  </div>

  <!-- About -->
  <section id="about">
    <h2>About Us</h2>
    <p>
      GMB Entertainment Group is a full-scale entertainment company specializing in 
      record label operations, live event curation, artist management, A&R services, 
      and music analytics. We empower artists and deliver unforgettable music 
      experiences to global audiences.
    </p>
  </section>

  <!-- Services -->
  <section id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="service">
        <h3>🎵 GMB Records</h3>
        <p>We sign, produce, and distribute groundbreaking music while supporting our artists' creative visions.</p>
      </div>
      <div class="service">
        <h3>🎤 GMB Live</h3>
        <p>We curate and promote concerts, festivals, and tours that connect artists with their fans worldwide.</p>
      </div>
      <div class="service">
        <h3>👥 GMB Management</h3>
        <p>We guide artists' careers through branding, PR, bookings, and long-term strategy.</p>
      </div>
      <div class="service">
        <h3>🔍 GMB A&amp;R</h3>
        <p>Our talent scouts discover and develop the next generation of music superstars.</p>
      </div>
      <div class="service">
        <h3>📊 GMB Music Analytics</h3>
        <p>We provide data-driven insights that empower artists and labels to succeed in a competitive market.</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: <a href="mailto:info@gmbentertainment.com">info@gmbentertainment.com</a></p>
    <p>Follow us on:
      <a href="#">Instagram</a> |
      <a href="#">YouTube</a> |
      <a href="#">Spotify</a>
    </p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 GMB Entertainment Group. All Rights Reserved.</p>
  </footer>
</body>
</html>
