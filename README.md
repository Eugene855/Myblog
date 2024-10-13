<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Blog</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background: #1a1a2e;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    nav {
      margin: 15px 0;
    }
    nav a {
      color: #ffd700;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      max-width: 1200px;
      margin: 20px auto;
      padding: 20px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    .section {
      margin-bottom: 40px;
    }
    .section h2 {
      color: #1a1a2e;
      border-bottom: 2px solid #1a1a2e;
      padding-bottom: 10px;
    }
    .btn {
      background: #1a1a2e;
      color: white;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      text-decoration: none;
    }
    .btn:hover {
      background: #ffd700;
      color: #1a1a2e;
    }
    footer {
      background: #1a1a2e;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    ul li {
      margin-bottom: 10px;
    }
    .social-icons a {
      margin: 0 10px;
      color: #ffd700;
      text-decoration: none;
      font-size: 1.5em;
    }
  </style>
</head>
<body>

<header>
  <h1>My Blog</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Me</a>
    <a href="#blog">Blog Categories</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="container" id="home">
  <div class="section">
    <h2>Welcome to My World</h2>
    <p>Hey! Welcome to my blog – where tech meets travel, life meets self-discovery, and music vibes guide the way.</p>
    <a href="#contact" class="btn">Let's Connect</a>
  </div>

  <div class="section" id="projects">
    <h2>Featured Projects</h2>
    <p><strong>Kovu Adventure:</strong> A thrilling travel initiative showcasing Kenya’s beauty.</p>
    <p><strong>Starlink Business:</strong> My vision for revolutionizing internet access.</p>
  </div>
</div>

<div class="container" id="about">
  <div class="section">
    <h2>About Me</h2>
    <p>I’m a 21-year-old tech enthusiast with a passion for travel and music. I’ve worked on exciting projects like Kovu Adventure and dream of expanding internet access through Starlink.</p>
    <p>When life gets tough, I take walks, vibe to good music, and dream of exploring new destinations like Ibiza.</p>
  </div>
</div>

<div class="container" id="blog">
  <div class="section">
    <h2>Blog Categories</h2>
    <ul>
      <li><strong>Tech & Innovation:</strong> Thoughts on emerging technologies and updates on Starlink.</li>
      <li><strong>Travel & Adventure:</strong> Stories from Kovu Adventure tours and future travel plans.</li>
      <li><strong>Life & Self-Discovery:</strong> Personal growth reflections and family dynamics.</li>
      <li><strong>Music & Vibes:</strong> My favorite playlists and musical commentary.</li>
    </ul>
  </div>
</div>

<div class="container" id="contact">
  <div class="section">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:eugenegray83@gmail.com">eugenegray83@gmail.com</a></p>
    <p>WhatsApp: <a href="https://wa.me/254711682494" target="_blank">+254 711 682494</a></p>
  </div>
</div>

<footer>
  <p>&copy; 2024 My Blog | All rights reserved</p>
  <div class="social-icons">
    <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook-f"></i></a>
    <a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i></a>
    <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
  </div>
</footer>
</body>
</html>
