<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>XTREME ASHWANI - Official Website</title>
  <style>
    /* Default Theme */
    :root {
      --primary-color: #ff6f61; /* Red accent color */
      --secondary-color: #00bcd4; /* Cyan for links and accents */
      --background-color: #111; /* Dark background */
      --header-bg-color: #222; /* Dark header */
      --text-color: #f0f0f0; /* Light text color */
      --button-bg-color: #ff6f61; /* Red buttons */
      --button-hover-bg-color: #ff3d2a; /* Darker red for hover */
    }

    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: var(--background-color);
      color: var(--text-color);
    }

    header {
      background-color: var(--header-bg-color);
      color: var(--primary-color);
      padding: 25px;
      text-align: center;
      border-bottom: 5px solid var(--primary-color);
    }

    header h1 {
      margin: 0;
      font-size: 3.5rem;
      letter-spacing: 3px;
      color: var(--primary-color);
      font-weight: bold;
      animation: slideIn 2s ease-out;
    }

    .marquee {
      background-color: #1f1f1f;
      padding: 12px 0;
      color: var(--secondary-color);
      font-weight: bold;
      font-size: 1.1rem;
    }

    .banner {
      width: 100%;
      height: 350px;
      background: url('https://via.placeholder.com/1200x350/FF0000/FFFFFF?text=XTREME+ASHWANI') no-repeat center center/cover;
      border-bottom: 3px solid var(--primary-color);
      box-shadow: 0px 5px 15px rgba(0,0,0,0.3);
    }

    section {
      padding: 40px 20px;
    }

    .videos, .featured-video, .contact-form, .form-section {
      background-color: #1c1c1c;
      border-radius: 12px;
      margin-bottom: 35px;
      padding: 30px;
      box-shadow: 0px 4px 12px rgba(255, 0, 0, 0.4);
    }

    .videos h2, .featured-video h2, .contact-form h2, .form-section h2 {
      color: var(--secondary-color);
      font-size: 2rem;
      margin-bottom: 15px;
      border-bottom: 3px solid var(--primary-color);
      padding-bottom: 10px;
    }

    .videos ul {
      padding-left: 20px;
      list-style-type: disc;
    }

    form input, form textarea {
      width: 100%;
      padding: 14px;
      margin-top: 14px;
      border-radius: 8px;
      border: 1px solid #444;
      background-color: #333;
      color: #fff;
      font-size: 1.1rem;
      transition: 0.3s ease;
    }

    form input:focus, form textarea:focus {
      border: 1px solid var(--primary-color);
    }

    form button {
      margin-top: 20px;
      padding: 14px 30px;
      background-color: var(--button-bg-color);
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 1.2rem;
      cursor: pointer;
      transition: 0.3s ease;
    }

    form button:hover {
      background-color: var(--button-hover-bg-color);
    }

    a {
      color: var(--secondary-color);
      text-decoration: none;
    }

    iframe {
      width: 100%;
      height: 350px;
      border: none;
      border-radius: 10px;
      margin-top: 20px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: var(--header-bg-color);
      color: #aaa;
      font-size: 1rem;
      border-top: 3px solid var(--primary-color);
    }

    @keyframes slideIn {
      0% {
        transform: translateX(-100%);
      }
      100% {
        transform: translateX(0);
      }
    }

    /* Moving Alert */
    .alert {
      background-color: #ff3d2a; /* Red background for alert */
      color: white;
      padding: 10px;
      font-size: 1.2rem;
      font-weight: bold;
      position: absolute;
      top: 50px; /* Shifted down to avoid overlap */
      width: 100%;
      text-align: center;
      animation: moveAlert 10s linear infinite;
    }

    @keyframes moveAlert {
      0% {
        transform: translateX(100%);
      }
      100% {
        transform: translateX(-100%);
      }
    }

    /* Adjusted Marquee */
    .marquee {
      margin-top: 90px; /* Added space to prevent overlap with the alert */
    }

    @media (max-width: 768px) {
      iframe {
        height: 250px;
      }
    }
  </style>
</head>
<body>

  <!-- Moving Alert -->
  <div class="alert">
    🚨 The Contact and Suggest options are currently unavailable. Stay tuned for updates! 🚨
  </div>

  <!-- Welcome Marquee -->
  <div class="marquee">
    <marquee scrollamount="6">🚀 WELCOME TO THE OFFICIAL XTREME ASHWANI WEBSITE! 🚀</marquee>
  </div>

  <header>
    <h1>XTREME ASHWANI</h1>
  </header>

  <div class="banner"></div>

  <section class="featured-video">
    <h2>🎬 Featured Video</h2>
    <p>Check out my latest video below 👇</p>
    <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Featured Video" allowfullscreen></iframe>
  </section>

  <section class="videos">
    <h2>📺 Upcoming Videos</h2>
    <ul>
      <li>Video Idea 1: Epic Gaming Moments</li>
      <li>Video Idea 2: Behind the Scenes of My Setup</li>
      <li>Video Idea 3: Q&A with Xtreme Ashwani</li>
    </ul>
    <p>Subscribe and stay tuned for more amazing content 👉 <a href="https://www.youtube.com/@XTREMEASHWANI" target="_blank">YouTube Channel</a></p>
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
    <h2>💡 Suggest a Video Idea</h2>
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
