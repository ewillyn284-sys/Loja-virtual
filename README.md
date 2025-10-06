<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja Virtual Exemplo</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f7f7f7;
      color: #333;
    }

    header {
      background-color: #2d89ef;
      color: white;
      text-align: center;
      padding: 30px 10px;
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    nav {
      background-color: #1b5fab;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 14px 20px;
      display: block;
      transition: background-color 0.3s;
    }

    nav a:hover {
      background-color: #104a87;
    }

    main {
      max-width: 1100px;
      margin: 20px auto;
      padding: 0 20px;
    }

    .banner {
      background: url('https://images.unsplash.com/photo-1503602642458-232111445657?auto=format&fit=crop&w=1100&q=80') center/cover no-repeat;
      height: 300px;
      border-radius: 10px;
      margin-bottom: 30px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      text-shadow: 2px 2px 8px rgba(0,0,0,0.6);
    }

    .produtos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .produto {
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
      padding: 15px;
      transition: transform 0.2s;
    }

    .produto:hover {
      transform: scale(1.03);
    }

    .produto img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }

    .produto h3 {
      margin: 10px 0 5px;
    }

    .produto p {
      color: #666;
      font-size: 0.9em;
    }

    .preco {
      color: #2d89ef;
      font-weight: bold;
      margin: 10px 0;
    }

    .botao-comprar {
      background-color: #2d89ef;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    .botao-comprar:hover {
      background-color: #1b5fab;
    }

    footer {
      background-color: #2d89ef;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Loja Virtual Exemplo</h1>
    <p>Os melhores produtos, pelos melhores preços!</p>
  </header>

  <nav>
    <a href="#inicio">Início</a>
    <a href="#produtos">Produtos</a>
    <a href="#sobre">Sobre Nós</a>
    <a href="#contato">Contato</a>
  </nav>

  <main>
    <section id="inicio" class="banner">
      Promoções Especiais de Outono 🍂
    </section>

    <section id="produtos">
      <h2>Produtos em Destaque</h2>
      <div class="produtos">
        <div class="produto">
          <img src="https://images.unsplash.com/photo-1585386959984-a41552231693?auto=format&fit=crop&w=800&q=80" alt="Tênis esportivo">
          <h3>Tênis Esportivo</h3>
          <p>Confortável e leve, ideal para o dia a dia.</p>
          <div class="preco">R$ 199,90</div>
          <button class="botao-comprar">Comprar</button>
        </div>

        <div class="produto">
          <img src="https://images.unsplash.com/photo-1606813902911-9b41b6f9e58a?auto=format&fit=crop&w=800&q=80" alt="Relógio moderno">
          <h3>Relógio Moderno</h3>
          <p>Design elegante com resistência à água.</p>
          <div class="preco">R$ 249,90</div>
          <button class="botao-comprar">Comprar</button>
        </div>

        <div class="produto">
          <img src="https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?auto=format&fit=crop&w=800&q=80" alt="Fone Bluetooth">
          <h3>Fone Bluetooth</h3>
          <p>Som de alta qualidade e bateria duradoura.</p>
          <div class="preco">R$ 149,90</div>
          <button class="botao-comprar">Comprar</button>
        </div>
      </div>
    </section>

    <section id="sobre" style="margin-top:40px;">
      <h2>Sobre Nós</h2>
      <p>Somos uma loja online comprometida em oferecer os melhores produtos com qualidade e preço justo. Nosso objetivo é proporcionar uma experiência de compra simples, rápida e segura.</p>
    </section>

    <section id="contato" style="margin-top:40px;">
      <h2>Contato</h2>
      <p>📧 E-mail: <a href="mailto:contato@lojavirtual.com">contato@lojavirtual.com</a></p>
      <p>📞 Telefone: (11) 99999-9999</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Loja Virtual Exemplo — Todos os direitos reservados.</p>
  </footer>

</body>
</html>
