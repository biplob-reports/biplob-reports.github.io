<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Name — Portfolio</title>
  <style>
    body { font-family: Arial, sans-serif; max-width: 900px; margin: 40px auto; padding: 0 16px; line-height: 1.6; }
    header { display: flex; justify-content: space-between; align-items: baseline; gap: 12px; flex-wrap: wrap; }
    nav a { margin-right: 12px; }
    .card { border: 1px solid #ddd; border-radius: 10px; padding: 16px; margin: 16px 0; }
    .muted { color: #555; }
    footer { margin-top: 40px; font-size: 0.9em; color: #666; }
  </style>
</head>
<body>
  <header>
    <div>
      <h1>Your Name</h1>
      <p class="muted">Role / Specialty — short sentence about what you do.</p>
    </div>
    <nav>
      <a href="#projects">Projects</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="projects">
    <h2>Projects</h2>

    <div class="card">
      <h3>Project One</h3>
      <p>1–2 sentences: what it is, what problem it solves, what you built.</p>
      <p>
        <a href="https://github.com/yourname/project-one">Code</a> |
        <a href="https://example.com">Live Demo</a>
      </p>
    </div>

    <div class="card">
      <h3>Project Two</h3>
      <p>Short description.</p>
      <p>
        <a href="https://github.com/yourname/project-two">Code</a>
      </p>
    </div>
  </section>

  <section id="about">
    <h2>About</h2>
    <p>
      Write 3–6 lines about your background, your skills, and what roles you want.
    </p>
    <ul>
      <li>Skill 1</li>
      <li>Skill 2</li>
      <li>Skill 3</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:you@email.com">you@email.com</a></p>
    <p>
      <a href="https://www.linkedin.com/in/yourname/">LinkedIn</a> |
      <a href="https://github.com/yourname">GitHub</a>
    </p>
  </section>

  <footer>
    <p>© <span id="y"></span> Your Name</p>
  </footer>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>
