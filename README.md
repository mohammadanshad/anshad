<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Anshad | Portfolio</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; background: #000; color: #fff; }
    header { background: #111; padding: 20px; text-align: center; }
    h1 { margin: 0; font-size: 2.5em; color: gold; }
    nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
    section { padding: 40px 20px; max-width: 900px; margin: auto; }
    h2 { color: gold; }
    .skills, .contact-info { display: flex; flex-wrap: wrap; gap: 10px; }
    .skills div, .service, .portfolio-item { background: #222; padding: 10px 15px; border-radius: 5px; }
    .portfolio-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; }
    footer { text-align: center; padding: 20px; background: #111; color: #aaa; }
    .logo { max-height: 80px; margin-bottom: 10px; }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Anshad Logo" class="logo" />
    <h1>Anshad</h1>
    <p>Graphic Designer & Civil Engineer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I am a creative and technically skilled Graphic Designer and Civil Engineer. With expertise in both design software and technical planning tools, I bridge the gap between creativity and structure.</p>
    <div class="skills">
      <div>Photoshop</div>
      <div>Illustrator</div>
      <div>InDesign</div>
      <div>CorelDRAW</div>
      <div>Excel</div>
      <div>Word</div>
      <div>PowerPoint</div>
      <div>AutoCAD</div>
      <div>MS Project</div>
    </div>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-grid">
      <div class="portfolio-item">Logo Design</div>
      <div class="portfolio-item">2D/3D Drawings</div>
      <div class="portfolio-item">Brochure & Flyer</div>
      <div class="portfolio-item">AutoCAD Projects</div>
    </div>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="skills">
      <div class="service">Logo & Branding</div>
      <div class="service">Business Cards</div>
      <div class="service">2D/3D Planning</div>
      <div class="service">MS Project Planning</div>
      <div class="service">Excel Dashboards</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:anshadachi68@gmail.com" style="color: gold;">anshadachi68@gmail.com</a></p>
    <p>Instagram, Behance, LinkedIn - Coming Soon</p>
  </section>

  <footer>
    &copy; 2025 Anshad. All Rights Reserved.
  </footer>
</body>
</html>
