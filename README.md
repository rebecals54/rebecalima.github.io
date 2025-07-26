<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio | Rebeca Lima</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
      background: #f9fafb;
      color: #111827;
    }
    header {
      background: #1f2937;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }
    header h1 { font-size: 2rem; margin-bottom: 0.5rem; }
    nav {
      background: white;
      padding: 1rem;
      display: flex;
      justify-content: center;
      gap: 2rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    nav a {
      text-decoration: none;
      color: #1f2937;
      font-weight: 600;
      padding: 0.5rem 1rem;
      border-radius: 8px;
    }
    nav a:hover {
      background-color: #e0f2fe;
    }
    .container {
      max-width: 1100px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .section {
      display: none;
    }
    .section.active {
      display: block;
      animation: fadeIn 0.3s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
      padding: 1.5rem;
      margin-bottom: 1.5rem;
    }
    .card h3 { margin-bottom: 0.5rem; }
    .card p { color: #4b5563; margin-bottom: 0.5rem; }
    .badge {
      display: inline-block;
      background-color: #e0f2fe;
      color: #0369a1;
      padding: 0.25rem 0.5rem;
      border-radius: 999px;
      font-size: 0.75rem;
      margin-right: 0.5rem;
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: #6b7280;
    }
  </style>
</head>
<body>
  <header>
    <h1>Rebeca Lima</h1>
    <p>Data Analyst • Power BI • Engenharia de Produção</p>
  </header>

  <nav>
    <a href="#" onclick="showSection('projetos')">Projetos</a>
    <a href="#" onclick="showSection('cursos')">Cursos</a>
    <a href="#" onclick="showSection('analises')">Análises</a>
  </nav>

  <main class="container">
    <section id="projetos" class="section active">
      <h2>Projetos</h2>
      <div class="card">
        <h3>DataToys Dashboard</h3>
        <span class="badge">ETL</span>
        <span class="badge">Data Visualization</span>
        <span class="badge">DAX</span>
        <p>Dashboard desenvolvido com foco em vendas e fluxo de caixa usando Power BI.</p>
        <a href="#">Leia mais →</a>
      </div>
      <div class="card">
        <h3>Logistics Dashboard</h3>
        <span class="badge">ETL</span>
        <span class="badge">DAX</span>
        <p>Relatório interativo para análise de KPIs logísticos e controle operacional.</p>
        <a href="#">Leia mais →</a>
      </div>
    </section>

    <section id="cursos" class="section">
      <h2>Cursos e Formação</h2>
      <div class="card">
        <h3>Engenharia de Produção</h3>
        <p>IFCE (2023 - 2027)</p>
      </div>
      <div class="card">
        <h3>Análise e Desenvolvimento de Sistemas</h3>
        <p>Unifanor Wyden (2023 - 2025)</p>
      </div>
      <div class="card">
        <h3>Power BI para BI e Ciência de Dados</h3>
        <p>Data Science Academy (2024)</p>
      </div>
    </section>

    <section id="analises" class="section">
      <h2>Análises</h2>
      <div class="card">
        <h3>Indicadores de Satisfação e Financeiros</h3>
        <p>Análise de VOC, Google Reviews e HSGI com foco em proposta de melhoria e experiência do cliente.</p>
      </div>
      <div class="card">
        <h3>Monitoramento de KPIs Logísticos</h3>
        <p>Construção de dashboards para acompanhamento de desempenho e apoio à tomada de decisão.</p>
      </div>
    </section>
  </main>

  <footer>
    <p>© 2025 Rebeca Lima • Portfólio Profissional</p>
  </footer>

  <script>
    function showSection(id) {
      document.querySelectorAll('.section').forEach(sec => sec.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>
</body>
</html>
