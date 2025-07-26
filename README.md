<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio | Rebeca Lima</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;600;800&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Montserrat', sans-serif;
      background-color: #0f172a;
      color: #ffffff;
    }
    header {
      background-color: #1e293b;
      padding: 1.5rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-weight: 800;
      font-size: 1rem;
      background: white;
      color: #0f172a;
      padding: 0.2rem 0.5rem;
      border-radius: 4px;
    }
    header span {
      color: #facc15;
      font-weight: 300;
      margin-left: 0.5rem;
    }
    nav {
      font-weight: 600;
      font-size: 0.9rem;
    }
    .grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      grid-template-rows: 300px 300px;
      gap: 0;
    }
    .card {
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 2rem;
    }
    .card h2 {
      font-size: 2rem;
      font-weight: 600;
      margin-bottom: 1rem;
    }
    .card p {
      text-transform: uppercase;
      font-size: 0.8rem;
      letter-spacing: 1px;
      max-width: 400px;
    }
    .python { background-color: #60a5fa; color: white; }
    .r { background-color: #8b5cf6; color: white; }
    .sql { background-color: #f87171; color: white; }
    .excel { background-color: #fbbf24; color: white; }
    @media (max-width: 768px) {
      .grid {
        grid-template-columns: 1fr;
        grid-template-rows: auto;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>DATA ANALYST PORTFÓLIO <span>by Rebeca Lima</span></h1>
    <nav>MENU &#9776;</nav>
  </header>

  <main class="grid">
    <div class="card python">
      <h2>Python</h2>
      <p>Transformando dados utilizando bibliotecas e estruturas do Python</p>
    </div>
    <div class="card r">
      <h2>R</h2>
      <p>Desbloqueando o poder dos dados com R<br>Em andamento...</p>
    </div>
    <div class="card sql">
      <h2>SQL</h2>
      <p>Dominando a consulta e o gerenciamento de dados com SQL</p>
    </div>
    <div class="card excel">
      <h2>Excel</h2>
      <p>Aproveitando todo o potencial do Excel para análise de dados</p>
    </div>
  </main>
</body>
</html>
