<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>XTREME ASHWANI - Audience Section</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }

    header {
      background-color: #ffffff;
      color: #222;
      padding: 20px 10px 10px;
      text-align: center;
      border-bottom: 3px solid #0066cc;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      letter-spacing: 2px;
      color: #0066cc;
      line-height: 1.2;
    }

    .marquee {
      background: #e6f2ff;
      padding: 10px 0;
      color: #003366;
      font-weight: bold;
      font-size: 1.2rem;
    }

    .banner {
      width: 100%;
      height: 300px;
      background: url('https://images.openai.com/blob/18b9a4d3-a0ad-48fb-b2a6-43b94ef0ea79/xtreme-banner.png') no-repeat center center/cover;
      border-bottom: 2px solid #0066cc;
    }

    section {
      padding: 30px 20px;
      max-width: 900px;
      margin: 0 auto;
    }

    .videos, .featured-video, .contact-form, .form-section {
      background: #ffffff;
      border-radius: 10px;
      margin-bottom: 30px;
      padding: 25px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .videos h2, .featured-video h2, .contact-form h2, .form-section h2 {
      color: #0066cc;
      border-bottom: 2px solid #0066cc;
      padding-bottom: 10px;
    }

    .videos ul {
      padding-left: 20px;
    }

    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin-top: 12px;
      border-radius: 5px;
      border: 1px solid #ccc;
      outline: none;
      font-size: 1rem;
      background-color: #fff;
      color: #333;
    }

    form textarea {
      resize: vertical;
    }

    form button {
      margin-top: 15px;
      padding: 12px 25px;
      background: #0066cc;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 1rem;
      cursor: pointer;
      transition: 0.3s ease;
    }

    form button:hover {
      background: #004999;
    }

    a {
      color: #0066cc;
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
      background: #f1f1f1;
      color: #555;
      font-size: 0.9rem;
      border-top: 2px solid #ccc;
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

  <div class="banner"></div>

  <section class="featured-video">
    <h2>🎬 Featured Video</h2>
    <p>Watch my latest content here 👇</p>
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Featured Video" allowfullscreen></iframe>
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
