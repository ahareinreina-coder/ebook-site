<!DOCTYPE html>
<html lang="mn">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Өсөлтийн нууц ба Өндөр болох нууц | EBook</title>
    <meta name="description" content="Өсөлтийн нууц болон Өндөр болох нууц EBook багц. Хувь хүний өсөлт, өндөр болох боломж, дасгал, хооллолтын зөвлөмжүүдийг нэг дороос.">
    <meta name="robots" content="index, follow">
    <meta name="googlebot" content="index, follow">
    <link rel="canonical" href="https://yourdomain.com/">
    <meta property="og:type" content="website">
    <meta property="og:title" content="Өсөлтийн нууц ба Өндөр болох нууц | EBook">
    <meta property="og:description" content="Өсөлт, өндөр болох боломж, дасгал, хооллолтын талаарх EBook багц.">
    <meta property="og:url" content="https://yourdomain.com/">
    <meta name="twitter:card" content="summary">

    <style>
      :root {
        --bg: #f7f3ee;
        --card: #ffffff;
        --primary: #1d4ed8;
        --primary-dark: #183ea7;
        --accent: #f59e0b;
        --text: #1f2937;
        --muted: #6b7280;
        --success: #0f766e;
        --shadow: 0 18px 45px rgba(15, 23, 42, 0.12);
      }

      * { box-sizing: border-box; }

      body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
        background: linear-gradient(135deg, #f8fafc 0%, #fff7ed 100%);
        color: var(--text);
        line-height: 1.6;
      }

      .container {
        max-width: 1100px;
        margin: 0 auto;
        padding: 24px;
      }

      .topbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 18px 0;
      }

      .brand {
        font-size: 1.5rem;
        font-weight: 700;
        color: var(--primary-dark);
      }

      .nav {
        display: flex;
        gap: 18px;
        font-size: 0.95rem;
        color: var(--muted);
      }

      .hero {
        background: linear-gradient(135deg, rgba(29, 78, 216, 0.12), rgba(245, 158, 11, 0.12));
        border: 1px solid rgba(29, 78, 216, 0.08);
        border-radius: 28px;
        box-shadow: var(--shadow);
        padding: 42px 32px;
        display: grid;
        grid-template-columns: 1.3fr 0.9fr;
        gap: 30px;
        align-items: center;
      }

      .eyebrow {
        display: inline-block;
        background: rgba(29, 78, 216, 0.08);
        color: var(--primary-dark);
        border-radius: 999px;
        padding: 8px 14px;
        font-size: 0.8rem;
        font-weight: 700;
        letter-spacing: 0.04em;
      }

      h1 {
        font-size: clamp(2.2rem, 4vw, 4rem);
        line-height: 1.1;
        margin: 18px 0 12px;
      }

      .lead {
        font-size: 1.08rem;
        color: var(--muted);
        margin-bottom: 22px;
      }

      .price-box {
        display: inline-flex;
        align-items: baseline;
        gap: 14px;
        flex-wrap: wrap;
        background: rgba(15, 118, 110, 0.08);
        border: 1px solid rgba(15, 118, 110, 0.12);
        border-radius: 18px;
        padding: 16px 18px;
        margin-bottom: 24px;
      }

      .old-price {
        font-size: 1.2rem;
        text-decoration: line-through;
        color: var(--muted);
      }

      .new-price {
        font-size: 2.2rem;
        font-weight: 800;
        color: var(--success);
      }

      .actions {
        display: flex;
        gap: 14px;
        flex-wrap: wrap;
      }

      .button {
        text-decoration: none;
        display: inline-block;
        border: none;
        border-radius: 14px;
        padding: 15px 26px;
        font-weight: 700;
        cursor: pointer;
        transition: 0.2s ease;
      }

      .button.primary {
        background: linear-gradient(135deg, var(--primary), var(--primary-dark));
        color: #fff;
        box-shadow: 0 10px 25px rgba(29, 78, 216, 0.25);
      }

      .button.secondary {
        background: #fff;
        color: var(--text);
        border: 1px solid rgba(15, 23, 42, 0.09);
      }

      .button:hover {
        transform: translateY(-1px);
      }

      .book-card {
        background: #fff;
        border-radius: 24px;
        box-shadow: var(--shadow);
        padding: 22px;
        border: 1px solid rgba(31, 41, 55, 0.08);
      }

      .book-cover {
        background: linear-gradient(135deg, #1d4ed8, #0f172a 100%);
        border-radius: 22px;
        min-height: 380px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: #fff;
        padding: 28px;
        text-align: center;
      }

      .book-cover-inner {
        background: rgba(255,255,255,0.08);
        border: 1px solid rgba(255,255,255,0.14);
        border-radius: 18px;
        padding: 26px 18px;
        width: 100%;
      }

      .book-title {
        font-size: 2rem;
        margin: 0 0 8px;
      }

      .book-meta {
        font-size: 0.95rem;
        opacity: 0.9;
      }

      .section {
        padding: 54px 0 0;
      }

      .section-title {
        font-size: clamp(1.8rem, 3vw, 2.6rem);
        margin: 0 0 18px;
        text-align: center;
      }

      .features {
        display: grid;
        grid-template-columns: repeat(3, minmax(0, 1fr));
        gap: 20px;
        margin-top: 28px;
      }

      .feature {
        background: var(--card);
        border-radius: 22px;
        padding: 26px 22px;
        border: 1px solid rgba(15, 23, 42, 0.06);
        box-shadow: 0 12px 24px rgba(15, 23, 42, 0.04);
      }

      .feature-icon {
        width: 52px;
        height: 52px;
        border-radius: 14px;
        background: linear-gradient(135deg, #dbeafe, #fef3c7);
        display: flex;
        align-items: center;
        justify-content: center;
        font-size: 1.6rem;
        margin-bottom: 12px;
      }

      .feature h3 {
        margin: 0 0 8px;
        font-size: 1.2rem;
      }

      .feature p {
        margin: 0;
        color: var(--muted);
      }

      .payment {
        background: linear-gradient(135deg, #fffaf1, #f0fdf4);
        border-radius: 28px;
        padding: 32px 26px;
        border: 1px solid rgba(15, 118, 110, 0.08);
        margin-top: 30px;
      }

      .payment-grid {
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 16px;
        align-items: center;
      }

      .payment-box {
        background: #fff;
        padding: 18px 20px;
        border-radius: 18px;
        border: 1px solid rgba(15, 23, 42, 0.05);
      }

      .payment-box strong {
        display: block;
        margin-bottom: 8px;
        font-size: 1.1rem;
      }

      .payment-box small {
        display: block;
        color: var(--muted);
        margin-top: 6px;
        font-size: 0.82rem;
      }

      .payment-note {
        margin-top: 14px;
        color: var(--muted);
        font-weight: 700;
      }

      .detail-grid {
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 20px;
        margin-top: 28px;
      }

      .detail-card {
        background: #fff;
        border-radius: 24px;
        border: 1px solid rgba(15, 23, 42, 0.06);
        box-shadow: 0 12px 24px rgba(15, 23, 42, 0.04);
        padding: 26px 22px;
      }

      .detail-label {
        display: inline-block;
        font-size: 0.78rem;
        font-weight: 700;
        letter-spacing: 0.08em;
        text-transform: uppercase;
        color: var(--primary-dark);
        background: rgba(29, 78, 216, 0.08);
        border-radius: 999px;
        padding: 8px 12px;
        margin-bottom: 14px;
      }

      .detail-card h3 {
        margin: 0 0 12px;
        font-size: 1.35rem;
      }

      .detail-list {
        margin: 0;
        padding-left: 18px;
        color: var(--muted);
        line-height: 1.9;
      }

      .footer {
        text-align: center;
        color: var(--muted);
        font-size: 0.95rem;
        padding: 40px 0 60px;
      }

      @media (max-width: 800px) {
        .hero {
          grid-template-columns: 1fr;
        }

        .features {
          grid-template-columns: 1fr;
        }

        .payment-grid {
          grid-template-columns: 1fr;
        }

        .nav {
          display: none;
        }
      }
    </style>
  
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "Product",
      "name": "Өсөлтийн нууц ба Өндөр болох нууц EBook",
      "description": "Өсөлтийн нууц болон Өндөр болох нууц EBook багц.",
      "offers": {
        "@type": "Offer",
        "priceCurrency": "MNT",
        "price": "29900",
        "availability": "https://schema.org/InStock"
      }
    }
    </script>
  </head>
  <body>
    <div class="container">
      <header class="topbar" aria-label="Үндсэн цэс">
        <div class="brand">EBook</div>
        <nav class="nav" aria-label="Навигаци">
          <span>Давуу тал</span>
          <span>Төлбөр</span>
          <span>Холбоо барих</span>
        </nav>
      </header>

      <main>
        <section class="section" aria-label="EBook тухай">
          <h2 class="section-title">Өсөлтийн нууц ба Өндөр болох нууц EBook</h2>
          <p class="lead" style="max-width:850px; margin:0 auto; text-align:center;">
            Өөрийгөө хөгжүүлэх, хувь хүний өсөлт, өндөр болох боломж, дасгал хөдөлгөөн,
            хооллолтын талаарх мэдээллийг нэг дороос авах EBook багц.
          </p>
        </section>

        <section class="hero">
          <div>
            <span class="eyebrow">Бүтэн PDF хувилбар</span>
            <h1>Өсөлт, амжилт, өөрийгөө сайжруулахад зориулагдсан EBook</h1>
            <p class="lead">
              “Өсөлтийн нууц” болон “Өндөр болох нууц”-ыг нэг дороос уншиж, амьдралаа сайжруулахад
ажиггүй алхам хийж эхлээрэй.
            </p>

            <div class="price-box">
              <span class="old-price">49,900₮</span>
              <span class="new-price">29,900₮</span>
            </div>

            <div class="actions">
              <a href="#payment" class="button primary">Худалдан авах</a>
              <a href="#features" class="button secondary">Давуу талууд</a>
            </div>
          </div>

          <div class="book-card">
            <div class="book-cover">
              <div class="book-cover-inner">
                <div class="book-title">EBook Package</div>
                <div class="book-meta">Өсөлт • Өндөр амжилт • Сэтгэлзүйн өөрчлөлт</div>
              </div>
            </div>
          </div>
        </section>

        <section class="detail-grid">
          <div class="detail-card">
            <div class="detail-label">Багцад юу багтана</div>
            <h3>Үнэлж баршгүй мэдээлэл</h3>
            <ul class="detail-list">
              <li>Өөрийгөө хөгжүүлэх практик алхмууд</li>
              <li>Амжилтанд хүрэхийн тулд хэрэгтэй сэтгэл зүйн арга техник</li>
              <li>Өдөр тутмын дасгал, хооллолт, хэвшлийг сайжруулах зөвлөмж</li>
              <li>Зорилго тодорхойлох, үр дүнг хэмжих систем</li>
            </ul>
          </div>

          <div class="detail-card">
            <div class="detail-label">Хэрхэн ажиллах вэ</div>
            <h3>3 алхмаар эхлээрэй</h3>
            <ul class="detail-list">
              <li>Сурах: үндсэн ойлголт, аргуудыг ойлгох</li>
              <li>Хэрэгжүүлэх: өдөр тутмын хэвшилд оруулах</li>
              <li>Өсөх: үр дүнгээ харж, замаа сайжруулах</li>
            </ul>
          </div>
        </section>

        <section class="section" id="features">
          <h2 class="section-title">Давуу талууд</h2>
          <div class="features">
            <div class="feature">
              <div class="feature-icon">📘</div>
              <h3>“Өсөлтийн нууц”</h3>
              <p>Ажлынхаа бүтээмж, хувь хүний өсөлтийг нэмэгдүүлэх практик зөвлөмж, стратеги.</p>
            </div>
            <div class="feature">
              <div class="feature-icon">🚀</div>
              <h3>“Өндөр болох нууц”</h3>
              <p>Өөрийн хэр өндөр болох боломжтойг шалгах, зорилгоо тодорхойлох боломжийг олгоно.</p>
            </div>
            <div class="feature">
              <div class="feature-icon">🧠</div>
              <h3>Шинжлэх ухаан дээр суурилсан</h3>
              <p>Зөвлөгөө, дасгал, хооллолтын системийг нэг дор цэгцэлсэн ойлголттойгоор танилцуулна.</p>
            </div>
          </div>

          <div class="payment" id="payment">
            <h2 class="section-title" style="text-align:left; margin-bottom:16px;">Төлбөр</h2>
            <div class="payment-grid">
              <div class="payment-box">
                <strong>Golomt Bank</strong>
                <div>14001500 3055212716</div>
                <small>Дансны дугаар</small>
              </div>
            </div>

            <div class="payment-note">Гүйлгээний утга: discord нэр</div>
            <div class="payment-note">Утас: 99593675</div>

            <div class="actions" style="margin-top: 20px; justify-content:flex-start;">
              <a href="tel:99593675" class="button primary">Утаслах</a>
            </div>
          </div>
        </section>
      </main>

      <footer class="footer">
        © 2025 EBook Package · Хямд, шууд эхлэх хамгийн зөв сонголт
      </footer>
    </div>
  </body>
</html>
