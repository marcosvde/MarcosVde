<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Marcos Vinícius | Data Science</title>

  <!-- Fontes e Ícones -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto&display=swap" rel="stylesheet">
  <script src="https://kit.fontawesome.com/your-awesome-kit.js" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <style>
    :root {
      --bg-color: #0f172a;
      --primary: #38bdf8;
      --secondary: #7c3aed;
      --accent: #22c55e;
      --text-color: #f1f5f9;
    }

    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
    }

    header {
      padding: 2rem;
      text-align: center;
      background: linear-gradient(to right, var(--primary), var(--secondary));
      color: white;
      animation: fadeIn 2s ease-out;
    }

    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      margin: 0;
    }

    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
      animation: fadeSlideUp 1s ease-in-out;
    }

    .section h2 {
      color: var(--accent);
      font-size: 2rem;
      border-bottom: 2px solid var(--accent);
      display: inline-block;
      margin-bottom: 1rem;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1rem;
      margin-top: 1rem;
    }

    .skill, .project {
      background: #1e293b;
      padding: 1rem;
      border-radius: 1rem;
      transition: transform 0.3s ease;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .skill:hover, .project:hover {
      transform: translateY(-5px) scale(1.05);
    }

    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #94a3b8;
    }

    .socials {
      margin-top: 2rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
    }

    .socials a {
      color: var(--text-color);
      font-size: 2rem;
      transition: color 0.3s ease;
    }

    .socials a:hover {
      color: var(--accent);
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes fadeSlideUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Marcos Vinícius</h1>
    <p>Estudante de Data Science | Python | Web | Machine Learning</p>

    <div class="socials">
      <a href="https://www.linkedin.com/in/marcosviniciustech/" target="_blank"><i class="fab fa-linkedin"></i></a>
      <a href="https://github.com/marcosvde" target="_blank"><i class="fab fa-github"></i></a>
    </div>
  </header>

  <section class="section">
    <h2>Sobre Mim</h2>
    <p>Sou apaixonado por dados e tecnologia. Atualmente estudo Data Science, focando em Python e suas bibliotecas como Pandas, NumPy, Matplotlib e Scikit-learn. Também tenho experiência com desenvolvimento web utilizando HTML, CSS e JavaScript. Sempre buscando transformar dados em soluções inteligentes.</p>
  </section>

  <section class="section">
    <h2>Habilidades</h2>
    <div class="skills">
      <div class="skill"><i class="fab fa-python"></i> Python</div>
      <div class="skill"><i class="fas fa-database"></i> Pandas</div>
      <div class="skill"><i class="fas fa-cogs"></i> Numpy</div>
      <div class="skill"><i class="fas fa-chart-bar"></i> Matplotlib</div>
      <div class="skill"><i class="fas fa-robot"></i> Scikit-learn</div>
      <div class="skill"><i class="fab fa-html5"></i> HTML</div>
      <div class="skill"><i class="fab fa-css3-alt"></i> CSS</div>
      <div class="skill"><i class="fab fa-js-square"></i> JavaScript</div>
      <div class="skill"><i class="fab fa-git-alt"></i> Git</div>
    </div>
  </section>

  <section class="section">
    <h2>Projetos</h2>
    <div class="projects">
      <div class="project">📊 Análise de Dados com Pandas e Matplotlib</div>
      <div class="project">🤖 Machine Learning com Scikit-learn</div>
      <div class="project">📈 Dashboard interativo com Power BI</div>
      <div class="project">💻 Site Pessoal com animações em JavaScript</div>
    </div>
  </section>

  <section class="section">
    <h2>Contato</h2>
    <p>Você pode me encontrar nas redes sociais acima ou enviar uma mensagem via LinkedIn.</p>
  </section>

  <footer>
    &copy; 2025 - Marcos Vinícius. Desenvolvido com 💙 e curiosidade.
  </footer>
</body>
</html>
