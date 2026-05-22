<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Areeb Khan | School Project</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, sans-serif;
    }

    body{
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color:white;
      min-height:100vh;
    }

    header{
      padding:20px 10%;
      display:flex;
      justify-content:space-between;
      align-items:center;
      background: rgba(255,255,255,0.05);
      backdrop-filter: blur(10px);
      position:sticky;
      top:0;
    }

    .logo{
      font-size:28px;
      font-weight:bold;
      color:#38bdf8;
    }

    nav a{
      color:white;
      text-decoration:none;
      margin-left:20px;
      transition:0.3s;
    }

    nav a:hover{
      color:#38bdf8;
    }

    .hero{
      height:90vh;
      display:flex;
      justify-content:center;
      align-items:center;
      text-align:center;
      padding:20px;
    }

    .hero-content{
      max-width:700px;
    }

    .hero h1{
      font-size:60px;
      margin-bottom:20px;
    }

    .hero h1 span{
      color:#38bdf8;
    }

    .hero p{
      font-size:20px;
      line-height:1.6;
      color:#d1d5db;
      margin-bottom:30px;
    }

    .btn{
      display:inline-block;
      padding:14px 30px;
      background:#38bdf8;
      color:#0f172a;
      text-decoration:none;
      font-weight:bold;
      border-radius:10px;
      transition:0.3s;
    }

    .btn:hover{
      background:white;
      transform:scale(1.05);
    }

    section{
      padding:80px 10%;
    }

    .section-title{
      text-align:center;
      font-size:40px;
      margin-bottom:50px;
      color:#38bdf8;
    }

    .cards{
      display:grid;
      grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
      gap:25px;
    }

    .card{
      background: rgba(255,255,255,0.08);
      padding:30px;
      border-radius:20px;
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-10px);
      background: rgba(255,255,255,0.12);
    }

    .card h3{
      margin-bottom:15px;
      color:#38bdf8;
    }

    footer{
      text-align:center;
      padding:25px;
      background: rgba(255,255,255,0.05);
      margin-top:50px;
      color:#cbd5e1;
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">Areeb Khan</div>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <div class="hero-content">
      <h1>Hello, I'm <span>Areeb Khan</span></h1>

      <p>
        Welcome to my school project website.
        This website is designed using HTML and CSS with a modern UI design.
      </p>

      <a href="#projects" class="btn">View My Work</a>
    </div>
  </section>

  <section id="about">
    <h2 class="section-title">About Me</h2>

    <div class="cards">
      <div class="card">
        <h3>Student</h3>
        <p>
          I am a creative student who enjoys learning web development
          and building modern websites.
        </p>
      </div>

      <div class="card">
        <h3>Skills</h3>
        <p>
          HTML, CSS, basic JavaScript, creativity, teamwork,
          and problem solving.
        </p>
      </div>

      <div class="card">
        <h3>Goals</h3>
        <p>
          My goal is to become a professional software developer
          and create amazing digital experiences.
        </p>
      </div>
    </div>
  </section>

  <section id="projects">
    <h2 class="section-title">My Projects</h2>

    <div class="cards">
      <div class="card">
        <h3>Portfolio Website</h3>
        <p>
          A responsive personal portfolio website using HTML and CSS.
        </p>
      </div>

      <div class="card">
        <h3>School Project</h3>
        <p>
          A modern design project showcasing creativity and coding skills.
        </p>
      </div>

      <div class="card">
        <h3>Future Apps</h3>
        <p>
          Planning to build games, apps, and advanced websites in the future.
        </p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2 class="section-title">Contact</h2>

    <div class="cards">
      <div class="card">
        <h3>Email</h3>
        <p>areebkhan@email.com</p>
      </div>

      <div class="card">
        <h3>School</h3>
        <p>Your School Name Here</p>
      </div>

      <div class="card">
        <h3>Location</h3>
        <p>United States</p>
      </div>
    </div>
  </section>

  <footer>
    © 2026 Areeb Khan | School Project Website
  </footer>

</body>
</html># khan
Class project website
