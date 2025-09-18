<html lang="da">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Golf Butikken</title>
  <style>
    /* Reset */
    * { margin: 0; padding: 0; box-sizing: border-box; }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #006400;
      color: #fff;
      padding: 15px;
      text-align: center;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: url("https://images.unsplash.com/photo-1508780709619-79562169bc64") no-repeat center center/cover;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px black;
      font-size: 2rem;
      text-align: center;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
      padding: 20px 0;
    }

    h2 {
      text-align: center;
      margin-bottom: 20px;
      color: #006400;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .product {
      background: white;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    .product img {
      max-width: 100%;
      border-radius: 10px;
    }

    .product h3 {
      margin: 10px 0;
    }

    .btn {
      display: inline-block;
      background: #006400;
      color: white;
      padding: 10px 15px;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 10px;
    }

    .btn:hover {
      background: #228B22;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Golf Butikken</h1>
    <nav>
      <ul>
        <li><a href="#forside">Forside</a></li>
        <li><a href="#produkter">Produkter</a></li>
        <li><a href="#kontakt">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero" id="forside">
    <h2>Velkommen til Golf Butikken<br>Alt til din golfoplevelse!</h2>
  </section>

  <section class="container" id="produkter">
    <h2>Produkter</h2>
    <div class="products">
      <div class="product">
        <img src="<img width="2986" height="1499" alt="image" src="https://github.com/user-attachments/assets/584a21ea-b8cf-44f5-a4c5-1980df8d4f4c" />
" alt="Golfkøller">
        <h3>Golfkøller</h3>
        <p>Topkvalitets køller.</p>
        <a href="#" class="btn">Køb nu</a>
      </div>
      <div class="product">
        <img src="<img width="1200" height="1200" alt="image" src="https://github.com/user-attachments/assets/0a8978e3-22ea-484b-b558-51a44c828833" />
" alt="Golfbolde">
        <h3>Golfbolde</h3>
        <p>Et dusin golfbolde.</p>
        <a href="#" class="btn">Køb nu</a>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1521412644187-c49fa049e84d" alt="Golftaske">
        <h3>Golftaske</h3>
        <p>Stilfuld og praktisk taske til hele sættet.</p>
        <a href="#" class="btn">Køb nu</a>
      </div>
    </div>
  </section>

  <footer id="kontakt">
    <h2>Kontakt os</h2>
    <p>Email: info@golfshoppen.dk</p>
    <p>Telefon: +45 12 34 56 78</p>
    <p>&copy; 2025 GolfShoppen</p>
  </footer>
</body>
</html>
