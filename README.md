<!DOCTYPE html>
<html lang="pt">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Valdimiro Digital</title>

  <meta name="description" content="Valdimiro Digital - Plataforma digital para vender produtos e serviços online.">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #222;
    }

    header {
      background: #111;
      color: white;
      text-align: center;
      padding: 35px 15px;
    }

    header h1 {
      font-size: 32px;
      margin-bottom: 10px;
    }

    header p {
      font-size: 16px;
      color: #ddd;
    }

    nav {
      background: #222;
      padding: 12px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 12px;
      font-weight: bold;
    }

    .hero {
      text-align: center;
      padding: 45px 20px;
      background: white;
    }

    .hero h2 {
      font-size: 28px;
      margin-bottom: 12px;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      line-height: 1.6;
      color: #555;
    }

    .produtos {
      max-width: 1100px;
      margin: 35px auto;
      padding: 0 20px;
    }

    .produtos h2 {
      text-align: center;
      margin-bottom: 25px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }

    .produto {
      background: white;
      border-radius: 12px;
      padding: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      text-align: center;
    }

    .produto .imagem {
      height: 160px;
      background: #eee;
      border-radius: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 55px;
      margin-bottom: 15px;
    }

    .produto h3 {
      margin-bottom: 10px;
    }

    .produto p {
      color: #666;
      line-height: 1.5;
      margin-bottom: 12px;
    }

    .preco {
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 15px;
    }

    .comprar {
      display: inline-block;
      width: 100%;
      padding: 13px;
      background: #25D366;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.2s;
    }

    .comprar:hover {
      background: #1ebe5d;
    }

    .sobre {
      background: white;
      padding: 45px 20px;
      text-align: center;
      margin-top: 40px;
    }

    .sobre p {
      max-width: 700px;
      margin: 15px auto;
      line-height: 1.7;
      color: #555;
    }

    footer {
      background: #111;
      color: white;
      text-align: center;
      padding: 25px 15px;
      margin-top: 0;
    }

    footer p {
      margin: 6px;
    }
  </style>
</head>

<body>

  <header>
    <h1>Valdimiro Digital</h1>
    <p>Produtos e serviços digitais online</p>
  </header>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#produtos">Produtos</a>
    <a href="#sobre">Sobre</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section class="hero" id="inicio">
    <h2>Bem-vindo à Valdimiro Digital</h2>
    <p>
      Encontre produtos e serviços digitais de forma simples,
      rápida e segura. Escolha o que deseja e fale diretamente
      connosco pelo WhatsApp.
    </p>
  </section>

  <section class="produtos" id="produtos">

    <h2>Os nossos produtos</h2>

    <div class="grid">

      <!-- PRODUTO 1 -->
      <div class="produto">
        <div class="imagem">📘</div>

        <h3>Mente Bilionária</h3>

        <p>
          Ebook sobre mentalidade, disciplina,
          objetivos e desenvolvimento pessoal.
        </p>

        <div class="preco">5.000 Kz</div>

        <a
          class="comprar"
          href="https://wa.me/244944217517?text=Olá!%20Quero%20comprar%20o%20Ebook%20Mente%20Bilionária."
          target="_blank"
          rel="noopener noreferrer">
          Comprar pelo WhatsApp
        </a>
      </div>


      <!-- PRODUTO 2 -->
      <div class="produto">
        <div class="imagem">💻</div>

        <h3>Curso Digital</h3>

        <p>
          Curso online para aprender a desenvolver
          projetos e trabalhar no mundo digital.
        </p>

        <div class="preco">10.000 Kz</div>

        <a
          class="comprar"
          href="https://wa.me/244944217517?text=Olá!%20Quero%20comprar%20o%20Curso%20Digital."
          target="_blank"
          rel="noopener noreferrer">
          Comprar pelo WhatsApp
        </a>
      </div>


      <!-- PRODUTO 3 -->
      <div class="produto">
        <div class="imagem">📱</div>

        <h3>Serviço Digital</h3>

        <p>
          Serviço digital personalizado para
          ajudar no teu projeto online.
        </p>

        <div class="preco">15.000 Kz</div>

        <a
          class="comprar"
          href="https://wa.me/244944217517?text=Olá!%20Tenho%20interesse%20no%20Serviço%20Digital."
          target="_blank"
          rel="noopener noreferrer">
          Comprar pelo WhatsApp
        </a>
      </div>

    </div>
  </section>


  <section class="sobre" id="sobre">

    <h2>Sobre a Valdimiro Digital</h2>

    <p>
      A Valdimiro Digital é uma plataforma criada para
      disponibilizar produtos e serviços online.
      O nosso objetivo é facilitar o acesso a soluções
      digitais e permitir que os clientes entrem
      diretamente em contacto connosco.
    </p>

  </section>


  <section class="sobre" id="contacto">

    <h2>Contacto</h2>

    <p>
      Para comprar um produto ou saber mais informações,
      fala connosco pelo WhatsApp.
    </p>

    <br>

    <a
      class="comprar"
      style="max-width:300px; margin:auto;"
      href="https://wa.me/244944217517?text=Olá!%20Vim%20pela%20Valdimiro%20Digital%20e%20quero%20mais%20informações."
      target="_blank"
      rel="noopener noreferrer">
      Falar no WhatsApp
    </a>

  </section>


  <footer>
    <p><strong>Valdimiro Digital</strong></p>
    <p>© 2026 Valdimiro Digital. Todos os direitos reservados.</p>
  </footer>

</body>
</html>
