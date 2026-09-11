<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Manik Shrivastav — AI & Systems Developer, software builder, and low-level programming enthusiast." />
  <title>Manik Shrivastav — Alien</title>
  <style>
    :root {
      --bg: #0b1020;
      --card: #11182b;
      --card-2: #0e1526;
      --text: #e8eefc;
      --muted: #9aa8c7;
      --accent: #70a5fd;
      --accent-2: #bf91f3;
      --border: #24314d;
    }

    * { box-sizing: border-box; }
    html { scroll-behavior: smooth; }

    body {
      margin: 0;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont,
                   "Segoe UI", sans-serif;
      background:
        radial-gradient(circle at top right, rgba(112,165,253,.13), transparent 28%),
        radial-gradient(circle at bottom left, rgba(191,145,243,.10), transparent 25%),
        var(--bg);
      color: var(--text);
      line-height: 1.65;
    }

    a { color: inherit; text-decoration: none; }

    .container {
      width: min(1100px, calc(100% - 32px));
      margin: auto;
    }

    header {
      min-height: 92vh;
      display: grid;
      place-items: center;
      text-align: center;
      padding: 70px 0;
    }

    .eyebrow {
      display: inline-block;
      padding: 7px 14px;
      border: 1px solid var(--border);
      border-radius: 999px;
      color: var(--accent);
      background: rgba(112,165,253,.06);
      font-size: .85rem;
      letter-spacing: .08em;
      text-transform: uppercase;
    }

    h1 {
      margin: 20px 0 8px;
      font-size: clamp(3rem, 9vw, 6.5rem);
      line-height: .95;
      letter-spacing: -.06em;
    }

    .alias {
      color: var(--accent);
      font-weight: 800;
    }

    .typing {
      min-height: 34px;
      color: var(--muted);
      font-size: clamp(1rem, 2vw, 1.25rem);
      margin: 24px auto;
    }

    .cursor {
      border-right: 2px solid var(--accent);
      animation: blink .8s step-end infinite;
    }

    @keyframes blink { 50% { border-color: transparent; } }

    .intro {
      max-width: 760px;
      margin: 0 auto 30px;
      color: var(--muted);
      font-size: 1.08rem;
    }

    .buttons {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    .btn {
      padding: 11px 18px;
      border-radius: 10px;
      border: 1px solid var(--border);
      background: var(--card);
      transition: .2s ease;
      font-weight: 700;
    }

    .btn:hover {
      transform: translateY(-2px);
      border-color: var(--accent);
      color: var(--accent);
    }

    section { padding: 80px 0; }

    .section-title {
      font-size: 2rem;
      margin: 0 0 10px;
      letter-spacing: -.03em;
    }

    .section-subtitle {
      color: var(--muted);
      margin: 0 0 28px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .card {
      background: linear-gradient(145deg, var(--card), var(--card-2));
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 24px;
      height: 100%;
    }

    .card h3 {
      margin-top: 0;
      margin-bottom: 8px;
    }

    .card p { color: var(--muted); }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 9px;
    }

    .tag {
      padding: 7px 11px;
      border-radius: 8px;
      background: #18233b;
      border: 1px solid var(--border);
      color: #cbd7ef;
      font-size: .9rem;
    }

    .project {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }

    .project .links {
      margin-top: auto;
      padding-top: 12px;
      color: var(--accent);
      font-weight: 700;
    }

    .stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 18px;
    }

    .stat {
      text-align: center;
      padding: 28px;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 16px;
    }

    .stat strong {
      display: block;
      font-size: 2rem;
      color: var(--accent);
    }

    .contact {
      text-align: center;
      padding: 70px 20px;
      border: 1px solid var(--border);
      border-radius: 20px;
      background: linear-gradient(145deg, var(--card), var(--card-2));
    }

    footer {
      text-align: center;
      padding: 40px 0 60px;
      color: var(--muted);
    }

    .alien {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    @media (max-width: 800px) {
      .grid, .stats { grid-template-columns: 1fr; }
      header { min-height: 80vh; }
      section { padding: 55px 0; }
    }
  </style>
</head>

<body>
  <header>
    <div class="container">
      <span class="eyebrow">AI • Systems • Software • Low Level</span>

      <h1>Hey 👋, I'm <span class="alias">Manik</span></h1>
      <h2>aka <span class="alias">Alien</span></h2>

      <div class="typing">
        <span id="typingText" class="cursor"></span>
      </div>

      <p class="intro">
        I build software and systems with a strong interest in AI, programming,
        operating systems, developer tools, hardware, and unconventional ideas.
        I enjoy going from low-level concepts to practical products that solve
        real problems.
      </p>

      <div class="buttons">
        <a class="btn" href="https://github.com/ManikShrivastav" target="_blank">GitHub</a>
        <a class="btn" href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
        <a class="btn" href="https://www.youtube.com/" target="_blank">YouTube</a>
        <a class="btn" href="mailto:manikshrivastav163@gmail.com">Email</a>
      </div>
    </div>
  </header>

  <main class="container">

    <section id="about">
      <h2 class="section-title">🧠 About Me</h2>
      <p class="section-subtitle">
        A builder-oriented profile based on the information represented in the
        provided GitHub profile and README reference.
      </p>

      <div class="grid">
        <article class="card">
          <h3>⚙️ Systems</h3>
          <p>
            Interested in low-level programming, Linux, CLI tools, operating
            systems, and understanding how software works beneath the surface.
          </p>
        </article>

        <article class="card">
          <h3>🤖 AI</h3>
          <p>
            Exploring Python, LLMs, and AI-driven software with an emphasis on
            turning ideas into usable systems.
          </p>
        </article>

        <article class="card">
          <h3>🚀 Building</h3>
          <p>
            I like experimenting, shipping projects, learning by building, and
            creating technology that reflects my own approach.
          </p>
        </article>
      </div>
    </section>

    <section id="stack">
      <h2 class="section-title">🛠️ Tech Stack</h2>
      <p class="section-subtitle">Technologies represented in the source profile.</p>

      <div class="grid">
        <article class="card">
          <h3>👨‍💻 Languages</h3>
          <div class="tags">
            <span class="tag">C</span>
            <span class="tag">Assembly</span>
            <span class="tag">Python</span>
            <span class="tag">Java</span>
            <span class="tag">PHP</span>
            <span class="tag">HTML</span>
            <span class="tag">CSS</span>
            <span class="tag">JavaScript</span>
          </div>
        </article>

        <article class="card">
          <h3>🤖 AI / ML</h3>
          <div class="tags">
            <span class="tag">Python</span>
            <span class="tag">LLMs</span>
            <span class="tag">AI Engineering</span>
          </div>
        </article>

        <article class="card">
          <h3>🐧 Systems & Hardware</h3>
          <div class="tags">
            <span class="tag">Linux</span>
            <span class="tag">Linux CLI</span>
            <span class="tag">Operating Systems</span>
            <span class="tag">Arduino</span>
            <span class="tag">Low-Level Programming</span>
          </div>
        </article>
      </div>
    </section>

    <section id="projects">
      <h2 class="section-title">🚀 Featured Projects</h2>
      <p class="section-subtitle">
        Projects currently represented on the GitHub profile.
      </p>

      <div class="grid">
        <article class="card project">
          <h3>🔧 KainOS</h3>
          <p>
            An operating-system-oriented project representing the systems and
            low-level side of the profile.
          </p>
          <div class="links">
            <a href="https://github.com/ManikShrivastav" target="_blank">View on GitHub →</a>
          </div>
        </article>

        <article class="card project">
          <h3>📝 Pariksha Plugin</h3>
          <p>
            A project from the GitHub profile focused on the Pariksha/plugin
            ecosystem.
          </p>
          <div class="links">
            <a href="https://github.com/ManikShrivastav" target="_blank">View on GitHub →</a>
          </div>
        </article>

        <article class="card project">
          <h3>🌐 EOE</h3>
          <p>
            One of the highlighted projects represented on the profile.
          </p>
          <div class="links">
            <a href="https://github.com/ManikShrivastav" target="_blank">View on GitHub →</a>
          </div>
        </article>

        <article class="card project">
          <h3>👽 Alien Sutra</h3>
          <p>
            A project connected with the Alien identity and creative/technical
            work represented in the profile.
          </p>
          <div class="links">
            <a href="https://github.com/ManikShrivastav" target="_blank">View on GitHub →</a>
          </div>
        </article>

        <article class="card project">
          <h3>🖱️ MousePad</h3>
          <p>
            Another repository represented among the profile's projects.
          </p>
          <div class="links">
            <a href="https://github.com/ManikShrivastav" target="_blank">View on GitHub →</a>
          </div>
        </article>

        <article class="card project">
          <h3>📓 MuktiNote</h3>
          <p>
            A repository from the profile's broader project collection.
          </p>
          <div class="links">
            <a href="https://github.com/ManikShrivastav" target="_blank">View on GitHub →</a>
          </div>
        </article>
      </div>
    </section>

    <section id="github">
      <h2 class="section-title">📊 GitHub</h2>
      <p class="section-subtitle">
        Profile information currently represented on GitHub.
      </p>

      <div class="stats">
        <div class="stat">
          <strong>20+</strong>
          Repositories
        </div>
        <div class="stat">
          <strong>11</strong>
          Followers
        </div>
        <div class="stat">
          <strong>9</strong>
          Following
        </div>
      </div>

      <div class="card" style="margin-top:18px;">
        <h3>🔗 Explore Everything</h3>
        <p>
          Browse repositories, projects, experiments, and contributions directly
          from the GitHub profile.
        </p>
        <a class="btn" href="https://github.com/ManikShrivastav" target="_blank">
          Open GitHub Profile
        </a>
      </div>
    </section>

    <section id="contact">
      <div class="contact">
        <div class="alien">👽</div>
        <h2 class="section-title">Let's Build Something Interesting</h2>
        <p class="section-subtitle">
          Have an idea, project, experiment, or technical problem?
          Let's connect.
        </p>

        <div class="buttons">
          <a class="btn" href="mailto:manikshrivastav163@gmail.com">Email Me</a>
          <a class="btn" href="https://github.com/ManikShrivastav" target="_blank">GitHub</a>
          <a class="btn" href="https://www.linkedin.com/" target="_blank">LinkedIn</a>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">
      <p>👽 Built by Manik Shrivastav · aka Alien</p>
      <p>Code. Experiment. Build. Repeat.</p>
    </div>
  </footer>

  <script>
    const roles = [
      "AI / Software Developer",
      "Systems & Low-Level Programming Enthusiast",
      "Python & LLM Explorer",
      "Linux / CLI Builder",
      "Hardware & Arduino Enthusiast",
      "Building unconventional things 👽"
    ];

    const element = document.getElementById("typingText");
    let roleIndex = 0;
    let charIndex = 0;
    let deleting = false;

    function type() {
      const role = roles[roleIndex];

      if (!deleting) {
        element.textContent = role.slice(0, charIndex++);
        if (charIndex > role.length) {
          deleting = true;
          setTimeout(type, 1300);
          return;
        }
      } else {
        element.textContent = role.slice(0, charIndex--);
        if (charIndex < 0) {
          deleting = false;
          roleIndex = (roleIndex + 1) % roles.length;
          charIndex = 0;
        }
      }

      setTimeout(type, deleting ? 45 : 75);
    }

    type();
  </script>
</body>
</html>
