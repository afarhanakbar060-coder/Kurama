<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kelompok 7 - Tulip Informatika</title>
  <style>
    body {
      background: #ffe0ef;
      font-family: Arial, sans-serif;
      color: #5a1a3a;
      margin: 0;
    }

    .kotak {
      border: 2px solid #ff6fb3;
      border-radius: 6px;
      margin: 10px;
      overflow: hidden;
      background: #fff0f7;
    }

    .judul-kotak {
      background: #ffe0ef;
      color: #e91e8c;
      font-weight: bold;
      font-size: 1.1rem;
      padding: 8px 14px;
      border-bottom: 1px solid #ff6fb3;
    }

    .isi { padding: 12px 16px; }

    .hero {
      background: linear-gradient(135deg, #ff6fb3, #ffafd2, #ffd6e7);
      text-align: center;
      padding: 30px 10px 20px;
    }
    .hero h1 {
      font-size: 2rem;
      color: white;
      text-shadow: 0 2px 8px rgba(200,0,100,0.5);
      margin: 0;
    }
    .hero p { color: white; margin: 4px 0 0; font-size: 0.9rem; }

    .logo-wrap {
      text-align: center;
      padding: 16px;
      background: #fff8fc;
    }

    .marquee-bar {
      background: #fff0f7;
      border-top: 1px solid #ffafd2;
      padding: 5px 0;
      overflow: hidden;
    }
    .marquee-dalam {
      display: flex;
      width: max-content;
      animation: jalan 12s linear infinite;
    }
    .marquee-dalam span {
      color: #e91e8c;
      padding: 0 40px;
      white-space: nowrap;
      font-style: italic;
    }
    @keyframes jalan {
      0%   { transform: translateX(0); }
      100% { transform: translateX(-50%); }
    }

    nav { padding: 10px 16px; }
    nav ul { list-style: disc; padding-left: 18px; margin: 0; }
    nav ul li { margin: 3px 0; }
    nav ul li a { color: #e91e8c; font-weight: bold; text-decoration: none; }

    .artikel { margin: 0 10px; padding: 10px 4px; font-size: 0.88rem; line-height: 1.7; }
    .kutipan { text-align: center; color: #e91e8c; font-style: italic; font-weight: bold; margin-top: 8px; }

    ol { padding-left: 20px; line-height: 2; font-size: 0.92rem; }

    .puisi { font-style: italic; line-height: 2; font-size: 0.9rem; color: #7a3050; }
    .sumber { font-size: 0.8rem; margin-bottom: 6px; }

    .thankyou {
      text-align: center;
      padding: 30px 10px;
      background: linear-gradient(135deg, #ffafd2, #ffe0ef);
    }
    .thankyou h2 {
      font-size: 2rem;
      color: #e91e8c;
      letter-spacing: 3px;
    }
  </style>
</head>
<body>

<!-- HEADER -->
<div class="kotak">
  <div class="judul-kotak">Selamat Datang</div>

  <div class="hero">
    <h1>🌷 KELOMPOK 7</h1>
    <p>Mekar, Tumbuh & Bersatu</p>
    <p style="font-size:0.78rem">Filosofi Tulip: Harapan, Pembaruan & Kebersamaan</p>
  </div>

  <div class="logo-wrap">
    <svg width="140" height="140" viewBox="0 0 140 140" xmlns="http://www.w3.org/2000/svg">
      <circle cx="70" cy="70" r="65" fill="none" stroke="#2d7a5e" stroke-width="3"/>
      <ellipse cx="42" cy="95" rx="14" ry="22" fill="#4caf50" transform="rotate(-30 42 95)"/>
      <ellipse cx="98" cy="95" rx="14" ry="22" fill="#4caf50" transform="rotate(30 98 95)"/>
      <rect x="67" y="85" width="6" height="28" fill="#2d7a5e" rx="3"/>
      <ellipse cx="50" cy="68" rx="12" ry="20" fill="#e8734a" transform="rotate(-20 50 68)"/>
      <ellipse cx="90" cy="68" rx="12" ry="20" fill="#e8734a" transform="rotate(20 90 68)"/>
      <ellipse cx="70" cy="58" rx="13" ry="24" fill="#f4a261"/>
      <text x="70" y="80" text-anchor="middle" font-size="22" font-weight="bold" fill="#2d7a5e">7</text>
      <text x="70" y="118" text-anchor="middle" font-size="9" font-weight="bold" fill="#2d7a5e">KELOMPOK 7</text>
      <text x="70" y="129" text-anchor="middle" font-size="7" fill="#5a9e80">Mekar, Tumbuh & Bersatu</text>
    </svg>
  </div>

  <div class="marquee-bar">
    <div class="marquee-dalam">
      <span>✿ desain by farhan ✿ desain by farhan ✿ desain by farhan ✿ desain by farhan ✿</span>
      <span>✿ desain by farhan ✿ desain by farhan ✿ desain by farhan ✿ desain by farhan ✿</span>
    </div>
  </div>
</div>

<!-- NAV -->
<div class="kotak">
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Design</a></li>
      <li><a href="#">Product</a></li>
    </ul>
  </nav>
</div>

<!-- ANGGOTA -->
<div class="kotak">
  <div class="judul-kotak">👥 Anggota</div>
  <div class="isi">
    <ol>
      <li>Aira Putri Kayana (2)</li>
      <li>Alya Adzra Zakiyyah (3)</li>
      <li>Dwi Arthur Siva (12)</li>
      <li>Farhan Akbar (16)</li>
    </ol>
  </div>
</div>

<!-- JOBDESK -->
<div class="kotak">
  <div class="judul-kotak">💼 Our Jobdesk</div>
  <div class="isi">
    <ol>
      <li>Web Programmer : Farhan Akbar</li>
      <li>Apps Programmer : Aira Putri Kayana</li>
      <li>Content Writer : Alya Adzra Zakiyyah</li>
      <li>Graphic Designer : Dwi Arthur Siva</li>
    </ol>
  </div>
</div>

<!-- MAKNA LOGO -->
<div class="kotak">
  <div class="judul-kotak">🌷 Makna Logo</div>
  <div class="isi" style="font-size:0.88rem; line-height:1.7">
    Konsep Tulip-Angka: Kelopak tulip dibentuk dari siluet angka '7' yang disederhanakan.
    Batang tulip dapat memanjang ke bawah membentuk ekor angka tujuh.
  </div>
</div>

<!-- INSPIRASI -->
<div class="kotak">
  <div class="judul-kotak">💡 Inspirasi</div>
  <div class="isi" style="font-size:0.88rem; line-height:1.7">
    Tulip "Kelahiran Kembali": Tulip mekar sempurna yang melambangkan harapan baru,
    dikelilingi 7 dedaunan kecil. Cocok untuk tim yang berfokus pada pertumbuhan atau ide baru.
  </div>
</div>

<!-- ARTIKEL -->
<div class="artikel">
  Perubahan iklim adalah perubahan jangka panjang dalam suhu dan pola cuaca iklim dalam
  periode waktu yang sangat lama. Bentuk perubahan iklim berkaitan dengan perubahan
  kebiasaan cuaca atau perubahan persebaran kejadian cuaca. Penyebab utama terjadinya
  perubahan iklim yaitu pemanasan global.
  <div class="kutipan">"Bumi yang Menjerit"</div>
</div>


<!-- PUISI -->
<div class="kotak" style="margin-top:10px">
  <div class="isi">
    <div class="sumber">oleh chat gpt</div>
    <div class="puisi">
      Bumi dulu bernyanyi,<br>
      dengan irama angin dan daun menari,<br>
      namun kini suaranya parau,<br>
      tercekik asap yang kita buat sendiri.
    </div>
  </div>
</div>

<!-- THANK YOU -->
<div class="kotak">
  <div class="thankyou">
    <h2>✨ THANK YOU ✨</h2>
    <p style="color:#c2185b; margin-top:6px; font-size:0.85rem">Tulip Informatika — Kelompok 7</p>
  </div>
</div>

</body>
</html>
