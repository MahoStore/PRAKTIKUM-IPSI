# PRAKTIKUM-IPSI
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Maho Store - Streetwear Mewah</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .fade-in {
      animation: fadeIn 0.8s ease-out forwards;
    }
  </style>
</head>
<body class="bg-gray-950 text-gray-200 font-sans">

  <!-- Navbar -->
  <header class="fixed top-0 w-full bg-gray-900/80 backdrop-blur border-b border-gray-800 z-50">
    <nav class="max-w-6xl mx-auto flex justify-between items-center px-6 py-4">
      <h1 class="text-2xl font-bold text-amber-400">Maho Store</h1>
      <ul class="flex space-x-6 text-sm">
        <li><a href="#" class="hover:text-amber-400 transition">Home</a></li>
        <li><a href="#" class="hover:text-amber-400 transition">Produk</a></li>
        <li><a href="#" class="hover:text-amber-400 transition">Tentang Kami</a></li>
        <li><a href="#" class="hover:text-amber-400 transition">Kontak</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="min-h-screen flex flex-col justify-center items-center text-center px-6 fade-in">
    <h2 class="text-5xl font-extrabold mb-4 text-white">Tampil <span class="text-amber-400">Berani</span> dengan Gaya Streetwear</h2>
    <p class="text-gray-400 max-w-2xl mb-8">Eksplorasi fashion yang menggambarkan keunikanmu — desain eksklusif hanya di Maho Store.</p>
    <a href="#produk" class="bg-amber-400 text-gray-900 px-8 py-3 rounded-full font-semibold hover:bg-amber-300 transition">Lihat Produk</a>
  </section>

  <!-- Produk Section -->
  <section id="produk" class="py-20 bg-gray-900 fade-in">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-3xl font-bold text-amber-400 mb-8">Produk Unggulan</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-gray-800 p-6 rounded-xl border border-gray-700 hover:border-amber-400 transition">
          <h4 class="text-xl font-semibold mb-2">Hoodie Street Classic</h4>
          <p class="text-gray-400 mb-2">Desain simpel, bahan lembut, cocok untuk semua gaya.</p>
          <span class="text-amber-400 font-bold">Rp 350.000</span>
        </div>
        <div class="bg-gray-800 p-6 rounded-xl border border-gray-700 hover:border-amber-400 transition">
          <h4 class="text-xl font-semibold mb-2">Kaos Oversized Black</h4>
          <p class="text-gray-400 mb-2">Gaya kasual dengan kenyamanan maksimal.</p>
          <span class="text-amber-400 font-bold">Rp 220.000</span>
        </div>
        <div class="bg-gray-800 p-6 rounded-xl border border-gray-700 hover:border-amber-400 transition">
          <h4 class="text-xl font-semibold mb-2">Celana Cargo Minimal</h4>
          <p class="text-gray-400 mb-2">Klasik, kuat, dan tetap stylish di segala situasi.</p>
          <span class="text-amber-400 font-bold">Rp 420.000</span>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-950 border-t border-gray-800 py-6 text-center text-gray-500">
    <p>&copy; 2025 <span class="text-amber-400">Maho Store</span> — Semua Hak Dilindungi.</p>
  </footer>

</body>
</html>
