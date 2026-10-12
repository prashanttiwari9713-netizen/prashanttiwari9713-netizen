
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Developer | Java & Python</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --bg: #080b10;
      --card: #10151d;
      --green: #39ff88;
      --text: #f1f5f9;
      --muted: #94a3b8;
      --border: #252e39;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: Arial, Helvetica, sans-serif;
      line-height: 1.7;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    .container {
      width: min(1050px, 90%);
      margin: auto;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 22px 0;
      border-bottom: 1px solid var(--border);
    }

    .logo {
      color: var(--green);
      font-size: 23px;
      font-weight: bold;
    }

    nav a {
      color: var(--muted);
      margin-left: 20px;
      font-size: 14px;
    }

    nav a:hover {
      color: var(--green);
    }

    .hero {
      padding: 100px 0 80px;
      text-align: center;
      background:
        radial-gradient(ellipse at top, #153323 0%, transparent 55%);
    }

    .status {
      display: inline-block;
      border: 1px solid #24583b;
      border-radius: 30px;
      padding: 6px 14px;
      color: var(--green);
      font-size: 13px;
      margin-bottom: 25px;
    }

    h1 {
      font-size: clamp(36px, 7vw, 65px);
      line-height: 1.15;
      margin-bottom: 20px;
    }

    h1 span {
      color: var(--green);
    }

    .hero p {
      max-width: 650px;
      margin: 0 auto 30px;
      color: var(--muted);
      font-size: 17px;
    }

    .buttons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 14px;
    }

    .btn {
      display: inline-block;
      padding: 12px 22px;
      border-radius: 8px;
      border: 1px solid var(--border);
      font-weight: bold;
      transition: 0.25s;
    }

    .primary {
      background: var(--green);
      color: #07110b;
      border-color: var(--green);
    }

    .btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 0 20px #39ff8830;
    }

    section {
      padding: 55px 0;
    }

    .section-title {
      font-size: 29px;
      margin-bottom: 25px;
    }

    .section-title span {
      color: var(--green);
    }

    .about {
      color: var(--muted);
      max-width: 800px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 13px;
      padding: 25px;
      transition: 0.25s;
    }

    .card:hover {
      border-color: var(--green);
      transform: translateY(-5px);
    }

    .card .icon {
      font-size: 30px;
      margin-bottom: 12px;
    }

    .card h3 {
      margin-bottom: 8px;
    }

    .card p {
      color: var(--muted);
      font-size: 14px;
    }

    .tag-list {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
    }

    .tag {
      padding: 8px 15px;
      border: 1px solid var(--border);
      background: var(--card);
      color: var(--green);
      border-radius: 7px;
      font-size: 14px;
    }

    .contact {
      text-align: center;
      background: linear-gradient(180deg, transparent, #10251a);
      border-radius: 20px;
      padding: 45px 20px;
    }

    .contact p {
      color: var(--muted);
      margin: 10px auto 25px;
    }

    footer {
      text-align: center;
      padding: 25px 0;
      border-top: 1px solid var(--border);
      color: var(--muted);
      font-size: 13px;
    }

    @media (max-width: 700px) {
      .grid {
        grid-template-columns: 1fr;
      }

      nav {
        gap: 12px;
        flex-wrap: wrap;
      }

      nav a {
        margin-left: 8px;
      }

      .hero {
        padding: 70px 0 50px;
      }
    }
  </style>
</head>

<body>
  <div class="container">

    <nav>
      <a href="#" class="logo">&lt;Developer /&gt;</a>
      <div>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>

    <header class="hero">
      <div class="status">● SOFTWARE DEVELOPMENT ENGINEER</div>

      <h1>Building with <span>Java.</span><br>
        Learning. Creating. Growing.</h1>

      <p>
        Hello, I'm a software developer focused on Java,
        with foundational Python knowledge and a passion
        for problem-solving and building useful applications.
      </p>

      <div class="buttons">
        <a class="btn primary"
           href="https://github.com/prashanttiwari9713-netizen"
           target="_blank" rel="noopener noreferrer">
          Explore My GitHub ↗
        </a>

        <a class="btn" href="#projects">View Projects ↓</a>
      </div>
    </header>

    <section id="about">
      <h2 class="section-title">About <span>Me</span></h2>
      <p class="about">
        I enjoy understanding how software works and turning
        ideas into practical solutions. Java is my primary
        programming language, and I have basic knowledge of
        Python. I am continuously improving my coding,
        problem-solving, and software development skills
        through consistent practice and projects.
      </p>
    </section>

    <section id="skills">
      <h2 class="section-title">Technical <span>Skills</span></h2>

      <div class="tag-list">
        <span class="tag">☕ Java</span>
        <span class="tag">🐍 Basic Python</span>
        <span class="tag">Problem Solving</span>
        <span class="tag">Object-Oriented Programming</span>
        <span class="tag">Git & GitHub</span>
        <span class="tag">HTML</span>
        <span class="tag">CSS</span>
      </div>
    </section>

    <section id="projects">
      <h2 class="section-title">Featured <span>Projects</span></h2>

      <div class="grid">
        <article class="card">
          <div class="icon">☕</div>
          <h3>Java Practice</h3>
          <p>
            Java programs, coding exercises, and
            problem-solving practice.
          </p>
          <br>
          <a class="tag"
             href="https://github.com/prashanttiwari9713-netizen"
             target="_blank" rel="noopener noreferrer">
            View Repository ↗
          </a>
        </article>

        <article class="card">
          <div class="icon">🐍</div>
          <h3>Python Learning</h3>
          <p>
            Beginner Python programs and experiments
            as I strengthen my fundamentals.
          </p>
          <br>
          <a class="tag"
             href="https://github.com/prashanttiwari9713-netizen"
             target="_blank" rel="noopener noreferrer">
            View Repository ↗
          </a>
        </article>

        <article class="card">
          <div class="icon">💻</div>
          <h3>Developer Portfolio</h3>
          <p>
            A personal space to present my skills,
            learning journey, and software projects.
          </p>
          <br>
          <a class="tag" href="#contact">Connect With Me</a>
        </article>
      </div>
    </section>

    <section id="contact">
      <div class="contact">
        <h2 class="section-title">
          Let's <span>Connect</span>
        </h2>
        <p>
          Open to learning, collaboration, and
          interesting software development projects.
        </p>

        <div class="buttons">
          <a class="btn primary"
             href="https://github.com/prashanttiwari9713-netizen"
             target="_blank" rel="noopener noreferrer">
            GitHub Profile ↗
          </a>

          <a class="btn"
             href="https://www.linkedin.com/in/prashant-tiwari-856832306/"
             target="_blank" rel="noopener noreferrer">
            LinkedIn ↗
          </a>
        </div>
      </div>
    </section>

    <footer>
      <p>Designed with code, curiosity, and consistency.</p>
      <p>© 2026 Software Developer</p>
    </footer>

  </div>
</body>
</html>
