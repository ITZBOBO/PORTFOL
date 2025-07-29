<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AGBOOLA ENOCH ADURAGBEMI | Portfolio</title>
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    :root {
      --primary-color: #0f0c29;
      --accent-color: #00fff7;
      --background-color: #0f0c29;
      --text-color: #e0f7fa;
      --card-color: #1a1a40;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: var(--background-color);
      color: var(--text-color);
    }

    header {
      background: linear-gradient(90deg, #0f0c29, #302b63, #24243e);
      color: white;
      padding: 2rem 1rem 1rem;
      text-align: center;
    }

    nav {
      background-color: var(--accent-color);
      padding: 0.5rem 1rem;
      text-align: center;
    }

    nav a {
      margin: 0 1rem;
      color: #0f0c29;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffffff;
    }

    .section {
      padding: 3rem 1rem;
    }

    .container {
      max-width: 1000px;
      margin: 0 auto;
    }

    h2 {
      text-align: center;
      color: var(--accent-color);
      margin-bottom: 2rem;
    }

    /* Neon Profile Styles */
    .neon-profile {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 1.5rem;
      margin: 2rem auto;
      background: rgba(0, 255, 247, 0.1);
      border: 2px solid #00fff7;
      border-radius: 20px;
      box-shadow: 0 0 15px #00fff7, 0 0 30px #00fff7, 0 0 45px #00fff7;
      max-width: 280px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      perspective: 1000px;
      transform-style: preserve-3d;
    }

    .neon-profile:hover {
      box-shadow: 0 0 25px #00fff7, 0 0 50px #00fff7, 0 0 75px #00fff7;
    }

    .neon-profile img {
      width: 180px;
      height: 180px;
      border-radius: 50%;
      border: 3px solid #00fff7;
      box-shadow: 0 0 10px #00fff7;
      margin-bottom: 1rem;
      object-fit: cover;
    }

    .neon-name {
      font-weight: bold;
      font-size: 1.1rem;
      color: var(--accent-color);
      text-shadow: 0 0 5px #00fff7, 0 0 10px #00fff7;
      text-align: center;
    }

    @keyframes floatBox {
      0% {
        transform: translateY(0px);
      }
      50% {
        transform: translateY(-10px);
      }
      100% {
        transform: translateY(0px);
      }
    }

    .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .project {
      background-color: var(--card-color);
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0, 255, 255, 0.2);
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .project:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 30px rgba(0, 255, 255, 0.4);
    }

    .project img {
      width: 100%;
      height: auto;
    }

    .project-content {
      padding: 1rem;
    }

    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
      text-align: center;
    }

    .service-card {
      background: var(--card-color);
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 20px rgba(0, 255, 255, 0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .service-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 30px rgba(0, 255, 255, 0.3);
    }

    .service-card i {
      font-size: 2rem;
      margin-bottom: 0.5rem;
      color: var(--accent-color);
    }

    footer {
      background-color: var(--primary-color);
      color: white;
      text-align: center;
      padding: 1rem;
    }

    .social-links {
      text-align: center;
      padding: 1rem;
    }

    .social-links a {
      margin: 0 10px;
      color: var(--accent-color);
      font-size: 1.5rem;
      transition: color 0.3s ease;
    }

    .social-links a:hover {
      color: #ffffff;
    }
  </style>
</head>

<body>
  <header>
    <h1>AGBOOLA ENOCH ADURAGBEMI</h1>
    <p>Welcome to my</p>
    <h2>Portfolio</h2>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="section" data-aos="fade-right">
    <div class="container">
      <h2>About Me</h2>
      <!-- ✅ Neon Profile Box with 3D Hover -->
      <div class="neon-profile" data-aos="zoom-in">
        <img src="https://pbs.twimg.com/media/GpfRBrWWwAE4ZHx?format=jpg&name=900x900" alt="Profile Picture" />
        <p class="neon-name">AGBOOLA ENOCH ADURAGBEMI</p>
      </div>
      <p>I am a passionate designer and developer focused on creating modern, accessible websites that deliver real value to users and businesses.</p>
    </div>
  </section>

  <section id="services" class="section">
    <div class="container">
      <h2 data-aos="fade-up">Services</h2>
      <div class="services-grid">
        <div class="service-card" data-aos="fade-up" data-aos-delay="100">
          <i class="fas fa-code"></i>
          <h3>Web Development</h3>
          <p>I build fast, responsive, and accessible websites.</p>
        </div>
        <div class="service-card" data-aos="fade-up" data-aos-delay="200">
          <i class="fas fa-pencil-ruler"></i>
          <h3>Graphic Design</h3>
          <p>I create clean and effective designs based on user needs.</p>
        </div>
        <div class="service-card" data-aos="fade-up" data-aos-delay="300">
          <i class="fas fa-mobile-alt"></i>
          <h3>Responsive Design</h3>
          <p>All my sites look great on any screen size.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="portfolio" class="section">
    <div class="container">
      <h2 data-aos="fade-up">Portfolio</h2>
      <div class="portfolio">
        <div class="project" data-aos="fade-up">
          <img src="https://pbs.twimg.com/media/GwsFvzAXgAAGDCN?format=jpg&name=medium" alt="Project 1" />
          <div class="project-content">
            <h3>Project One</h3>
            <p>Short description of the project.</p>
          </div>
        </div>
        <div class="project" data-aos="fade-up" data-aos-delay="150">
          <img src="https://pbs.twimg.com/media/Gwh0og2W0AAruqu?format=jpg&name=900x900" alt="Project 2" />
          <div class="project-content">
            <h3>Project Two</h3>
            <p>Another project with some details.</p>
          </div>
        </div>
        <div class="project" data-aos="fade-up" data-aos-delay="300">
          <img src="https://pbs.twimg.com/media/Gwr8XHSXgAAaveG?format=jpg&name=900x900" alt="Project 3" />
          <div class="project-content">
            <h3>Project Three</h3>
            <p>Something creative I built recently.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="contact" class="section" data-aos="zoom-in">
    <div class="container">
      <h2>Contact Me</h2>
      <p>Email: enochbobo28@gmail.com</p>
      <p>Phone: +2348142825071, +2349052548681</p>
    </div>
  </section>

  <div class="social-links" data-aos="fade-up">
    <a href="https://x.com/b0b02824" target="_blank"><i class="fab fa-twitter"></i></a>
    <a href="https://facebook.com/yourprofile" target="_blank"><i class="fab fa-facebook"></i></a>
    <a href="https://instagram.com/yourprofile" target="_blank"><i class="fab fa-instagram"></i></a>
    <a href="https://www.linkedin.com/in/enoch-agboola-239aa1293/" target="_blank"><i class="fab fa-linkedin"></i></a>
  </div>

  <footer data-aos="fade-up" data-aos-delay="300">
    &copy; <span id="year"></span> AGBOOLA ENOCH ADURAGBEMI. All rights reserved.
  </footer>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

  <!-- ✅ 3D Tilt Mouse Effect Script -->
  <script>
    const card2 = document.querySelector('.neon-profile');
  
    card2.addEventListener('mousemove', (e) => {
      const rect = card2.getBoundingClientRect();
      const x = e.clientX - rect.left;
      const y = e.clientY - rect.top;
      const centerX = rect.width / 2;
      const centerY = rect.height / 2;
  
      const rotateX = ((y - centerY) / centerY) * 10;
      const rotateY = ((x - centerX) / centerX) * -10;
  
      card2.style.transform = `rotateX(${rotateX}deg) rotateY(${rotateY}deg)`;
    });
  
    card2.addEventListener('mouseleave', () => {
      card2.style.transform = 'rotateX(0deg) rotateY(0deg)';
    });
  </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Enoch's Portfolio</title>
  <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #0f0f1b;
      color: white;
    }

    .section {
      padding: 60px 20px;
    }

    h2 {
      text-align: center;
      color: #00fff7;
      font-size: 2rem;
    }

    .container {
      max-width: 900px;
      margin: auto;
    }

    .neon-profile {
      background: rgba(26, 26, 64, 0.6);
      border: 2px solid rgba(0, 255, 247, 0.4);
      border-radius: 15px;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.2),
                  0 0 30px rgba(0, 255, 255, 0.1),
                  0 0 45px rgba(0, 255, 255, 0.05);
      padding: 2rem;
      max-width: 400px;
      margin: 2rem auto;
      text-align: center;
      transition: transform 0.5s ease, box-shadow 0.5s ease;
      perspective: 1000px;
      transform-style: preserve-3d;
      backdrop-filter: blur(6px);
    }

    .neon-profile img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #00fff7;
      box-shadow: 0 0 10px #00fff7;
      margin-bottom: 1rem;
    }

    .neon-profile h3 {
      margin: 0;
      font-size: 1.4rem;
      color: #00fff7;
      text-shadow: 0 0 5px #00fff7;
    }

    .neon-profile p {
      color: #c7faff;
      margin-top: 0.8rem;
      font-size: 1rem;
      line-height: 1.5;
    }
  </style>
</head>
<body>

<section id="about" class="section" data-aos="fade-right">
  <div class="container">
    <h2>PARTNER</h2>
    <div class="neon-profile">
      <img src="https://pbs.twimg.com/media/GwsFvzAXgAAGDCN?format=jpg&name=medium" alt="Profile Image">
      <h3>ODETAYO EMMANUEL</h3>
      <p>I am a passionate designer and developer focused on creating modern, accessible websites that deliver real value to users and businesses.</p>
    </div>
  </div>
</section>

<script src="https://unpkg.com/aos@next/dist/aos.js"></script>
<script>
  AOS.init();
</script>

<script>
  const card = document.querySelector('.neon-profile');

  card.addEventListener('mousemove', (e) => {
    const rect = card.getBoundingClientRect();
    const x = e.clientX - rect.left;
    const y = e.clientY - rect.top;
    const centerX = rect.width / 2;
    const centerY = rect.height / 2;

    const rotateX = ((y - centerY) / centerY) * 10;
    const rotateY = ((x - centerX) / centerX) * -10;

    card.style.transform = `rotateX(${rotateX}deg) rotateY(${rotateY}deg)`;
  });

  card.addEventListener('mouseleave', () => {
    card.style.transform = 'rotateX(0deg) rotateY(0deg)';
  });
</script>

</body>
</html>
