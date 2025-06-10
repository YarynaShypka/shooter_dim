<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Shooter Dim – Котеджі для відпочинку</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --main-color: #229ED9;
      --bg-color: #f9f9f9;
      --text-color: #333;
      --accent: #007aff;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }
    body { font-family: 'Inter', sans-serif; background: var(--bg-color); color: var(--text-color); line-height: 1.6; }
    header { background: white; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 1000; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    header h1 { color: var(--main-color); font-size: 1.5rem; }
    nav a { margin-left: 1.5rem; color: var(--text-color); text-decoration: none; font-weight: 500; }
    .hero { background: url('https://via.placeholder.com/1400x500?text=Shooter+Dim') center/cover no-repeat; padding: 100px 2rem; text-align: center; color: white; }
    .hero h2 { font-size: 2.5rem; margin-bottom: 1rem; }
    .hero a { padding: 0.8rem 2rem; background: var(--accent); color: white; text-decoration: none; border-radius: 5px; font-weight: 600; }

    section { padding: 3rem 2rem; max-width: 1100px; margin: auto; }
    .section-title { font-size: 2rem; margin-bottom: 1.5rem; color: var(--main-color); }

    .cottages { display: grid; gap: 2rem; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); }
    .card { background: white; border-radius: 10px; padding: 1rem; box-shadow: 0 2px 10px rgba(0,0,0,0.05); }
    .card h3 { margin-bottom: 0.5rem; }
    .card ul { list-style: none; padding-left: 1rem; }
    .card ul li::before { content: '• '; color: var(--accent); }
    .btn { display: inline-block; margin-top: 1rem; padding: 0.5rem 1.5rem; background: var(--accent); color: white; text-decoration: none; border-radius: 5px; }

    .reviews blockquote { font-style: italic; background: white; padding: 1rem; border-left: 4px solid var(--accent); margin-bottom: 1rem; }

    .contact form { display: grid; gap: 1rem; max-width: 500px; }
    .contact input, .contact textarea { padding: 0.8rem; border: 1px solid #ccc; border-radius: 5px; width: 100%; }
    .contact button { background: var(--main-color); color: white; padding: 0.8rem; border: none; border-radius: 5px; font-weight: bold; cursor: pointer; }

    footer { background: #222; color: white; text-align: center; padding: 2rem; font-size: 0.9rem; }

    @media(max-width: 600px) {
      nav a { margin-left: 0.5rem; font-size: 0.9rem; }
      .hero h2 { font-size: 1.8rem; }
    }
  </style>
</head>
<body>

<header>
  <h1>Shooter Dim</h1>
  <nav>
    <a href="#about">Про нас</a>
    <a href="#cottages">Котеджі</a>
    <a href="#reviews">Відгуки</a>
    <a href="#contact">Контакти</a>
  </nav>
</header>

<section class="hero">
  <h2>В об’єднанні з природою</h2>
  <a href="https://t.me/yourbotlink">Забронювати</a>
</section>

<section id="about">
  <h2 class="section-title">Про нас</h2>
  <p>Shooter_dim — це не просто оренда, це емоція. Тут ви відчуєте себе в іншому ритмі життя, ближче до себе і до природи. Ми поєднали сучасні технології та екологічні матеріали, щоб створити простір, де кожна деталь продумана — від освітлення до зручних меблів.</p>
</section>

<section id="cottages">
  <h2 class="section-title">Котеджі</h2>
  <div class="cottages">
    <div class="card">
      <h3>Shooter Dim (Lake)</h3>
      <ul>
        <li>105 м², 3 кімнати</li>
        <li>1 санвузол, Wi-Fi, TV</li>
        <li>Кухня, мангал, посуд</li>
      </ul>
      <a href="https://t.me/yourbotlink" class="btn">Забронювати</a>
    </div>
    <div class="card">
      <h3>Shooter Dim (Forest)</h3>
      <ul>
        <li>105 м², 3 кімнати</li>
        <li>1 санвузол, світломузика</li>
        <li>Рушники, фен, гігієна</li>
      </ul>
      <a href="https://t.me/yourbotlink" class="btn">Забронювати</a>
    </div>
  </div>
</section>

<section id="reviews">
  <h2 class="section-title">Відгуки</h2>
  <div class="reviews">
    <blockquote>“Свято у вашому будинку вийшло дуже яскравим. Дякуємо від душі!”</blockquote>
    <blockquote>“Будинок чудовий, затишний, сервіс на найвищому рівні. Дуже атмосферно!”</blockquote>
    <blockquote>“Природа, озеро, спокій — це був ідеальний відпочинок!”</blockquote>
  </div>
</section>

<section id="contact" class="contact">
  <h2 class="section-title">Контакти</h2>
  <p>С. Суховоля, Львівська обл., вул. Рибацька 28</p>
  <p>Тел: <a href="tel:+380964273008">+380 96 427 30 08</a> | <a href="tel:+380630631462">+380 63 063 14 62</a></p>
  <form>
    <input type="text" placeholder="Ваше ім’я" required>
    <input type="tel" placeholder="Номер телефону" required>
    <textarea placeholder="Повідомлення"></textarea>
    <button type="submit">Підтвердити</button>
  </form>
</section>

<footer>
  &copy; 2025 Shooter Dim — Усі права захищені
</footer>

<script>
  // Плавне закриття форми при сабміті (можна підключити backend через emailJS або Google Forms)
  document.querySelector('form').addEventListener('submit', e => {
    e.preventDefault();
    alert('Дякуємо! Ми з вами зв’яжемось найближчим часом.');
    e.target.reset();
  });
</script>

</body>
</html>
