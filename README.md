<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>KONVEKSI SUMENEP</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #0b0b0b;
      color: white;
      line-height: 1.6;
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.8)),
        url('https://images.unsplash.com/photo-1521572267360-ee0c2909d518?auto=format&fit=crop&w=1200&q=80') center/cover;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 30px;
    }

    .hero-content {
      max-width: 900px;
    }

    .hero h1 {
      font-size: 52px;
      color: gold;
      margin-bottom: 20px;
      font-weight: bold;
    }

    .hero p {
      font-size: 22px;
      margin-bottom: 15px;
    }

    .subtext {
      color: #ddd;
      font-size: 18px;
      margin-bottom: 30px;
    }

    .btn-group {
      margin-top: 30px;
    }

    .btn {
      display: inline-block;
      margin: 10px;
      padding: 14px 28px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn-primary {
      background: gold;
      color: black;
    }

    .btn-primary:hover {
      background: #ffd84d;
    }

    .btn-secondary {
      border: 2px solid gold;
      color: gold;
    }

    .btn-secondary:hover {
      background: gold;
      color: black;
    }

    section {
      padding: 70px 20px;
    }

    .container {
      max-width: 1100px;
      margin: auto;
    }

    h2 {
      text-align: center;
      color: gold;
      margin-bottom: 40px;
      font-size: 36px;
    }

    .about p {
      text-align: center;
      max-width: 850px;
      margin: auto;
      color: #ddd;
      font-size: 18px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
    }

    .card {
      background: #171717;
      border: 1px solid #2a2a2a;
      border-radius: 16px;
      padding: 25px;
      text-align: center;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: gold;
    }

    .card h3 {
      color: gold;
      margin-bottom: 12px;
    }

    .reasons {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 20px;
      text-align: center;
    }

    .reason-box {
      background: #171717;
      border-radius: 16px;
      padding: 25px;
      border: 1px solid #2a2a2a;
    }

    .contact-box {
      background: linear-gradient(135deg, gold, #e0b500);
      color: black;
      text-align: center;
      border-radius: 20px;
      padding: 40px 20px;
    }

    .contact-box h2 {
      color: black;
    }

    .contact-box p {
      font-size: 18px;
      margin-bottom: 20px;
    }

    .social-links a {
      display: inline-block;
      margin: 8px;
      text-decoration: none;
      color: white;
      background: #1c1c1c;
      padding: 12px 20px;
      border-radius: 30px;
      transition: 0.3s;
    }

    .social-links a:hover {
      background: gold;
      color: black;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #050505;
      color: #aaa;
      font-size: 14px;
    }

    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }

      .hero p {
        font-size: 18px;
      }

      .subtext {
        font-size: 16px;
      }

      h2 {
        font-size: 28px;
      }
    }
  </style>
</head>
<body>

  <section class="hero">
    <div class="hero-content">
      <h1>KONVEKSI SUMENEP</h1>
      <p>Jaket • Hoodie • Kaos • Seragam Custom</p>
      <p class="subtext">
        Konveksi profesional di Sumenep untuk kebutuhan organisasi, komunitas, sekolah, kampus, dan usaha.
      </p>
      <div class="btn-group">
        <a class="btn btn-primary" href="https://wa.me/6285944010327">Pesan Sekarang</a>
        <a class="btn btn-secondary" href="#produk">Lihat Produk</a>
      </div>
    </div>
  </section>

  <section class="about">
    <div class="container">
      <h2>Tentang Kami</h2>
      <p>
        KONVEKSI SUMENEP melayani pembuatan berbagai kebutuhan konveksi custom dengan kualitas jahitan rapi,
        bahan pilihan, dan desain yang dapat disesuaikan. Kami siap membantu kebutuhan jaket, hoodie, kaos,
        polo, seragam, hingga bordir dan sablon custom.
      </p>
    </div>
  </section>

  <section id="produk">
    <div class="container">
      <h2>Produk Unggulan</h2>
      <div class="products">
        <div class="card">
          <h3>Jaket Organisasi</h3>
          <p>Cocok untuk kampus, sekolah, komunitas, dan event.</p>
        </div>
        <div class="card">
          <h3>Hoodie Custom</h3>
          <p>Bisa sablon atau bordir sesuai desain yang diinginkan.</p>
        </div>
        <div class="card">
          <h3>Kaos Sablon</h3>
          <p>Untuk promosi, event, komunitas, dan kebutuhan brand.</p>
        </div>
        <div class="card">
          <h3>Seragam Kerja</h3>
          <p>Tampil rapi, profesional, dan nyaman digunakan.</p>
        </div>
        <div class="card">
          <h3>Polo Shirt</h3>
          <p>Model elegan untuk komunitas, instansi, dan perusahaan.</p>
        </div>
        <div class="card">
          <h3>Topi & Bordir</h3>
          <p>Melayani bordir logo dan aksesoris custom.</p>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <h2>Kenapa Harus KONVEKSI SUMENEP?</h2>
      <div class="reasons">
        <div class="reason-box">
          <h3>Jahitan Rapi</h3>
          <p>Setiap produk dibuat dengan hasil rapi dan nyaman dipakai.</p>
        </div>
        <div class="reason-box">
          <h3>Custom Desain</h3>
          <p>Bisa menyesuaikan model, warna, logo, dan kebutuhan pelanggan.</p>
        </div>
        <div class="reason-box">
          <h3>Respon Cepat</h3>
          <p>Admin siap membantu konsultasi dan pemesanan dengan mudah.</p>
        </div>
        <div class="reason-box">
          <h3>Harga Bersaing</h3>
          <p>Kualitas bagus dengan harga yang tetap ramah untuk pelanggan.</p>
        </div>
      </div>
    </div>
  </section>

  <section>
    <div class="container">
      <div class="contact-box">
        <h2>Hubungi Kami</h2>
        <p>Bilapora Barat, Kec. Ganding, Kabupaten Sumenep</p>
        <p><strong>Admin:</strong> +62 859-4401-0327</p>
        <a class="btn btn-primary" href="https://wa.me/6285944010327">Chat WhatsApp</a>

        <div class="social-links" style="margin-top: 25px;">
          <a href="https://www.instagram.com/konveksisumenep?igsh=MWpkZXRvbmFpMjJzZQ==">Instagram</a>
          <a href="https://www.tiktok.com/@konveksisumenep?_r=1&_t=ZS-94TPsW25qx3">TikTok</a>
          <a href="https://www.facebook.com/share/18NUp2vTZE/">Facebook</a>
          <a href="https://share.google/rO0W6z72tSiuVUL31">Lokasi</a>
        </div>
      </div>
    </div>
  </section>

  <footer>
    © 2026 KONVEKSI SUMENEP — Konveksi Jaket, Hoodie, Kaos, dan Seragam Custom
  </footer>

</body>
</html>
