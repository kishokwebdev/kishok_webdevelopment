<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Kishok Studio</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700;900&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{--gold:#b8860b;--gold2:#d4a017;--bg:#faf9f6;--bg2:#f2f0eb;--bg3:#e8e4dc;--dark:#1a1a1a;--dark2:#2d2d2d;--muted:#888;--border:#ddd8ce;--white:#fff}
html{scroll-behavior:smooth}
body{font-family:'Outfit',sans-serif;background:var(--bg);color:var(--dark);overflow-x:hidden}
::-webkit-scrollbar{width:4px}::-webkit-scrollbar-track{background:var(--bg2)}::-webkit-scrollbar-thumb{background:var(--gold);border-radius:2px}

nav{position:fixed;top:0;left:0;right:0;z-index:1000;padding:16px 40px;display:flex;align-items:center;justify-content:space-between;background:rgba(250,249,246,0.94);backdrop-filter:blur(20px);border-bottom:1px solid var(--border)}
.nav-logo{font-family:'Playfair Display',serif;font-size:22px;font-weight:900;letter-spacing:2px;color:var(--gold);cursor:pointer}
.nav-links{display:flex;gap:28px;align-items:center}
.nav-links a{color:var(--muted);text-decoration:none;font-size:12px;letter-spacing:1.5px;text-transform:uppercase;transition:color .3s;cursor:pointer;font-weight:500}
.nav-links a:hover{color:var(--gold)}
.nav-btn{background:transparent;border:1.5px solid var(--gold);color:var(--gold);padding:8px 20px;border-radius:2px;font-size:11px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;transition:all .3s;font-family:'Outfit',sans-serif;font-weight:600}
.nav-btn:hover,.nav-btn.admin{background:var(--gold);color:var(--white)}

#hero{min-height:100vh;position:relative;display:flex;align-items:center;justify-content:center;overflow:hidden}
.hero-bg{position:absolute;inset:0;z-index:0}
.slide{position:absolute;inset:0;opacity:0;transition:opacity 1.2s ease-in-out}
.slide.active{opacity:1}
.slide-overlay{position:absolute;inset:0;background:linear-gradient(135deg,rgba(250,249,246,0.93),rgba(250,249,246,0.72),rgba(250,249,246,0.90))}
.slide::after{content:'';position:absolute;inset:0;background-image:linear-gradient(rgba(184,134,11,.06) 1px,transparent 1px),linear-gradient(90deg,rgba(184,134,11,.06) 1px,transparent 1px);background-size:50px 50px}
.particles{position:absolute;inset:0;overflow:hidden;z-index:1}
.particle{position:absolute;width:2px;height:2px;background:var(--gold);border-radius:50%;animation:float linear infinite;opacity:0}
@keyframes float{0%{transform:translateY(100vh);opacity:0}10%{opacity:.4}90%{opacity:.15}100%{transform:translateY(-80px) translateX(30px);opacity:0}}
.hero-content{position:relative;z-index:2;text-align:center;padding:0 20px;max-width:860px}
.hero-tag{font-size:11px;letter-spacing:5px;text-transform:uppercase;color:var(--gold);margin-bottom:24px;opacity:0;animation:fadeUp 1s .3s forwards}
.hero-title{font-family:'Playfair Display',serif;font-size:clamp(48px,7vw,90px);font-weight:900;line-height:1.05;margin-bottom:20px;color:var(--dark);opacity:0;animation:fadeUp 1s .5s forwards}
.hero-title span{color:var(--gold)}
.hero-sub{font-size:clamp(14px,1.8vw,17px);color:var(--muted);margin-bottom:44px;opacity:0;animation:fadeUp 1s .7s forwards}
.hero-btns{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;opacity:0;animation:fadeUp 1s .9s forwards}
.btn-primary{background:var(--gold);color:var(--white);padding:15px 40px;border:none;font-family:'Outfit',sans-serif;font-size:12px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;font-weight:600;transition:all .3s;border-radius:2px}
.btn-primary:hover{background:var(--gold2);transform:translateY(-2px)}
.btn-outline{background:transparent;color:var(--dark);padding:15px 40px;border:1.5px solid var(--border);font-family:'Outfit',sans-serif;font-size:12px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;font-weight:500;transition:all .3s;border-radius:2px}
.btn-outline:hover{border-color:var(--gold);color:var(--gold)}
.slide-counter{position:absolute;bottom:36px;right:36px;z-index:10;font-size:11px;letter-spacing:2px;color:var(--muted)}
.slide-dots{position:absolute;bottom:36px;left:50%;transform:translateX(-50%);z-index:10;display:flex;gap:6px}
.dot{width:18px;height:2px;background:var(--border);cursor:pointer;transition:all .3s}
.dot.active{background:var(--gold);width:36px}
@keyframes fadeUp{from{opacity:0;transform:translateY(28px)}to{opacity:1;transform:translateY(0)}}

#about{padding:110px 40px;background:var(--white);border-top:1px solid var(--border)}
.about-grid{max-width:1060px;margin:0 auto;display:grid;grid-template-columns:1fr 1fr;gap:72px;align-items:center}
.section-label{font-size:10px;letter-spacing:5px;text-transform:uppercase;color:var(--gold);margin-bottom:14px;font-weight:600}
.section-title{font-family:'Playfair Display',serif;font-size:clamp(32px,3.5vw,50px);font-weight:700;line-height:1.15;margin-bottom:22px}
.section-text{color:var(--muted);line-height:1.85;font-size:15px;margin-bottom:28px}
.stat-row{display:flex;gap:36px}
.stat-num{font-family:'Playfair Display',serif;font-size:40px;font-weight:900;color:var(--gold)}
.stat-label{font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-top:4px}
.about-card{background:var(--bg2);border:1px solid var(--border);padding:36px;border-radius:4px;position:relative}
.about-card::before{content:'';position:absolute;top:0;left:0;width:50px;height:3px;background:var(--gold)}
.profile-ring{width:88px;height:88px;border-radius:50%;border:2px solid var(--gold);display:flex;align-items:center;justify-content:center;margin:0 auto 20px;font-family:'Playfair Display',serif;font-size:32px;font-weight:900;color:var(--gold);background:var(--white)}
.skill-bar{margin-bottom:18px}
.skill-label{display:flex;justify-content:space-between;font-size:11px;margin-bottom:7px;letter-spacing:1px}
.bar-bg{height:3px;background:var(--border);border-radius:2px;overflow:hidden}
.bar-fill{height:100%;border-radius:2px;background:linear-gradient(90deg,var(--gold),var(--gold2));width:0;transition:width 1.5s ease}

#services{padding:110px 40px;background:var(--bg)}
.services-header{text-align:center;max-width:560px;margin:0 auto 52px}
.services-grid{max-width:1060px;margin:0 auto;display:grid;grid-template-columns:repeat(auto-fit,minmax(290px,1fr));gap:1px;background:var(--border)}
.service-card{background:var(--white);padding:40px 34px;transition:all .3s;position:relative}
.service-card:hover{box-shadow:0 20px 50px rgba(0,0,0,.08);z-index:2;transform:translateY(-4px)}
.svc-photo-wrap{width:100%;height:175px;border-radius:3px;margin-bottom:22px;background:var(--bg3);display:flex;align-items:center;justify-content:center;overflow:hidden}
.svc-photo-wrap img{width:100%;height:100%;object-fit:cover}
.svc-placeholder{color:var(--muted);font-size:12px;letter-spacing:1px;text-align:center;padding:16px}
.service-icon{font-size:30px;margin-bottom:16px;display:block}
.service-name{font-family:'Playfair Display',serif;font-size:21px;font-weight:700;margin-bottom:11px}
.service-desc{color:var(--muted);line-height:1.75;font-size:13.5px;margin-bottom:18px}
.price-row{display:flex;align-items:baseline;gap:8px;margin-bottom:6px}
.price-main{font-size:28px;font-weight:700;color:var(--gold);font-family:'Playfair Display',serif}
.price-original{font-size:14px;color:var(--muted);text-decoration:line-through}
.svc-offer{display:inline-block;background:rgba(184,134,11,.1);border:1px solid rgba(184,134,11,.3);color:var(--gold);font-size:10px;letter-spacing:1.5px;padding:5px 12px;text-transform:uppercase;margin-bottom:14px;border-radius:2px;font-weight:600}
.svc-conditions{margin-top:14px;padding-top:14px;border-top:1px solid var(--border)}
.cond-title{font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--muted);margin-bottom:9px;font-weight:600}
.cond-item{display:flex;align-items:flex-start;gap:8px;font-size:12px;color:var(--dark2);margin-bottom:6px;line-height:1.5}
.cond-dot{color:var(--gold);font-size:13px;flex-shrink:0;line-height:1.4}
.order-svc-btn{width:100%;margin-top:18px;background:var(--gold);color:var(--white);border:none;padding:13px;font-family:'Outfit',sans-serif;font-size:11px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;font-weight:600;transition:all .3s;border-radius:2px}
.order-svc-btn:hover{background:var(--gold2)}

#order{padding:110px 40px;background:var(--white);border-top:1px solid var(--border)}
.order-wrap{max-width:740px;margin:0 auto}
.order-form{background:var(--bg2);border:1px solid var(--border);padding:50px;border-radius:4px;position:relative}
.order-form::before{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,var(--gold),var(--gold2))}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:18px;margin-bottom:18px}
.fg{margin-bottom:18px}
.fg label{display:block;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);margin-bottom:9px;font-weight:600}
.fg input,.fg select,.fg textarea{width:100%;background:var(--white);border:1px solid var(--border);color:var(--dark);padding:13px 16px;font-family:'Outfit',sans-serif;font-size:13px;outline:none;transition:border-color .3s;border-radius:2px}
.fg input:focus,.fg select:focus,.fg textarea:focus{border-color:var(--gold)}
.fg select option{background:var(--white)}
.fg textarea{height:88px;resize:vertical}
.upload-area{border:1.5px dashed var(--border);padding:26px;text-align:center;cursor:pointer;transition:all .3s;border-radius:2px;background:var(--white)}
.upload-area:hover{border-color:var(--gold)}
.upload-area input{display:none}
.upload-txt{color:var(--muted);font-size:12px}
.upload-txt strong{color:var(--gold)}
.submit-btn{width:100%;background:var(--gold);color:var(--white);padding:17px;border:none;font-family:'Outfit',sans-serif;font-size:12px;letter-spacing:3px;text-transform:uppercase;cursor:pointer;font-weight:700;transition:all .3s;margin-top:10px;border-radius:2px}
.submit-btn:hover{background:var(--gold2)}
.form-note{text-align:center;font-size:11px;color:var(--muted);margin-top:14px}

/* EDIT PANEL */
.edit-overlay{position:fixed;inset:0;background:rgba(0,0,0,.35);z-index:1999;display:none}
#editPanel{display:none;position:fixed;top:0;right:0;bottom:0;width:430px;background:var(--white);border-left:1px solid var(--border);z-index:2000;overflow-y:auto;box-shadow:-8px 0 40px rgba(0,0,0,.1)}
.ep-header{padding:22px 26px;border-bottom:1px solid var(--border);display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;background:var(--white);z-index:1}
.ep-title{font-family:'Playfair Display',serif;font-size:19px;font-weight:700}
.ep-sub{font-size:11px;color:var(--muted);margin-top:2px}
.ep-close{background:transparent;border:none;font-size:22px;cursor:pointer;color:var(--muted);line-height:1;transition:color .3s}
.ep-close:hover{color:var(--dark)}
.ep-body{padding:26px}
.ep-section{margin-bottom:26px}
.ep-section-title{font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:14px;font-weight:600;border-bottom:1px solid var(--border);padding-bottom:8px}
.ep-group{margin-bottom:14px}
.ep-label{font-size:11px;letter-spacing:1px;text-transform:uppercase;color:var(--dark2);margin-bottom:7px;display:block;font-weight:500}
.ep-input,.ep-textarea,.ep-select{width:100%;background:var(--bg2);border:1px solid var(--border);color:var(--dark);padding:10px 13px;font-family:'Outfit',sans-serif;font-size:13px;outline:none;transition:border-color .3s;border-radius:2px}
.ep-input:focus,.ep-textarea:focus{border-color:var(--gold)}
.ep-textarea{resize:vertical;min-height:78px;line-height:1.6}
.svc-tabs{display:flex;gap:8px;margin-bottom:22px;flex-wrap:wrap}
.svc-tab{padding:7px 15px;border:1px solid var(--border);background:var(--bg2);font-size:11px;letter-spacing:1px;text-transform:uppercase;cursor:pointer;border-radius:2px;font-family:'Outfit',sans-serif;transition:all .3s;color:var(--muted)}
.svc-tab.active{background:var(--gold);color:var(--white);border-color:var(--gold)}
.ep-upload{border:1.5px dashed var(--border);padding:22px;text-align:center;cursor:pointer;transition:all .3s;border-radius:2px;background:var(--bg2)}
.ep-upload:hover{border-color:var(--gold)}
.ep-upload input{display:none}
.ep-upload-txt{font-size:12px;color:var(--muted)}
.ep-upload-txt strong{color:var(--gold)}
.photo-prev{width:100%;height:110px;object-fit:cover;border-radius:3px;margin-top:10px;display:none}
.cond-row{display:flex;gap:8px;margin-bottom:8px;align-items:center}
.cond-row input{flex:1;background:var(--bg2);border:1px solid var(--border);color:var(--dark);padding:8px 11px;font-family:'Outfit',sans-serif;font-size:12px;outline:none;border-radius:2px}
.cond-row input:focus{border-color:var(--gold)}
.cond-remove{background:transparent;border:1px solid var(--border);color:var(--muted);width:28px;height:28px;border-radius:2px;cursor:pointer;font-size:14px;flex-shrink:0;transition:all .3s;display:flex;align-items:center;justify-content:center}
.cond-remove:hover{border-color:#e74c3c;color:#e74c3c}
.add-cond-btn{background:transparent;border:1px dashed var(--border);color:var(--muted);padding:8px 14px;font-size:11px;letter-spacing:1px;cursor:pointer;border-radius:2px;font-family:'Outfit',sans-serif;transition:all .3s;width:100%;margin-top:4px}
.add-cond-btn:hover{border-color:var(--gold);color:var(--gold)}
.save-btn{width:100%;background:var(--gold);color:var(--white);border:none;padding:14px;font-family:'Outfit',sans-serif;font-size:12px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;font-weight:700;border-radius:2px;transition:all .3s;margin-top:6px}
.save-btn:hover{background:var(--gold2)}

/* MODALS */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,.5);z-index:3000;display:flex;align-items:center;justify-content:center;opacity:0;pointer-events:none;transition:opacity .3s;padding:20px}
.modal-overlay.open{opacity:1;pointer-events:all}
.modal{background:var(--white);border:1px solid var(--border);max-width:450px;width:100%;border-radius:4px;transform:translateY(16px);transition:transform .3s;overflow:hidden;max-height:90vh;overflow-y:auto}
.modal-overlay.open .modal{transform:translateY(0)}
.modal-stripe{height:3px;background:linear-gradient(90deg,var(--gold),var(--gold2))}
.modal-head{padding:30px 34px 18px;position:relative}
.modal-title{font-family:'Playfair Display',serif;font-size:21px;font-weight:700}
.modal-sub{color:var(--muted);font-size:12px;margin-top:4px}
.modal-close{position:absolute;top:18px;right:18px;background:transparent;border:none;color:var(--muted);font-size:20px;cursor:pointer;line-height:1;transition:color .3s}
.modal-close:hover{color:var(--dark)}
.modal-body{padding:18px 34px 34px}
.modal-body .fg{margin-bottom:14px}
.modal-body input{width:100%;background:var(--bg2);border:1px solid var(--border);color:var(--dark);padding:12px 15px;font-family:'Outfit',sans-serif;font-size:13px;outline:none;transition:border-color .3s;border-radius:2px}
.modal-body input:focus{border-color:var(--gold)}
.modal-btn{width:100%;background:var(--gold);color:var(--white);padding:14px;border:none;font-family:'Outfit',sans-serif;font-size:11px;letter-spacing:3px;text-transform:uppercase;cursor:pointer;font-weight:700;border-radius:2px;transition:all .3s}
.modal-btn:hover{background:var(--gold2)}
.err-msg{color:#c0392b;font-size:11px;margin-top:8px;display:none;background:rgba(192,57,43,.07);padding:8px 12px;border-radius:2px}

/* CONFIRM */
.confirm-overlay{position:fixed;inset:0;background:rgba(0,0,0,.5);z-index:4000;display:flex;align-items:center;justify-content:center;opacity:0;pointer-events:none;transition:opacity .3s;padding:20px}
.confirm-overlay.open{opacity:1;pointer-events:all}
.confirm-box{background:var(--white);border:1px solid var(--border);padding:42px 34px;max-width:410px;width:100%;text-align:center;border-radius:4px;position:relative;overflow:hidden}
.confirm-box::before{content:'';position:absolute;top:0;left:0;right:0;height:3px;background:linear-gradient(90deg,var(--gold),var(--gold2))}
.confirm-title{font-family:'Playfair Display',serif;font-size:22px;margin-bottom:10px}
.confirm-text{color:var(--muted);font-size:13px;line-height:1.75;margin-bottom:26px}
.confirm-btns{display:flex;gap:12px;justify-content:center}
.confirm-yes{background:var(--gold);color:var(--white);padding:13px 34px;border:none;font-family:'Outfit',sans-serif;font-size:11px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;font-weight:700;border-radius:2px;transition:all .3s}
.confirm-yes:hover{background:var(--gold2)}
.confirm-no{background:transparent;color:var(--dark);padding:13px 34px;border:1.5px solid var(--border);font-family:'Outfit',sans-serif;font-size:11px;letter-spacing:2px;text-transform:uppercase;cursor:pointer;border-radius:2px;transition:all .3s}
.confirm-no:hover{border-color:var(--gold);color:var(--gold)}

/* DASHBOARD */
#dashboard{display:none;min-height:100vh;padding:88px 40px 60px;background:var(--bg)}
.dash-header{max-width:1060px;margin:0 auto 32px;display:flex;align-items:center;justify-content:space-between}
.dash-welcome{font-family:'Playfair Display',serif;font-size:26px}
.dash-welcome span{color:var(--gold)}
.dash-actions{display:flex;gap:10px}
.dash-btn{padding:10px 18px;border:1.5px solid var(--border);background:var(--white);color:var(--dark2);font-size:11px;letter-spacing:1.5px;cursor:pointer;border-radius:2px;font-family:'Outfit',sans-serif;transition:all .3s;font-weight:500;text-transform:uppercase}
.dash-btn:hover{border-color:var(--gold);color:var(--gold)}
.dash-btn.primary{background:var(--gold);color:var(--white);border-color:var(--gold)}
.dash-btn.primary:hover{background:var(--gold2)}
.orders-section{max-width:1060px;margin:0 auto}
.orders-lbl{font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);font-weight:600;margin-bottom:18px}
.order-card{background:var(--white);border:1px solid var(--border);padding:24px;margin-bottom:12px;border-radius:4px;display:grid;grid-template-columns:1fr auto;gap:16px;align-items:start}
.order-card:hover{box-shadow:0 4px 20px rgba(0,0,0,.06)}
.order-info h4{font-family:'Playfair Display',serif;font-size:17px;margin-bottom:6px}
.order-info p{color:var(--muted);font-size:12px;line-height:1.7}
.order-badge{background:rgba(184,134,11,.1);border:1px solid rgba(184,134,11,.3);color:var(--gold);font-size:10px;letter-spacing:2px;padding:5px 13px;text-transform:uppercase;border-radius:2px;font-weight:600;white-space:nowrap}
.reply-wa{display:block;margin-top:9px;background:transparent;border:1px solid var(--border);color:var(--muted);padding:7px 13px;font-size:10px;letter-spacing:1px;cursor:pointer;border-radius:2px;font-family:'Outfit',sans-serif;transition:all .3s;width:100%;text-align:center}
.reply-wa:hover{border-color:#25d366;color:#25d366}
.no-orders{text-align:center;padding:64px;color:var(--muted)}

footer{background:var(--dark);color:var(--white);padding:52px 40px 34px;text-align:center}
.footer-logo{font-family:'Playfair Display',serif;font-size:26px;font-weight:900;color:var(--gold);margin-bottom:12px}
.footer-text{color:rgba(255,255,255,.4);font-size:12px;line-height:1.8}
.footer-divider{width:48px;height:1px;background:var(--gold);margin:18px auto}

.reveal{opacity:0;transform:translateY(32px);transition:opacity .8s ease,transform .8s ease}
.reveal.visible{opacity:1;transform:translateY(0)}

.notif{position:fixed;bottom:26px;right:26px;background:var(--dark);color:var(--white);padding:13px 20px;font-size:12px;z-index:9999;opacity:0;transform:translateY(10px);transition:all .4s;border-radius:3px;max-width:280px;border-left:3px solid var(--gold)}
.notif.show{opacity:1;transform:translateY(0)}

@media(max-width:768px){nav{padding:14px 18px}.nav-links{display:none}.about-grid{grid-template-columns:1fr;gap:36px}.form-row{grid-template-columns:1fr}.order-form{padding:26px 18px}#about,#services,#order{padding:68px 18px}#editPanel{width:100%}}
</style>
</head>
<body>

<nav id="mainNav">
  <div class="nav-logo" onclick="ss('#hero')">K·STUDIO</div>
  <div class="nav-links">
    <a onclick="ss('#about')">About</a>
    <a onclick="ss('#services')">Services</a>
    <a onclick="ss('#order')">Order</a>
    <button class="nav-btn" onclick="openModal('client')">Client Login</button>
    <button class="nav-btn admin" onclick="openModal('admin')">Provider Login</button>
  </div>
</nav>

<section id="hero">
  <div class="hero-bg" id="heroBg"><div class="particles" id="particles"></div></div>
  <div class="hero-content">
    <div class="hero-tag">✦ Digital Excellence Studio ✦</div>
    <h1 class="hero-title">Where Data<br>Meets <span>Design</span></h1>
    <p class="hero-sub">Premium Web Development & Data Analytics — Crafted with Precision & Purpose</p>
    <div class="hero-btns">
      <button class="btn-primary" onclick="ss('#services')">Explore Services</button>
      <button class="btn-outline" onclick="ss('#order')">Place Order</button>
    </div>
  </div>
  <div class="slide-counter" id="slideCounter">01 / 20</div>
  <div class="slide-dots" id="slideDots"></div>
</section>

<section id="about">
  <div class="about-grid">
    <div class="reveal">
      <div class="section-label">The Craftsman</div>
      <h2 class="section-title">Building Digital<br><span style="color:var(--gold)">Masterpieces</span></h2>
      <p class="section-text">Every pixel intentional. Every data point meaningful. Websites that don't just look beautiful — they convert, engage, and grow your business with precision and purpose.</p>
      <div class="stat-row">
        <div><div class="stat-num">50+</div><div class="stat-label">Projects Done</div></div>
        <div><div class="stat-num">98%</div><div class="stat-label">Satisfaction</div></div>
        <div><div class="stat-num">3+</div><div class="stat-label">Years Exp.</div></div>
      </div>
    </div>
    <div class="reveal">
      <div class="about-card">
        <div class="profile-ring">K</div>
        <h3 style="font-family:'Playfair Display',serif;text-align:center;margin-bottom:6px;font-size:20px">Kishok</h3>
        <p style="text-align:center;color:var(--muted);font-size:12px;margin-bottom:24px;letter-spacing:1px;text-transform:uppercase">Web Developer & Data Analyst</p>
        <div class="skill-bar"><div class="skill-label"><span>Web Development</span><span style="color:var(--gold)">95%</span></div><div class="bar-bg"><div class="bar-fill" data-width="95"></div></div></div>
        <div class="skill-bar"><div class="skill-label"><span>Data Analytics</span><span style="color:var(--gold)">88%</span></div><div class="bar-bg"><div class="bar-fill" data-width="88"></div></div></div>
        <div class="skill-bar"><div class="skill-label"><span>UI/UX Design</span><span style="color:var(--gold)">82%</span></div><div class="bar-bg"><div class="bar-fill" data-width="82"></div></div></div>
        <div class="skill-bar"><div class="skill-label"><span>SEO & Optimization</span><span style="color:var(--gold)">78%</span></div><div class="bar-bg"><div class="bar-fill" data-width="78"></div></div></div>
      </div>
    </div>
  </div>
</section>

<section id="services">
  <div class="services-header reveal">
    <div class="section-label">What I Offer</div>
    <h2 class="section-title">Services Built for<br><span style="color:var(--gold)">Results</span></h2>
  </div>
  <div class="services-grid reveal" id="servicesGrid"></div>
</section>

<section id="order">
  <div style="text-align:center;max-width:540px;margin:0 auto 44px" class="reveal">
    <div class="section-label">Start Your Journey</div>
    <h2 class="section-title">Place Your <span style="color:var(--gold)">Order</span></h2>
    <p style="color:var(--muted);margin-top:12px;font-size:14px">Response guaranteed within 20 minutes.</p>
  </div>
  <div class="order-wrap reveal">
    <div class="order-form">
      <div class="form-row">
        <div class="fg"><label>Your Name</label><input type="text" id="oName" placeholder="Your full name"></div>
        <div class="fg"><label>Phone Number</label><input type="tel" id="oPhone" placeholder="+91 XXXXXXXXXX"></div>
      </div>
      <div class="fg"><label>Email Address</label><input type="email" id="oEmail" placeholder="your@email.com"></div>
      <div class="fg"><label>Service Required</label><select id="oService"><option value="">Select a service</option></select></div>
      <div class="fg"><label>Project Details</label><textarea id="oDetails" placeholder="Describe your project, requirements, deadline..."></textarea></div>
      <div class="fg">
        <label>Upload Reference Files (optional)</label>
        <div class="upload-area" onclick="document.getElementById('fileInput').click()">
          <input type="file" id="fileInput" multiple accept="image/*,video/*,.pdf,.doc,.docx" onchange="handleUpload(this)">
          <div class="upload-txt" id="uploadTxt"><strong>Click to upload</strong> photos, videos or documents<br><span style="font-size:11px">JPG, PNG, MP4, PDF, DOC supported</span></div>
        </div>
      </div>
      <button class="submit-btn" onclick="submitOrder()">✦ Place Order Now ✦</button>
      <p style="text-align:center;font-size:11px;color:var(--muted);margin-top:14px">Your order reaches Kishok directly. No middleman.</p>
    </div>
  </div>
</section>

<footer>
  <div class="footer-logo">K·STUDIO</div>
  <div class="footer-divider"></div>
  <div class="footer-text">Crafting digital excellence, one project at a time.<br>© 2025 Kishok Studio. All rights reserved.</div>
</footer>

<!-- EDIT PANEL -->
<div class="edit-overlay" id="editOverlay" onclick="closeEP()"></div>
<div id="editPanel">
  <div class="ep-header">
    <div><div class="ep-title">Edit Services</div><div class="ep-sub">Provider Panel — Live Edit</div></div>
    <button class="ep-close" onclick="closeEP()">×</button>
  </div>
  <div class="ep-body">
    <div class="svc-tabs" id="svcTabs"></div>

    <div class="ep-section">
      <div class="ep-section-title">Service Photo</div>
      <div class="ep-group">
        <div class="ep-upload" onclick="document.getElementById('svcPhotoInput').click()">
          <input type="file" id="svcPhotoInput" accept="image/*" onchange="handleSvcPhoto(this)">
          <div class="ep-upload-txt" id="photoUploadTxt"><strong>Click to upload photo</strong><br><span style="font-size:11px">JPG, PNG — 600×300px recommended</span></div>
        </div>
        <img id="photoPrev" class="photo-prev" alt="Preview">
      </div>
    </div>

    <div class="ep-section">
      <div class="ep-section-title">Basic Info</div>
      <div class="ep-group"><label class="ep-label">Service Name</label><input class="ep-input" id="eName" placeholder="e.g. Web Development"></div>
      <div class="ep-group"><label class="ep-label">Icon / Emoji</label><input class="ep-input" id="eIcon" placeholder="e.g. ⬡ or 💻"></div>
      <div class="ep-group"><label class="ep-label">Description</label><textarea class="ep-textarea" id="eDesc" placeholder="What does this service include?"></textarea></div>
    </div>

    <div class="ep-section">
      <div class="ep-section-title">Pricing</div>
      <div class="ep-group"><label class="ep-label">Price (₹)</label><input class="ep-input" id="ePrice" type="number" placeholder="e.g. 4999"></div>
      <div class="ep-group"><label class="ep-label">Original Price (₹) — strikethrough</label><input class="ep-input" id="eOriginal" type="number" placeholder="e.g. 7999 (leave blank to hide)"></div>
      <div class="ep-group"><label class="ep-label">Offer / Badge Text</label><input class="ep-input" id="eOffer" placeholder="e.g. 🔥 30% OFF — Limited Time"></div>
    </div>

    <div class="ep-section">
      <div class="ep-section-title">Terms & Conditions</div>
      <div id="condList"></div>
      <button class="add-cond-btn" onclick="addCond()">+ Add Condition</button>
    </div>

    <button class="save-btn" onclick="saveSvc()">Save Changes ✓</button>
  </div>
</div>

<!-- CLIENT MODAL -->
<div class="modal-overlay" id="clientModal">
  <div class="modal">
    <div class="modal-stripe"></div>
    <div class="modal-head">
      <button class="modal-close" onclick="closeModal('clientModal')">×</button>
      <div class="modal-title">Client Portal</div>
      <div class="modal-sub">Track your project progress</div>
    </div>
    <div class="modal-body">
      <div id="cLoginForm">
        <div class="fg"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Email</label><input type="email" id="cEmail" placeholder="your@email.com"></div>
        <div class="fg" style="margin-bottom:18px"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Password</label><input type="password" id="cPass" placeholder="••••••••"></div>
        <div class="err-msg" id="clientErr">Invalid credentials. Please try again.</div>
        <button class="modal-btn" onclick="clientLogin()">Access Portal</button>
        <p style="text-align:center;margin-top:16px;font-size:12px;color:var(--muted)">No account? <span style="color:var(--gold);cursor:pointer;font-weight:600" onclick="showReg()">Register →</span></p>
      </div>
      <div id="cRegForm" style="display:none">
        <div class="fg"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Full Name</label><input type="text" id="rName" placeholder="Your name"></div>
        <div class="fg"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Email</label><input type="email" id="rEmail" placeholder="your@email.com"></div>
        <div class="fg" style="margin-bottom:18px"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Password</label><input type="password" id="rPass" placeholder="Create a password"></div>
        <button class="modal-btn" onclick="registerClient()">Create Account</button>
        <p style="text-align:center;margin-top:16px;font-size:12px;color:var(--muted)">Already have an account? <span style="color:var(--gold);cursor:pointer;font-weight:600" onclick="showLogin()">Login →</span></p>
      </div>
    </div>
  </div>
</div>

<!-- ADMIN MODAL -->
<div class="modal-overlay" id="adminModal">
  <div class="modal">
    <div class="modal-stripe"></div>
    <div class="modal-head">
      <button class="modal-close" onclick="closeModal('adminModal')">×</button>
      <div class="modal-title">Provider Access</div>
      <div class="modal-sub">Authorized personnel only</div>
    </div>
    <div class="modal-body">
      <div class="fg"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Username</label><input type="text" id="aUser" placeholder="Username"></div>
      <div class="fg"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Password</label><input type="password" id="aPass" placeholder="••••••••"></div>
      <div class="fg"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Security Code</label><input type="password" id="aCode" placeholder="••••"></div>
      <div class="fg" style="margin-bottom:18px"><label style="font-size:10px;letter-spacing:2px;text-transform:uppercase;color:var(--gold);display:block;margin-bottom:8px;font-weight:600">Pet Name</label><input type="text" id="aPet" placeholder="Security answer"></div>
      <div class="err-msg" id="adminErr">Access denied. Check all credentials.</div>
      <button class="modal-btn" onclick="adminLogin()">Authenticate</button>
    </div>
  </div>
</div>

<!-- CONFIRM -->
<div class="confirm-overlay" id="confirmOverlay">
  <div class="confirm-box">
    <div style="font-size:40px;margin-bottom:16px">📋</div>
    <div class="confirm-title">Confirm Order</div>
    <div class="confirm-text" id="confirmText"></div>
    <div class="confirm-btns">
      <button class="confirm-yes" onclick="confirmOrder()">Yes, Confirm ✓</button>
      <button class="confirm-no" onclick="closeConfirm()">Review Again</button>
    </div>
  </div>
</div>

<!-- DASHBOARD -->
<div id="dashboard">
  <div class="dash-header">
    <div>
      <div style="font-size:10px;letter-spacing:3px;text-transform:uppercase;color:var(--gold);margin-bottom:8px;font-weight:600">Provider Dashboard</div>
      <div class="dash-welcome">Welcome, <span>Kishok</span> 👋</div>
    </div>
    <div class="dash-actions">
      <button class="dash-btn primary" onclick="openEP()">✏ Edit Services</button>
      <button class="dash-btn" onclick="logout()">Logout</button>
    </div>
  </div>
  <div class="orders-section">
    <div class="orders-lbl">Incoming Orders</div>
    <div id="ordersContainer"></div>
  </div>
</div>

<div class="notif" id="notif"></div>

<script>
const OWNER={user:'kishok',pass:'priya775',code:'8226',pet:'sarco'};
let clients=JSON.parse(localStorage.getItem('ks_clients')||'[]');
let orders=JSON.parse(localStorage.getItem('ks_orders')||'[]');
let pendingOrder=null;
let editingSvc=0;
let svcPhotos={};

const defaultSvcs=[
  {name:'Web Development',icon:'⬡',desc:'Cinematic-level websites that captivate your audience, drive conversions, and establish trust from the first second. Built with modern tech for speed and scale.',price:4999,original:7999,offer:'🔥 Launch Offer — 30% Off',photo:'',conditions:['100% responsive & mobile-first design','3 rounds of revisions included','Delivery within 7–14 working days','Source code handed over on completion']},
  {name:'Data Analytics',icon:'◈',desc:'Transform raw data into actionable insights. Interactive dashboards, trend analysis, and business intelligence that drive smart decisions.',price:3999,original:5999,offer:'📊 Free Consultation Included',photo:'',conditions:['Custom dashboard tailored to your data','Weekly progress reports shared','Delivery within 5–10 working days','Supports Excel, CSV, SQL, and APIs']},
  {name:'Full Package',icon:'◇',desc:'Complete digital presence — stunning website + powerful analytics dashboard. Everything you need to dominate your market online.',price:7999,original:12000,offer:'⭐ Best Value — Save ₹4,000',photo:'',conditions:['Includes both web & analytics services','Priority support for 30 days','Dedicated WhatsApp project channel','Payment: 50% advance + 50% on delivery']}
];

let services=JSON.parse(localStorage.getItem('ks_services')||JSON.stringify(defaultSvcs));

// SLIDES
const grads=[
  ['#f0e8d8','#e8dcc8'],['#dce8f0','#c8d8e8'],['#e8f0dc','#d8e8c8'],
  ['#f0dce8','#e8c8d8'],['#dcf0e8','#c8e8d8'],['#f0f0dc','#e8e8c8'],
  ['#dcdcf0','#c8c8e8'],['#f0e8dc','#e8d8c8'],['#dcf0f0','#c8e8e8'],
  ['#f0dce0','#e8c8cc'],['#e0f0dc','#cce8c8'],['#dce0f0','#c8cce8'],
  ['#f0f0e8','#e8e8d8'],['#e8dcf0','#d8c8e8'],['#f0ece0','#e8dcd0'],
  ['#e0ece8','#d0dcd8'],['#ece8e0','#dcd8d0'],['#e8f0e8','#d8e8d8'],
  ['#f0e8f0','#e8d8e8'],['#e8ecf0','#d8dce8']
];
let curSlide=0;
const heroBg=document.getElementById('heroBg');
const dotsEl=document.getElementById('slideDots');
const ctrEl=document.getElementById('slideCounter');
grads.forEach((c,i)=>{
  const s=document.createElement('div');s.className='slide';
  s.style.background=`linear-gradient(135deg,${c[0]},${c[1]})`;
  s.innerHTML='<div class="slide-overlay"></div>';heroBg.appendChild(s);
  const d=document.createElement('div');d.className='dot'+(i===0?' active':'');
  d.onclick=()=>goSlide(i);dotsEl.appendChild(d);
});
const pEl=document.getElementById('particles');
for(let i=0;i<18;i++){const p=document.createElement('div');p.className='particle';p.style.cssText=`left:${Math.random()*100}%;animation-duration:${10+Math.random()*12}s;animation-delay:${Math.random()*10}s;width:${1+Math.random()*2}px;height:${1+Math.random()*2}px`;pEl.appendChild(p);}
const allSlides=heroBg.querySelectorAll('.slide');allSlides[0].classList.add('active');
function goSlide(n){allSlides[curSlide].classList.remove('active');dotsEl.children[curSlide].classList.remove('active');curSlide=n%grads.length;allSlides[curSlide].classList.add('active');dotsEl.children[curSlide].classList.add('active');ctrEl.textContent=(curSlide+1).toString().padStart(2,'0')+' / 20';}
setInterval(()=>goSlide(curSlide+1),2000);

// RENDER SERVICES
function renderSvcs(){
  const grid=document.getElementById('servicesGrid');
  grid.innerHTML=services.map((s,i)=>`
    <div class="service-card">
      <div class="svc-photo-wrap">${s.photo?`<img src="${s.photo}" alt="${s.name}">`:`<div class="svc-placeholder">${s.icon||'⬡'}<br><br><span style="font-size:11px">${s.name}</span></div>`}</div>
      <span class="service-icon">${s.icon}</span>
      <div class="service-name">${s.name}</div>
      <div class="service-desc">${s.desc}</div>
      <div class="price-row"><div class="price-main">₹${Number(s.price).toLocaleString('en-IN')}</div>${s.original?`<div class="price-original">₹${Number(s.original).toLocaleString('en-IN')}</div>`:''}</div>
      ${s.offer?`<div class="svc-offer">${s.offer}</div>`:''}
      ${s.conditions&&s.conditions.length?`<div class="svc-conditions"><div class="cond-title">Terms & Conditions</div>${s.conditions.map(c=>`<div class="cond-item"><span class="cond-dot">✦</span><span>${c}</span></div>`).join('')}</div>`:''}
      <button class="order-svc-btn" onclick="prefillOrder('${s.name}')">Order This Service →</button>
    </div>`).join('');
  const sel=document.getElementById('oService');
  sel.innerHTML='<option value="">Select a service</option>'+services.map(s=>`<option value="${s.name} — ₹${Number(s.price).toLocaleString('en-IN')}">${s.name} — ₹${Number(s.price).toLocaleString('en-IN')}</option>`).join('');
}
renderSvcs();

function prefillOrder(name){ss('#order');setTimeout(()=>{const sel=document.getElementById('oService');for(const o of sel.options){if(o.value.startsWith(name)){sel.value=o.value;break;}}},600);}

// SCROLL
function ss(sel){const el=document.querySelector(sel);if(el)el.scrollIntoView({behavior:'smooth'});}

// REVEAL
const obs=new IntersectionObserver(entries=>{entries.forEach(e=>{if(e.isIntersecting){e.target.classList.add('visible');e.target.querySelectorAll('.bar-fill').forEach(b=>{b.style.width=b.dataset.width+'%'});}});},{threshold:.12});
document.querySelectorAll('.reveal').forEach(el=>obs.observe(el));

// MODALS
function openModal(type){document.getElementById(type==='client'?'clientModal':'adminModal').classList.add('open');}
function closeModal(id){document.getElementById(id).classList.remove('open');['clientErr','adminErr'].forEach(e=>{const el=document.getElementById(e);if(el)el.style.display='none';});}
['clientModal','adminModal'].forEach(id=>document.getElementById(id).addEventListener('click',function(e){if(e.target===this)closeModal(id);}));

// ADMIN
function adminLogin(){
  const u=document.getElementById('aUser').value.trim().toLowerCase();
  const p=document.getElementById('aPass').value;
  const c=document.getElementById('aCode').value;
  const pet=document.getElementById('aPet').value.trim().toLowerCase();
  if(u===OWNER.user&&p===OWNER.pass&&c===OWNER.code&&pet===OWNER.pet){closeModal('adminModal');showDash();}
  else document.getElementById('adminErr').style.display='block';
}

// CLIENT
function showReg(){document.getElementById('cLoginForm').style.display='none';document.getElementById('cRegForm').style.display='block';}
function showLogin(){document.getElementById('cRegForm').style.display='none';document.getElementById('cLoginForm').style.display='block';}
function registerClient(){
  const n=document.getElementById('rName').value.trim(),e=document.getElementById('rEmail').value.trim(),p=document.getElementById('rPass').value;
  if(!n||!e||!p){showNotif('Fill all fields');return;}
  if(clients.find(c=>c.email===e)){showNotif('Email already registered');return;}
  clients.push({name:n,email:e,pass:p});localStorage.setItem('ks_clients',JSON.stringify(clients));
  showNotif('Account created! Login now.');showLogin();
}
function clientLogin(){
  const e=document.getElementById('cEmail').value.trim(),p=document.getElementById('cPass').value;
  const f=clients.find(c=>c.email===e&&c.pass===p);
  if(f){closeModal('clientModal');showNotif('Welcome, '+f.name+'!');}
  else document.getElementById('clientErr').style.display='block';
}

// EDIT PANEL
function openEP(){editingSvc=0;buildTabs();loadToPanel(0);document.getElementById('editPanel').style.display='block';document.getElementById('editOverlay').style.display='block';}
function closeEP(){document.getElementById('editPanel').style.display='none';document.getElementById('editOverlay').style.display='none';}
function buildTabs(){
  document.getElementById('svcTabs').innerHTML=services.map((s,i)=>`<div class="svc-tab${i===editingSvc?' active':''}" onclick="switchSvc(${i})">${s.name}</div>`).join('');
}
function switchSvc(i){editingSvc=i;buildTabs();loadToPanel(i);}
function loadToPanel(i){
  const s=services[i];
  document.getElementById('eName').value=s.name||'';
  document.getElementById('eIcon').value=s.icon||'';
  document.getElementById('eDesc').value=s.desc||'';
  document.getElementById('ePrice').value=s.price||'';
  document.getElementById('eOriginal').value=s.original||'';
  document.getElementById('eOffer').value=s.offer||'';
  const prev=document.getElementById('photoPrev');
  const txt=document.getElementById('photoUploadTxt');
  if(s.photo){prev.src=s.photo;prev.style.display='block';txt.innerHTML='<strong style="color:var(--gold)">Photo uploaded ✓</strong><br><span style="font-size:11px">Click to change</span>';}
  else{prev.style.display='none';txt.innerHTML='<strong>Click to upload photo</strong><br><span style="font-size:11px">JPG, PNG — 600×300px recommended</span>';}
  renderConds(s.conditions||[]);
}
function renderConds(conds){
  document.getElementById('condList').innerHTML=conds.map((c,i)=>`
    <div class="cond-row" id="cr${i}">
      <input type="text" value="${c.replace(/"/g,'&quot;')}" id="ci${i}" placeholder="e.g. Delivery within 7 days">
      <button class="cond-remove" onclick="removeCond(${i})">×</button>
    </div>`).join('');
}
function addCond(){
  const s=services[editingSvc];if(!s.conditions)s.conditions=[];
  s.conditions.push('');renderConds(s.conditions);
  const inputs=document.getElementById('condList').querySelectorAll('input');
  if(inputs.length)inputs[inputs.length-1].focus();
}
function removeCond(i){services[editingSvc].conditions.splice(i,1);renderConds(services[editingSvc].conditions);}
function handleSvcPhoto(input){
  const file=input.files[0];if(!file)return;
  const reader=new FileReader();
  reader.onload=function(e){
    svcPhotos[editingSvc]=e.target.result;
    const prev=document.getElementById('photoPrev');prev.src=e.target.result;prev.style.display='block';
    document.getElementById('photoUploadTxt').innerHTML='<strong style="color:var(--gold)">Photo uploaded ✓</strong><br><span style="font-size:11px">Click to change</span>';
  };reader.readAsDataURL(file);
}
function saveSvc(){
  const i=editingSvc;
  const condInputs=document.getElementById('condList').querySelectorAll('input');
  const conds=[];condInputs.forEach(inp=>{if(inp.value.trim())conds.push(inp.value.trim());});
  services[i]={...services[i],
    name:document.getElementById('eName').value.trim()||services[i].name,
    icon:document.getElementById('eIcon').value.trim()||services[i].icon,
    desc:document.getElementById('eDesc').value.trim()||services[i].desc,
    price:parseFloat(document.getElementById('ePrice').value)||services[i].price,
    original:parseFloat(document.getElementById('eOriginal').value)||'',
    offer:document.getElementById('eOffer').value.trim(),
    conditions:conds,photo:svcPhotos[i]||services[i].photo||''
  };
  localStorage.setItem('ks_services',JSON.stringify(services));
  buildTabs();renderSvcs();showNotif('✓ Service updated!');
}

// ORDER
function handleUpload(input){
  const files=Array.from(input.files);
  if(files.length)document.getElementById('uploadTxt').innerHTML=`<strong style="color:var(--gold)">✓ ${files.length} file(s) selected</strong><br><span style="font-size:11px">${files.map(f=>f.name).join(', ').slice(0,60)}</span>`;
}
function submitOrder(){
  const n=document.getElementById('oName').value.trim(),ph=document.getElementById('oPhone').value.trim(),em=document.getElementById('oEmail').value.trim(),sv=document.getElementById('oService').value,dt=document.getElementById('oDetails').value.trim();
  if(!n||!ph||!em||!sv||!dt){showNotif('Please fill all required fields');return;}
  pendingOrder={name:n,phone:ph,email:em,service:sv,details:dt,time:new Date().toLocaleString()};
  document.getElementById('confirmText').innerHTML=`<strong style="color:var(--gold);font-size:15px">${sv}</strong><br><br><table style="margin:0 auto;text-align:left;font-size:13px;border-collapse:collapse"><tr><td style="color:var(--muted);padding:3px 12px 3px 0">Name</td><td>${n}</td></tr><tr><td style="color:var(--muted);padding:3px 12px 3px 0">Phone</td><td>${ph}</td></tr><tr><td style="color:var(--muted);padding:3px 12px 3px 0">Email</td><td>${em}</td></tr></table><br><span style="font-size:12px;color:var(--muted)">Confirm to send your order to Kishok?</span>`;
  document.getElementById('confirmOverlay').classList.add('open');
}
function closeConfirm(){document.getElementById('confirmOverlay').classList.remove('open');}
function confirmOrder(){
  if(!pendingOrder)return;
  orders.push({...pendingOrder,id:'ORD'+Date.now()});localStorage.setItem('ks_orders',JSON.stringify(orders));
  const msg=`🔔 NEW ORDER — K·STUDIO\n\n👤 ${pendingOrder.name}\n📱 ${pendingOrder.phone}\n📧 ${pendingOrder.email}\n\n🛠 Service: ${pendingOrder.service}\n\n📝 ${pendingOrder.details}\n\n⏰ ${pendingOrder.time}`;
  const a=document.createElement('a');a.href=`https://wa.me/919578445549?text=${encodeURIComponent(msg)}`;a.target='_blank';a.rel='noopener';document.body.appendChild(a);a.click();document.body.removeChild(a);
  closeConfirm();
  ['oName','oPhone','oEmail','oDetails'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('oService').value='';
  document.getElementById('uploadTxt').innerHTML='<strong>Click to upload</strong> photos, videos or documents<br><span style="font-size:11px">JPG, PNG, MP4, PDF, DOC supported</span>';
  showNotif('✓ Order placed! Kishok will contact you within 20 minutes.');pendingOrder=null;
}

// DASHBOARD
function showDash(){
  ['hero','about','services','order'].forEach(id=>{const el=document.getElementById(id);if(el)el.style.display='none';});
  document.getElementById('mainNav').style.display='none';document.querySelector('footer').style.display='none';
  document.getElementById('dashboard').style.display='block';
  orders=JSON.parse(localStorage.getItem('ks_orders')||'[]');
  const c=document.getElementById('ordersContainer');
  if(orders.length===0){c.innerHTML='<div class="no-orders"><div style="font-size:34px;margin-bottom:12px">📭</div><p>No orders yet.</p></div>';}
  else{c.innerHTML=[...orders].reverse().map(o=>`<div class="order-card"><div class="order-info"><h4>${o.name}</h4><p>📱 ${o.phone} · 📧 ${o.email}<br>🛠 <strong>${o.service}</strong><br>${o.details.slice(0,120)}${o.details.length>120?'...':''}<br><span style="font-size:11px;color:var(--muted)">⏰ ${o.time}</span></p></div><div style="text-align:right"><div class="order-badge">New</div><button class="reply-wa" onclick="replyWA('${o.phone}','${o.name}')">💬 Reply on WhatsApp</button></div></div>`).join('');}
}
function replyWA(phone,name){const c=phone.replace(/\D/g,'');window.open(`https://wa.me/${c.startsWith('91')?c:'91'+c}?text=${encodeURIComponent('Hi '+name+', this is Kishok from K·Studio! Let\'s start your project 🚀')}`, '_blank');}
function logout(){
  ['hero','about','services','order'].forEach(id=>{const el=document.getElementById(id);if(el)el.style.display='';});
  document.getElementById('mainNav').style.display='flex';document.querySelector('footer').style.display='block';document.getElementById('dashboard').style.display='none';closeEP();
}

// NOTIF
function showNotif(msg){const n=document.getElementById('notif');n.textContent=msg;n.classList.add('show');setTimeout(()=>n.classList.remove('show'),4000);}
</script>
</body>
</html>
