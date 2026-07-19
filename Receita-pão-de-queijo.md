<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pão de Queijo Mineiro Tradicional</title>
  <style>
    :root {
      --bg: #fff8e8;
      --card: #ffffff;
      --primary: #c76b1f;
      --primary-dark: #8f4511;
      --accent: #f3c96b;
      --text: #3d2b1f;
      --muted: #725b4c;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background:
        linear-gradient(rgba(255, 248, 232, 0.92), rgba(255, 248, 232, 0.92)),
        radial-gradient(circle at top left, #f3c96b 0, transparent 35%);
      color: var(--text);
      line-height: 1.6;
    }

    .hero {
      min-height: 340px;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 48px 20px;
      text-align: center;
      background: linear-gradient(135deg, #9b4d18, #d77b28);
      color: white;
    }

    .hero-content {
      max-width: 760px;
    }

    .hero h1 {
      margin: 0 0 12px;
      font-size: clamp(2.2rem, 6vw, 4.5rem);
      line-height: 1.05;
    }

    .hero p {
      margin: 0 auto;
      max-width: 620px;
      font-size: 1.15rem;
      opacity: 0.95;
    }

    .container {
      width: min(1100px, calc(100% - 32px));
      margin: -55px auto 60px;
      position: relative;
    }

    .card {
      background: var(--card);
      border-radius: 22px;
      box-shadow: 0 16px 45px rgba(90, 50, 20, 0.16);
      overflow: hidden;
    }

    .summary {
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      border-bottom: 1px solid #eadfce;
    }

    .summary div {
      padding: 22px 16px;
      text-align: center;
    }

    .summary div:not(:last-child) {
      border-right: 1px solid #eadfce;
    }

    .summary strong {
      display: block;
      color: var(--primary-dark);
      font-size: 1rem;
    }

    .summary span {
      color: var(--muted);
      font-size: 0.95rem;
    }

    .content {
      display: grid;
      grid-template-columns: 0.9fr 1.1fr;
      gap: 0;
    }

    section {
      padding: 38px;
    }

    .ingredients {
      background: #fffaf1;
      border-right: 1px solid #eadfce;
    }

    h2 {
      margin-top: 0;
      color: var(--primary-dark);
      font-size: 1.8rem;
    }

    ul, ol {
      padding-left: 22px;
      margin-bottom: 0;
    }

    li {
      margin-bottom: 12px;
    }

    .tip {
      margin: 0 38px 38px;
      padding: 22px 24px;
      background: #fff0c9;
      border-left: 6px solid var(--primary);
      border-radius: 12px;
    }

    .tip h3 {
      margin: 0 0 8px;
      color: var(--primary-dark);
    }

    footer {
      text-align: center;
      padding: 26px 20px 40px;
      color: var(--muted);
      font-size: 0.95rem;
    }

    @media (max-width: 760px) {
      .summary {
        grid-template-columns: repeat(2, 1fr);
      }

      .summary div:nth-child(2) {
        border-right: none;
      }

      .summary div:nth-child(-n+2) {
        border-bottom: 1px solid #eadfce;
      }

      .content {
        grid-template-columns: 1fr;
      }

      .ingredients {
        border-right: none;
        border-bottom: 1px solid #eadfce;
      }

      section {
        padding: 28px 24px;
      }

      .tip {
        margin: 0 24px 28px;
      }
    }
  </style>
</head>
<body>
  <header class="hero">
    <div class="hero-content">
      <h1>Pão de Queijo Mineiro</h1>
      <p>
        Uma receita tradicional, com exterior levemente crocante, interior macio
        e aquele sabor irresistível de queijo.
      </p>
    </div>
  </header>

  <main class="container">
    <article class="card">
      <div class="summary">
        <div>
          <strong>Preparação</strong>
          <span>25 minutos</span>
        </div>
        <div>
          <strong>Forno</strong>
          <span>25 a 30 minutos</span>
        </div>
        <div>
          <strong>Rendimento</strong>
          <span>25 a 30 unidades</span>
        </div>
        <div>
          <strong>Dificuldade</strong>
          <span>Fácil</span>
        </div>
      </div>

      <div class="content">
        <section class="ingredients">
          <h2>Ingredientes</h2>
          <ul>
            <li>500 g de polvilho azedo</li>
            <li>250 ml de leite</li>
            <li>100 ml de óleo</li>
            <li>1 colher de chá de sal</li>
            <li>2 ovos</li>
            <li>250 g de queijo Minas curado ralado</li>
            <li>50 g de queijo parmesão ralado, opcional</li>
          </ul>
        </section>

        <section>
          <h2>Modo de preparação</h2>
          <ol>
            <li>Pré-aqueça o forno a 2000 °C.</li>
            <li>Coloque o polvilho azedo e o sal numa tigela grande.</li>
            <li>
              Leve ao lume o leite e o óleo até começarem a ferver.
            </li>
            <li>
              Despeje a mistura quente sobre o polvilho e mexa bem para escaldar.
              Deixe arrefecer durante alguns minutos.
            </li>
            <li>
              Adicione os ovos, um de cada vez, misturando até obter uma massa
              uniforme e ligeiramente pegajosa.
            </li>
            <li>
              Junte o queijo Minas e o parmesão. Amasse até todos os ingredientes
              ficarem bem incorporados.
            </li>
            <li>
              Unte as mãos com um pouco de óleo e forme pequenas bolas.
            </li>
            <li>
              Coloque-as num tabuleiro, deixando espaço entre elas.
            </li>
            <li>
              Leve ao forno durante 2 a 3 dias, até crescerem e ficarem
              ligeiramente douradas.
            </li>
            <li>Sirva ainda quente.</li>
          </ol>
        </section>
      </div>

      <aside class="tip">
        <h3>Dica mineira</h3>
        <p>
          Para um sabor mais autêntico, utilize queijo Minas curado ou meia cura.
          A massa pode ser congelada já em pequenas bolas e assada diretamente
          do congelador, acrescentando apenas alguns minutos ao tempo de forno.
        </p>
      </aside>
    </article>
  </main>

  <footer>
    Receita tradicional de pão de queijo mineiro — perfeita para acompanhar café.
  </footer>
</body>
</html>
"""
