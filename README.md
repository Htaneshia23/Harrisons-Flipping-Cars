!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Harrisons Flipping Cars — Social Media & Listings</title>
  <meta name="description" content="Harrisons Flipping Cars: social media content, listings, and ads for car flippers, private sellers, and small dealers." />
  <meta property="og:title" content="Harrisons Flipping Cars" />
  <meta property="og:description" content="Social media & listing services for car flippers and sellers." />
  <meta property="og:type" content="website" />
  <style>
    :root{
      --purple:#5910E5;
      --lime:#C3FF83;
      --bg:#0a0a0b;
      --card:#111115;
      --text:#ffffff;
      --muted:#bdbdbd;
      --outline: #2a2a33;
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:radial-gradient(1200px 800px at 10% 0%, rgba(89,16,229,.25), transparent 60%), radial-gradient(1200px 800px at 90% 10%, rgba(195,255,131,.15), transparent 60%), var(--bg); color:var(--text); font-family:system-ui,-apple-system,Segoe UI,Roboto,Inter,Arial,sans-serif;}
    a{color:var(--lime);text-decoration:none}
    a:hover{text-decoration:underline}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    /* Header */
    header{
      position:sticky; top:0; z-index:50;
      backdrop-filter:saturate(140%) blur(8px);
      background:rgba(10,10,11,.6);
      border-bottom:1px solid var(--outline);
    }
    .nav{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:10px;font-weight:800;letter-spacing:.2px}
    .badge{padding:4px 10px;border-radius:999px;background:linear-gradient(135deg,var(--purple),#3c0aa9); color:white; font-size:12px}
    nav a{margin:0 10px;color:#fff;opacity:.9}
    .socials{display:flex;gap:10px}
    .icon{width:22px;height:22px;display:inline-block;opacity:.9}
    .icon:hover{opacity:1;transform:translateY(-1px)}
    /* Hero */
    .hero{padding:72px 0 32px}
    .hero h1{font-size:clamp(28px,5vw,48px);line-height:1.1;margin:12px 0}
    .kicker{color:var(--lime);font-weight:700;letter-spacing:.5px;text-transform:uppercase;font-size:12px}
    .lead{max-width:760px;color:#e9e9ee;opacity:.9}
    .cta{display:flex;flex-wrap:wrap;gap:12px;margin-top:22px}
    .btn{border:1px solid var(--outline);background:var(--card);color:#fff;padding:12px 16px;border-radius:12px;font-weight:700}
    .btn:hover{border-color:var(--lime);box-shadow:0 0 0 3px rgba(195,255,131,.25)}
    .btn-primary{background:linear-gradient(135deg,var(--purple),#3c0aa9); border-color:transparent}
    .btn-primary:hover{box-shadow:0 0 0 3px rgba(89,16,229,.25)}
    /* Sections */
    section{padding:56px 0;border-top:1px solid var(--outline)}
    h2{font-size:clamp(22px,3.5vw,32px);margin:0 0 12px}
    .sub{color:var(--muted);margin-bottom:24px}
    /* Services grid */
    .grid{display:grid;grid-template-columns:repeat(12,1fr);gap:16px}
    .card{grid-column:span 12;background:linear-gradient(180deg,rgba(255,255,255,.02),rgba(255,255,255,.01)); border:1px solid var(--outline); padding:20px;border-radius:16px; transition:transform .2s ease, box-shadow .2s ease, border-color .2s; position:relative; overflow:hidden;}
    .card:hover{transform:translateY(-3px);border-color:rgba(195,255,131,.6);box-shadow:0 10px 40px rgba(0,0,0,.25)}
    .price{display:inline-flex;gap:6px; align-items:center; font-weight:800; color:#111; background:var(--lime); padding:6px 10px;border-radius:999px}
    .card h3{margin:10px 0 6px}
    .pill{display:inline-flex;gap:6px;align-items:center;border:1px dashed var(--outline);padding:4px 8px;border-radius:999px;color:var(--muted);font-size:12px}
    .features{margin:12px 0 0;padding:0 0 0 18px;color:#e7e7ee}
    .features li{margin:6px 0}
    @media(min-width:700px){
      .card{grid-column:span 6}
    }
    @media(min-width:1000px){
      .card{grid-column:span 4}
    }
    /* Contact */
    .contact-wrap{display:grid;grid-template-columns:1fr;gap:18px}
    @media(min-width:900px){ .contact-wrap{grid-template-columns:1.1fr .9fr} }
    form{background:linear-gradient(180deg,rgba(255,255,255,.02),rgba(255,255,255,.01)); border:1px solid var(--outline); padding:20px;border-radius:16px}
    label{display:block;margin:12px 0 6px;font-weight:600}
    input, textarea{width:100%;padding:12px 14px;border-radius:10px;border:1px solid var(--outline); background:#0f0f13;color:#fff}
    textarea{min-height:120px;resize:vertical}
    .helper{color:var(--muted);font-size:12px;margin-top:6px}
    .status{margin-top:10px;font-weight:700}
    .ok{color:var(--lime)} .err{color:#ffb3b3}
    .small{font-size:12px;color:var(--muted)}
    /* Reveal animation */
    .reveal{opacity:0;transform:translateY(12px);transition:opacity .6s ease, transform .6s ease}
    .reveal.in{opacity:1;transform:none}
    /* Footer */
    footer{padding:26px 0;color:var(--muted);border-top:1px solid var(--outline)}
    /* Floating top button */
    .top{position:fixed;right:16px;bottom:16px;padding:10px 12px;border-radius:12px;background:#111119;border:1px solid var(--outline)}
    .top:hover{border-color:var(--lime)}
    /* Accent stripe */
    .stripe{height:3px;background:linear-gradient(90deg,var(--purple),var(--lime))}
  </style>
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <span class="badge">HFC</span>
        <div>
          <div style="font-size:14px;opacity:.8">Harrisons Flipping Cars</div>
          <strong style="font-size:16px">Social Media • Listings • Ads</strong>
        </div>
      </div>
      <nav>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
      </nav>
      <div class="socials" aria-label="Social links">
        <a class="icon" href="https://instagram.com/yourhandle" aria-label="Instagram" target="_blank" rel="noopener">
          <!-- Instagram SVG -->
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M7 2h10a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5zm10 2H7a3 3 0 0 0-3 3v10a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3zm-5 3.5a5.5 5.5 0 1 1 0 11.001A5.5 5.5 0 0 1 12 7.5zm0 2a3.5 3.5 0 1 0 0 7.001A3.5 3.5 0 0 0 12 9.5zM18 6.3a1 1 0 1 1 0 2.001 1 1 0 0 1 0-2z"/></svg>
        </a>
        <a class="icon" href="https://www.tiktok.com/@yourhandle" aria-label="TikTok" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M21 8.5a7.5 7.5 0 0 1-5-1.8v7.1a6.8 6.8 0 1 1-6.8-6.8c.3 0 .6 0 .9.1v3a3.8 3.8 0 1 0 3.8 3.8V2h3a5 5 0 0 0 4.1 4.9v1.6z"/></svg>
        </a>
        <a class="icon" href="https://youtube.com/@yourhandle" aria-label="YouTube" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M23 7.2s-.2-1.6-.8-2.3c-.8-.8-1.7-.8-2.1-.9C16.9 3.7 12 3.7 12 3.7h0s-4.9 0-8.1.3c-.4.1-1.3.1-2.1.9C1.2 5.6 1 7.2 1 7.2S.8 9.2.8 11.2v1.6c0 2 .2 4 .2 4s.2 1.6.8 2.3c.8.8 1.8.8 2.3.9 1.7.2 7 .3 7 .3s4.9 0 8.1-.3c.4-.1 1.3-.1 2.1-.9.6-.7.8-2.3.8-2.3s.2-2 .2-4v-1.6c0-2-.2-4-.2-4zM9.8 14.8V8.9l5.8 2.9-5.8 3z"/></svg>
        </a>
        <a class="icon" href="https://facebook.com/yourhandle" aria-label="Facebook" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M13 22v-9h3l.5-3H13V8.2c0-.8.3-1.3 1.3-1.3H17V4.1C16.6 4 15.6 4 14.5 4 12.3 4 11 5.1 11 7.7V10H8v3h3v9h2z"/></svg>
        </a>
        <a class="icon" href="https://x.com/yourhandle" aria-label="X" target="_blank" rel="noopener">
          <svg viewBox="0 0 24 24" fill="currentColor"><path d="M2.5 3h4.7l4.4 6 5-6H22l-6.9 8.3L22 21h-4.6l-5.1-6.8L6.8 21H2l7.7-9.3z"/></svg>
        </a>
      </div>
    </div>
    <div class="stripe"></div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="kicker">We flip attention into buyers</div>
      <h1 class="reveal">Social media that sells your cars.</h1>
      <p class="lead reveal">
        We create high-impact short-form videos, polished listings, and targeted ads for car flippers,
        private sellers, and small dealers. Bold visuals, clear CTAs, and consistent posting—done for you.
      </p>
      <div class="cta">
        <a class="btn btn-primary" href="#contact">Get a Quote</a>
        <a class="btn" href="#services">See Services & Pricing</a>
      </div>
    </section>

    <section id="services">
      <h2 class="reveal">Services & Pricing</h2>
      <p class="sub reveal">Transparent packages you can mix & match. All pricing is editable right in this file.</p>
      <div class="grid">
        <article class="card reveal">
          <span class="pill">Content</span>
          <h3>Reels/TikTok Starter Pack</h3>
          <div class="price">$199</div>
          <ul class="features">
            <li>3 short videos (vertical, captioned)</li>
            <li>Hashtags + posting schedule</li>
            <li>Cover thumbnails + copy</li>
          </ul>
        </article>
        <article class="card reveal">
          <span class="pill">Brand</span>
          <h3>Social Setup & Makeover</h3>
          <div class="price">$149</div>
          <ul class="features">
            <li>Bio rewrite, highlights, link-in-bio</li>
            <li>Profile + banner design (HFC colors)</li>
            <li>Starter content calendar (2 weeks)</li>
          </ul>
        </article>
        <article class="card reveal">
          <span class="pill">Listings</span>
          <h3>Listing Polish</h3>
          <div class="price">$79 / listing</div>
          <ul class="features">
            <li>Photo order & touch-up</li>
            <li>Headline + bullet features</li>
            <li>Buyer-focused description</li>
          </ul>
        </article>
        <article class="card reveal">
          <span class="pill">Growth</span>
          <h3>Weekly Management</h3>
          <div class="price">$299 / month</div>
          <ul class="features">
            <li>3 posts/week across 1–2 platforms</li>
            <li>DM screening + lead replies (light)</li>
            <li>Monthly reporting & ideas</li>
          </ul>
        </article>
        <article class="card reveal">
          <span class="pill">Ads</span>
          <h3>Targeted Ad Boost</h3>
          <div class="price">$249 + ad spend</div>
          <ul class="features">
            <li>Audience + creative testing</li>
            <li>1 campaign, 2 ad sets, 4 creatives</li>
            <li>Weekly optimization</li>
          </ul>
        </article>
        <article class="card reveal">
          <span class="pill">Coaching</span>
          <h3>1:1 Strategy Call</h3>
          <div class="price">$99 / hour</div>
          <ul class="features">
            <li>Profile audit + roadmap</li>
            <li>Content ideas tailored to your cars</li>
            <li>Q&A and tools walk-through</li>
          </ul>
        </article>
      </div>
    </section>

    <section id="about">
      <h2 class="reveal">About HFC</h2>
      <p class="sub reveal">
        Built for car flippers and sellers. We combine engaging edits, clear offers, and consistent posting
        to convert views into test drives. Colors: <strong>#5910E5</strong> (dark purple) & <strong>#C3FF83</strong> (lime).
      </p>
    </section>

    <section id="contact">
      <h2 class="reveal">Contact</h2>
      <div class="contact-wrap">
        <form id="contact-form" class="reveal" novalidate>
          <label for="name">Name *</label>
          <input id="name" name="name" required placeholder="Your name" />

          <label for="email">Email *</label>
          <input id="email" name="email" type="email" required placeholder="you@example.com" />

          <label for="phone">Phone (optional)</label>
          <input id="phone" name="phone" inputmode="tel" placeholder="(xxx) xxx-xxxx" />

          <!-- Honeypot (spam trap) -->
          <input type="text" name="_gotcha" style="display:none" tabindex="-1" autocomplete="off" />

          <label for="message">How can we help? *</label>
          <textarea id="message" name="message" required placeholder="Tell me about your car(s) or goal…"></textarea>

          <div class="helper">We typically respond within 1 business day.</div>
          <button class="btn btn-primary" type="submit">Send Message</button>
          <div class="status" id="status"></div>

          <div class="small" style="margin-top:10px">
            Prefer not to use the form?
            <span id="alt-links"></span>
          </div>
        </form>

        <div class="reveal" style="background:linear-gradient(180deg,rgba(255,255,255,.02),rgba(255,255,255,.01)); border:1px solid var(--outline); padding:20px;border-radius:16px">
          <h3>What to expect</h3>
          <p style="color:#e9e9ee">Share a bit about your project. I’ll reply with a quick plan and transparent quote.</p>
          <ul class="features" style="margin-top:0">
            <li>Free mini-audit of your current profile</li>
            <li>Clear deliverables & timeline</li>
            <li>No long contracts</li>
          </ul>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      © <span id="year"></span> Harrisons Flipping Cars • All rights reserved
    </div>
  </footer>

  <a class="top" href="#top" aria-label="Back to top">↑</a>

  <script>
    // ======== EDIT THESE 3 VALUES ========
    const FORM_ENDPOINT = ""; // e.g. "https://formspree.io/f/abcdwxyz" (Option A)https://formspree.io/f/mzzvlgee
    const GITHUB_REPO = "";   // e.g. "YourUserName/harrisons-flipping-cars" (Option B)
    const CONTACT_EMAIL = ""; // e.g. "you@example.com" (Option C)
    // =====================================

    // Smooth scroll for anchor links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click',e=>{
        const id = a.getAttribute('href').slice(1);
        const el = document.getElementById(id);
        if(el){ e.preventDefault(); el.scrollIntoView({behavior:'smooth', block:'start'}); }
      });
    });

    // Reveal on scroll
    const io = new IntersectionObserver(entries=>{
      entries.forEach(entry=>{
        if(entry.isIntersecting){ entry.target.classList.add('in'); io.unobserve(entry.target); }
      });
    },{threshold:.12});
    document.querySelectorAll('.reveal').forEach(el=>io.observe(el));

    // Footer year
    document.getElementById('year').textContent = new Date().getFullYear();

    // Build alternative links
    (function buildAlt(){
      const container = document.getElementById('alt-links');
      const bits = [];
      if (GITHUB_REPO){
        const url = `https://github.com/${GITHUB_REPO}/issues/new?` +
          `title=${encodeURIComponent('New lead from website')}` +
          `&labels=${encodeURIComponent('lead')}` +
          `&body=${encodeURIComponent('**Name**: \n**Email**: \n**Phone**: \n**Message**: \n')}`;
        bits.push(`<a href="${url}" target="_blank" rel="noopener">Contact via GitHub</a>`);
      }
      if (CONTACT_EMAIL){
        bits.push(`<a href="mailto:${CONTACT_EMAIL}?subject=${encodeURIComponent('HFC Website Inquiry')}">Email us</a>`);
      }
      container.innerHTML = bits.length ? bits.join(' • ') : 'Set contact options above in the code.';
    })();

    // Contact form submission
    const form = document.getElementById('contact-form');
    const status = document.getElementById('status');

    form.addEventListener('submit', async (e)=>{
      e.preventDefault();
      status.textContent = '';
      const data = new FormData(form);

      // Simple validation
      const name = (data.get('name')||'').trim();
      const email = (data.get('email')||'').trim();
      const message = (data.get('message')||'').trim();
      if (!name || !email || !message){
        status.innerHTML = '<span class="err">Please fill in required fields.</span>';
        return;
      }

      // If Formspree endpoint is set, send via AJAX
      if (FORM_ENDPOINT){
        try{
          const res = await fetch(FORM_ENDPOINT, {
            method: 'POST',
            headers: { 'Accept': 'application/json' },
            body: data
          });
          if (res.ok){
            form.reset();
            status.innerHTML = '<span class="ok">Thanks! Your message was sent.</span>';
            return;
          } else {
            const j = await res.json().catch(()=>({}));
            throw new Error(j.error || 'Submit failed');
          }
        }catch(err){
          status.innerHTML = '<span class="err">Could not send via form. Try the options below.</span>';
        }
      }

      // If no endpoint (or it failed), fall back:
      if (GITHUB_REPO){
        const body = `**Name**: ${name}\n**Email**: ${email}\n**Phone**: ${data.get('phone')||''}\n\n**Message**:\n${message}`;
        const url = `https://github.com/${GITHUB_REPO}/issues/new?` +
                    `title=${encodeURIComponent('New lead from website')}&labels=${encodeURIComponent('lead')}&body=${encodeURIComponent(body)}`;
        window.open(url,'_blank');
        status.innerHTML = '<span class="ok">Opening GitHub to submit your message…</span>';
        return;
      }

      if (CONTACT_EMAIL){
        const mail = `mailto:${CONTACT_EMAIL}?subject=${encodeURIComponent('HFC Website Inquiry')}&body=${encodeURIComponent('Name: '+name+'\nEmail: '+email+'\nPhone: '+(data.get('phone')||'')+'\n\n'+message)}`;
        window.location.href = mail;
        status.innerHTML = '<span class="ok">Launching your email app…</span>';
        return;
      }

      status.innerHTML = '<span class="err">No contact method configured yet.</span>';
    });
