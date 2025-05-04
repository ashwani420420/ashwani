
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>XTREME ASHWANI - Audience Section</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background: radial-gradient(circle at top, #0a0a0a, #1a1a1a);
      color: #e0e0e0;
    }

    header {
      background-color: #111;
      color: #00ffff;
      padding: 20px 10px 10px;
      text-align: center;
      border-bottom: 3px solid #00ffff;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      letter-spacing: 2px;
    }

    .marquee {
      background: #0f0f0f;
      padding: 10px 0;
      color: #00ffff;
      font-weight: bold;
      font-size: 1.2rem;
    }

    .shyari-box {
      text-align: center;
      color: #ff4081;
      font-size: 1.3rem;
      margin-top: 10px;
      animation: fadeIn 2s ease-in;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .banner {
      width: 100%;
      height: 300px;
      background: url('https://images.openai.com/blob/18b9a4d3-a0ad-48fb-b2a6-43b94ef0ea79/xtreme-banner.png') no-repeat center center/cover;
      border-bottom: 2px solid #00ffff;
    }

    nav {
      background: #181818;
      display: flex;
      justify-content: center;
      padding: 15px;
      gap: 30px;
    }

    nav a {
      color: #00ffff;
      text-decoration: none;
      font-size: 1rem;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff4081;
    }

    section {
      padding: 30px 20px;
      max-width: 900px;
      margin: 0 auto;
    }

    .videos, .featured-video, .contact-form, .form-section {
      background: #1f1f1f;
      border-radius: 10px;
      margin-bottom: 30px;
      padding: 25px;
      box-shadow: 0 6px 20px rgba(0, 255, 255, 0.1);
    }

    .videos h2, .featured-video h2, .contact-form h2, .form-section h2 {
      color: #00ffff;
      border-bottom: 2px solid #00ffff;
      padding-bottom: 10px;
      font-size: 1.5rem;
    }

    .videos ul {
      padding-left: 20px;
    }

    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin-top: 12px;
      border-radius: 5px;
      border: 1px solid #444;
      outline: none;
      font-size: 1rem;
      background-color: #0e0e0e;
      color: #f0f0f0;
    }

    form textarea {
      resize: vertical;
    }

    form button {
      margin-top: 15px;
      padding: 12px 25px;
      background: #00ffff;
      color: #000;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      cursor: pointer;
      transition: 0.3s ease;
    }

    form button:hover {
      background: #ff4081;
      color: white;
    }

    a {
      color: #00ffff;
      text-decoration: none;
    }

    iframe {
      width: 100%;
      height: 315px;
      border: none;
      border-radius: 10px;
      margin-top: 15px;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #111;
      color: #aaa;
      font-size: 0.9rem;
      border-top: 2px solid #00ffff;
    }

    @media (max-width: 600px) {
      iframe {
        height: 200px;
      }
    }
  </style>
</head>
<body>

  <div class="marquee">
    <marquee scrollamount="7">🚀 WELCOME TO OFFICIAL WEBSITE OF XTREME ASHWANI 🚀</marquee>
  </div>

  <header>
    <h1>XTREME ASHWANI</h1>
  </header>

  <div class="shyari-box">
    "सपनों को सच करने के लिए पहले सपना देखना ज़रूरी है। स्वागत है आप सभी का!"
  </div>

  <nav>
    <a href="#">Home</a>
    <a href="#">Videos</a>
    <a href="#">Contact</a>
  </nav>

  <div class="banner"></div>

  <section class="featured-video">
    <h2>🎬 Featured Video</h2>
    <p>Watch my latest content here 👇</p>
    <iframe src="http://www.youtube.com/@XTREMEASHWANI" title="Featured Video" allowfullscreen></iframe>
  </section>

  <section class="videos">
    <h2>📺 Upcoming Videos</h2>
    <ul>
      <li><!-- Video Idea 1 --></li>
      <li><!-- Video Idea 2 --></li>
      <li><!-- Video Idea 3 --></li>
    </ul>
    <p>Subscribe 👉 <a href="https://www.youtube.com/@XTREMEASHWANI" target="_blank">YouTube Channel</a></p>
  </section>

  <section class="contact-form">
    <h2>📨 Contact Me</h2>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="tel" name="phone" placeholder="Phone Number" required>
      <input type="email" name="email" placeholder="Email Address" required>
      <textarea name="reason" rows="4" placeholder="Reason for Contact" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <section class="form-section">
    <h2>💡 Suggest a Video Topic</h2>
    <form action="#" method="post">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="suggestion" rows="5" placeholder="Your Video Suggestion..." required></textarea>
      <button type="submit">Send Suggestion</button>
    </form>
  </section>

  <footer>
    &copy; 2025 XTREME ASHWANI. All rights reserved.
  </footer>

</body>
</html>

