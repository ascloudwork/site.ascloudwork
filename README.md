<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AS CLOUD WORK | CFTV & Redes</title>
  <style>
    body { margin: 0; font-family: 'Segoe UI', sans-serif; background: linear-gradient(135deg,#020617,#0f172a); color: white; }
    a { color: inherit; text-decoration: none; }
    /* NAV */
    nav { position: sticky; top: 0; backdrop-filter: blur(10px); background: rgba(2,6,23,0.7); border-bottom: 1px solid rgba(255,255,255,0.1); z-index: 10; }
    .nav-container { max-width: 1200px; margin: auto; display: flex; justify-content: space-between; align-items: center; padding: 15px 20px; }
    .logo { font-weight: bold; font-size: 20px; letter-spacing: 1px; }
    .menu { display: flex; gap: 20px; }
    .menu a:hover { color: #22c55e; }

    header { text-align: center; padding: 100px 20px 80px; }
    h1 { font-size: 42px; margin-bottom: 10px; }
    .slogan { font-size: 18px; opacity: 0.8; }

    section { padding: 60px 20px; max-width: 1200px; margin: auto; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px,1fr)); gap: 25px; }
    .card { background: rgba(30,41,59,0.7); backdrop-filter: blur(10px); padding: 25px; border-radius: 16px; transition: 0.3s; border: 1px solid rgba(255,255,255,0.1); }
    .card:hover { transform: translateY(-5px) scale(1.02); }

    button { padding: 12px 25px; border: none; background: linear-gradient(90deg,#22c55e,#4ade80); color: black; border-radius: 10px; cursor: pointer; font-weight: bold; }
    input { padding: 12px; width: 280px; border-radius: 10px; border: none; }

    footer { text-align: center; padding: 30px; background: #020617; margin-top: 40px; }
  </style>
</head>
<body>

<!-- MENU -->
<nav>
  <div class="nav-container">
    <div class="logo">☁️ AS CLOUD WORK</div>
    <div class="menu">
      <a href="#servicos">Serviços</a>
      <a href="#produtos">Produtos</a>
      <a href="#blog">Blog</a>
      <a href="#contato">Contato</a>
    </div>
  </div>
</nav>

<!-- HERO -->
<header>
  <h1>AS CLOUD WORK</h1>
  <p class="slogan">Infraestrutura Inteligente em Redes e Segurança</p>
  <br>
  <button onclick="window.open('https://wa.me/5511999999999?text=Ol%C3%A1%2C%20vim%20pelo%20site%20e%20quero%20um%20or%C3%A7amento')">Falar no WhatsApp</button>
</header>

<!-- SERVIÇOS -->
<section id="servicos">
  <h2>🚀 Serviços Profissionais</h2>
  <div class="grid">
    <div class="card">
      <h3>📹 CFTV Inteligente</h3>
      <p>Monitoramento remoto, câmeras IP e gravação em nuvem.</p>
    </div>
    <div class="card">
      <h3>🌐 Cabeamento Estruturado</h3>
      <p>Projetos certificados seguindo normas técnicas.</p>
    </div>
    <div class="card">
      <h3>📡 Wi-Fi Corporativo</h3>
      <p>Alta cobertura, segurança e desempenho.</p>
    </div>
  </div>
</section>

<!-- PRODUTOS -->
<section id="produtos">
  <h2>🛒 Produtos</h2>
  <div class="grid">
    <div class="card">
      <h3>Câmeras Full HD</h3>
      <p>Segurança 24h com alta definição.</p>
      <button onclick="alert('Chame no WhatsApp para comprar')">Comprar</button>
    </div>
    <div class="card">
      <h3>Roteadores Profissionais</h3>
      <p>Alta performance empresarial.</p>
      <button onclick="alert('Chame no WhatsApp para comprar')">Comprar</button>
    </div>
    <div class="card">
      <h3>Cabos Cat6</h3>
      <p>Alta velocidade e estabilidade.</p>
      <button onclick="alert('Chame no WhatsApp para comprar')">Comprar</button>
    </div>
  </div>
</section>

<!-- BLOG -->
<section id="blog">
  <h2>📚 Blog Técnico</h2>
  <div class="grid">
    <div class="card">
      <h3>O que é Cabeamento Estruturado?</h3>
      <p>Sistema padronizado para dados, voz e imagem.</p>
    </div>
    <div class="card">
      <h3>Normas TIA/EIA</h3>
      <p>Garantem qualidade e segurança.</p>
    </div>
    <div class="card">
      <h3>Cat5e vs Cat6</h3>
      <p>Escolha correta para seu projeto.</p>
    </div>
  </div>
</section>

<!-- CONTATO -->
<section id="contato" style="text-align:center;">
  <h2>📞 Contato</h2>
  <p>Solicite um orçamento rápido</p>
  <input placeholder="Seu email"><br><br>
  <button onclick="alert('Mensagem enviada!')">Enviar</button>
</section>

<footer>
  <p>© 2026 AS CLOUD WORK | Todos os direitos reservados</p>
</footer>

</body>
</html>
