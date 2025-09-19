# Booking-
Booking agency 
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>CelebConnect — Fan Membership & Charity</title>
  <meta name="description" content="Get in touch with your favourite celebrity, apply for fan membership card, donate to charity projects, and join meet & greets vacations." />
  <style>
    :root {
      --bg:#fdfdfd; --card:#ffffff; --muted:#6b7280;
      --accent:#e11d48; --accent-2:#f97316;
      --radius:14px; --shadow:0 8px 30px rgba(0,0,0,0.08);
      --max-width:1100px; --fw-regular:400; --fw-bold:700;
    }
    html.dark { --bg:#111827; --card:#1f2937; --muted:#9ca3af; --accent:#f43f5e; --accent-2:#fb923c; color-scheme:dark; }
    *,*::before,*::after{box-sizing:border-box}
    body{margin:0;font-family:Inter,Arial,sans-serif;background:var(--bg);color:#111;line-height:1.5;padding:20px;display:flex;justify-content:center}
    .site{width:100%;max-width:var(--max-width);background:var(--card);border-radius:var(--radius);box-shadow:var(--shadow);overflow:hidden}
    header{display:flex;justify-content:space-between;align-items:center;padding:18px 28px;background:var(--accent);color:white}
    .brand{display:flex;gap:12px;align-items:center}
    .logo{width:42px;height:42px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:grid;place-items:center;font-weight:900}
    nav a{color:white;text-decoration:none;margin-left:14px;font-weight:600}
    nav a:hover{text-decoration:underline}
    .hero{padding:50px 28px;display:grid;grid-template-columns:1fr 400px;gap:28px;align-items:center}
    .hero h2{margin:0 0 14px;font-size:2.2rem}
    .lead{color:var(--muted);font-size:1.1rem;margin:0 0 18px}
    .btn{display:inline-block;padding:12px 18px;border-radius:10px;background:var(--accent);color:white;font-weight:700;text-decoration:none}
    .btn.secondary{background:var(--accent-2)}
    .features{padding:40px 28px;display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .feature{background:var(--card);padding:20px;border-radius:12px;box-shadow:var(--shadow)}
    .feature h3{margin:0 0 8px}
    .feature p{margin:0;color:var(--muted)}
    .pricing{padding:40px 28px;display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .plan{padding:20px;border-radius:12px;background:var(--card);box-shadow:var(--shadow);display:flex;flex-direction:column;gap:12px}
    .price{font-size:1.6rem;font-weight:var(--fw-bold)}
    .testimonials{padding:40px 28px;display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:20px}
    .testimonial{background:var(--card);padding:18px;border-radius:12px;box-shadow:var(--shadow)}
    .contact{padding:40px 28px;display:grid;grid-template-columns:1fr 300px;gap:20px}
    form{display:flex;flex-direction:column;gap:12px}
    input,textarea,select{padding:10px;border-radius:8px;border:1px solid #ddd}
    footer{padding:20px 28px;text-align:center;color:var(--muted);background:#f9fafb}
    @media(max-width:800px){
      .hero{grid-template-columns:1fr}
      .features{grid-template-columns:1fr}
      .pricing{grid-template-columns:1fr}
      .contact{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
<div class="site">
  <!-- Header -->
  <header>
    <div class="brand">
      <div class="logo">★</div>
      <h1>CelebConnect</h1>
    </div>
    <nav>
      <a href="#features">Features</a>
      <a href="#pricing">Membership</a>
      <a href="#testimonials">Fans</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero -->
  <section class="hero">
    <div>
      <h2>Get closer to your favourite celebrity ❤️</h2>
      <p class="lead">Apply for your fan membership card, donate to global charity projects, and join unforgettable meet & greet vacations.</p>
      <a class="btn" href="#pricing">Join Now</a>
      <a class="btn secondary" href="#contact">Contact Us</a>
    </div>
    <div>
      <img src="https://placehold.co/400x250?text=Celeb+Photo" alt="Celebrity Fans" style="border-radius:12px;width:100%;box-shadow:var(--shadow)">
    </div>
  </section>

  <!-- Features -->
  <section class="features" id="features">
    <div class="feature">
      <h3>🎫 Fan Membership Card</h3>
      <p>Exclusive access to events, updates, and personalized fan perks.</p>
    </div>
    <div class="feature">
      <h3>🌍 Donate to Charity</h3>
      <p>Support causes your celebrity cares about and make a difference globally.</p>
    </div>
    <div class="feature">
      <h3>✈️ Meet & Greets Vacations</h3>
      <p>Travel, relax, and connect with your idols in dream destinations.</p>
    </div>
  </section>

  <!-- Pricing -->
  <section class="pricing" id="pricing">
    <div class="plan">
      <h3>Free</h3>
      <p class="muted">Stay updated</p>
      <div class="price">$0</div>
      <ul>
        <li>Newsletter updates</li>
        <li>Charity news</li>
      </ul>
      <a href="#contact" class="btn">Get Started</a>
    </div>
    <div class="plan">
      <h3>Premium</h3>
      <p class="muted">Fan card + perks</p>
      <div class="price">$20/mo</div>
      <ul>
        <li>Fan membership card</li>
        <li>Priority event invites</li>
      </ul>
      <a href="#contact" class="btn">Go Premium</a>
    </div>
    <div class="plan">
      <h3>VIP</h3>
      <p class="muted">All access</p>
      <div class="price">$99/mo</div>
      <ul>
        <li>Meet & greet vacations</li>
        <li>Exclusive charity dinners</li>
      </ul>
      <a href="#contact" class="btn secondary">Join VIP</a>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="testimonials" id="testimonials">
    <div class="testimonial">
      <strong>Jane D.</strong>
      <p>“Meeting my favourite artist through CelebConnect was a dream come true!”</p>
    </div>
    <div class="testimonial">
      <strong>Sam R.</strong>
      <p>“I love that I can donate to charity projects supported by my idol.”</p>
    </div>
    <div class="testimonial">
      <strong>Alicia K.</strong>
      <p>“The fan card gave me early access to the meet & greet vacation — unforgettable memories!”</p>
    </div>
  </section>

  <!-- Contact -->
  <section class="contact" id="contact">
    <div>
      <h2>Contact Us</h2>
      <p class="muted">Want to apply for a fan card, donate, or plan a meet & greet? Send us a message.</p>
      <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Your Email" required>
        <select required>
          <option value="">Choose topic</option>
          <option>Membership</option>
          <option>Charity</option>
          <option>Meet & Greets</option>
        </select>
        <textarea rows="4" placeholder="Your message..." required></textarea>
        <button type="submit" class="btn">Send</button>
      </form>
    </div>
    <div>
      <h3>Contact Info</h3>
      <p>Email: hello@celebconnect.com</p>
      <p>Location: Worldwide</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © <span id="year"></span> CelebConnect — Connecting Fans & Celebrities
    
    <!-- Newsletter signup -->
    <div class="newsletter">
      <form id="newsletter-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST" style="display:flex; gap:10px; width:100%; max-width:500px; margin:10px auto;">
        <input type="email" name="email" placeholder="Subscribe for updates..." required>
        <button type="submit" class="btn">Subscribe</button>
      </form>
      <p id="newsletter-message" style="margin-top:10px; display:none;">
        ✅ Thanks for subscribing! Check your email for confirmation.
      </p>
    </div>
  </footer>
</div>

<script>
document.addEventListener("DOMContentLoaded", () => {
  // Year auto-update
  document.getElementById("year").textContent = new Date().getFullYear();

  // Newsletter form handler
  const form = document.getElementById("newsletter-form");
  if (!form) return;
  form.addEventListener("submit", async function(event) {
    event.preventDefault();
    const data = new FormData(form);
    const response = await fetch(form.action, {
      method: form.method,
      body: data,
      headers: { 'Accept': 'application/json' }
    });
    const message = document.getElementById("newsletter-message");
    if (response.ok) {
      message.style.color = "green";
      message.textContent = "✅ Thanks for subscribing! Check your email for confirmation.";
      message.style.display = "block";
      form.reset();
    } else {
      message.style.color = "red";
      message.textContent = "❌ Oops, something went wrong. Please try again.";
      message.style.display = "block";
    }
  });
});
</script>
</body>
</html>
