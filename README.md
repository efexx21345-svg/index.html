<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>5 Ayımız ♡ Seninle Her Şey Daha Güzel</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    
    body {
      font-family: 'Segoe UI', system-ui, sans-serif;
      background: linear-gradient(135deg, #0d001a, #1a0033, #2a004d);
      color: #f0e6ff;
      min-height: 100vh;
      overflow-x: hidden;
      position: relative;
    }

    /* Yıldız efekti (daha doğal olsun) */
    .stars {
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      pointer-events: none;
      background: transparent;
      z-index: -1;
    }
    .star {
      position: absolute;
      background: white;
      border-radius: 50%;
      animation: twinkle 5s infinite alternate;
      opacity: 0.5;
      box-shadow: 0 0 8px rgba(255,255,255,0.8);
    }
    @keyframes twinkle {
      0% { opacity: 0.3; transform: scale(0.7); }
      100% { opacity: 0.9; transform: scale(1.2); }
    }

    header {
      text-align: center;
      padding: 100px 20px 50px;
    }

    h1 {
      font-size: 5rem;
      color: #d7b4ff;
      text-shadow: 0 0 40px rgba(215,180,255,0.7);
      margin-bottom: 0.1em;
      letter-spacing: -2px;
    }

    .subtitle {
      font-size: 1.8rem;
      color: #c9aaff;
      opacity: 0.95;
      margin: 15px 0 50px;
    }

    .heart {
      color: #ff6bcb;
      font-size: 1.2em;
      animation: beat 1.5s infinite;
    }
    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    main {
      max-width: 900px;
      margin: 0 auto;
      padding: 0 20px 80px;
    }

    .card {
      background: rgba(30, 10, 60, 0.4);
      border-radius: 24px;
      padding: 45px;
      margin: 35px 0;
      border: 1px solid rgba(200, 160, 255, 0.25);
      backdrop-filter: blur(15px);
      box-shadow: 0 10px 40px rgba(0,0,0,0.5);
    }

    .card h2 {
      color: #e0c3ff;
      font-size: 2.4rem;
      margin-bottom: 1.5rem;
      text-align: center;
    }

    .letter {
      font-size: 1.22rem;
      line-height: 1.9;
      text-align: center;
      color: #e8deff;
    }

    .date {
      font-size: 1.5rem;
      color: #b19cd9;
      text-align: center;
      margin: 35px 0;
      font-style: italic;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin: 50px 0;
    }

    .gallery img {
      width: 300px;
      height: 300px;
      object-fit: cover;
      border-radius: 20px;
      border: 2px solid rgba(255,255,255,0.15);
      transition: all 0.5s ease;
    }

    .gallery img:hover {
      transform: scale(1.08);
      box-shadow: 0 0 30px rgba(200,140,255,0.5);
    }

    footer {
      text-align: center;
      padding: 60px 20px;
      font-size: 1.1rem;
      opacity: 0.8;
      border-top: 1px solid rgba(200,160,255,0.2);
    }

    /* Müzik butonu */
    #musicControl {
      position: fixed;
      bottom: 30px;
      right: 30px;
      z-index: 1000;
      background: rgba(167, 139, 250, 0.5);
      color: white;
      border: none;
      padding: 14px 24px;
      border-radius: 50px;
      cursor: pointer;
      backdrop-filter: blur(12px);
      font-size: 1.1rem;
      box-shadow: 0 5px 20px rgba(0,0,0,0.4);
      transition: all 0.4s;
    }

    #musicControl:hover {
      background: rgba(167, 139, 250, 0.8);
      transform: scale(1.08);
    }

    @media (max-width: 600px) {
      h1 { font-size: 3.5rem; }
      .subtitle { font-size: 1.4rem; }
      .card { padding: 30px; }
      .gallery img { width: 100%; height: auto; }
    }
  </style>
</head>
<body>

  <div class="stars"></div>

  <header>
    <h1>5 Ay ♡</h1>
    <p class="subtitle">Seninle geçen her an <span class="heart">daha da</span> güzel oluyor</p>
  </header>

  <main>
    <div class="card">
      <h2>Sevgilim,</h2>
      <p class="letter">
        Bugün tam 5 ay oldu.<br><br>
        Sanki dün gibi… ama bir yandan da sanki ömür boyu yan yanayız.<br>
        Seninle kahkaha atmak, gece yarısı saçmalamak, en kötü günümde bile içimi ısıtan o gülümsemen…<br><br>
        
        <strong>Teşekkür ederim</strong> bana kendimi bu kadar değerli hissettirdiğin için.<br>
        <strong>Teşekkür ederim</strong> her şeye rağmen yanımda olduğun için.<br><br>
        
        Daha nice 5 aylara, 5 yıllara… ve inşallah sonsuza kadar seninle.
      </p>
      <p class="date">Mart 2026 – ilk günümüzden bugüne ♡</p>
    </div>

    <div class="card" style="text-align:center;">
      <h2>Biraz da anılarımızdan...</h2>
      <div class="gallery">
        <!-- Kendi fotoğraflarını buraya ekle (imgur linki vs.) -->
        <img src="https://picsum.photos/300/300?random=1" alt="Anı 1">
        <img src="https://picsum.photos/300/300?random=2" alt="Anı 2">
        <img src="https://picsum.photos/300/300?random=3" alt="Anı 3">
        <img src="https://picsum.photos/300/300?random=4" alt="Anı 4">
      </div>
      <p style="margin-top:25px; opacity:0.85; font-style:italic;">
        (iyiki varsın bebeğim ♡)
      </p>
    </div>

    <div class="card" style="text-align:center;">
      <h2>Sana sözüm var</h2>
      <p class="letter" style="font-size:1.3rem;">
        Seni her zaman dinleyeceğim.<br>
        Seni her zaman anlayacağım (ya da en azından elimden geleni yapacağım 😊).<br>
        Ve en önemlisi… seni hep seveceğim.<br><br>
        <strong>5 ay daha değil… sonsuza kadar.</strong>
      </p>
    </div>
  </main>

  <footer>
    Seninle her şey daha anlamlı ♡ Mart 2026
  </footer>

  <!-- Romantik arka plan müziği (güncel royalty-free piyano parçası - Pixabay benzeri) -->
  <audio id="bgMusic" loop>
    <source src="https://cdn.pixabay.com/download/audio/2024/05/15/audio_8f9d2e3f4a.mp3?filename=romantic-piano-ambient-2024.mp3" type="audio/mpeg">
    Tarayıcınız ses oynatmayı desteklemiyor.
  </audio>

  <!-- Müzik kontrol butonu -->
  <button id="musicControl">🎵 Müziği Aç ♡</button>

  <script>
    // Rastgele yıldızlar (daha yumuşak)
    const starsContainer = document.querySelector('.stars');
    for (let i = 0; i < 100; i++) {
      const star = document.createElement('div');
      star.className = 'star';
      const size = Math.random() * 3 + 1;
      star.style.width = star.style.height = size + 'px';
      star.style.left = Math.random() * 100 + '%';
      star.style.top = Math.random() * 100 + '%';
      star.style.animationDelay = Math.random() * 6 + 's';
      starsContainer.appendChild(star);
    }

    // Müzik kontrolü
    const music = document.getElementById('bgMusic');
    const btn = document.getElementById('musicControl');

    btn.addEventListener('click', () => {
      if (music.paused) {
        music.volume = 0.3;
        music.play().catch(e => console.log("Oynatma hatası:", e));
        btn.textContent = '🎵 Müziği Kapat ♡';
      } else {
        music.pause();
        btn.textContent = '🎵 Müziği Aç ♡';
      }
    });

    // İlk tıklamada otomatik başlat (mobil için)
    document.body.addEventListener('click', () => {
      if (music.paused) {
        music.volume = 0.3;
        music.play().catch(() => {});
      }
    }, { once: true });
  </script>

</body>
</html>
