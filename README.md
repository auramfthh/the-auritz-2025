<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Auritz</title>
  <!-- Bootstrap CDN -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
    }
    .navbar-brand {
      font-weight: 700;
    }
    /* Hero Section dengan gambar background */
    .hero-section {
      height: 100vh;
      position: relative;
      color: white;
    }
    .hero-text h1 {
      font-size: 3rem;
      font-weight: bold;
    }
    .hero-text p {
      font-size: 1.25rem;
    }
    .navbar {
      z-index: 100; /* Navbar tetap di atas */
    }
    /* Produk Section */
    .product-card img {
      object-fit: cover;
      height: 200px;
    }
    .tag-button {
      margin: 5px;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">The Auritz</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link active" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Produk</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Tentang Kami</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Kontak</a>
          </li>
        </ul>
      </div>
    </div>BB
  </nav>

  <!-- Hero Section (Welcome Section) -->
  <section class="hero-section">
    <img src="welcome toko.png" alt="Hero Image" class="w-100 h-100 position-absolute top-0 start-0 object-fit-cover">
    <div class="hero-text text-center position-relative z-index-1">
      <h1>Selamat Datang di The Auritz</h1>
      <p>Temukan berbagai macam produk fashion dan aksesori yang trendy untuk melengkapi gaya Anda.</p>
      <a href="#produk" class="btn btn-primary">Lihat Produk</a>
    </div>
  </section>

  <!-- Button Tags for Filtering -->
  <section class="container mt-5">
    <h2 class="text-center mb-4">Filter Berdasarkan Kategori</h2>
    <div class="d-flex justify-content-center flex-wrap">
      <button class="btn btn-secondary tag-button">Sepatu</button>
      <button class="btn btn-secondary tag-button">Tas</button>
      <button class="btn btn-secondary tag-button">Aksesori</button>
      <button class="btn btn-secondary tag-button">Pakaian</button>
      <button class="btn btn-secondary tag-button">Anyaman Serat Lontar</button>
    </div>
  </section>

  <!-- Produk Section -->
<section id="produk" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Produk Unggulan</h2>
    <div class="row g-4">
      <!-- Produk ngguUlan: Songkok Guru -->
      <div class="col-md-4">
        <div class="card" style="background-color: #f8d7e1; border: none;">
          <img src="songkok guru.png" class="card-img-top" alt="Songkok Guru">
          <div class="card-body">
            <h5 class="card-title">Songkok Guru</h5>
            <p class="card-text">Songkok tradisional yang dibuat dengan serat lontar, dihiasi aksara lontarak yang sarat makna budaya.</p>
            <p class="card-text font-weight-bold" style="font-size: 1.25rem;">Rp 150.000</p>
            <a href="#" class="btn btn-primary">Beli Sekarang</a>
          </div>
        </div>
      </div>

      <!-- Produk Unggulan: Bakul -->
      <div class="col-md-4">
        <div class="card" style="background-color: #f8d7e1; border: none;">
          <img src="bakul.png" class="card-img-top" alt="Bakul">
          <div class="card-body">
            <h5 class="card-title">Bakul</h5>
            <p class="card-text">Bakul anyaman dari serat lontar yang indah, dipadukan dengan aksara lontarak, menciptakan karya seni yang fungsional.</p>
            <p class="card-text font-weight-bold" style="font-size: 1.25rem;">Rp 100.000</p>
            <a href="#" class="btn btn-primary">Beli Sekarang</a>
          </div>
        </div>
      </div>

      <!-- Produk Unggulan: Kipas Serat Lontar -->
      <div class="col-md-4">
        <div class="card" style="background-color: #f8d7e1; border: none;">
          <img src="kipas lontar.png" class="card-img-top" alt="Kipas Aksara Lontarak">
          <div class="card-body">
            <h5 class="card-title">Kipas Serat Lontarak</h5>
            <p class="card-text">Kipas tradisional yang terbuat dari serat lontar dengan desain aksara lontarak yang elegan dan penuh makna.</p>
            <p class="card-text font-weight-bold" style="font-size: 1.25rem;">Rp 50.000</p>
            <a href="#" class="btn btn-primary">Beli Sekarang</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

  <!-- Produk Section -->
  <section id="produk" class="py-5">
    <div class="container">
      <h2 class="text-center mb-4">Produk Unggulan</h2>
      <div class="row g-4">
        <!-- Produk 1: Sepatu Sport -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 1.png" class="card-img-top" alt="Sepatu Sport"> <!-- Gambar Produk 1 -->
            <div class="card-body">
              <h5 class="card-title">Sepatu Sport</h5>
              <p class="card-text">Sepatu sport nyaman untuk berbagai aktivitas outdoor.</p>
            </div>
          </div>
        </div>
        <!-- Produk 2: Tote Bag Canvas -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 2.png" class="card-img-top" alt="Tote Bag Canvas"> <!-- Gambar Produk 2 -->
            <div class="card-body">
              <h5 class="card-title">Tote Bag Canvas</h5>
              <p class="card-text">Tas canvas trendy untuk keperluan sehari-hari.</p>
            </div>
          </div>
        </div>
        <!-- Produk 3: Kacamata Hitam Trendy -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 3.png" class="card-img-top" alt="Kacamata Hitam Trendy"> <!-- Gambar Produk 3 -->
            <div class="card-body">
              <h5 class="card-title">Kacamata Hitam Trendy</h5>
              <p class="card-text">Kacamata hitam dengan desain fashionable dan modern.</p>
            </div>
          </div>
        </div>
        <!-- Produk 4: Earphone Wireless -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 4.png" class="card-img-top" alt="Earphone Wireless"> <!-- Gambar Produk 4 -->
            <div class="card-body">
              <h5 class="card-title">Earphone Wireless</h5>
              <p class="card-text">Earphone wireless dengan kualitas suara terbaik dan nyaman dipakai.</p>
            </div>
          </div>
        </div>
        <!-- Produk 5: Hoodie Oversize -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 5.png" class="card-img-top" alt="Hoodie Oversize"> <!-- Gambar Produk 5 -->
            <div class="card-body">
              <h5 class="card-title">Hoodie Oversize</h5>
              <p class="card-text">Hoodie oversize yang nyaman dan stylish untuk cuaca dingin.</p>
            </div>
          </div>
        </div>
        <!-- Produk 6: Casing HP Lucu -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 6.png" class="card-img-top" alt="Casing HP Lucu"> <!-- Gambar Produk 6 -->
            <div class="card-body">
              <h5 class="card-title">Casing HP Lucu</h5>
              <p class="card-text">Casing HP dengan desain lucu dan keren untuk smartphone Anda.</p>
            </div>
          </div>
        </div>
        <!-- Produk 7: Celana Cargo -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 7.png" class="card-img-top" alt="Celana Cargo"> <!-- Gambar Produk 7 -->
            <div class="card-body">
              <h5 class="card-title">Celana Cargo</h5>
              <p class="card-text">Celana cargo dengan desain modern dan banyak kantong praktis.</p>
            </div>
          </div>
        </div>
        <!-- Produk 8: Kaos Graphic Tee -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 8.png" class="card-img-top" alt="Kaos Graphic Tee"> <!-- Gambar Produk 8 -->
            <div class="card-body">
              <h5 class="card-title">Kaos Graphic Tee</h5>
              <p class="card-text">Kaos dengan desain grafis yang trendy dan unik.</p>
            </div>
          </div>
        </div>
        <!-- Produk 9: Gelang Manik-Manik -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 9.png" class="card-img-top" alt="Gelang Manik-Manik"> <!-- Gambar Produk 9 -->
            <div class="card-body">
              <h5 class="card-title">Gelang Manik-Manik</h5>
              <p class="card-text">Gelang manik-manik dengan desain etnik dan unik.</p>
            </div>
          </div>
        </div>
        <!-- Produk 10: Parfum Pocket Size -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 10 - Copy.png" class="card-img-top" alt="Parfum Pocket Size"> <!-- Gambar Produk 10 -->
            <div class="card-body">
              <h5 class="card-title">Parfum Pocket Size</h5>
              <p class="card-text">Parfum ukuran kecil yang praktis untuk dibawa kemana saja.</p>
            </div>
          </div>
        </div>
        <!-- Produk 11: Jaket Varsity -->
        <div class="col-md-4">
          <div class="card product-card">
            <img src="produk 11.png" class="card-img-top" alt="Jaket Varsity"> <!-- Gambar Produk 11 -->
            <div class="card-body">
              <h5 class="card-title">Jaket Varsity</h5>
              <p class="card-text">Jaket varsity dengan desain sporty dan nyaman untuk musim dingin.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

 <!-- Footer -->
<footer class="bg-dark text-white py-4">
  <div class="container text-center">
    <p>&copy; 2025 The Auritz. Semua Hak Dilindungi.</p>
    <div>
      <!-- Sosial Media Links -->
      <a href="https://facebook.com/TheAuritz" target="_blank" class="text-white mx-2">
        <i class="fab fa-facebook"></i> Facebook
      </a>|
      <a href="https://instagram.com/TheAuritz" target="_blank" class="text-white mx-2">
        <i class="fab fa-instagram"></i> Instagram
      </a>|
      <a href="https://twitter.com/TheAuritz" target="_blank" class="text-white mx-2">
        <i class="fab fa-twitter"></i> Twitter
      </a>
    </div>
  </div>
</footer>

<!-- CDN Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Font Awesome CDN (untuk icon sosial media) -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">

<!-- CDN Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

<a href="https://wa.me/6285395247576?text=Halo%20saya%20mau%20beli%20produk%20ini" target="_blank" class="btn btn-success btn-lg w-100 mt-3">
  Beli Sekarang via WhatsApp
</a>


