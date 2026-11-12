# Ansaeku-multimedia-
Into multiple media
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ansaeku Multimedia | Bringing Your Vision to Life</title>
<meta name="description" content="Ansaeku Multimedia - Video, Photography, Graphic Design, Audio, Microsoft Works in Accra, Ghana. Call 0553558771">
<style>
  *{margin:0;padding:0;box-sizing:border-box;font-family:'Segoe UI',Arial,sans-serif}
  body{background:#0a0f1e;color:#fff;line-height:1.6;overflow-x:hidden;position:relative}
  body::before{content:"";position:fixed;inset:0;z-index:-2;
    background:
      radial-gradient(circle at 15% 20%, rgba(255,215,0,.45) 0 120px, transparent 130px),
      radial-gradient(circle at 85% 10%, rgba(255,180,0,.5) 0 90px, transparent 100px),
      radial-gradient(circle at 70% 80%, rgba(255,200,80,.35) 0 140px, transparent 150px),
      radial-gradient(circle at 25% 85%, rgba(255,170,0,.30) 0 100px, transparent 110px),
      linear-gradient(180deg,#1a1400 0%,#0a0f1e 40%,#1a1200 100%)}
  .bokeh{position:fixed;inset:0;pointer-events:none;z-index:-1;opacity:.55;
    background-image:radial-gradient(circle, rgba(255,215,100,.9) 0 3px, transparent 4px),radial-gradient(circle, rgba(255,255,255,.9) 0 2px, transparent 3px),radial-gradient(circle, rgba(255,180,0,.8) 0 6px, transparent 7px);
    background-size:180px 180px,260px 260px,320px 320px;animation:shimmer 6s ease-in-out infinite alternate}
  @keyframes shimmer{from{opacity:.35}to{opacity:.7}}
  a{text-decoration:none;color:inherit}
  header{position:sticky;top:0;z-index:10;display:flex;justify-content:space-between;align-items:center;padding:12px 5%;background:rgba(10,15,30,.9);backdrop-filter:blur(12px);border-bottom:1px solid rgba(255,215,0,.35);box-shadow:0 0 40px rgba(255,190,0,.25)}
  .logo{display:flex;align-items:center;gap:12px}
  .logo-mark{width:48px;height:48px;border-radius:50%;background:linear-gradient(135deg,#ffd700,#ff8c2e,#14c8b8);display:flex;align-items:center;justify-content:center;font-size:24px;box-shadow:0 0 20px rgba(255,215,0,.7)}
  .logo-text{font-weight:900;font-size:22px;line-height:1}.logo-text small{color:#ffb347;font-size:11px;letter-spacing:4px}
  nav{display:flex;gap:20px;align-items:center} nav a{font-size:14px} nav a:hover{color:#ffd700}
  .btn{background:linear-gradient(90deg,#ffd700,#ff8c2e);color:#000;padding:11px 20px;border-radius:10px;font-weight:800;border:0;cursor:pointer;box-shadow:0 0 25px rgba(255,200,0,.5);display:inline-block}
  .btn-teal{background:linear-gradient(90deg,#14c8b8,#0aa89a);color:#fff}
  .hero{display:flex;flex-wrap:wrap;gap:30px;align-items:center;padding:55px 5%}
  .hero-text{flex:1;min-width:280px}.hero-text h1{font-size:48px;line-height:1.05;text-shadow:0 0 30px rgba(255,215,0,.4)}
  .hero-text h1 em{color:#14c8b8;font-style:normal}.hero-text h1 i{color:#ffb347;font-style:normal}
  .hero-text p{margin:16px 0;color:#f5e6b8}
  .hero-visual{flex:1;min-width:280px;background:linear-gradient(135deg,#ffd700,#ff8c2e,#14c8b8);border-radius:22px;padding:4px;box-shadow:0 0 50px rgba(255,200,0,.6)}
  .hero-visual-inner{background:#0a0f1e;border-radius:18px;overflow:hidden}
  .hero-visual-inner img{width:100%;height:220px;object-fit:cover;display:block}
  .hero-visual-inner div{padding:18px;text-align:center}
  .section{padding:50px 5%}.section h2{text-align:center;font-size:32px}.section p.sub{text-align:center;color:#f0d98a;margin-bottom:28px}
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
  .card{background:rgba(17,24,46,.92);border:1px solid rgba(255,215,0,.4);border-radius:18px;padding:22px;box-shadow:0 0 25px rgba(255,200,0,.15)}
  .card img{width:100%;height:150px;object-fit:cover;border-radius:12px;margin-bottom:12px}
  .card h3{margin:6px 0}.card p{color:#e8dcc0;font-size:14px}
  .card ul{list-style:none;margin-top:10px;color:#e8dcc0;font-size:14px}.card ul li{margin:6px 0}.card ul li:before{content:"✓ ";color:#ffd700;font-weight:700}
  .microsoft{grid-column:1/-1;background:linear-gradient(90deg,rgba(17,24,46,.95),rgba(60,45,5,.9));border:1px solid #ffd700}
  /* PORTFOLIO */
  .portfolio{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px}
  .portfolio img{width:100%;height:180px;object-fit:cover;border-radius:14px;border:1px solid rgba(255,215,0,.4)}
  .portfolio div{text-align:center;font-size:13px;color:#f0d98a;margin-top:6px}
  /* PRICING */
  .price-card{background:rgba(17,24,46,.95);border:1px solid rgba(255,215,0,.5);border-radius:18px;padding:24px;text-align:center}
  .price-card.featured{border:2px solid #ffd700;transform:scale(1.03);box-shadow:0 0 35px rgba(255,215,0,.4)}
  .price{font-size:36px;font-weight:900;color:#ffd700;margin:10px 0}.price small{font-size:14px;color:#fff}
  .price-card ul{list-style:none;color:#e8dcc0;font-size:14px;text-align:left;margin:14px 0}.price-card ul li{margin:8px 0}
  /* BOOKING FORM */
  .booking{max-width:650px;margin:0 auto;background:rgba(17,24,46,.95);border:1px solid #ffd700;border-radius:20px;padding:28px;box-shadow:0 0 35px rgba(255,200,0,.3)}
  .booking label{display:block;text-align:left;font-size:14px;margin:14px 0 6px;color:#ffd700;font-weight:700}
  .booking input,.booking select,.booking textarea{width:100%;padding:13px;border-radius:10px;border:1px solid #333;background:#0a0f1e;color:#fff;font-size:15px}
  .contact-boxes{display:flex;flex-wrap:wrap;justify-content:center;gap:16px;margin-top:24px}
  .contact-box{background:rgba(17,24,46,.95);border:1px solid rgba(255,215,0,.5);padding:16px 22px;border-radius:14px;min-width:240px}
  .contact-box b{display:block;color:#ffd700}
  .whatsapp{position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:14px 20px;border-radius:50px;font-weight:800;box-shadow:0 0 30px rgba(37,211,102,.6);z-index:20}
  footer{padding:20px 5%;display:flex;justify-content:space-between;flex-wrap:wrap;color:#d8c88a;font-size:13px;background:rgba(0,0,0,.5)}
  @media(max-width:600px){.hero-text h1{font-size:36px} nav{display:none}}
</style>
</head>
<body>
<div class="bokeh"></div>
<header>
  <div class="logo"><div class="logo-mark">A</div><div class="logo-text">ANSAEKU<br><small>MULTIMEDIA</small></div></div>
  <nav><a href="#home">Home</a><a href="#services">Services</a><a href="#portfolio">Portfolio</a><a href="#pricing">Prices</a><a href="#booking">Book</a><a class="btn" href="tel:+233553558771">Call Now</a></nav>
</header>

<section class="hero" id="home">
  <div class="hero-text">
    <h1>Bringing Your <em>Vision</em> to <i>Life</i> Through Media</h1>
    <p>We craft professional video production, photography, graphic design, audio & content solutions to elevate your brand. From concept to final delivery, we turn your ideas into impactful media.</p>
    <div style="display:flex;gap:12px;flex-wrap:wrap"><a href="#services" class="btn btn-teal">Our Services →</a><a href="#booking" class="btn">Book Now ✨</a></div>
    <p style="font-size:13px;margin-top:14px">⭐ Trusted in Accra • Fast Delivery • Affordable Prices • Call / WhatsApp: <b>0553558771</b></p>
  </div>
  <div class="hero-visual"><div class="hero-visual-inner">
    <img src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?w=800&q=80" alt="Ansaeku Multimedia Camera">
    <div><p style="color:#ffd700;font-weight:800">✨ Video • Photo • Design • Audio • Office ✨</p><p style="color:#fff;font-size:14px">Golden • Cinematic • Ethereal • Vintage</p></div>
  </div></div>
</section>

<section class="section" id="services">
  <h2>✨ What We Offer ✨</h2><p class="sub">OUR SERVICES — Creative • Innovative • Reliable</p>
  <div class="grid">
    <div class="card"><img src="https://images.unsplash.com/photo-1574717024653-61fd2cf4d44d?w=600&q=80"><h3>🎬 Video Production</h3><p>Cinematic videos, commercials, event coverage, editing & post-production.</p><p><b style="color:#ffd700">From GH₵ 250</b></p></div>
    <div class="card"><img src="https://images.unsplash.com/photo-1516035069371-29a1b244cc32?w=600&q=80"><h3>📸 Photography</h3><p>Portraits, products, events, branding, and commercial shoots.</p><p><b style="color:#ffd700">From GH₵ 150</b></p></div>
    <div class="card"><img src="https://images.unsplash.com/photo-1561070791-2526d30994b5?w=600&q=80"><h3>🎨 Graphic Design</h3><p>Logos, flyers, posters, social media designs, brand identity.</p><p><b style="color:#ffd700">From GH₵ 80</b></p></div>
    <div class="card"><img src="https://images.unsplash.com/photo-1590602847861-f357a9332bbc?w=600&q=80"><h3>🎙️ Audio & Content</h3><p>Podcast production, voiceovers, sound design, content creation.</p><p><b style="color:#ffd700">From GH₵ 100</b></p></div>
    <div class="card microsoft"><h3>💻 Microsoft Works / Microsoft Office</h3>
      <ul><li><b>Word</b> — Document drafting & formatting — GH₵ 20+</li><li><b>Excel</b> — Data entry, spreadsheets, analysis — GH₵ 30+</li><li><b>PowerPoint</b> — Presentations & slides — GH₵ 50+</li><li><b>Typing</b> — Fast, accurate typing — GH₵ 10/page</li><li><b>Printing</b> — Document printing — GH₵ 2/page</li><li><b>Document Formatting</b> — Professional layout — GH₵ 30+</li></ul>
    </div>
  </div>
</section>

<section class="section" id="portfolio">
  <h2>Our Work</h2><p class="sub">Portfolio — Real work, real results</p>
  <div class="portfolio">
    <div><img src="https://images.unsplash.com/photo-1519741497674-611481863552?w=600&q=80"><div>Wedding Photography</div></div>
    <div><img src="https://images.unsplash.com/photo-1505373877841-8d25f7d46678?w=600&q=80"><div>Event Coverage</div></div>
    <div><img src="https://images.unsplash.com/photo-1533750349088-cd871a92f312?w=600&q=80"><div>Product Shoot</div></div>
    <div><img src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?w=600&q=80"><div>Brand Video</div></div>
  </div>
  <p style="text-align:center;margin-top:16px;color:#f0d98a">Want your work here? Send us your photos on WhatsApp and we will add them.</p>
</section>

<section class="section" id="pricing">
  <h2>Simple Pricing</h2><p class="sub">Transparent • No hidden charges • Pay on delivery available</p>
  <div class="grid">
    <div class="price-card"><h3>Starter</h3><div class="price">GH₵ 80<small> / project</small></div><ul><li>✓ 1 Flyer / Logo</li><li>✓ 1 Revision</li><li>✓ 24hr Delivery</li><li>✓ WhatsApp Support</li></ul><a href="#booking" class="btn btn-teal">Choose Starter</a></div>
    <div class="price-card featured"><h3>⭐ Popular — Creator</h3><div class="price">GH₵ 250<small> / project</small></div><ul><li>✓ Photoshoot + 10 Edited Photos</li><li>✓ 1 Promo Video (60s)</li><li>✓ 3 Flyers / Social Posts</li><li>✓ 48hr Delivery</li></ul><a href="#booking" class="btn">Choose Creator</a></div>
    <div class="price-card"><h3>Business Pro</h3><div class="price">GH₵ 550<small> / project</small></div><ul><li>✓ Full Event Coverage</li><li>✓ Full Brand Kit (Logo + Flyers)</li><li>✓ 3 Videos + 30 Photos</li><li>✓ Priority Support</li></ul><a href="#booking" class="btn btn-teal">Choose Pro</a></div>
  </div>
  <p style="text-align:center;margin-top:14px;color:#f0d98a">Microsoft Works prices start from GH₵ 10. Final price depends on pages / complexity. Message us for a free quote.</p>
</section>

<section class="section" id="booking">
  <h2>Book Ansaeku Multimedia</h2><p class="sub">Fill this form — it will open WhatsApp to us automatically</p>
  <form class="booking" onsubmit="bookNow(event)">
    <label>Your Name *</label><input id="name" required placeholder="e.g. Kwame Mensah">
    <label>Phone / WhatsApp *</label><input id="phone" required placeholder="e.g. 0553558771">
    <label>What do you need? *</label>
    <select id="service"><option>Video Production</option><option>Photography</option><option>Graphic Design</option><option>Audio & Content</option><option>Microsoft Word / Excel / PowerPoint</option><option>Typing / Printing / Formatting</option><option>Other</option></select>
    <label>Package</label><select id="package"><option>Starter - GH₵ 80</option><option>Creator - GH₵ 250</option><option>Business Pro - GH₵ 550</option><option>Custom / Just need a quote</option></select>
    <label>Date Needed</label><input id="date" type="date">
    <label>Details</label><textarea id="details" rows="4" placeholder="Tell us about your project, location, number of pages, etc."></textarea>
    <br><br><button class="btn" style="width:100%;font-size:17px" type="submit">Send Booking on WhatsApp →</button>
    <p style="text-align:center;font-size:13px;margin-top:10px;color:#e8dcc0">Or call directly: <b style="color:#ffd700">0553558771</b></p>
  </form>
  <div class="contact-boxes">
    <div class="contact-box"><b>📞 Phone / WhatsApp</b>+233 55 355 8771<br>0553558771</div>
    <div class="contact-box"><b>✉️ Email</b>info@ansaeku.com</div>
    <div class="contact-box"><b>📍 Location</b>Accra, Ghana</div>
  </div>
</section>

<a class="whatsapp" href="https://wa.me/233553558771">💬 WhatsApp Us</a>
<footer><span>© 2026 Ansaeku Multimedia. All rights reserved.</span><span>Creative • Professional • Reliable • Golden</span></footer>

<script>
function bookNow(e){
  e.preventDefault();
  var name=document.getElementById('name').value;
  var phone=document.getElementById('phone').value;
  var service=document.getElementById('service').value;
  var pkg=document.getElementById('package').value;
  var date=document.getElementById('date').value;
  var details=document.getElementById('details').value;
  var msg="Hello Ansaeku Multimedia!%0A%0A*NEW BOOKING*%0AName: "+encodeURIComponent(name)+"%0APhone: "+encodeURIComponent(phone)+"%0AService: "+encodeURIComponent(service)+"%0APackage: "+encodeURIComponent(pkg)+"%0ADate: "+encodeURIComponent(date)+"%0ADetails: "+encodeURIComponent(details);
  window.open("https://wa.me/233553558771?text="+msg,"_blank");
}
</script>
</body>
</html>
