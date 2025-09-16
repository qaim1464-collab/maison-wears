<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maison Wears</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white">

  <!-- Navbar -->
  <nav class="flex justify-between items-center p-6 bg-black/60">
    <h1 class="text-2xl font-bold">Maison Wears</h1>
    <div class="space-x-6">
      <a href="#lookbook" class="hover:underline">Lookbook</a>
      <a href="#story" class="hover:underline">Story</a>
      <a href="#contact" class="hover:underline">Contact</a>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="h-[85vh] flex flex-col items-center justify-center bg-black/40">
    <div class="text-center">
      <h2 class="text-6xl font-extrabold">Maison Wears</h2>
      <p class="text-lg text-gray-200 mt-4">Maison Wears is more than clothing...</p>
      <a href="#lookbook" class="px-8 py-3 mt-6 inline-block bg-white text-black rounded-lg font-bold">Explore</a>
    </div>
  </section>

  <!-- Lookbook Section -->
  <section id="lookbook" class="py-20 px-6">
    <h3 class="text-4xl font-bold mb-10 text-center">Lookbook</h3>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="rounded-2xl overflow-hidden">
        <img src="https://via.placeholder.com/300" alt="Look 1" />
      </div>
      <div class="rounded-2xl overflow-hidden">
        <img src="https://via.placeholder.com/300" alt="Look 2" />
      </div>
      <div class="rounded-2xl overflow-hidden">
        <img src="https://via.placeholder.com/300" alt="Look 3" />
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20 px-6 text-center">
    <h3 class="text-4xl font-bold mb-6">About Us</h3>
    <p class="max-w-3xl mx-auto">
      Maison Wears is more than clothing. We combine comfort, style, and elegance to bring you timeless fashion pieces.
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20 px-6 text-center bg-black/50">
    <h3 class="text-4xl font-bold mb-6">Contact Us</h3>
    <p>Email: maisonwears@example.com</p>
  </section>

  <!-- Footer -->
  <footer class="py-6 text-center bg-black/70">
    <p>&copy; 2025 Maison Wears. All rights reserved.</p>
  </footer>

</body>
</html>
