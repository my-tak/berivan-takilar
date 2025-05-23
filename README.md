<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Berivan Takılar</title>
  <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #e6f0ff;
      color: #222f3e;
      margin: 0;
      padding: 0;
    }
    nav {
      background-color: #1E3A8A;
      padding: 10px 20px;
      display: flex;
      justify-content: center;
      gap: 30px;
      position: sticky;
      top: 0;
      z-index: 999;
    }
    nav a {
      color: white;
      font-weight: bold;
      text-decoration: none;
      font-size: 1rem;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #FFD700;
    }
    header.site-title {
      font-family: 'Dancing Script', cursive;
      font-weight: 700;
      text-align: center;
      font-size: 3.5rem;
      color: #1E3A8A;
      text-transform: uppercase;
      letter-spacing: 5px;
      margin: 30px 0 20px;
      user-select: none;
    }
    h2.category-title,
    h3.category-title {
      color: #1E3A8A;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 1.5px;
      margin-top: 40px;
      margin-bottom: 20px;
      text-align: center;
    }
    .products-container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      padding: 0 20px;
    }
    .product-card {
      background-color: #ffffff;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(30, 144, 255, 0.15);
      overflow: hidden;
      width: 280px;
      display: flex;
      flex-direction: column;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .product-card:hover {
      transform: translateY(-8px);
      box-shadow: 0 10px 20px rgba(30, 144, 255, 0.35);
    }
    .product-image img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      display: block;
    }
    .product-info {
      padding: 16px 20px 24px;
      flex-grow: 1;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .product-info h3 {
      margin: 0 0 10px;
      font-size: 1.25rem;
      color: #1B263B;
    }
    .product-info p {
      flex-grow: 1;
      font-size: 0.95rem;
      color: #2C3E50;
      margin-bottom: 16px;
    }
    .product-info form input[type="submit"] {
      background-color: #0074E8;
      border: none;
      color: white;
      font-weight: 700;
      padding: 12px 0;
      width: 100%;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
      transition: background-color 0.3s ease;
    }
    .product-info form input[type="submit"]:hover {
      background-color: #005cbf;
    }
    #iletisim {
      margin-top: 60px;
      background-color: #ffffff;
      padding: 30px 25px;
      border-radius: 12px;
      box-shadow: 0 6px 14px rgba(30, 144, 255, 0.1);
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
    }
    #iletisim h2 {
      margin-top: 0;
      color: #1E3A8A;
      text-align: center;
    }
    #iletisim p {
      font-size: 1rem;
      color: #34495e;
      margin-bottom: 20px;
      text-align: center;
    }
    #iletisim a {
      display: inline-block;
      padding: 12px 24px;
      border-radius: 8px;
      font-weight: 700;
      text-decoration: none;
      font-size: 1.2rem;
      margin: 10px auto;
    }
    .whatsapp {
      background-color: #25D366;
      color: white;
    }
    .instagram {
      background-color: #C13584;
      color: white;
    }
    @media (max-width: 600px) {
      .product-card {
        width: 100%;
        max-width: 320px;
      }
      nav {
        flex-direction: column;
        gap: 10px;
      }
    }
  </style>
</head>
<body>
  <nav>
    <a href="#anasayfa">Ana Sayfa</a>
    <a href="#urunler">Takılar</a>
    <a href="#iletisim">İletişim</a>
  </nav>
  <header class="site-title" id="anasayfa">BERİVAN TAKILAR</header>
  <section id="urunler">
    <h2 class="category-title">Ürünler</h2>
    <h3 class="category-title">Yüzükler</h3>
    <div class="products-container">
      <article class="product-card">
        <div class="product-image">
          <img src="https://images.pexels.com/photos/1374062/pexels-photo-1374062.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=300" alt="Gümüş Yüzük" />
        </div>
        <div class="product-info">
          <h3>Gümüş Yüzük</h3>
          <p>925 ayar el yapımı şık gümüş yüzük.</p>
          <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
            <input type="hidden" name="cmd" value="_xclick" />
            <input type="hidden" name="business" value="senin-paypal-email@example.com" />
            <input type="hidden" name="item_name" value="Gümüş Yüzük" />
            <input type="hidden" name="amount" value="150.00" />
            <input type="hidden" name="currency_code" value="TRY" />
            <input type="submit" value="Satın Al - 150₺" />
          </form>
        </div>
      </article>
    </div>
    <h3 class="category-title">Kolye</h3>
    <div class="products-container">
      <article class="product-card">
        <div class="product-image">
          <img src="https://images.pexels.com/photos/7141377/pexels-photo-7141377.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=300" alt="El Yapımı Kolye" />
        </div>
        <div class="product-info">
          <h3>El Yapımı Kolye</h3>
          <p>Doğal taşlarla tasarlanmış özgün kolye.</p>
          <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
            <input type="hidden" name="cmd" value="_xclick" />
            <input type="hidden" name="business" value="senin-paypal-email@example.com" />
            <input type="hidden" name="item_name" value="El Yapımı Kolye" />
            <input type="hidden" name="amount" value="200.00" />
            <input type="hidden" name="currency_code" value="TRY" />
            <input type="submit" value="Satın Al - 200₺" />
          </form>
        </div>
      </article>
    </div>
    <h3 class="category-title">Bileklik</h3>
    <div class="products-container">
      <article class="product-card">
        <div class="product-image">
          <img src="https://images.pexels.com/photos/4148861/pexels-photo-4148861.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=300" alt="Doğal Taş Bileklik" />
        </div>
        <div class="product-info">
          <h3>Doğal Taş Bileklik</h3>
          <p>Şık ve rahat doğal taş bileklik.</p>
          <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
            <input type="hidden" name="cmd" value="_xclick" />
            <input type="hidden" name="business" value="senin-paypal-email@example.com" />
            <input type="hidden" name="item_name" value="Doğal Taş Bileklik" />
            <input type="hidden" name="amount" value="120.00" />
            <input type="hidden" name="currency_code" value="TRY" />
            <input type="submit" value="Satın Al - 120₺" />
          </form>
        </div>
      </article>
    </div>
  </section>
  <section id="iletisim">
    <h2>İletişim</h2>
    <p>Bize aşağıdaki iletişim kanallarından ulaşabilirsiniz:</p>
    <p><a class="whatsapp" href="https://wa.me/905010361656" target="_blank">WhatsApp ile İletişime Geç</a></p>
    <p><a class="instagram" href="https://www.instagram.com/Bernbnzgl" target="_blank">Instagram'da Takip Et: @Bernbnzgl</a></p>
  </section>
</body>
</html>
