<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ammu Makeovers</title>
  <meta name="description" content="Ammu Makeovers — Bridal & party makeup, hair styling and pre-bridal packages in Vijaynagar, Bangalore." />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#fff9f8;
      --rose-1:#fdeef0;
      --rose-2:#f8d7da;
      --accent:#c76b6b;
      --gold:#d9b08d;
      --text:#2b2b2b;
      --muted:#6b6b6b;
      --glass:rgba(255,255,255,0.6);
      --card-shadow: 0 12px 36px rgba(199,107,107,0.07);
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{font-family:'Poppins',sans-serif;margin:0;background:linear-gradient(180deg,var(--bg),#fff);color:var(--text);-webkit-font-smoothing:antialiased}

    /* Topbar */
    .topbar{position:fixed;left:0;right:0;top:0;z-index:60;padding:12px 18px;display:flex;align-items:center;justify-content:space-between;gap:12px;background:linear-gradient(90deg,rgba(255,255,255,0.72),rgba(255,255,255,0.45));backdrop-filter:blur(6px);border-bottom:1px solid rgba(0,0,0,0.04)}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:52px;height:52px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--gold));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:800;font-size:18px}
    .brand h1{font-size:16px;margin:0}
    .brand p{margin:0;font-size:12px;color:var(--muted)}
    .navlinks{display:flex;gap:14px;align-items:center}
    .navlinks a{color:var(--text);text-decoration:none;font-weight:600;font-size:14px}

    /* hamburger */
    .hamburger{display:none;flex-direction:column;gap:4px;cursor:pointer}
    .hamburger span{width:22px;height:2px;background:var(--text);display:block;border-radius:2px}

    /* Hero */
    .hero-wrap{padding-top:88px}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;padding:48px 24px}
    .hero-card{background:linear-gradient(180deg,var(--rose-1),#fff);padding:28px;border-radius:16px;box-shadow:var(--card-shadow)}
    .hero h2{font-size:34px;margin:0 0 8px}
    .lead{color:var(--muted);margin:0 0 14px}
    .btn{display:inline-flex;align-items:center;gap:10px;padding:12px 16px;border-radius:10px;font-weight:700;text-decoration:none}
    .btn-primary{background:linear-gradient(90deg,var(--accent),var(--gold));color:#fff}
    .btn-ghost{background:transparent;border:2px solid var(--accent);color:var(--accent)}

    .info-row{display:flex;gap:12px;margin-top:18px}
    .info{background:#fff;padding:12px;border-radius:12px;flex:1;box-shadow:0 8px 28px rgba(0,0,0,0.04)}

    .aside{background:#fff;padding:18px;border-radius:14px;box-shadow:0 12px 36px rgba(0,0,0,0.06)}
    .aside .meta{font-size:13px;color:var(--muted);margin-bottom:8px}

    section{padding:36px 18px}
    .container{max-width:1100px;margin:0 auto}
    h3{font-size:22px;margin:0 0 10px}

    /* services */
    .services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
    .service{background:linear-gradient(180deg,rgba(255,255,255,0.95),#fff);padding:18px;border-radius:12px;box-shadow:0 8px 28px rgba(217,176,141,0.06)}

    /* gallery */
    .gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(160px,1fr));gap:12px}
    .gallery img{width:100%;height:160px;object-fit:cover;border-radius:10px;cursor:pointer;transition:transform .25s}
    .gallery img:hover{transform:scale(1.03)}

    /* testimonials */
    .testimonials{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:12px}
    .testi{background:#fff;padding:16px;border-radius:12px;box-shadow:0 10px 30px rgba(0,0,0,0.04)}

    /* contact */
    .contact-grid{display:grid;grid-template-columns:1fr 380px;gap:18px}
    form input,form textarea{width:100%;padding:12px;border-radius:10px;border:1px solid rgba(0,0,0,0.08);margin-bottom:10px}

    /* floating WhatsApp */
    .wa-float{position:fixed;right:18px;bottom:18px;background:linear-gradient(90deg,var(--accent),var(--gold));width:56px;height:56px;border-radius:999px;display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;box-shadow:0 10px 30px rgba(0,0,0,0.18);z-index:70}

    footer{padding:22px 18px;background:transparent;border-top:1px solid rgba(0,0,0,0.04)}

    /* modal */
    .modal{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,0.6);z-index:80}
    .modal img{max-width:92%;max-height:86%;border-radius:8px}

    /* mobile adjustments */
    @media (max-width:980px){
      .hero{grid-template-columns:1fr;padding:28px}
      .aside{order:2}
      .hamburger{display:flex}
      .navlinks{display:none}
      .contact-grid{grid-template-columns:1fr}
    }

    @media (max-width:520px){
      .logo{width:44px;height:44px;font-size:16px}
      .hero h2{font-size:22px}
      .brand h1{font-size:14px}
    }

    /* small animations */
    .fade-in{opacity:0;transform:translateY(8px);animation:fadeIn .7s ease forwards}
    @keyframes fadeIn{to{opacity:1;transform:none}}

  </style>
</head>
<body>

  <!-- Top bar -->
  <div class="topbar container" role="navigation" aria-label="Main navigation">
    <div class="brand">
      <div class="logo" aria-hidden="true">AM</div>
      <div>
        <h1>Ammu Makeovers</h1>
        <p>Vijaynagar, Bangalore</p>
      </div>
    </div>

    <nav>
      <div class="navlinks" aria-hidden="false">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#gallery">Gallery</a>
        <a href="#testimonials">Testimonials</a>
        <a href="#contact">Contact</a>
      </div>
      <button class="hamburger" id="hamburger" aria-label="Open menu" onclick="toggleMenu()">
        <span></span><span></span><span></span>
      </button>
    </nav>
  </div>

  <!-- Mobile menu overlay -->
  <div id="mobileMenu" style="display:none;position:fixed;inset:72px 18px 18px 18px;z-index:75;background:linear-gradient(180deg,var(--rose-1),#fff);border-radius:12px;padding:18px;box-shadow:0 20px 50px rgba(0,0,0,0.12)" aria-hidden="true">
    <div style="display:flex;flex-direction:column;gap:12px">
      <a href="#home" onclick="toggleMenu()">Home</a>
      <a href="#about" onclick="toggleMenu()">About</a>
      <a href="#services" onclick="toggleMenu()">Services</a>
      <a href="#gallery" onclick="toggleMenu()">Gallery</a>
      <a href="#testimonials" onclick="toggleMenu()">Testimonials</a>
      <a href="#contact" onclick="toggleMenu()">Contact</a>
    </div>
  </div>

  <!-- Hero -->
  <main id="home" class="hero-wrap">
    <div class="hero container">
      <div class="hero-card fade-in" role="region" aria-labelledby="hero-heading">
        <span style="display:inline-block;background:var(--glass);padding:6px 10px;border-radius:999px;font-weight:700">Bridal • Party • Pre-bridal</span>
        <h2 id="hero-heading" style="margin-top:12px">Look flawless on your special day</h2>
        <p class="lead">Ammu Makeovers — Professional bridal makeup, hair styling and skin prep in Vijaynagar. Personalised packages for every client.</p>

        <div style="margin-top:16px;display:flex;gap:12px;flex-wrap:wrap">
          <a class="btn btn-primary" href="tel:+919482661947">Call / WhatsApp</a>
          <a class="btn btn-ghost" href="#services">View Services</a>
        </div>

        <div class="info-row fade-in" style="margin-top:18px">
          <div class="info">
            <strong>Experienced Artist</strong>
            <div class="small">10+ years serving Bangalore brides</div>
          </div>
          <div class="info">
            <strong>On-location</strong>
            <div class="small">Home & venue bookings available</div>
          </div>
        </div>

        <div style="margin-top:20px">
          <small class="small">Studio timings: 10:00 AM — 8:00 PM (Mon–Sun)</small>
        </div>
      </div>

      <aside class="aside fade-in" role="region" aria-label="Booking panel">
        <div class="meta">BOOK A TRIAL</div>
        <h3 style="margin-top:6px;margin-bottom:6px">Free consultation & trial</h3>
        <p class="small">Schedule a trial or ask about package customisation. Appointments available daily.</p>
        <div style="margin-top:12px">
          <a class="btn btn-primary" href="https://wa.me/919482661947">Message on WhatsApp</a>
        </div>

        <hr style="margin:16px 0;border:none;border-top:1px solid rgba(0,0,0,0.06)"/>
        <div class="small"><strong>Location:</strong><br/>1st Main B cross, Pattegarpalya, Vijaynagar, Bangalore — 560079</div>
        <div class="small" style="margin-top:8px"><strong>Email:</strong><br/><a href="mailto:arkstoney@gmail.com">arkstoney@gmail.com</a></div>
      </aside>
    </div>
  </main>

  <!-- About -->
  <section id="about" class="container">
    <div style="display:grid;grid-template-columns:280px 1fr;gap:18px;align-items:center">
      <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Ammu" style="width:100%;border-radius:12px;object-fit:cover"/>
      <div>
        <h3>About Ammu</h3>
        <p style="margin-top:8px">Ammu is a professional beautician with over a decade of experience creating natural and long-lasting bridal looks. She specialises in HD bridal makeup, pre-bridal skin prep, hair styling and saree draping.</p>
        <p class="small"><strong>Why clients choose us:</strong> Professional products, hygienic kit, punctuality and personalised consultations.</p>
      </div>
    </div>
  </section>

  <!-- Services -->
  <section id="services" class="container">
    <h3>Services</h3>
    <p class="small">Custom packages for bridal, pre-bridal, parties and photoshoots. Contact for group bookings and venue travel.</p>
    <div class="services" style="margin-top:12px">
      <div class="service">
        <h4>Bridal Makeup</h4>
        <div class="small">Trial + wedding day makeup, HD products, long-wear finishing.</div>
      </div>
      <div class="service">
        <h4>Pre-Bridal Packages</h4>
        <div class="small">Facials, threadings, and skin prep for glowing makeup base.</div>
      </div>
      <div class="service">
        <h4>Party & Event Makeup</h4>
        <div class="small">Glam and editorial looks for parties and shoots.</div>
      </div>
      <div class="service">
        <h4>Hair Styling & Draping</h4>
        <div class="small">Updos, blowouts, saree draping and accessories.</div>
      </div>
      <div class="service">
        <h4>Facials & Skin Prep</h4>
        <div class="small">Pre-event skin treatments for long-lasting makeup.</div>
      </div>
      <div class="service">
        <h4>On-location Services</h4>
        <div class="small">Travel to home or venue for bridal days (travel charges may apply).</div>
      </div>
    </div>
  </section>

  <!-- Gallery -->
  <section id="gallery" class="container">
    <h3>Gallery</h3>
    <p class="small">Tap any image to view larger.</p>
    <div class="gallery" style="margin-top:12px">
      <img loading="lazy" src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look1" onclick="openModal(this.src)"/>
      <img loading="lazy" src="https://images.unsplash.com/photo-1517841905240-472988babdf9?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look2" onclick="openModal(this.src)"/>
      <img loading="lazy" src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look3" onclick="openModal(this.src)"/>
      <img loading="lazy" src="https://images.unsplash.com/photo-1526178613914-78a10b3dca2d?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look4" onclick="openModal(this.src)"/>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="container">
    <h3>Testimonials</h3>
    <div class="testimonials" style="margin-top:12px">
      <div class="testi">“Ammu did my bridal makeup and I felt so confident all day — long-lasting and flawless!”<div class="small" style="margin-top:8px">— Priya K., Bangalore</div></div>
      <div class="testi">“Quick, professional and so friendly. My party makeup was perfect.”<div class="small" style="margin-top:8px">— Ananya S.</div></div>
      <div class="testi">“Loved the pre-bridal package. Skin looked amazing on the wedding day.”<div class="small" style="margin-top:8px">— Radhika P.</div></div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="container">
    <h3>Contact & Bookings</h3>
    <div class="contact-grid" style="margin-top:12px">
      <div>
        <p class="small"><strong>Address</strong><br/>1st Main B cross, Pattegarpalya, Vijaynagar, Bangalore — 560079</p>
        <p class="small"><strong>Phone / WhatsApp</strong><br/><a href="tel:+919482661947">+91 94826 61947</a></p>
        <p class="small"><strong>Email</strong><br/><a href="mailto:arkstoney@gmail.com">arkstoney@gmail.com</a></p>
        <div style="margin-top:14px"><a class="btn btn-primary" href="https://wa.me/919482661947">Message on WhatsApp</a></div>
      </div>

      <div>
        <form id="contactForm" onsubmit="submitForm(event)">
          <input type="text" id="name" placeholder="Your name" required />
          <input type="email" id="email" placeholder="Email" required />
          <input type="tel" id="phone" placeholder="Phone (optional)" />
          <textarea id="message" rows="5" placeholder="Tell us about your event / preferred date" required></textarea>
          <button class="btn btn-primary" type="submit">Send Inquiry</button>
          <p class="small" style="margin-top:8px">Or email us at <a href="mailto:arkstoney@gmail.com">arkstoney@gmail.com</a></p>
        </form>
      </div>
    </div>
  </section>

  <footer class="container">
    <div style="display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
      <div class="small">© <strong>Ammu Makeovers</strong> — Vijaynagar, Bangalore</div>
      <div class="small">Made with care • For bookings call <a href="tel:+919482661947">+91 94826 61947</a></div>
    </div>
  </footer>

  <!-- Floating WhatsApp -->
  <a class="wa-float" href="https://wa.me/919482661947" aria-label="WhatsApp">
    <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="1.6" stroke-linecap="round" stroke-linejoin="round"><path d="M21 11.5a8.38 8.38 0 0 1-1.16 4.3c-.62 1.07-1.4 2.02-2.35 2.86a8.12 8.12 0 0 1-6.86 2.01 8.2 8.2 0 0 1-4.18-1.8L3 21l1.92-3.9A8.2 8.2 0 0 1 3 11.5 8.5 8.5 0 1 1 21 11.5z"></path><path d="M14.5 10.5c-.2-.03-1.1-.26-1.27-.29-.17-.03-.3-.03-.43.03-.14.06-.6.29-.73.36-.12.06-.24.06-.36.02-.12-.04-.45-.16-.86-.51-.41-.34-1.02-1.07-1.02-2.07 0-1.03.54-1.77.92-2.2.24-.27.53-.33.7-.33.17 0 .35 0 .5.01.16.01.4-.06.6.45.2.51.68 1.77.74 1.9.07.14.1.24.02.38-.09.14-.13.25-.25.38-.12.12-.28.26-.4.38-.12.12-.25.26-.12.5.12.24.53.93 1.14 1.49.78.57 1.44.78 1.67.86.23.07.37.06.5-.04.12-.1.53-.61.64-.86.12-.25.12-.46.08-.5-.04-.05-.16-.08-.36-.12z"></path></svg>
  </a>

  <!-- Gallery modal -->
  <div id="modal" class="modal" onclick="closeModal(event)" role="dialog" aria-hidden="true"><img id="modalImg" src="" alt="expanded"/></div>

  <script>
    // Smooth scroll for anchors
    document.querySelectorAll('a[href^="#"]').forEach(a=>{a.addEventListener('click',function(e){
      // allow external links (mailto, tel, wa) to work
      var href=this.getAttribute('href');
      if(href.startsWith('#')){e.preventDefault();var t=document.querySelector(href);if(t)t.scrollIntoView({behavior:'smooth',block:'start'});}
    })});

    // Mobile menu toggle (accessible)
    function toggleMenu(){
      var m=document.getElementById('mobileMenu');
      var btn=document.getElementById('hamburger');
      var expanded = m.style.display==='block';
      if(!expanded){m.style.display='block';m.setAttribute('aria-hidden','false');btn.setAttribute('aria-label','Close menu');}
      else{m.style.display='none';m.setAttribute('aria-hidden','true');btn.setAttribute('aria-label','Open menu');}
    }

    // Modal
    function openModal(src){document.getElementById('modalImg').src=src;document.getElementById('modal').style.display='flex';document.getElementById('modal').setAttribute('aria-hidden','false')}
    function closeModal(e){if(e.target.id==='modal'){document.getElementById('modal').style.display='none';document.getElementById('modal').setAttribute('aria-hidden','true')}}

    // Contact form opens mail client (simple, no backend)
    function submitForm(e){
      e.preventDefault();
      var name=document.getElementById('name').value;
      var email=document.getElementById('email').value;
      var phone=document.getElementById('phone').value;
      var msg=document.getElementById('message').value;
      var subject=encodeURIComponent('Booking inquiry from '+name);
      var body=encodeURIComponent('Name: '+name+'
Email: '+email+'
Phone: '+phone+'

Message:
'+msg);
      window.location.href='mailto:arkstoney@gmail.com?subject='+subject+'&body='+body;
    }
  </script>
</body>
</html>
