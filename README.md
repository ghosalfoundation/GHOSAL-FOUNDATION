# GHOSAL-FOUNDATION
index.html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ghosal Foundation | NGO Hooghly West Bengal</title>
  <meta name="description" content="Ghosal Foundation — empowering lives through education, health and community work in Polba, Hooghly, West Bengal." />
  <!-- Open Graph (basic) -->
  <meta property="og:title" content="Ghosal Foundation | NGO Hooghly West Bengal" />
  <meta property="og:description" content="Empowering lives through education, health and community work in Polba, Hooghly." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://images2.imgbox.com/39/53/7uJ6SNoO_o.jpg" />

  <!-- CDN: Tailwind and FontAwesome (consider using SRI in production) -->
  <script src="https://cdn.tailwindcss.com" defer></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" />

  <style>
    /* small local overrides */
    .hero-bg {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images2.imgbox.com/39/53/7uJ6SNoO_o.jpg');
      background-size: cover;
      background-position: center;
    }
    .accent-green { color: #8CC63F; }
    .bg-accent-green { background-color: #8CC63F; }
    html { scroll-behavior: smooth; }
    /* visible skip link for keyboard users */
    .skip-to-content {
      position: absolute;
      left: -999px;
      top: auto;
      width: 1px;
      height: 1px;
      overflow: hidden;
    }
    .skip-to-content:focus {
      left: 1rem;
      top: 1rem;
      width: auto;
      height: auto;
      background: white;
      padding: 0.5rem 1rem;
      z-index: 9999;
      border-radius: 4px;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800 font-sans">

  <a class="skip-to-content" href="#maincontent">Skip to content</a>

  <!-- Navigation -->
  <nav class="bg-white shadow-md sticky top-0 z-50" aria-label="Primary Navigation">
    <div class="container mx-auto px-6 py-3 flex justify-between items-center">
      <a href="/" aria-label="Ghosal Foundation home">
        <img src="https://images2.imgbox.com/5a/e3/W6T8eD0l_o.png" alt="Ghosal Foundation Logo" class="h-12">
      </a>

      <div class="hidden md:flex space-x-6 font-semibold items-center" role="menubar">
        <a href="#about" class="hover:text-green-600 transition" role="menuitem">About</a>
        <a href="#focus" class="hover:text-green-600 transition" role="menuitem">What We Do</a>
        <a href="https://www.facebook.com/Ghosalfoundation" target="_blank" rel="noopener noreferrer" class="text-blue-600 text-xl" aria-label="Follow on Facebook">
          <i class="fab fa-facebook"></i>
        </a>
        <a href="#donate" class="bg-accent-green text-white px-6 py-2 rounded-full hover:bg-green-700 transition shadow-md" role="button">Donate Now</a>
      </div>

      <!-- Mobile icons -->
      <div class="md:hidden flex space-x-4">
        <a href="https://www.facebook.com/Ghosalfoundation" target="_blank" rel="noopener noreferrer" aria-label="Facebook" class="text-blue-600 text-2xl">
          <i class="fab fa-facebook"></i>
        </a>
        <a href="https://wa.me/917686856104" aria-label="WhatsApp" class="text-green-600 text-2xl">
          <i class="fab fa-whatsapp"></i>
        </a>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <header class="hero-bg h-[550px] flex items-center justify-center text-center text-white px-4" role="banner" aria-label="Hero banner">
    <div class="animate-fade-in">
      <h1 class="text-4xl md:text-6xl font-extrabold mb-4 drop-shadow-lg">Empowering Lives. Building Futures.</h1>
      <p class="text-xl mb-8 max-w-2xl mx-auto drop-shadow-md font-light">Join Ghosal Foundation in our journey to bring education, healthcare, and hope to rural West Bengal.</p>
      <div class="flex flex-col md:flex-row justify-center gap-4">
        <a href="#donate" class="bg-accent-green px-10 py-4 rounded-full font-bold text-lg hover:bg-green-600 transition shadow-xl">Start Donating</a>
        <a href="https://www.facebook.com/Ghosalfoundation" target="_blank" rel="noopener noreferrer" class="bg-blue-600 px-10 py-4 rounded-full font-bold text-lg hover:bg-blue-700 transition shadow-xl" aria-label="Follow Ghosal Foundation on Facebook">Follow on Facebook</a>
      </div>
    </div>
  </header>

  <main id="maincontent" role="main" class="focus:outline-none">
    <!-- Impact & Facebook Feed Section -->
    <section class="py-16 bg-white" aria-labelledby="impact-heading">
      <div class="container mx-auto px-6">
        <h2 id="impact-heading" class="sr-only">Impact</h2>
        <div class="grid md:grid-cols-3 gap-8 text-center">
          <div class="p-8 rounded-2xl bg-gray-50 shadow-sm border-b-4 border-green-500">
            <i class="fas fa-graduation-cap text-4xl accent-green mb-4" aria-hidden="true"></i>
            <h3 class="text-xl font-bold">Education</h3>
            <p class="text-gray-600">300+ children getting access to quality learning.</p>
          </div>
          <div class="p-8 rounded-2xl bg-gray-50 shadow-sm border-b-4 border-blue-500">
            <i class="fas fa-heartbeat text-4xl text-blue-500 mb-4" aria-hidden="true"></i>
            <h3 class="text-xl font-bold">Health</h3>
            <p class="text-gray-600">Free medical camps and hygiene kits for families.</p>
          </div>
          <div class="p-8 rounded-2xl bg-gray-50 shadow-sm border-b-4 border-orange-500">
            <i class="fas fa-users text-4xl text-orange-500 mb-4" aria-hidden="true"></i>
            <h3 class="text-xl font-bold">Community</h3>
            <p class="text-gray-600">Join our growing community on social media.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-50" aria-labelledby="about-heading">
      <div class="container mx-auto px-6 flex flex-col md:flex-row items-center gap-12">
        <div class="md:w-1/2">
          <img src="https://images2.imgbox.com/83/80/E56u7I2Q_o.jpg" alt="Foundation Activities" class="rounded-3xl shadow-2xl" loading="lazy">
        </div>
        <div class="md:w-1/2">
          <span class="text-green-600 font-bold tracking-widest uppercase text-sm">Our Mission</span>
          <h2 id="about-heading" class="text-4xl font-bold mt-2 mb-6">Changing lives in <span class="accent-green">Polba, Hooghly</span></h2>
          <p class="text-lg text-gray-700 mb-6 leading-relaxed">The Ghosal Foundation is a social welfare trust committed to grassroots development. We believe that sustainable change happens when we empower women, educate children, and provide basic health security to the most vulnerable.</p>
          <div class="flex items-center space-x-4 p-4 bg-blue-50 rounded-xl">
            <i class="fab fa-facebook text-3xl text-blue-600" aria-hidden="true"></i>
            <div>
              <p class="font-bold">Follow our daily updates!</p>
              <a href="https://www.facebook.com/Ghosalfoundation" target="_blank" rel="noopener noreferrer" class="text-blue-700 underline">facebook.com/Ghosalfoundation</a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Donation Section -->
    <section id="donate" class="py-20 bg-slate-900 text-white" aria-labelledby="donate-heading">
      <div class="container mx-auto px-6">
        <div class="text-center mb-16">
          <h2 id="donate-heading" class="text-4xl font-bold mb-4">Help Us Create an Impact</h2>
          <p class="text-gray-400">Secure payments directly to our Trust's official bank account.</p>
        </div>

        <div class="grid md:grid-cols-2 gap-12 max-w-5xl mx-auto">
          <!-- QR Code Card -->
          <div class="bg-white p-10 rounded-3xl text-black text-center shadow-2xl">
            <h3 class="text-xl font-bold mb-6">Scan & Pay (Any UPI)</h3>
            <img src="https://i.ibb.co/v4S8W5W/Whats-App-Image-2024-05-18-at-12-00-00.jpg" alt="Donation QR Code" class="mx-auto w-56 mb-6 rounded-lg border shadow-inner" loading="lazy">
            <p class="font-mono bg-blue-50 text-blue-700 p-3 rounded-lg text-sm select-all" title="UPI ID">UPI ID: 7686856104-4@axl</p>
            <p class="text-xs text-gray-500 mt-4">Verified Name: Ghosal Foundation</p>
            <!-- NOTE: Consider not committing UPI/Account info to public repo -->
          </div>

          <!-- Details Card -->
          <div class="flex flex-col justify-center">
            <h3 class="text-2xl font-bold accent-green mb-6 border-l-4 border-green-500 pl-4">Bank Transfer Details</h3>
            <div class="space-y-4 bg-slate-800 p-8 rounded-3xl border border-slate-700">
              <div class="flex justify-between border-b border-slate-700 pb-2"><span>Bank:</span><span class="font-bold">UCO Bank</span></div>
              <div class="flex justify-between border-b border-slate-700 pb-2"><span>Account Name:</span><span class="font-bold">Ghosal Foundation</span></div>
              <div class="flex justify-between border-b border-slate-700 pb-2"><span>Account No:</span><span class="font-bold select-all">07380110057711</span></div>
              <div class="flex justify-between border-b border-slate-700 pb-2"><span>IFSC Code:</span><span class="font-bold select-all">UCBA0000738</span></div>
              <div class="flex justify-between border-b border-slate-700 pb-2"><span>Branch:</span><span class="font-bold">Polba</span></div>
              <div class="flex justify-between"><span>Account Type:</span><span class="font-bold">Savings</span></div>
            </div>
            <a href="https://wa.me/917686856104" target="_blank" rel="noopener noreferrer" class="mt-8 flex items-center justify-center gap-3 bg-green-500 p-4 rounded-xl font-bold hover:bg-green-600 transition" aria-label="Send payment screenshot via WhatsApp">
              <i class="fab fa-whatsapp" aria-hidden="true"></i> Send Payment Screenshot
            </a>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer class="bg-white py-12 border-t border-gray-100" role="contentinfo">
    <div class="container mx-auto px-6">
      <div class="flex flex-col md:flex-row justify-between items-center text-center md:text-left">
        <div class="mb-8 md:mb-0">
          <img src="https://images2.imgbox.com/5a/e3/W6T8eD0l_o.png" alt="Ghosal Foundation logo" class="h-12 mx-auto md:mx-0 mb-4">
          <p class="text-gray-600">Polba, Hooghly, West Bengal, India</p>
          <p class="text-gray-600 italic">"Empowering the underprivileged with dignity."</p>
        </div>
        <div>
          <h4 class="font-bold mb-4">Quick Links</h4>
          <div class="flex flex-col space-y-2 text-gray-600">
            <a href="https://www.facebook.com/Ghosalfoundation" target="_blank" rel="noopener noreferrer" class="hover:text-blue-600">Facebook</a>
            <a href="mailto:ghosalfoundation@gmail.com" class="hover:text-red-500">Email Us</a>
            <a href="https://wa.me/917686856104" target="_blank" rel="noopener noreferrer" class="hover:text-green-500">WhatsApp Support</a>
          </div>
        </div>
      </div>
      <hr class="my-10 border-gray-100">
      <p class="text-center text-gray-400 text-sm font-light">© 2024 Ghosal Foundation. Registered Social Welfare Trust. <br>Designed for Hope.</p>
    </div>
  </footer>

  <!-- Floating Action Buttons -->
  <div class="fixed bottom-6 right-6 flex flex-col space-y-4 z-50" aria-hidden="true">
    <a href="https://www.facebook.com/Ghosalfoundation" target="_blank" rel="noopener noreferrer" class="bg-blue-600 text-white p-4 rounded-full shadow-2xl hover:bg-blue-700 transition transform hover:scale-110" aria-label="Facebook">
      <i class="fab fa-facebook text-2xl"></i>
    </a>
    <a href="https://wa.me/917686856104" target="_blank" rel="noopener noreferrer" class="bg-green-500 text-white p-4 rounded-full shadow-2xl hover:bg-green-600 transition transform hover:scale-110" aria-label="WhatsApp">
      <i class="fab fa-whatsapp text-2xl"></i>
    </a>
  </div>

  <!-- noscript fallback -->
  <noscript>
    <style>
      .hero-bg { background: url('https://images2.imgbox.com/39/53/7uJ6SNoO_o.jpg') center/cover no-repeat; }
    </style>
    <div style="background:#111;color:#fff;padding:1rem;text-align:center;">
      JavaScript is disabled in your browser. For the best experience enable JavaScript.
    </div>
  </noscript>
</body>
</html>