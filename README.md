<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Vinicius Moura Costa</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: var(--bg);
      color: var(--text);
      transition: 0.3s;
    }

    /* Auto theme */
    @media (prefers-color-scheme: light) {
      :root { --bg: #ffffff; --text: #111111; --card: #f4f4f4; }
    }
    @media (prefers-color-scheme: dark) {
      :root { --bg: #1a1a1a; --text: #e2e2e2; --card: #2a2a2a; }
    }

    header {
      padding: 40px 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-size: 2.8rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
      flex-wrap: wrap;
    }
    nav a {
      text-decoration: none;
      color: var(--text);
      font-weight: bold;
      padding: 8px 14px;
      border-radius: 6px;
    }
    nav a:hover {
      background: var(--card);
    }

    section {
      max-width: 900px;
      margin: 50px auto;
      padding: 20px;
      background: var(--card);
      border-radius: 12px;
    }

    h2 {
      margin-top: 0;
    }

    footer {
      text-align: center;
      padding: 20px;
      opacity: 0.6;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Vinicius Moura Costa</h1>
    <p>Research • Engineering • Distributed Fiber Optic Sensing • COMSOL • Machine Learning</p>
    <nav>
      <a href="#about">About Me</a>
      <a href="#projects">Projects</a>
      <a href="#teaching">Teaching & Mentoring</a>
      <a href="#awards">Awards</a>
      <a href="#blog">Blog</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Write your professional bio here. Include your PhD topic, research focus (DFOS, Brillouin, COMSOL modeling), your ambitions
      for MIT/NASA/NIST/NEC internships, your publications, and your broader engineering interests.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <p>List your main research and technical projects here. Examples:</p>
    <ul>
      <li>DFOS Modeling in COMSOL (Brillouin, Raman, Rayleigh)</li>
      <li>Nebraska Steel Girder Bridge FE Model</li>
      <li>PPP-BOTDA Python Implementation</li>
      <li>Machine Learning Fairness Analysis (HMDA dataset)</li>
    </ul>
  </section>

  <section id="teaching">
    <h2>Teaching & Mentoring</h2>
    <p>Include any mentoring, tutoring, or TA experience, even informal research mentorship.</p>
  </section>

  <section id="awards">
    <h2>Awards</h2>
    <p>List academic awards, scholarships, research recognitions, etc.</p>
  </section>

  <section id="blog">
    <h2>Blog</h2>
    <p>Write research notes, summaries of papers, DFOS insights, or engineering reflections.</p>
  </section>

  <footer>
    © 2025 Vinicius Moura Costa
  </footer>
</body>
</html>
