# sarilogam.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sari Logam</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body { font-family: 'Roboto', sans-serif; background-color: #1e1e1e; color: white; }
    header { background-color: #ff4500; padding: 20px; text-align: center; }
    header h1 { font-size: 2.5em; }
    nav { display: flex; justify-content: center; background: #333; padding: 10px; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    nav a:hover { text-decoration: underline; }
    .hero { padding: 60px 20px; text-align: center; background: url('https://images.unsplash.com/photo-1577968899251-90cdd0bb549e') no-repeat center/cover; color: #fff; }
    .hero h2 { font-size: 2.5em; margin-bottom: 20px; }
    .hero p { font-size: 1.2em; }
    section { padding: 40px 20px; max-width: 1000px; margin: auto; }
    .features { display: flex; flex-wrap: wrap; justify-content: space-around; }
    .feature { width: 30%; background: #2c2c2c; margin: 10px; padding: 20px; border-radius: 10px; }
    .feature h3 { color: #ff4500; }
    footer { background: #111; color: #aaa; padding: 20px; text-align: center; }
    @media (max-width: 768px) {
      .feature { width: 100%; }
    }
  </style>
</head>
<body>
  <header>
    <h1>SARI LOGAM</h1>
    <p>Custom Steel Solutions • Welding • Fabrication</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    <h2>Stronger. Smarter. Steel.</h2>
    <p>We deliver precision-cut steel and custom metalwork for every need.</p>
  </div>

  <section id="about">
    <h2>About Sari Logam</h2>
    <p>
      Founded with a vision to modernize traditional steel work, Sari Logam offers premium-grade steel materials, cutting, welding, and custom metal fabrication services. Serving contractors, DIY builders, and businesses in need of fast, reliable solutions.
    </p>
  </section>

  <section id="services">
    <h2>Our Services</h2>
    <div class="features">
      <div class="feature">
        <h3>Steel Materials</h3>
        <p>We stock hollow, plat, pipa, siku, wiremesh, and more for construction and furniture builds.</p>
      </div>
      <div class="feature">
        <h3>Cutting & Welding</h3>
        <p>Custom cuts and welding for any project, from home canopies to industrial frames.</p>
      </div>
      <div class="feature">
        <h3>Custom Fabrication</h3>
        <p>Need a steel rack, fence, or table frame? We fabricate based on your design or concept.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📍 Visit us at: Jl. [Your Address], [Your City]</p>
    <p>📞 Call or WhatsApp: 08xx-xxxx-xxxx</p>
    <p>📧 Email: info@sarilogam.id</p>
  </section>

  <footer>
    &copy; 2025 Sari Logam. All rights reserved.
  </footer>
</body>
</html>

