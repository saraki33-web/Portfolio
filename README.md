# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nadada_web_tech Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0f172a;
      color: #e2e8f0;
      line-height: 1.6;
    }

    header {
      background: #1e293b;
      padding: 2rem 1rem;
      text-align: center;
    }

    nav {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1rem;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: bold;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 1.5rem;
      padding: 1rem;
      background: #1e293b;
      border-radius: 1rem;
      box-shadow: 0 4px 15px rgba(56, 189, 248, 0.2);
      justify-content: center;
      flex-wrap: wrap;
    }

    .nav-links li a {
      text-decoration: none;
      color: #cbd5e1;
      padding: 0.5rem 1rem;
      border: 2px solid transparent;
      border-radius: 0.5rem;
      transition: all 0.3s ease;
      font-weight: 500;
    }

    .nav-links li a:hover {
      color: #0f172a;
      background: #38bdf8;
      border-color: #38bdf8;
      box-shadow: 0 0 10px #38bdf8;
    }

    .hero {
      padding: 4rem 1rem;
    }

    .hero h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .hero h2 span {
      color: #38bdf8;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 1rem;
    }

    .social-icons a {
      color: #e2e8f0;
      margin: 0 0.5rem;
      font-size: 1.5rem;
      transition: color 0.3s;
    }

    .social-icons a:hover {
      color: #38bdf8;
    }

    .about, .projects, .contact {
      padding: 4rem 1rem;
      max-width: 1100px;
      margin: 0 auto;
    }

    .about h2, .projects h2, .contact h2 {
      font-size: 2rem;
      margin-bottom: 2rem;
      text-align: center;
    }

    .about-content {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 1.5rem;
    }

    .about-content img {
      width: 200px;
      border-radius: 1rem;
      border: 2px solid #38bdf8;
    }

    .projects .project-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .project-card {
      background: #1e293b;
      padding: 1.5rem;
      border-radius: 1rem;
      border: 1px solid #334155;
      transition: transform 0.3s;
    }

    .project-card:hover {
      transform: translateY(-5px);
      border-color: #38bdf8;
    }

    .project-card a {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: #38bdf8;
      color: #0f172a;
      border-radius: 0.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    .contact form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
      margin: 0 auto;
    }

    .contact input, .contact textarea {
      padding: 0.75rem;
      border-radius: 0.5rem;
      border: none;
      background: #1e293b;
      color: #e2e8f0;
    }

    .contact button {
      padding: 0.75rem;
      background: #38bdf8;
      color: #0f172a;
      border: none;
      border-radius: 0.5rem;
      cursor: pointer;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #1e293b;
      color: #94a3b8;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header id="home">
    <nav>
        <img src="image" alt="image">
      <h1 class="logo">Nadada_web_tech</h1>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#projects">My Projects   </a></li>
        <li><a href="#contact">Contact Me</a></li>
      </ul>
    </nav>

    <section class="hero">
      <h2>Hello, I'm <span>Muttaka Muhammad Auwal (Nadadawebtech).  </span></h2>
      <p>UI/UX | Web Developer | Designer | Freelancer</p>
      <div class="social-icons">
  <a href="https://github.com/saraki33-web" target="_blank">
    <i class="fab fa-github"></i>
  </a>
  <a href="#"><i class="fab fa-linkedin"></i></a>
  <a href="#"><i class="fab fa-twitter"></i></a>
 <a href="https://wa.me/2348103214013" target="_blank">
  <i class="fab fa-whatsapp"></i>
</a>
</div>
    </section>
  </header>

  <section id="about" class="about">
    <h2>About Me</h2>
    <div class="about-content">
      <img src="muttaka.jpg" alt="Muttaka Muhammad Auwal profile picture" />
      <p>I'm a passionate web developer with experience in building modern, responsive websites using HTML, CSS, JavaScript and Python. I enjoy turning ideas into reality on the web.</p>
    </div>
  </section>


  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project-list">
      <div class="project-card">
        <h3>Nadada Online Voting</h3>
        <p>A secure, school-focused online voting system built with HTML, CSS, and JavaScript.</p>
        <a href="new.jpg">View Project</a>
      </div>
      <div class="project-card">
        <h3>Portfolio Website</h3>
        <p>A responsive personal portfolio website to showcase your work, skills, and contact details.</p>
        <a href="film.mp4">View Project</a>
      </div>
    </div>
  </section>
  

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Muttaka Muhammad Auwal. All rights reserved.</p>
  </footer>

  <script>
    const form = document.querySelector('form');
    form.addEventListener('submit', function (e) {
      e.preventDefault();
      const name = form.querySelector('input[type="text"]').value;
      const email = form.querySelector('input[type="email"]').value;
      const message = form.querySelector('textarea').value;
      if (name && email && message) {
        alert(`Thank you, ${name}! Your message has been sent.`);
        form.reset();
      } else {
        alert('Please fill in all fields.');
      }
    });
  </script>
</body>
</html>