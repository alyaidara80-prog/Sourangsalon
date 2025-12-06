<!DOCTYPE html>
<html lang="fr" class="dark:bg-gray-900 dark:text-white">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ndèye Sourang Cissé — Espace Multifonction Premium</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    .dark-mode-toggle { cursor: pointer; }
  </style>
</head>
<body class="font-sans bg-gray-50 dark:bg-gray-900 dark:text-white">

<!-- HEADER -->
<header class="bg-white dark:bg-gray-800 shadow-md sticky top-0 z-50">
  <div class="max-w-7xl mx-auto px-4 py-4 flex justify-between items-center">
    <div class="flex items-center gap-3">
      <img src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&w=150" alt="Logo" class="w-12 h-12 rounded-full shadow" />
      <h1 class="text-2xl font-bold text-red-600 dark:text-red-400">Ndèye Sourang Cissé</h1>
    </div>

    <nav class="hidden md:flex gap-6 text-lg font-semibold">
      <a href="#accueil" class="hover:text-red-500">Accueil</a>
      <a href="#coiffure" class="hover:text-red-500">Coiffure</a>
      <a href="#boutique" class="hover:text-red-500">Boutique</a>
      <a href="#vetements" class="hover:text-red-500">Vêtements</a>
      <a href="#jus" class="hover:text-red-500">Jus</a>
      <a href="#contact" class="hover:text-red-500">Contact</a>
    </nav>

    <div class="dark-mode-toggle text-2xl" onclick="toggleDarkMode()">🌙</div>
  </div>
</header>

<!-- ACCUEIL -->
<section id="accueil" class="py-20 bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&w=1600');">
  <div class="bg-black bg-opacity-60 py-24">
    <div class="max-w-4xl mx-auto text-center text-white">
      <h1 class="text-5xl font-bold mb-4">Espace Multifonction Professionnel</h1>
      <p class="text-xl opacity-90 mb-6">Coiffure • Boutique • Vêtements • Jus naturels</p>
      <a href="#contact" class="bg-red-600 px-8 py-4 rounded-xl text-white text-lg shadow-lg hover:bg-red-700">Nous Contacter</a>
    </div>
  </div>
</section>

<!-- COIFFURE -->
<section id="coiffure" class="py-20 bg-gray-100 dark:bg-gray-800">
  <div class="max-w-7xl mx-auto px-4">
    <h2 class="text-4xl font-bold text-red-500 mb-10 text-center">Salon de Coiffure Homme / Femme</h2>

    <div class="grid md:grid-cols-2 gap-8">
      <img src="https://images.unsplash.com/photo-1522336572468-97b06e8ef143?auto=format&w=1200" class="rounded-xl shadow-xl" />

      <div>
        <p class="text-lg mb-4">Coupe homme, femme, dégradés, coloration, barbe, coiffures femmes, pédicure, manucure…</p>
        <ul class="list-disc ml-6 text-gray-700 dark:text-gray-300">
          <li>Coupe : 1 000–2 000 F</li>
          <li>Coiffure enfant : 500–1 000 F</li>
          <li>Barbe : 500 F</li>
          <li>Coiffures femmes : 2 000 à +10 000 F</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- BOUTIQUE -->
<section id="boutique" class="py-20">
  <div class="max-w-7xl mx-auto px-4">
    <h2 class="text-4xl font-bold text-red-500 mb-10 text-center">Mini-boutique Alimentaire</h2>

    <div class="grid md:grid-cols-2 gap-8 items-center">
      <div>
        <p class="text-lg mb-4">Boissons, gâteaux, bonbons, eau, biscuits…</p>
        <p class="text-gray-600 dark:text-gray-300 mb-4">Ventes rapides et quotidiennes.</p>
      </div>
      <img src="https://images.unsplash.com/photo-1556911220-e15b29be8c33?auto=format&w=1200" class="rounded-xl shadow-xl" />
    </div>
  </div>
</section>

<!-- VÊTEMENTS -->
<section id="vetements" class="py-20 bg-gray-100 dark:bg-gray-800">
  <div class="max-w-7xl mx-auto px-4">
    <h2 class="text-4xl font-bold text-red-500 mb-10 text-center">Vêtements Neufs</h2>

    <div class="grid md:grid-cols-3 gap-6">
      <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&w=800" class="rounded-xl shadow-xl" />
      <img src="https://images.unsplash.com/photo-1520962918287-7448c2878f65?auto=format&w=800" class="rounded-xl shadow-xl" />
      <img src="https://images.unsplash.com/photo-1523381294911-8d3cead13475?auto=format&w=800" class="rounded-xl shadow-xl" />
    </div>
  </div>
</section>

<!-- JUS -->
<section id="jus" class="py-20">
  <div class="max-w-7xl mx-auto px-4">
    <h2 class="text-4xl font-bold text-red-500 mb-10 text-center">Jus Naturels Maison</h2>

    <div class="grid md:grid-cols-2 gap-8 items-center">
      <img src="https://images.unsplash.com/photo-1556911220-e15b29be8c33?auto=format&w=1200" class="rounded-xl shadow-xl" />
      <ul class="list-disc ml-6 text-lg">
        <li>Bissap</li>
        <li>Bouye</li>
        <li>Gingembre</li>
        <li>Cocktail spécial maison</li>
      </ul>
    </div>
  </div>
</section>

<!-- RÉSERVATION -->
<section id="reservation" class="py-20 bg-gray-100 dark:bg-gray-800">
  <div class="max-w-4xl mx-auto px-4 text-center">
    <h2 class="text-4xl font-bold text-red-500 mb-8">Réserver une prestation</h2>

    <form action="https://formspree.io/f/mwpkkqye" method="POST" class="grid gap-6 bg-white dark:bg-gray-900 p-6 rounded-xl shadow-xl">
      <input name="nom" type="text" placeholder="Votre nom" required class="p-3 rounded-lg bg-gray-100 dark:bg-gray-700" />
      <input name="whatsapp" type="text" placeholder="Numéro WhatsApp" required class="p-3 rounded-lg bg-gray-100 dark:bg-gray-700" />
      <select name="prestation" class="p-3 rounded-lg bg-gray-100 dark:bg-gray-700">
        <option>Coiffure Homme</option>
        <option>Coiffure Femme</option>
        <option>Vêtements</option>
        <option>Jus naturels</option>
      </select>
      <button class="bg-red-600 text-white py-3 rounded-lg hover:bg-red-700">Envoyer</button>
    </form>
  </div>
</section>

<!-- CONTACT -->
<section id="contact" class="py-20 text-center">
  <h2 class="text-4xl font-bold text-red-500 mb-6">Nous Contacter</h2>
  <a href="https://wa.me/221777062661" class="bg-green-600 text-white px-8 py-4 rounded-xl text-lg shadow-xl">💬 WhatsApp</a>
</section>

<!-- FOOTER -->
<footer class="bg-gray-900 text-white py-6 text-center">
  © 2025 Ndèye Sourang Cissé — Tous droits réservés.
</footer>

<script>
function toggleDarkMode() {
  document.documentElement.classList.toggle('dark');
}
</script>

</body>
</html>
