<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ammu Makeovers</title>
  <meta name="description" content="Ammu Makeovers — Professional bridal, party & party makeup services in Vijaynagar, Bangalore." />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#fffaf9;
      --rose-1:#f6dede;
      --rose-2:#f4b8c4;
      --accent:#b86b6b;
      --gold:#d9b08d;
      --text:#2b2b2b;
      --muted:#6b6b6b;
    }
    *{box-sizing:border-box}
    body{font-family:'Poppins',sans-serif;margin:0;background:linear-gradient(180deg,var(--bg),#fff);color:var(--text);-webkit-font-smoothing:antialiased}
    header{background:linear-gradient(90deg,var(--rose-1),var(--rose-2));padding:18px 24px;display:flex;align-items:center;justify-content:space-between;gap:16px;position:sticky;top:0;z-index:30;box-shadow:0 2px 8px rgba(0,0,0,0.04)}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:12px;background:linear-gradient(135deg,var(--accent),var(--gold));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:18px}
    nav a{margin-left:14px;text-decoration:none;color:var(--text);font-weight:600}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:24px;padding:48px 24px;align-items:center}
    .hero-left h1{font-size:40px;margin:0 0 12px}
    .tag{display:inline-block;background:rgba(255,255,255,0.6);padding:6px 10px;border-radius:999px;font-weight:600}
    .cta{margin-top:18px}
    .btn{background:linear-gradient(90deg,var(--accent),var(--gold));color:#fff;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700;display:inline-block}
    .cards{display:flex;gap:12px;margin-top:20px}
    .card{background:#fff;padding:12px;border-radius:12px;box-shadow:0 6px 18px rgba(184,107,107,0.08);flex:1}
    .hero-right{background:#fff;padding:20px;border-radius:12px;box-shadow:0 6px 18px rgba(0,0,0,0.06)}
    .meta{font-size:14px;color:var(--muted);margin-bottom:10px}
    section{padding:36px 24px}
    .container{max-width:1100px;margin:0 auto}
    h2{font-size:26px;margin:0 0 14px}
    .about{display:flex;gap:18px;align-items:center}
    .about img{width:280px;border-radius:12px;object-fit:cover}
    .services-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
    .service{background:linear-gradient(180deg,rgba(255,255,255,0.9),#fff);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(217,176,141,0.06)}
    .gallery-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px}
    .gallery-grid img{width:100%;height:160px;object-fit:cover;border-radius:10px;cursor:pointer}
    .testi{background:#fff;padding:16px;border-radius:10px;box-shadow:0 8px 24px rgba(0,0,0,0.04)}
    footer{background:#fff;padding:24px;border-top:1px solid rgba(0,0,0,0.04)}
    .contact-grid{display:grid;grid-template-columns:1fr 360px;gap:18px}
    form input, form textarea{width:100%;padding:10px;border-radius:8px;border:1px solid rgba(0,0,0,0.08);margin-bottom:10px}
    .small{font-size:13px;color:var(--muted)}
    /* modal */
    .modal{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,0.5);z-index:60}
    .modal .panel{background:#fff;padding:12px;border-radius:10px;max-width:92%;max-height:92%;overflow:auto}
    /* responsive */
    @media (max-width:880px){.hero{grid-template-columns:1fr;padding:28px;grid-template-rows:auto auto}.hero-right{order:2}.hero-left{order:1}.contact-grid{grid-template-columns:1fr}.about{flex-direction:column}.hero-left h1{font-size:28px}}
  </style>
</head>
<body>
  <header class="container">
    <div class="brand">
      <div class="logo">AM</div>
      <div>
        <div style="font-weight:700">Ammu Makeovers</div>
        <div class="small">Vijaynagar, Bangalore</div>
      </div>
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#gallery">Gallery</a>
      <a href="#testimonials">Testimonials</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main id="home" class="hero container">
    <div class="hero-left">
      <span class="tag">Professional Makeup & Bridal</span>
      <h1>Look flawless on every special day — <br/>Ammu Makeovers</h1>
      <p class="small">Trusted beautician in Vijaynagar. Bridal makeup, party looks, pre-bridal packages, hair styling and grooming services tailored for you.</p>
      <div class="cta">
        <a class="btn" href="tel:+919482661947">Call / WhatsApp +91 94826 61947</a>
        <a class="btn" style="margin-left:12px;background:transparent;color:var(--accent);border:2px solid var(--accent)" href="#services">View Services</a>
      </div>

      <div class="cards">
        <div class="card"><strong>Experienced Artist</strong><div class="small">10+ years serving Bangalore brides</div></div>
        <div class="card"><strong>Home & Studio</strong><div class="small">On-location bridal & studio bookings</div></div>
      </div>
    </div>

    <aside class="hero-right">
      <div class="meta">BOOK A TRIAL</div>
      <h3 style="margin-top:6px;margin-bottom:6px">Get a free consultation</h3>
      <p class="small">Schedule a trial or ask about packages. Appointments available Monday–Sunday.</p>
      <div style="margin-top:12px">
        <a class="btn" href="https://wa.me/919482661947">Message on WhatsApp</a>
      </div>
      <hr style="margin:16px 0;border:none;border-top:1px solid rgba(0,0,0,0.06)"/>
      <div class="small"><strong>Location:</strong><br/>1st Main B cross, Pattegarpalya, Vijaynagar, Bangalore – 560079</div>
      <div class="small" style="margin-top:8px"><strong>Email:</strong><br/><a href="mailto:arkstoney@gmail.com">arkstoney@gmail.com</a></div>
    </aside>
  </main>

  <section id="about" class="container">
    <h2>About Ammu</h2>
    <div class="about">
      <img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="Ammu"/>
      <div>
        <p style="margin-top:0">Ammu Makeovers is run by Ammu — a professional beautician with over a decade of experience helping brides, models and everyday clients look their best. She believes in natural enhancement, long-lasting looks and personalised consultations for every client.</p>
        <p class="small"><strong>Why clients choose us:</strong> Bridal precision, professional products, hygienic kit, punctuality and friendly service.</p>
      </div>
    </div>
  </section>

  <section id="services" class="container">
    <h2>Services</h2>
    <p class="small">Tailored packages for every occasion. Below are our most popular services — contact for custom bundles and group bookings.</p>
    <div class="services-grid" style="margin-top:14px">
      <div class="service">
        <h3>Bridal Makeup</h3>
        <p class="small">Full bridal makeup + trial, HD makeup, lash extensions, and touch-up kit.</p>
        <div class="small"><strong>Starting at:</strong> Custom quotes</div>
      </div>
      <div class="service">
        <h3>Party & Event Makeup</h3>
        <p class="small">Glam looks for parties, corporate events and photoshoots.</p>
      </div>
      <div class="service">
        <h3>Pre-Bridal Packages</h3>
        <p class="small">Facials, threading, pre-bridal trial & hair styling bundles.</p>
      </div>
      <div class="service">
        <h3>Hair Styling & Draping</h3>
        <p class="small">Updos, blowouts, saree draping and groom touch-ups.</p>
      </div>
      <div class="service">
        <h3>Facials & Skin Prep</h3>
        <p class="small">Professional skin prep treatments for long-lasting makeup.</p>
      </div>
      <div class="service">
        <h3>On‑location Services</h3>
        <p class="small">We travel to homes or venues for bridal days (travel charges may apply).</p>
      </div>
    </div>
  </section>

  <section id="gallery" class="container">
    <h2>Gallery</h2>
    <p class="small">A selection of looks created by Ammu. Tap any image to view larger.</p>
    <div class="gallery-grid" style="margin-top:12px">
      <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look1" onclick="openModal(this.src)"/>
      <img src="https://images.unsplash.com/photo-1517841905240-472988babdf9?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look2" onclick="openModal(this.src)"/>
      <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look3" onclick="openModal(this.src)"/>
      <img src="https://images.unsplash.com/photo-1526178613914-78a10b3dca2d?q=80&w=800&auto=format&fit=crop&ixlib=rb-4.0.3&s=placeholder" alt="look4" onclick="openModal(this.src)"/>
    </div>
  </section>

  <section id="testimonials" class="container">
    <h2>Testimonials</h2>
    <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:12px;margin-top:12px">
      <div class="testi">“Ammu did my bridal makeup and I felt so confident all day — long-lasting and flawless!”<div class="small" style="margin-top:8px">— Priya K., Bangalore</div></div>
      <div class="testi">“Quick, professional and so friendly. My party makeup was perfect.”<div class="small" style="margin-top:8px">— Ananya S.</div></div>
      <div class="testi">“Loved the pre-bridal package. Skin looked amazing on the wedding day.”<div class="small" style="margin-top:8px">— Radhika P.</div></div>
    </div>
  </section>

  <section id="contact" class="container">
    <h2>Contact & Bookings</h2>
    <div class="contact-grid">
      <div>
        <p class="small"><strong>Address</strong><br/>1st Main B cross, Pattegarpalya, Vijaynagar, Bangalore — 560079</p>
        <p class="small"><strong>Phone / WhatsApp</strong><br/><a href="tel:+919482661947">+91 94826 61947</a></p>
        <p class="small"><strong>Email</strong><br/><a href="mailto:arkstoney@gmail.com">arkstoney@gmail.com</a></p>
        <p class="small"><strong>Studio timings</strong><br/>10:00 AM — 8:00 PM (Mon–Sun)</p>
        <div style="margin-top:12px">
          <a class="btn" href="https://wa.me/919482661947">Message on WhatsApp</a>
        </div>
      </div>

      <div>
        <form id="contactForm" onsubmit="submitForm(event)">
          <input type="text" id="name" placeholder="Your name" required />
          <input type="email" id="email" placeholder="Email" required />
          <input type="tel" id="phone" placeholder="Phone (optional)" />
          <textarea id="message" rows="5" placeholder="Tell us about your event / preferred date" required></textarea>
          <button class="btn" type="submit">Send Inquiry</button>
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

  <!-- modal for gallery -->
  <div id="modal" class="modal" onclick="closeModal(event)">
    <div class="panel"><img id="modalImg" src="" style="max-width:100%;height:auto;border-radius:8px;display:block"/></div>
  </div>

  <script>
    function openModal(src){document.getElementById('modalImg').src=src;document.getElementById('modal').style.display='flex'}
    function closeModal(e){if(e.target.id==='modal' || e.target.className==='panel'){document.getElementById('modal').style.display='none'}}

    function submitForm(e){e.preventDefault();
      // client-side: open mail client with pre-filled message
      var name=document.getElementById('name').value;
      var email=document.getElementById('email').value;
      var phone=document.getElementById('phone').value;
      var msg=document.getElementById('message').value;
      var subject=encodeURIComponent('Booking inquiry from '+name);
      var body=encodeURIComponent('Name: '+name+'\nEmail: '+email+'\nPhone: '+phone+'\n\nMessage:\n'+msg);
      window.location.href='mailto:arkstoney@gmail.com?subject='+subject+'&body='+body;
    }

    // smooth scroll for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{a.addEventListener('click',function(e){e.preventDefault();var t=document.querySelector(this.getAttribute('href'));if(t) t.scrollIntoView({behavior:'smooth',block:'start'});});});
  </script>
</body>
</html>
