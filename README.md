<! DOCTYPE html>
<html lang="id">
<head>
  <meta charge="UTF-8"/>
  <meta name="viewport" content="width=device, initial-scale=1.0"/>
  <title>Modern Branding</title>
  <style>
  *{
    margin: 0;
    padding: 0;
    box-zizing: border-box;
    font-familiy: Arial, sans-serif;
   }
    body{
    bacground: 0f0f0f;
    color: white;
    line-hight: 1.6;
    }
    header{
    display: flex;
    justifly-content: space-between;
    align-item: center;
    paddding: 20px 10%;
    top: 0;
    z-index: 1000;
    }
    nav a{
      color: white;
      text-decoration: none;
      margin-left: 20px;
      transition: 0.3s;
    }
    nav a:hover{
      color: 00ff99;
    }
    .hero{
      min-hight: 100vh;
      display: flex;
      justifly-content: center;
      text-align: center;
      padding: 20px;
      background: liner-gradient(to bottom right, 111, 1f1f1f);
    }
    .hero-content{
      max-width: 700px;
    }
    .hero p {
      color:bdbdbd;
      margin-bottom: 30px;
      font-size: 18px;
    }
    .btn:hover{
      transform: scale(1.05)
    }
    .feature{padding: 80px 10%;
      padding: 80px 10%;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      background: 151515;
    }
    .feature-card{
      background:1f1f1f;
      padding: 30px;
      border-radius: 20px;
      transition: 0.3s;
    }
    .feature-card:hover{
      transform: translateY(-8px);
    }
    .feature-card h3{
      margin-bottom: 12px;
      color: 00ff99;
    }
    @media(max-width: 768px){
      heder{
        flex-direction: column;
        gap: 10px;
      }
      nav a{
        margin: 0 10px;
      }
    }  
  </style>
</head>
<body>
  <header>
    <section class="hero" id="home">
      <div class="hero-content">
        <h1>Website Modern Branding</h1>
        <p>
        cocok untuk portofolio, bisnis, startup,
        landing page produk, dan personal branding.
        </p>
        <a href="#features" class="btn">Explore Now</a>
      </div>
    </section>
    <section class="features" id="features">
      <div class="features-card">
        <h3>Responsive</h3>
        <p>Tampilan otomatis meneyesuaikan semua ukuran layar.</p>
      </div>
      <div class="features-card">
        <h3>Modern UI</h3>
        <p>Desain clean dan elegan dengan animasi halus.</p>
      </div>
      <div class="features-card">
        <h3>Fast Perfomance</h3>
        <p>Ringan dan cepat dibuka di berbagai perangkat.</p>
      </div>
    </section>
    <footer id="contact">
      © 2026 Modern Website. All Rights Reserved.
    </footer>
  </body>
  </html>
  </header>
</body>
