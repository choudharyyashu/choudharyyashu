<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Yashwant Choudhary | MERN Stack Developer</title>

  <!-- SEO -->
  <meta name="description" content="Yashwant Choudhary – MERN Stack Developer | React, Node.js, MongoDB | Portfolio" />

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />

  <style>
    :root {
      --bg: #0b1120;
      --card: #111827;
      --primary: #38bdf8;
      --secondary: #22c55e;
      --text: #e5e7eb;
      --muted: #94a3b8;
      --gradient: linear-gradient(135deg, #38bdf8, #22c55e);
    }

    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }

    body {
      background: radial-gradient(circle at top, #111827, #020617 60%);
      color: var(--text);
      line-height: 1.7;
      scroll-behavior: smooth;
    }

    a { color: inherit; text-decoration: none; }

    /* NAV */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      background: rgba(2,6,23,.8);
      backdrop-filter: blur(12px);
      z-index: 1000;
    }

    .nav-container {
      max-width: 1200px;
      margin: auto;
      padding: 15px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-weight: 800;
      font-size: 1.2rem;
      background: var(--gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .nav-links a {
      margin-left: 25px;
      font-weight: 500;
      color: var(--muted);
    }

    .nav-links a:hover { color: var(--primary); }

    /* HERO */
    header {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 120px 20px 80px;
    }

    .hero {
      max-width: 900px;
      text-align: center;
    }

    .hero h1 {
      font-size: clamp(2.5rem, 5vw, 4rem);
      font-weight: 800;
    }

    .hero span {
      background: var(--gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .hero p {
      margin-top: 20px;
      font-size: 1.15rem;
      color: var(--muted);
    }

    .hero-buttons {
      margin-top: 35px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 14px 30px;
      border-radius: 30px;
      font-weight: 600;
      transition: .3s ease;
    }

    .btn-primary {
      background: var(--gradient);
      color: #020617;
    }

    .btn-outline {
      border: 1px solid var(--primary);
      color: var(--primary);
    }

    .btn:hover { transform: translateY(-3px); }

    /* SECTION */
    section {
      max-width: 1200px;
      margin: auto;
      padding: 90px 20px;
    }

    section h2 {
      text-align: center;
      font-size: 2.3rem;
      margin-bottom: 20px;
    }

    section h2 span {
      background: var(--gradient);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .section-desc {
      text-align: center;
      max-width: 700px;
      margin: auto;
      color: var(--muted);
      margin-bottom: 60px;
    }

    /* CARDS */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .card {
      background: linear-gradient(180deg, #020617, #020617) padding-box,
                  linear-gradient(135deg, #38bdf8, #22c55e) border-box;
      border: 1px solid transparent;
      border-radius: 20px;
      padding: 30px;
      transition: .4s ease;
    }

    .card:hover { transform: translateY(-8px); }

    .card h3 { margin-bottom: 10px; }
    .card p { color: var(--muted); }

    /* SKILLS */
    .skills span {
      display: inline-block;
      margin: 8px;
      padding: 10px 18px;
      border-radius: 20px;
      background: #020617;
      border: 1px solid #1e293b;
      font-size: .9rem;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 40px 20px;
      background: #020617;
      color: var(--muted);
    }

    footer a { margin: 0 10px; color: var(--primary); }

    @media (max-width: 768px) {
      .nav-links { display: none; }
    }
  </style>
</head>
<body>

<nav>
  <div class="nav-container">
    <div class="logo">Yashwant.dev</div>
    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </div>
</nav>

<header>
  <div class="hero">
    <h1>Hi, I'm <span>Yashwant Choudhary</span></h1>
    <p>MERN Stack Developer passionate about building scalable web applications and clean user interfaces.</p>
    <div class="hero-buttons">
      <a href="#projects" class="btn btn-primary">View Projects</a>
      <a href="mailto:yashuchoudhary3621@gmail.com" class="btn btn-outline">Hire Me</a>
    </div>
  </div>
</header>

<section id="about">
  <h2>About <span>Me</span></h2>
  <p class="section-desc">
    MCA graduate with hands-on MERN stack training at Dr. Reddy’s Foundation. Strong foundation in JavaScript,
    React, Node.js, MongoDB, and RESTful APIs. Passionate about learning, building, and improving.
  </p>
</section>

<section id="skills">
  <h2>My <span>Skills</span></h2>
  <div class="skills center">
    <span>JavaScript</span><span>React.js</span><span>Node.js</span><span>Express.js</span>
    <span>MongoDB</span><span>MySQL</span><span>HTML5</span><span>CSS3</span>
    <span>Git & GitHub</span><span>Postman</span>
  </div>
</section>

<section id="projects">
  <h2>Featured <span>Projects</span></h2>
  <div class="grid">
    <div class="card">
      <h3>Shopping24 – E‑Commerce</h3>
      <p>Product catalog, authentication, cart & checkout using MERN stack.</p>
    </div>
    <div class="card">
      <h3>Gym Management System</h3>
      <p>Member registration, subscriptions, attendance tracking & dashboards.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Get In <span>Touch</span></h2>
  <p class="section-desc">Open to internships, full‑time roles, and freelance opportunities.</p>
  <div class="hero-buttons">
    <a href="mailto:yashuchoudhary3621@gmail.com" class="btn btn-primary">Email Me</a>
    <a href="https://github.com/yashwantchoudhary" class="btn btn-outline" target="_blank">GitHub</a>
  </div>
</section>

<footer>
  © 2026 Yashwant Choudhary · MERN Stack Developer
</footer>

</body>
</html>
