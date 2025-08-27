<!doctype html>

<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Digital Culture</title>
  <style>
    :root{ --bg:#f5f7fa; --accent1:#0077ff; --accent2:#00c6ff; --text:#333 }
    *{ box-sizing: border-box }
    html,body{ height:100% }
    body{
      font-family: Arial, Helvetica, sans-serif;
      margin:0; padding:0;
      background: var(--bg);
      color: var(--text);
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }
    header{
      background: linear-gradient(135deg, var(--accent1), var(--accent2));
      color: #fff; text-align:center; padding:2.5rem 1rem;
    }
    header h1{ margin:0; font-size: clamp(1.5rem, 3.5vw, 2.5rem) }
    header p{ margin:0.5rem 0 0; font-size:1.05rem; opacity:.95 }
    main{ max-width:900px; margin:2rem auto; padding:0 1rem }
    section{ background:#fff; border-radius:12px; padding:1.5rem; margin-bottom:1.5rem; box-shadow:0 6px 20px rgba(0,0,0,.06) }
    section h2{ color: var(--accent1); margin-top:0 }
    section img{ width:100%; height:auto; border-radius:8px; margin:1rem 0; display:block }
    footer{ background:#333; color:#fff; text-align:center; padding:1rem; margin-top:1rem }
    .container-row{ display:flex; gap:1rem; flex-wrap:wrap }
    .card{ flex:1 1 240px; padding:1rem; border-radius:8px; background:#fafafa }
    @media (max-width:480px){ header{ padding:1.5rem } main{ margin:1rem } }
  </style>
</head>
<body>
  <header>
    <h1>Digital Culture</h1>
    <p>Exploring how technology shapes our society, creativity, and future</p>
  </header>  <main>
    <section>
      <h2>🌐 What is Digital Culture?</h2>
      <p>Digital culture refers to the ways people use digital technologies to create, communicate, and organize everyday life — including social media, memes, online communities, digital art, and remote work practices.</p>
      <img src="https://source.unsplash.com/900x400/?technology,digital" alt="Digital technology illustration">
    </section><section>
  <h2>How technology shapes society</h2>
  <ul>
    <li><strong>Communication</strong>: instant global connections and new norms.</li>
    <li><strong>Creativity</strong>: digital tools lower the barrier to publish and collaborate.</li>
    <li><strong>Economy</strong>: remote work, gig platforms, and new business models.</li>
  </ul>
</section>

<section>
  <h2>Examples &amp; further reading</h2>
  <div class="container-row">
    <div class="card">
      <h3>Memes &amp; identity</h3>
      <p>Memes act as cultural shorthand and are a rapid form of social commentary.</p>
    </div>
    <div class="card">
      <h3>Online communities</h3>
      <p>Communities on forums, Discord, and other platforms shape tastes, knowledge, and politics.</p>
    </div>
  </div>
</section>

  </main>  <footer>
    <p>&copy; <span id="year"></span> Digital Culture — Created for BCA 1st Sem</p>
  </footer>  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script></body>
</html>
