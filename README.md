<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Deepika | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">

  <style>
    body {
      background: #0d0d0d;
      min-height: 100vh;
      font-family: 'Orbitron', sans-serif;
      color: white;
      padding: 40px;
      text-align: center;
    }

    h1 {
      font-size: 3.5rem;
      text-transform: uppercase;
      background: linear-gradient(90deg, #00f0ff, #ff00f0, #00f0ff);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: gradientMove 3s infinite;
      background-size: 200% auto;
      text-shadow: 0px 0px 10px #00f0ff;
    }

    @keyframes gradientMove {
      0% {
        background-position: 0% 50%;
      }
      100% {
        background-position: 100% 50%;
      }
    }

    h2 {
      margin-top: 50px;
      font-size: 2rem;
    }

    p {
      font-size: 1.2rem;
    }

    hr {
      border: 1px solid #444;
      margin: 40px 0;
    }

    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }

    .tech-item {
      text-align: center;
      transition: transform 0.3s ease-in-out;
    }

    .tech-item:hover {
      transform: translateY(-10px);
    }

    .badge, .gif, .typing {
      margin: 20px auto;
      display: block;
    }

    .social-icons img {
      margin: 10px;
    }

    @media(max-width: 600px) {
      h1 { font-size: 2.5rem; }
      h2 { font-size: 1.5rem; }
      .tech-item img { height: 40px; }
    }
  </style>
</head>

<body>

  <!-- 🚀 Hero Section -->
  <h1>👩‍💻 Hello, I'm Deepika</h1>
  <p>🚀 Data Science | Python Developer | AI Enthusiast</p>

  <img class="badge" src="https://img.shields.io/badge/Mindset-Lifelong%20Learner-orange?style=for-the-badge&logo=protonmail" />
  <img class="gif" src="https://user-images.githubusercontent.com/89788178/235298118-4c98504d-7c3a-4d30-b2a7-ccc3d89c45ac.gif" width="250"/>

  <hr />

  <!-- 🌟 About Me -->
  <h2>🌟 About Me</h2>
  <p align="left" style="max-width: 700px; margin: auto;">
    🎓 B.Tech CSE graduate from <strong>Sanskrithi School of Engineering, Puttaparthi</strong><br>
    💼 Currently working in <strong>Data Science & Python Development</strong><br>
    🧠 Exploring <strong>AI, Front-End Development, and Data Analytics</strong><br>
    💬 Ask me about <strong>Python, SQL, MERN Stack, or AI projects</strong>
  </p>

  <hr />

  <!-- 🧰 Tech Stack -->
  <h2>🧰 Tech Stack – Floating in 3D</h2>
  <div class="tech-stack">
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=python" height="50"/><p>Python</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=html" height="50"/><p>HTML</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=css" height="50"/><p>CSS</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=js" height="50"/><p>JavaScript</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=react" height="50"/><p>React</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=nodejs" height="50"/><p>Node.js</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=mongodb" height="50"/><p>MongoDB</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=git" height="50"/><p>Git</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=vscode" height="50"/><p>VS Code</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=figma" height="50"/><p>Figma</p></div>
    <div class="tech-item"><img src="https://skillicons.dev/icons?i=sql" height="50"/><p>SQL</p></div>
  </div>

  <hr />

  <!-- 📊 GitHub Stats -->
  <h2>📊 GitHub Stats</h2>
  <p>
    <img src="https://github-readme-stats.vercel.app/api?username=nukaladeepika&show_icons=true&theme=tokyonight" /><br>
    <img src="https://github-readme-streak-stats.herokuapp.com?user=nukaladeepika&theme=tokyonight" />
  </p>

  <hr />

  <!-- 🌐 Connect -->
  <h2>🌐 Connect With Me</h2>
  <p class="social-icons">
    <a href="https://www.linkedin.com/in/nukala-deepika-90105a23a">
      <img src="https://img.shields.io/badge/LinkedIn-Deepika-blue?style=for-the-badge&logo=linkedin"/>
    </a>
    <a href="mailto:youremail@example.com">
      <img src="https://img.shields.io/badge/Gmail-Contact-red?style=for-the-badge&logo=gmail"/>
    </a>
    <a href="https://github.com/nukaladeepika">
      <img src="https://img.shields.io/badge/GitHub-nukaladeepika-black?style=for-the-badge&logo=github"/>
    </a>
  </p>

  <hr />

  <!-- ✨ Footer -->
  <h2>✨ Let's Build the Future Together</h2>
  <img class="typing" src="https://readme-typing-svg.demolab.com?font=Orbitron&size=24&pause=1000&color=F7F7F7&background=0FAAFF00&center=true&vCenter=true&width=435&lines=Code.+Build.+Innovate." />

</body>
</html>
