# The-Syed-Practice-Dental-Aesthetics
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>The Syed Practice – Dental & Aesthetics</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #004d40;
      color: white;
      padding: 2em;
      text-align: center;
    }
    .hero {
      background: #e0f2f1;
      padding: 2em;
      text-align: center;
    }
    .about, .services, .contact {
      padding: 2em;
      background: white;
      margin: 1em;
      border-radius: 8px;
    }
    .services ul {
      list-style: none;
      padding: 0;
    }
    .services li {
      padding: 0.5em 0;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    form input, form textarea {
      margin-bottom: 1em;
      padding: 0.75em;
      font-size: 1em;
    }
    form button {
      background: #004d40;
      color: white;
      padding: 0.75em;
      border: none;
      cursor: pointer;
    }
    footer {
      background: #004d40;
      color: white;
      text-align: center;
      padding: 1em;
      margin-top: 2em;
    }
  </style>
</head>
<body>
  <header>
    <h1>The Syed Practice</h1>
    <p>Dental & Aesthetics | Smile in Serenity</p>
  </header>

  <section class="hero">
    <h2>Where Nature Meets Dentistry</h2>
    <p>Experience gentle, advanced dental care in a peaceful mountain retreat.</p>
  </section>

  <section class="about">
    <h2>About Us</h2>
    <p>At The Syed Practice, we blend expert dental care with the tranquility of nature. Our scenic clinic offers a calming atmosphere for your comfort and wellbeing.</p>
  </section>

  <section class="services">
    <h2>Our Services</h2>
    <ul>
      <li>General Dentistry</li>
      <li>Cosmetic Dentistry</li>
      <li>Dental Implants</li>
      <li>Teeth Whitening</li>
      <li>Orthodontics</li>
      <li>Oral Surgery</li>
      <li>Preventive Care</li>
      <li>Emergency Dental Services</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contact Us</h2>
    <form name="contact" method="POST" data-netlify="true">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p>Location: Mountain View Retreat Area</p>
    <iframe src="https://maps.google.com/maps?q=mountains&t=&z=10&ie=UTF8&iwloc=&output=embed" width="100%" height="250" frameborder="0" style="border:0" allowfullscreen></iframe>
  </section>

  <footer>
    <p>© 2025 The Syed Practice – Dental & Aesthetics. All rights reserved.</p>
  </footer>
</body>
</html>
