<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>AM Study Advisor | Study Abroad & Scholarships</title>
<style>
  /* Reset */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
  }
  body {
    font-family: 'Poppins', sans-serif;
    background: #0a0a0a;
    color: #eee;
    line-height: 1.6;
    font-size: 16px;
    min-height: 100vh;
  }
  .container {
    max-width: 1100px;
    margin: auto;
    padding: 0 20px 50px;
  }

  /* Header */
  header {
    background: #000;
    padding: 20px 0;
    position: sticky;
    top: 0;
    z-index: 1000;
    border-bottom: 4px solid #ff1f1f;
  }
  .nav-container {
    max-width: 1100px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 20px;
  }
  .logo {
    font-size: 2.4rem;
    color: #ff1f1f;
    font-weight: 700;
    letter-spacing: 3px;
    user-select: none;
    text-shadow:
      2px 2px 0 #000,
      4px 4px 4px rgba(255,31,31,0.6);
  }
  nav a {
    color: #eee;
    margin-left: 25px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1rem;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #ff1f1f;
  }
  @media (max-width: 768px) {
    .nav-container {
      flex-direction: column;
      gap: 15px;
    }
    nav {
      order: 2;
    }
  }

  /* Hero */
  .hero {
    background: linear-gradient(135deg, #ff1f1f 0%, #000 100%);
    text-align: center;
    padding: 100px 20px 80px;
    user-select: none;
  }
  .hero h1 {
    font-size: 3rem;
    color: #fff;
    font-weight: 800;
    margin-bottom: 15px;
    letter-spacing: 3px;

    /* 3D text effect */
    text-shadow:
      1px 1px 0 #b21717,
      2px 2px 0 #7f0f0f,
      3px 3px 5px rgba(0,0,0,0.6);
  }
  .hero p {
    font-size: 1.3rem;
    max-width: 700px;
    margin: auto;
    margin-bottom: 40px;
    color: #f0f0f0cc;
  }
  .btn-primary {
    background: #ff1f1f;
    border: none;
    padding: 16px 50px;
    font-size: 1.2rem;
    font-weight: 700;
    border-radius: 50px;
    cursor: pointer;
    color: #fff;
    box-shadow: 0 0 15px #ff1f1f;
    transition: all 0.3s ease;
  }
  .btn-primary:hover {
    background: #b21717;
    box-shadow: 0 0 30px #b21717;
  }

  /* Section Titles with 2D shadow */
  h2.section-title {
    font-size: 2.5rem;
    font-weight: 700;
    color: #ff1f1f;
    text-align: center;
    margin-bottom: 40px;
    text-shadow: 2px 2px #000;
    user-select: none;
  }

  /* Destinations */
  .destinations {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 20px;
    margin-bottom: 60px;
  }
  .country-card {
    background: #1a1a1a;
    border-radius: 12px;
    padding: 20px;
    cursor: pointer;
    box-shadow: 0 0 15px #ff1f1f60;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    user-select: none;
    position: relative;
  }
  .country-card:hover {
    transform: scale(1.05);
    box-shadow: 0 0 30px #ff1f1f;
  }
  .country-name {
    font-size: 1.6rem;
    font-weight: 700;
    margin-bottom: 10px;
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .country-desc {
    font-size: 1rem;
    color: #ddd;
    line-height: 1.4;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.4s ease;
  }
  .country-card.active .country-desc {
    max-height: 500px;
    margin-top: 10px;
  }

  /* Services */
  .services-list {
    max-width: 700px;
    margin: 0 auto 60px;
    list-style: none;
    color: #ccc;
    font-weight: 500;
  }
  .services-list li {
    margin-bottom: 18px;
    position: relative;
    padding-left: 28px;
    font-size: 1.15rem;
  }
  .services-list li::before {
    content: "✔";
    color: #ff1f1f;
    position: absolute;
    left: 0;
    top: 0;
    font-weight: 900;
    font-size: 1.2rem;
  }

  /* Why Choose Us */
  .why-us {
    max-width: 900px;
    margin: 0 auto 60px;
    background: #1a1a1a;
    border-radius: 15px;
    padding: 30px 40px;
    box-shadow: 0 0 25px #ff1f1f60;
    color: #eee;
  }
  .why-us h3 {
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 20px;
    color: #ff1f1f;
    user-select: none;
  }
  .why-list {
    list-style: none;
    padding-left: 20px;
  }
  .why-list li {
    margin-bottom: 16px;
    font-size: 1.2rem;
    position: relative;
    padding-left: 28px;
    font-weight: 600;
  }
  .why-list li::before {
    content: "✓";
    position: absolute;
    left: 0;
    top: 0;
    color: #ff1f1f;
    font-weight: 900;
    font-size: 1.3rem;
  }

  /* Client Satisfaction */
  .client-satisfaction {
    max-width: 800px;
    margin: 0 auto 80px;
    text-align: center;
  }
  .stars {
    color: #ff1f1f;
    font-size: 2rem;
    margin-bottom: 20px;
  }
  .testimonials {
    font-style: italic;
    font-size: 1.1rem;
    color: #ddd;
  }
  .testimonial {
    margin-bottom: 15px;
  }

  /* Contact Section */
  .contact-section {
    max-width: 700px;
    margin: 0 auto;
    background: #1a1a1a;
    padding: 30px 40px;
    border-radius: 12px;
    box-shadow: 0 0 30px #ff1f1f80;
    text-align: center;
  }
  .contact-section p {
    font-size: 1.1rem;
    margin-bottom: 12px;
    font-weight: 600;
    color: #ddd;
  }
  .contact-section button {
    margin-top: 25px;
  }

  /* Footer */
  footer {
    background: #000;
    color: #ff1f1f;
    text-align: center;
    padding: 25px 20px;
    font-weight: 600;
    user-select: none;
  }

  /* Responsive */
  @media (max-width: 768px) {
    .destinations {
      grid-template-columns: 1fr;
    }
    .why-us {
      padding: 25px;
    }
    .contact-section {
      padding: 25px;
    }
  }
</style>
</head>
<body>

<header>
  <div class="nav-container">
    <div class="logo">AM Study Advisor</div>
    <nav>
      <a href="#destinations">Destinations</a>
      <a href="#services">Services</a>
      <a href="#why-us">Why Us</a>
      <a href="#client-satisfaction">Clients</a>
      <a href="#contact">Contact</a>
    </nav>
  </div>
</header>

<section class="hero">
  <h1>AM Study Advisor</h1>
  <p>Your Gateway to Fully Funded Scholarships & Admissions in Europe & UK</p>
  <button class="btn-primary" onclick="scrollToSection('contact')">Get Started</button>
</section>

<section id="destinations" class="container">
  <h2 class="section-title">🌍 Study Abroad Destinations</h2>
  <div class="destinations" aria-label="Study Abroad Countries">

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-italy" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇮🇹 Italy</div>
      <p id="desc-italy" class="country-desc">Known for its rich culture, historic universities, and affordable tuition fees. Italy offers diverse courses and scholarship options for international students.</p>
    </article>

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-france" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇫🇷 France</div>
      <p id="desc-france" class="country-desc">France has world-class universities and many scholarships. It’s popular for art, engineering, and business programs.</p>
    </article>

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-cyprus" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇨🇾 Cyprus</div>
      <p id="desc-cyprus" class="country-desc">Cyprus offers English-taught degrees, modern campuses, and a multicultural environment, ideal for international students.</p>
    </article>

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-malta" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇲🇹 Malta</div>
      <p id="desc-malta" class="country-desc">Malta combines Mediterranean lifestyle with quality education. Scholarships are available for various fields of study.</p>
    </article>

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-georgia" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇬🇪 Georgia</div>
      <p id="desc-georgia" class="country-desc">Georgia is gaining popularity due to affordable living costs, English programs, and welcoming policies for international students.</p>
    </article>

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-uk" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇬🇧 United Kingdom</div>
      <p id="desc-uk" class="country-desc">Home to some of the world's top universities, the UK offers numerous scholarships and strong post-study work opportunities.</p>
    </article>

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-germany" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇩🇪 Germany</div>
      <p id="desc-germany" class="country-desc">Germany is famous for tuition-free public universities, quality engineering programs, and extensive scholarship schemes.</p>
    </article>

    <article class="country-card" tabindex="0" role="button" aria-expanded="false" aria-controls="desc-netherlands" onclick="toggleDesc(this)" onkeydown="if(event.key==='Enter'){toggleDesc(this)}">
      <div class="country-name">🇳🇱 Netherlands</div>
      <p id="desc-netherlands" class="country-desc">The Netherlands offers English-taught programs, innovative teaching styles, and many scholarships for international students.</p>
    </article>

  </div>
</section>

<section id="services" class="container">
  <h2 class="section-title">🎓 Our Services</h2>
  <ul class="services-list">
    <li>University Admission Processing</li>
    <li>Fully Funded Scholarship Applications</li>
    <li>Visa Filing & Assistance</li>
    <li>Pre-departure & Post-arrival Support</li>
    <li>Documentation & Interview Preparation</li>
    <li>Personalized Counseling & Consultation</li>
    <li>Language & Test Preparation Guidance</li>
    <li>Career Pathway Planning</li>
  </ul>
</section>

<section id="why-us" class="why-us container" tabindex="0">
  <h3>Why Choose AM Study Advisor?</h3>
  <ul class="why-list">
    <li>Expert guidance with years of experience in international education.</li>
    <li>Strong network of partner universities across Europe and UK.</li>
    <li>100% transparent and personalized services tailored to you.</li>
    <li>High success rate in securing scholarships and admissions.</li>
    <li>Dedicated support at every step – from application to landing abroad.</li>
  </ul>
</section>

<section id="client-satisfaction" class="client-satisfaction container" tabindex="0">
  <h2 class="section-title">⭐ Client Satisfaction</h2>
  <div class="stars" aria-label="5 star rating">★★★★★</div>
  <div class="testimonials">
    <p class="testimonial">"AM Study Advisor helped me get a fully funded scholarship in Italy. Their team was professional and supportive throughout." – Aisha K.</p>
    <p class="testimonial">"Thanks to AM Study Advisor, I got admission in a top UK university with visa assistance. Highly recommended!" – Omar R.</p>
    <p class="testimonial">"Excellent guidance and quick response. They made the whole process easy and stress-free." – Sana M.</p>
  </div>
</section>

<section id="contact" class="contact-section container" tabindex="0" aria-label="Contact Information">
  <h2 class="section-title">📞 Contact Us</h2>
  <p><strong>Office:</strong> Opposite Street No-65, G-14/2 Islamabad</p>
  <p><strong>Phone:</strong> 0348 5534461</p>
  <p><strong>Email:</strong> amstudyadvisor@gmail.com</p>
  <p><strong>Instagram:</strong> @amstudyadvisor</p>
  <button class="btn-primary" onclick="sendMessage()">Send Quick Message</button>
</section>

<footer>
  <p>© 2025 AM Study Advisor. All rights reserved.</p>
</footer>

<script>
  // Toggle country description
  function toggleDesc(card) {
    const isActive = card.classList.contains('active');
    // Close all open descriptions
    document.querySelectorAll('.country-card.active').forEach(c => {
      c.classList.remove('active');
      c.setAttribute('aria-expanded', 'false');
    });
    if (!isActive) {
      card.classList.add('active');
      card.setAttribute('aria-expanded', 'true');
    }
  }
  // Scroll smoothly to section
  function scrollToSection(id) {
    document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
  }
  // Alert on contact button click
  function sendMessage() {
    alert("Thank you for reaching out! Contact us at 0348 5534461 or email amstudyadvisor@gmail.com");
  }
</script>

</body>
</html>
