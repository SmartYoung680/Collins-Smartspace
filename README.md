<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Collins Smartspace | Smart. Modern. Yours.</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #111111;
      color: #ffffff;
      line-height: 1.6;
    }

    header {
      padding: 25px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #333;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #d4af37;
    }

    nav a {
      color: #ffffff;
      text-decoration: none;
      margin-left: 25px;
      font-size: 15px;
    }

    nav a:hover {
      color: #d4af37;
    }

    .hero {
      min-height: 85vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 50px 8%;
    }

    .hero-content {
      max-width: 850px;
    }

    .hero h1 {
      font-size: clamp(45px, 8vw, 80px);
      line-height: 1.05;
      margin-bottom: 25px;
    }

    .hero h1 span {
      color: #d4af37;
    }

    .hero p {
      color: #cccccc;
      font-size: 19px;
      max-width: 650px;
      margin: 0 auto 30px;
    }

    .quote {
      font-size: 23px !important;
      font-style: italic;
      color: #d4af37 !important;
    }

    .btn {
      display: inline-block;
      padding: 15px 32px;
      background: #d4af37;
      color: #111111;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      margin-top: 10px;
    }

    .btn:hover {
      background: #ffffff;
    }

    .about {
      padding: 80px 8%;
      background: #181818;
      text-align: center;
    }

    .about h2 {
      font-size: 40px;
      margin-bottom: 20px;
      color: #d4af37;
    }

    .about p {
      max-width: 700px;
      margin: auto;
      color: #cccccc;
      font-size: 17px;
    }

    .services {
      padding: 80px 8%;
      text-align: center;
    }

    .services h2 {
      font-size: 40px;
      margin-bottom: 40px;
    }

    .cards {
      display: flex;
      justify-content: center;
      gap: 25px;
      flex-wrap: wrap;
    }

    .card {
      width: 280px;
      padding: 30px;
      background: #1b1b1b;
      border: 1px solid #333;
      border-radius: 10px;
    }

    .card h3 {
      color: #d4af37;
      margin-bottom: 15px;
    }

    .card p {
      color: #bbbbbb;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: #0b0b0b;
      color: #888;
    }

    @media (max-width: 700px) {
      nav {
        display: none;
      }

      .hero {
        min-height: 80vh;
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <div class="logo">COLLINS SMARTSPACE</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>


  <!-- HERO SECTION -->
  <section class="hero" id="home">
    <div class="hero-content">

      <h1>
        Welcome to <span>Collins Smartspace</span>
      </h1>

      <p class="quote">
        “Smart ideas. Modern style. Meaningful experiences.”
      </p>

      <p>
        Collins Smartspace is a modern digital brand focused on
        creativity, technology, fashion, lifestyle, and smart
        solutions designed to connect people with what matters.
      </p>

      <a href="#services" class="btn">
        Explore Smartspace
      </a>

    </div>
  </section>


  <!-- ABOUT -->
  <section class="about" id="about">
    <h2>About Collins Smartspace</h2>

    <p>
      We believe the future belongs to brands that combine
      creativity, technology, quality, and purpose.
      Collins Smartspace is built to create a space where
      modern ideas become real experiences.
    </p>
  </section>


  <!-- SERVICES -->
  <section class="services" id="services">

    <h2>What We Do</h2>

    <div class="cards">

      <div class="card">
        <h3>Digital Solutions</h3>
        <p>
          Modern websites, digital branding, and creative
          solutions for individuals and businesses.
        </p>
      </div>

      <div class="card">
        <h3>Fashion & Style</h3>
        <p>
          Discover modern fashion, accessories, watches,
          and lifestyle products.
        </p>
      </div>

      <div class="card">
        <h3>Creative Design</h3>
        <p>
          Creative visual concepts designed to help brands
          stand out and make an impression.
        </p>
      </div>

    </div>
  </section>


  <!-- CONTACT -->
  <section class="about" id="contact">

    <h2>Let's Connect</h2>

    <p>
      Have an idea, project, or business you want to bring
      to life? Collins Smartspace is ready to connect with you.
    </p>

    <br>

    <a href="mailto:your@email.com" class="btn">
      Contact Us
    </a>

  </section>


  <!-- FOOTER -->
  <footer>
    © 2026 Collins Smartspace. All Rights Reserved.
  </footer>

</body>
</html>
