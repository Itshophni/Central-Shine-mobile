<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ShinePro Mobile Detailing</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --primary: #4fd1c5;
      --secondary: #2d3748;
      --accent: #f56565;
      --bg: #f9fafb;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: var(--bg);
      color: var(--secondary);
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #4fd1c5, #81e6d9);
      color: white;
      text-align: center;
      padding: 4rem 2rem;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
    }

    header p {
      margin-top: 1rem;
      font-size: 1.2rem;
    }

    nav {
      background: white;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }

    nav a {
      padding: 1rem 1.5rem;
      display: block;
      text-decoration: none;
      color: var(--secondary);
      font-weight: 600;
    }

    nav a:hover {
      color: var(--primary);
    }

    section {
      padding: 4rem 2rem;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      text-align: center;
    }

    .about p {
      text-align: center;
      max-width: 700px;
      margin: auto;
      font-size: 1.1rem;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
    }

    .service-card {
      background: white;
      border-radius: 1rem;
      padding: 2rem;
      box-shadow: 0 10px 25px rgba(0,0,0,0.05);
      transition: transform 0.3s ease;
    }

    .service-card:hover {
      transform: translateY(-5px);
    }

    .service-card strong {
      display: block;
      font-size: 1.2rem;
      margin-bottom: 0.5rem;
      color: var(--primary);
    }

    form {
      background: white;
      border-radius: 1rem;
      padding: 2rem;
      max-width: 600px;
      margin: auto;
      box-shadow: 0 10px 25px rgba(0,0,0,0.05);
    }

    input, textarea {
      width: 100%;
      padding: 1rem;
      margin-bottom: 1rem;
      border: 2px solid #e2e8f0;
      border-radius: 0.5rem;
      font-family: inherit;
    }

    button {
      background: var(--primary);
      color: white;
      padding: 1rem 2rem;
      border: none;
      border-radius: 2rem;
      font-weight: 600;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #38b2ac;
    }
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Your Detail Co. — Mobile Detailing in Orlando</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <meta name="description" content="Professional mobile detailing servicing Orlando & Kissimmee — packages, booking, hours, and contact." />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Ccircle cx='50' cy='50' r='45' fill='%23ef4444'/%3E%3Ctext x='50' y='58' font-size='48' text-anchor='middle' fill='white'%3E🚗%3C/text%3E%3C/svg%3E">
</head>
<body class="min-h-screen bg-gradient-to-br from-slate-900 via-slate-800 to-indigo-900 text-slate-100 font-sans">
  <!-- NAV -->
  <nav class="max-w-6xl mx-auto p-6 flex items-center justify-between">
    <a href="#" class="flex items-center gap-3">
      <div class="w-11 h-11 bg-gradient-to-tr from-pink-500 to-yellow-400 rounded-xl flex items-center justify-center shadow-lg">🚗</div>
      <div>
        <h1 class="font-bold text-xl">Your Detail Co.</h1>
        <p class="text-xs text-slate-300">Mobile Detailing — Orlando & Kissimmee</p>
      </div>
    </a>
    <div class="hidden md:flex items-center gap-6">
      <a href="#services" class="hover:underline">Services</a>
      <a href="#menu" class="hover:underline">Wash Menu</a>
      <a href="#reviews" class="hover:underline">Reviews</a>
      <a href="#contact" class="hover:underline">Contact</a>
      <a href="https://book.squareup.com" target="_blank" class="ml-2 inline-block bg-amber-400 text-slate-900 px-4 py-2 rounded-full font-semibold shadow hover:scale-105 transition">Book Now</a>
    </div>
    <button id="mobileMenuBtn" class="md:hidden bg-slate-700/40 p-2 rounded-lg">☰</button>
  </nav>

    footer {
      text-align: center;
      padding: 2rem;
      background: #edf2f7;
      font-size: 0.9rem;
      color: #718096;
    }
  <!-- HERO -->
  <header class="max-w-6xl mx-auto px-6 py-12 grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
    <div>
      <h2 class="text-4xl md:text-5xl font-extrabold leading-tight">Not your average car wash — Mobile detailing that shines ✨</h2>
      <p class="mt-4 text-slate-300">From express exterior washes to full paint correction and ceramic coatings — we bring professional detailing to your driveway. Serving Orlando, Kissimmee, and surrounding areas.</p>

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }
      <div class="mt-6 flex flex-wrap gap-3">
        <a href="https://book.squareup.com" target="_blank" class="bg-amber-400 text-slate-900 px-5 py-3 rounded-full font-semibold shadow-lg hover:shadow-xl">Book Now</a>
        <a href="#menu" class="border border-slate-600 px-5 py-3 rounded-full text-slate-200 hover:bg-slate-700/50">View Wash Menu</a>
      </div>

      nav ul {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
      <div class="mt-8 grid grid-cols-2 gap-4 text-sm">
        <div class="bg-white/5 p-4 rounded-lg">
          <div class="font-bold text-lg">Hours</div>
          <div class="text-slate-300">Daily: 7:00 AM — 6:00 PM</div>
        </div>
        <div class="bg-white/5 p-4 rounded-lg">
          <div class="font-bold text-lg">Call</div>
          <div class="text-amber-300 font-semibold">(863) 604-8725</div>
        </div>
      </div>
    </div>

  <header>
    <h1>ShinePro Detailing</h1>
    <p>✨ Premium mobile detailing at your doorstep</p>
    <div class="relative">
      <img src="https://images.unsplash.com/photo-1542362567-b07e54358753?q=80&w=1200&auto=format&fit=crop&ixlib=rb-4.0.3&s=1" alt="Detailing van" class="rounded-3xl shadow-2xl w-full object-cover h-80 md:h-[420px]" />
      <div class="absolute -bottom-6 left-6 bg-gradient-to-r from-slate-800/80 to-slate-700/70 p-4 rounded-2xl shadow-lg flex items-center gap-4">
        <div class="w-14 h-14 rounded-lg bg-white/5 flex items-center justify-center">⭐️</div>
        <div>
          <div class="text-xs text-slate-300">EXCELLENT</div>
          <div class="font-bold">Based on 43 reviews</div>
        </div>
      </div>
    </div>
  </header>

  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#services">Services</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="about" class="about">
    <h2>About Us</h2>
    <p>We’re not just cleaning your car — we’re restoring its vibe. ShinePro brings pro-level car care right to your home or office, with eco-friendly products and next-level shine.</p>
  <!-- SERVICES -->
  <section id="services" class="max-w-6xl mx-auto px-6 py-14">
    <h3 class="text-2xl font-bold">Our Mobile Detailing Services</h3>
    <p class="mt-2 text-slate-300">Packages for every need — single service options and full-service plans.</p>

    <div class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-6">
      <article class="bg-white/5 p-6 rounded-2xl">
        <h4 class="font-semibold text-lg">Exterior Hand Wash</h4>
        <p class="mt-2 text-slate-300 text-sm">Premium soaps, gentle hand washing, and protective finishing to restore showroom shine.</p>
        <div class="mt-4 font-bold">From $80</div>
      </article>

      <article class="bg-white/5 p-6 rounded-2xl">
        <h4 class="font-semibold text-lg">Interior Detailing</h4>
        <p class="mt-2 text-slate-300 text-sm">Vacuuming, steam cleaning, stain removal, leather conditioning and interior trim care.</p>
        <div class="mt-4 font-bold">From $100</div>
      </article>

      <article class="bg-white/5 p-6 rounded-2xl">
        <h4 class="font-semibold text-lg">Paint Correction & Ceramic</h4>
        <p class="mt-2 text-slate-300 text-sm">Multi-stage polishing and long-lasting ceramic coatings for show-quality protection.</p>
        <div class="mt-4 font-bold">From $250</div>
      </article>
    </div>
  </section>

  <section id="services">
    <h2>What We Do</h2>
    <div class="services">
      <div class="service-card">
        <strong>🚗 Exterior Wash & Wax</strong>
        Hand wash, clay bar, and wax — the full gloss treatment.
      </div>
      <div class="service-card">
        <strong>🧼 Interior Deep Clean</strong>
        Full vacuum, shampoo, stain removal, and leather conditioning.
  <!-- MENU CTA -->
  <section id="menu" class="max-w-6xl mx-auto px-6 py-10">
    <div class="bg-gradient-to-r from-slate-800/60 to-indigo-800/40 p-8 rounded-2xl flex flex-col md:flex-row items-center justify-between gap-6">
      <div>
        <h4 class="text-xl font-bold">Single Price Packages — No Hidden Charges</h4>
        <p class="mt-2 text-slate-300">Choose a package that fits your car and your schedule.</p>
      </div>
      <div class="service-card">
        <strong>💎 Full Detail</strong>
        Interior + exterior perfection. Your ride, reborn.
      <div class="flex gap-4">
        <a href="https://book.squareup.com" target="_blank" class="bg-amber-400 text-slate-900 px-5 py-3 rounded-full font-semibold">Check Our Menu</a>
        <a href="#contact" class="border border-slate-600 px-5 py-3 rounded-full">Contact Us</a>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Get in Touch</h2>
    <form action="https://formspree.io/f/yourformid" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <textarea name="message" rows="5" placeholder="Tell us what you need..." required></textarea>
      <button type="submit">Send It 🚀</button>
    </form>
  <!-- REVIEWS -->
  <section id="reviews" class="max-w-6xl mx-auto px-6 py-12">
    <h3 class="text-2xl font-bold">What people say</h3>
    <div class="mt-6 grid grid-cols-1 md:grid-cols-3 gap-6">
      <blockquote class="bg-white/5 p-6 rounded-lg">
        <p class="text-slate-200">“Top tier service for a great price — left my truck looking brand new.”</p>
        <footer class="mt-4 text-sm text-slate-400">— Jose D.</footer>
      </blockquote>
      <blockquote class="bg-white/5 p-6 rounded-lg">
        <p class="text-slate-200">“Very thorough! Finally got the new car smell back.”</p>
        <footer class="mt-4 text-sm text-slate-400">— Sophia T.</footer>
      </blockquote>
      <blockquote class="bg-white/5 p-6 rounded-lg">
        <p class="text-slate-200">“Amazing service, fast and professional.”</p>
        <footer class="mt-4 text-sm text-slate-400">— David A.</footer>
      </blockquote>
    </div>
  </section>

  <footer>
    &copy; 2025 ShinePro Mobile Detailing. Built with ❤️ for the road.
  <!-- CONTACT -->
  <section id="contact" class="max-w-6xl mx-auto px-6 py-12">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-start">
      <div class="bg-white/5 p-6 rounded-2xl">
        <h4 class="text-xl font-bold">Contact & Booking</h4>
        <p class="mt-2 text-slate-300">Call or text us to check availability in your neighborhood.</p>
        <div class="mt-4">
          <div class="font-semibold">Phone</div>
          <a href="tel:+18636048725" class="text-amber-300">(863) 604-8725</a>
        </div>
        <div class="mt-4">
          <div class="font-semibold">Email</div>
          <a href="mailto:info@yourdetailco.com" class="text-slate-200">info@yourdetailco.com</a>
        </div>
        <div class="mt-6">
          <div class="font-semibold">Hours</div>
          <div class="text-slate-300 text-sm">Sun–Sat: 7:00 AM – 6:00 PM</div>
        </div>
      </div>

      <form class="bg-white/5 p-6 rounded-2xl" onsubmit="handleForm(event)">
        <h4 class="text-lg font-semibold">Send us a message</h4>
        <label class="block mt-4 text-sm">
          <span class="text-slate-300">Name</span>
          <input required name="name" class="mt-1 block w-full rounded-md bg-slate-800 border border-slate-700 px-3 py-2" />
        </label>
        <label class="block mt-4 text-sm">
          <span class="text-slate-300">Phone or Email</span>
          <input required name="contact" class="mt-1 block w-full rounded-md bg-slate-800 border border-slate-700 px-3 py-2" />
        </label>
        <label class="block mt-4 text-sm">
          <span class="text-slate-300">Message</span>
          <textarea required name="message" rows="4" class="mt-1 block w-full rounded-md bg-slate-800 border border-slate-700 px-3 py-2"></textarea>
        </label>
        <div class="mt-4 flex items-center gap-3">
          <button type="submit" class="bg-amber-400 text-slate-900 px-4 py-2 rounded-full font-semibold">Send Message</button>
          <div id="formStatus" class="text-sm text-slate-300"></div>
        </div>
      </form>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="max-w-6xl mx-auto px-6 py-8 border-t border-slate-700/30 text-sm text-slate-400 flex flex-col md:flex-row justify-between">
    <div>© <span id="year"></span> Your Detail Co. — Serving Orlando • Powered by You</div>
    <div class="mt-3 md:mt-0">Follow us: <a class="underline" href="#">Instagram</a> • <a class="underline" href="#">TikTok</a> • <a class="underline" href="#">YouTube</a></div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();

    function handleForm(e) {
      e.preventDefault();
      const form = e.target;
      const status = document.getElementById('formStatus');
      status.textContent = 'Sending...';

      // NOTE: Replace below with your backend endpoint or an email API (Formspree, Netlify Forms, etc.)
      setTimeout(() => {
        status.textContent = 'Thanks — we received your message!';
        form.reset();
      }, 900);
    }

    // Simple mobile menu toggle
    const btn = document.getElementById('mobileMenuBtn');
    btn && btn.addEventListener('click', () => {
      alert('Mobile menu — link to sections or off-canvas menu can be implemented.');
    });
  </script>
</body>
</html>
