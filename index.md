<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Santhosh Balaji | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="navbar">
    <div class="logo">portfolio</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <div class="hero-text">
      <p class="intro">Hey, it's me</p>
      <h1 class="name">Santhosh Balaji</h1>
      <h2 class="role">I work with <span class="highlight">Data & AI</span></h2>
      <p class="description">
        I’m a Master’s student in Human-Centered AI. I enjoy working with data — cleaning it, structuring it,
        and building pipelines around it — and I’m motivated by how strong data workflows unlock efficient,
        reliable AI systems.
      </p>
      <div class="hero-buttons">
        <a href="resume.pdf" class="btn" target="_blank">Download CV</a>
      </div>
      <div class="socials">
        <a href="https://github.com/Sanba1" target="_blank">GitHub</a>
        <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
        <a href="mailto:santhoshbalaji59@gmail.com">Email</a>
      </div>
    </div>
    <div class="hero-image">
      <img src="profile.jpg" alt="Profile photo of Santhosh" />
    </div>
  </section>

  <section id="about" class="section">
    <h2>About</h2>
    <p>
      I’m a data-oriented AI student with experience in Python, SQL, machine learning, and distributed AI deployment.
      I’ve built embedding pipelines, document processing tools, backend model APIs, and deployed quantized LLMs on
      mobile devices. My work spans data engineering, system integration, and real-world ML pipelines.
    </p>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>

    <div class="project">
      <h3>Distributed Neural Networks – Decentralized Data Pipeline</h3>
      <p>
        Built a distributed data pipeline where mobile devices perform local vector search, embedding processing,
        and 4-bit LLM inference, then send partial answers to a central summariser. Orchestrated the flow via
        Slack → Python → Firestore and optimised JSON streaming and communication.
      </p>
    </div>

    <div class="project">
      <h3>Topic &amp; Sentiment Analysis of 50,000 News Articles</h3>
      <p>
        Analysed 50k articles using TF-IDF, K-Means, MinHash/LSH, and Louvain to extract topics and communities,
        and tracked sentiment across time and publications.
      </p>
    </div>

    <div class="project">
      <h3>Powerlifting Performance ML Pipeline</h3>
      <p>
        Cleaned 18k+ powerlifting records, performed PCA, and trained regression and ANN models with
        cross-validation and statistical tests to compare performance.
      </p>
    </div>

    <div class="project">
      <h3>GCL Programming Language Toolchain</h3>
      <p>
        Implemented a full parser → compiler → interpreter toolchain for Guarded Command Language with
        static analysis and model checking.
      </p>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: <a href="mailto:santhoshbalaji59@gmail.com">santhoshbalaji59@gmail.com</a></p>
    <p>Location: Copenhagen, Denmark</p>
  </section>

  <footer class="footer">
    © <span id="year"></span> Santhosh Balaji
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
