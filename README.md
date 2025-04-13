<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Disneyland World</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff8f0;
    }

    .sidebar {
      height: 100vh;
      background-color: #ff6f61;
      color: white;
      padding: 1.5rem;
      position: fixed;
      width: 250px;
    }

    .sidebar h4 {
      font-weight: bold;
      margin-bottom: 2rem;
    }

    .sidebar a {
      color: white;
      display: block;
      margin: 0.7rem 0;
      text-decoration: none;
    }

    .sidebar a:hover {
      text-decoration: underline;
    }

    .content {
      margin-left: 270px;
      padding: 2rem;
    }

    .hero {
      background: url('https://wallpaperaccess.com/full/233358.jpg') no-repeat center center;
      background-size: cover;
      border-radius: 10px;
      color: white;
      padding: 3rem;
      margin-bottom: 2rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    .hero h1 {
      font-weight: bold;
      text-shadow: 2px 2px 5px #000;
    }

    .card {
      border: none;
      border-radius: 10px;
    }

    .card-title {
      color: #ff6f61;
    }

    footer {
      text-align: center;
      margin-top: 4rem;
      padding: 1rem;
      background-color: #ffe0d2;
      font-size: 0.85rem;
    }

    .bi {
      font-size: 2rem;
      color: #ff6f61;
    }
  </style>
</head>
<body>

  <!-- Sidebar -->
  <div class="sidebar">
    <h4><i class="bi bi-stars me-2"></i>Disneyland</h4>
    <a href="#"><i class="bi bi-house-door me-2"></i>Beranda</a>
    <a href="#"><i class="bi bi-person-bounding-box me-2"></i>Karakter</a>
    <a href="#"><i class="bi bi-film me-2"></i>Film</a>
    <a href="#"><i class="bi bi-images me-2"></i>Galeri</a>
    <a href="#"><i class="bi bi-envelope me-2"></i>Kontak</a>
  </div>

  <!-- Konten Utama -->
  <div class="content">
    <div class="hero">
      <h1>Selamat Datang di Dunia Disney</h1>
      <p>Jelajahi dunia penuh keajaiban bersama karakter-karakter favoritmu dari Disney!</p>
    </div>

    <div class="row g-4">
      <div class="col-md-4">
        <div class="card p-3 shadow-sm text-center">
          <img src="https://pngimg.com/uploads/mickey_mouse/mickey_mouse_PNG15.png" alt="Mickey" width="80">
          <h5 class="card-title mt-2">Mickey Mouse</h5>
          <p>Karakter ikonik Disney yang penuh semangat dan ceria. Teman semua orang!</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-3 shadow-sm text-center">
          <img src="STICH.jpg" alt="Stitch" width="80">
          <h5 class="card-title mt-2">Stitch</h5>
          <p>Alien lucu yang suka berpetualang dan sangat mencintai 'ohana' (keluarga).</p>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card p-3 shadow-sm text-center">
          <img src="ELSA.jpg" alt="Elsa" width="80">
          <h5 class="card-title mt-2">Elsa</h5>
          <p>Ratu dari Arendelle dengan kekuatan es ajaib. "Let it go~"</p>
        </div>
      </div>
    </div>

    <footer class="mt-5">
      <small>© 2025 Disneyland World. Keajaiban Dimulai dari Sini ✨</small>
    </footer>
  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
