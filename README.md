# Portfolio-project
A portfolio project showing web design skills and services.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Danny Designs</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body style="background-color:soft white;">

  <!-- Navigation Bar -->
  <header>
    <nav>
      <div class="logo">DANNY DESIGNS</div>
      <ul class="nav-links">
        <li><a href="#">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Reliable and exquisite UI/UX designs.</h1>
    <p>We design projects according to client wants and make your ideas come to life.</p>
    <a href="#contact" class="btn">Get a Free Quote</a>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <div class="about-image"></div>
    <div class="about-text">
      <h2>About Danny Designs</h2>
      <p>Having experience with design tools like Figma, Canva, Adobe Illustrator and so on we are efficient in creating all client desires and still with continous learning.</p>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="services">
    <h2>Our Services</h2>
    <div class="service-cards">
      <div class="card">
        <h3>Figma Designs</h3>
        <p>We can provide landing pages,UI apps and webpages.</p>
      </div>
      <div class="card">
        <h3>Canva Designs</h3>
        <p>Flyers ,Instagram Reels ,Business Cards and Posters.</p>
      </div>
      <div class="card">
        <h3>Prototypes</h3>
        <p>Concerning webpages and sites and even App UI, prototypes are available.</p>
      </div>
    </div>
  </section>

<!-- Projects Section -->
<section id="projects" class="projects">
  <h2>My Projects</h2>
  <div class="project-cards">
    <div class="project">
      <img src="Portfolio.png " alt="Project 1">
      <h3>Modern Portfolio Website</h3>
      <p>A responsive portfolio built with HTML, CSS, and JavaScript.</p>
      <a href="https://yourprojectlink.com" target="_blank" class="btn">View Project</a>
    </div>

    <div class="project">
      <img src="nova space-landing page.png" alt="Project 2">
      <h3>Landing Page Design</h3>
      <p>Clean, minimal landing page made with Figma and Canva.</p>
      <a href="https://www.figma.com/design/YNqvKu7YWX9sWqzfXjyFXr/Nova-Space---Landing-Page?t=lOK3lWKeP7Fjw1Je-1" target="_blank" class="btn">View Design</a>
    </div>

    <div class="project">
      <img src="e-commerce product page.png" alt="Project 3">
      <h3>E-commerce UI Prototype</h3>
      <p>App UI prototype created using Adobe Illustrator and Figma.</p>
      <a href="https://www.figma.com/design/D9U5XcGHRllhZwRWer05Ie/E-Commerce-Product-Page?t=lOK3lWKeP7Fjw1Je-1" target="_blank" class="btn">View Prototype</a>
    </div>
  </div>
</section>


  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact Us</h2>
    <p>Email: danielawakhu54@gmail.com</p>
    <p>Phone: +254 115956300</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Danny Designs. All rights reserved.</p>
  </footer>

<script>
alert("Welcome to our website!");
</script>
<script>
  // Fade-in effect on scroll
  const sections = document.querySelectorAll("section");

  const revealSection = () => {
    const triggerBottom = window.innerHeight * 0.85;
    sections.forEach(section => {
      const boxTop = section.getBoundingClientRect().top;
      if (boxTop < triggerBottom) {
        section.classList.add("visible");
      }
    });
  };

  window.addEventListener("scroll", revealSection);
  revealSection(); // run on load
</script>


</body>
</html>
