<!--DOCTYPE html-->
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Afia Animah Fosu - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: radial-gradient(ellipse at top, #0f172a, #1e293b);
      color: #f8fafc;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(90deg, #4f46e5, #9333ea);
      color: white;
      padding: 4rem 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
    }
    header h2 {
      font-weight: 400;
      font-size: 1.25rem;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1rem;
      color: #e0e7ff;
    }
    nav {
      background: #0f172a;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
      padding: 1rem 2rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      text-decoration: none;
      color: #a5b4fc;
      font-weight: 600;
      transition: color 0.2s;
    }
    nav a:hover {
      color: #c084fc;
    }
    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: 0 auto;
    }
    .section h3 {
      font-size: 1.75rem;
      margin-bottom: 1rem;
      color: #a78bfa;
    }
    .card {
      background: #1e293b;
      border-radius: 1rem;
      box-shadow: 0 4px 6px rgba(0,0,0,0.3);
      padding: 2rem;
      margin-bottom: 2rem;
      transition: transform 0.2s;
    }
    .card:hover {
      transform: translateY(-4px);
    }
    .profile-pic {
      display: block;
      max-width: 200px;
      border-radius: 1rem;
      margin: 0 auto 2rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      background: #0f172a;
      color: #94a3b8;
      font-size: 0.9rem;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      background: #4f46e5;
      color: white;
      padding: 0.75rem 1.25rem;
      border-radius: 0.5rem;
      text-decoration: none;
      font-weight: 600;
      transition: background 0.3s;
    }
    .btn:hover {
      background: #4338ca;
    }
    @media (max-width: 480px) {
      header h1 {
        font-size: 1.5rem;
      }
      nav {
        padding: 0.75rem 1rem;
      }
      nav a {
        font-size: 0.6rem;
      }
      .section h3 {
        font-size: 1.5rem;
      }
      .card {
        margin-bottom: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Afia Animah Fosu</h1>
    <h2>Computer Science & Mathematics Student</h2>
    <p>Tech innovator, research assistant, and frontend developer passionate about making a difference.</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#experience">Experience</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="section" id="about">
    <h3>About Me</h3>
    <div class="card">
      <img src="IMG_3673.jpeg" alt="Afia Animah Fosu" class="profile-pic" />
      <p>Hi! I'm Afia, a student at Wesleyan University with a passion for software engineering, robotics, and building tech solutions for real-world problems. I'm driven by curiosity and creativity and I love collaborating with others to build impactful projects.</p>
    </div>
  </div>

  <div class="section" id="projects">
    <h3>Projects</h3>
    <div class="card">
      <h4>CoThrift</h4>
      <p>A campus-wide sustainable thrifting app built using HTML, CSS, and JavaScript. Won the Sustainability Award at Hoya Hacks 2025.</p>
    </div>
    <div class="card">
      <h4>TechXplore</h4>
      <p>A student-led tech club enabling peers to explore, collaborate, and build projects in AI, web, and hardware domains.</p>
    </div>
  </div>

  <div class="section" id="experience">
    <h3>Experience</h3>
    <div class="card">
      <p><strong>Research Assistant</strong> – Wesleyan Soft Robots Lab (Jan 2025 – Present)</p>
      <p>Developed knitted robotic actuators, prototyped soft systems, and contributed to research publications.</p>
    </div>
    <div class="card">
      <p><strong>Frontend Developer</strong> – Hoya Hacks (Jan 2025)</p>
      <p>Led front-end development for CoThrift platform promoting sustainable student consumption.</p>
    </div>
    <div class="card">
      <p><strong>Founder</strong> – TechXplore (Apr 2025 – Present)</p>
      <p>Established and led a student tech club offering guided learning and hands-on technical project support.</p>
    </div>
  </div>

  <div class="section" id="skills">
    <h3>Skills</h3>
    <div class="card">
      <p><strong>Languages & Tools:</strong> Python, HTML, CSS, JavaScript, Git, Microsoft Office</p>
      <p><strong>Other Skills:</strong> Design Thinking, Cross-functional collaboration, Communication</p>
    </div>
  </div>

  <div class="section" id="contact">
    <h3>Contact</h3>
    <div class="card">
      <p>Email: <a href="mailto:afosu@wesleyan.edu">afosu@wesleyan.edu</a></p>
      <p>Phone: <a href="tel:+19042289241">(904) 228-9241</a></p>
      <p>LinkedIn: <a href="https://linkedin.com/in/afia-fosu-4ab952299" target="_blank" rel="noopener noreferrer">afia-fosu</a></p>
      <a class="btn" href="Afia_Resume.pdf" download="Afia_Fosu_Resume.pdf">Download Resume</a>
    </div>
  </div>

  <footer>
    © 2025 Afia Animah Fosu. All rights reserved.
  </footer>
</body>
</html>
