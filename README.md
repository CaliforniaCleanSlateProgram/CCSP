<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>California Clean Slate Program | Streets to Sheets</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    .hero-bg {
      background-image: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.65)), url('van.jpg');
      background-size: cover;
      background-position: center;
    }
  </style>
</head>
<body class="font-sans text-gray-800">

  <!-- Navbar -->
  <nav class="bg-white shadow-md sticky top-0 z-50">
    <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
      <div class="flex items-center gap-3">
        <i class="fas fa-shower text-3xl text-blue-600"></i>
        <h1 class="text-2xl font-bold">Clean Slate</h1>
      </div>
      <div class="hidden md:flex gap-8 text-lg">
        <a href="#mission" class="hover:text-blue-600">Mission</a>
        <a href="#program" class="hover:text-blue-600">Program</a>
        <a href="#van" class="hover:text-blue-600">Our Van</a>
        <a href="#donate" class="hover:text-blue-600">Donate</a>
      </div>
      <a href="#donate" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-full font-semibold">Donate Now</a>
    </div>
  </nav>

  <!-- Hero -->
  <section class="hero-bg text-white py-40 md:py-56 text-center">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-5xl md:text-6xl font-bold mb-6">From Streets to Sheets</h2>
      <p class="text-2xl md:text-3xl mb-10 max-w-3xl mx-auto">Restoring dignity, hope, and opportunity — one shower at a time in Santa Cruz and beyond.</p>
      <div class="flex flex-col sm:flex-row gap-4 justify-center">
        <a href="#donate" class="bg-white text-blue-700 hover:bg-gray-100 px-10 py-5 rounded-full text-xl font-semibold">Donate Today</a>
        <a href="https://www.youtube.com/watch?v=1jT8LUaMA0o" target="_blank" class="border-2 border-white hover:bg-white hover:text-blue-700 px-10 py-5 rounded-full text-xl font-semibold">Watch Our Story →</a>
      </div>
    </div>
  </section>

  <!-- Mission -->
  <section id="mission" class="py-20 bg-gray-50">
    <div class="max-w-6xl mx-auto px-6">
      <div class="grid md:grid-cols-2 gap-12 items-center">
        <div>
          <h3 class="text-4xl font-bold mb-6">Meeting People Where They Are</h3>
          <p class="text-lg text-gray-600 leading-relaxed">California’s homelessness crisis is complex. We focus on one powerful first step: restoring basic human dignity through hygiene, trust, and real support.</p>
          <ul class="mt-8 space-y-4 text-lg">
            <li class="flex gap-3"><i class="fas fa-check text-green-600 mt-1"></i> Mobile Shower Services</li>
            <li class="flex gap-3"><i class="fas fa-check text-green-600 mt-1"></i> Street Outreach</li>
            <li class="flex gap-3"><i class="fas fa-check text-green-600 mt-1"></i> Recovery & Housing Referrals</li>
            <li class="flex gap-3"><i class="fas fa-check text-green-600 mt-1"></i> Workforce Re-Entry Support</li>
          </ul>
        </div>
        <img src="van.jpg" alt="California Clean Slate Mobile Shower Van" class="rounded-3xl shadow-2xl">
      </div>
    </div>
  </section>

  <!-- Program -->
  <section id="program" class="py-20">
    <div class="max-w-6xl mx-auto px-6">
      <h3 class="text-4xl font-bold text-center mb-12">Our 5-Phase “Streets to Sheets” Program</h3>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-xl transition">
          <h4 class="font-bold text-xl mb-3">1. Street Outreach</h4>
          <p>Building trust and providing immediate help on the streets.</p>
        </div>
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-xl transition">
          <h4 class="font-bold text-xl mb-3">2. Mobile Hygiene Units</h4>
          <p>Hot showers, laundry, and clean clothes — restoring dignity daily.</p>
        </div>
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-xl transition">
          <h4 class="font-bold text-xl mb-3">3. Recovery Support</h4>
          <p>Connecting individuals to treatment and sober living resources.</p>
        </div>
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-xl transition">
          <h4 class="font-bold text-xl mb-3">4. Housing Navigation</h4>
          <p>Helping people move from streets to stable housing.</p>
        </div>
        <div class="bg-white p-8 rounded-2xl shadow hover:shadow-xl transition">
          <h4 class="font-bold text-xl mb-3">5. Workforce Re-Entry</h4>
          <p>Job skills, record relief, and long-term stability.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Video -->
  <section class="py-20 bg-gray-900 text-white">
    <div class="max-w-4xl mx-auto px-6 text-center">
      <h3 class="text-4xl font-bold mb-8">Watch Our Story</h3>
      <div class="aspect-video rounded-2xl overflow-hidden shadow-2xl">
        <iframe width="100%" height="100%" src="https://www.youtube.com/embed/1jT8LUaMA0o" frameborder="0" allowfullscreen></iframe>
      </div>
    </div>
  </section>

  <!-- Donate -->
  <section id="donate" class="py-24 bg-blue-600 text-white">
    <div class="max-w-6xl mx-auto px-6 text-center">
      <h3 class="text-4xl font-bold mb-6">Help Us Launch Mobile Showers in Santa Cruz</h3>
      <p class="text-xl mb-10 max-w-2xl mx-auto">Your donation directly funds our mobile hygiene unit, supplies, and outreach efforts.</p>
      
      <div class="grid md:grid-cols-3 gap-6 max-w-3xl mx-auto mb-12">
        <div class="bg-white/10 backdrop-blur p-8 rounded-2xl">
          <span class="text-4xl font-bold">$50</span>
          <p class="mt-3">Hygiene kits for 10+ people</p>
        </div>
        <div class="bg-white/10 backdrop-blur p-8 rounded-2xl">
          <span class="text-4xl font-bold">$250</span>
          <p class="mt-3">Full day of mobile shower operations</p>
        </div>
        <div class="bg-white/10 backdrop-blur p-8 rounded-2xl">
          <span class="text-4xl font-bold">$1,000</span>
          <p class="mt-3">Helps maintain and fuel the van</p>
        </div>
      </div>

      <a href="https://givebutter.com/californiacleanslate" target="_blank" 
         class="inline-block bg-white text-blue-600 hover:bg-gray-100 px-12 py-6 rounded-full text-2xl font-bold">
        Donate Securely Now →
      </a>
      <p class="mt-6 text-sm">501(c)(3) Public Benefit Corporation • Tax deductible</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-900 text-gray-400 py-12">
    <div class="max-w-6xl mx-auto px-6 text-center">
      <p class="mb-2">California Clean Slate Program • Santa Cruz, California</p>
      <p class="text-sm">© 2026 California Clean Slate Program. All Rights Reserved.</p>
    </div>
  </footer>

</body>
</html>
