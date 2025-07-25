<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Portfolio</title>
  <style>
    :root {
      --primary: #0077cc;
      --accent: #ff8c42;
      --background: #fefefe;
      --text: #1a1a1a;
      --soft-blue: #e0f7ff;
      --soft-orange: #fff1e6;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: var(--background);
      color: var(--text);
    }

    header {
      background: linear-gradient(135deg, var(--primary), var(--accent));
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
    }

    header p {
      font-size: 1.2rem;
      color: #f0f0f0;
    }

    nav {
      display: flex;
      justify-content: center;
      background: var(--soft-blue);
      padding: 10px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: var(--primary);
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .card {
      background: white;
      padding: 20px;
      margin: 20px 0;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
      border-left: 6px solid var(--accent);
      border-radius: 10px;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 8px;
    }

    .video-container {
      margin-top: 20px;
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .video-container iframe {
      width: 100%;
      max-width: 480px;
      height: 270px;
      border: none;
      border-radius: 8px;
    }

    footer {
      background: var(--soft-orange);
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: var(--text);
    }
  </style>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <p>Creative Professional | Florida Vibes | Bold Vision</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#videos">Videos</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <div class="card">
      <h2>About Me</h2>
      <p>I am a passionate professional merging tropical inspiration with American drive. I believe in colorful ideas, elegant execution, and creating meaningful impact through creativity, strategy, and technology.</p>
    </div>
  </section>

  <section id="portfolio">
    <div class="card">
      <h2>Project Gallery</h2>
      <div class="gallery">
        <img src="https://via.placeholder.com/400x250?text=Project+1" alt="Project 1">
        <img src="https://via.placeholder.com/400x250?text=Project+2" alt="Project 2">
        <img src="https://via.placeholder.com/400x250?text=Project+3" alt="Project 3">
        <img src="https://via.placeholder.com/400x250?text=Project+4" alt="Project 4">
      </div>
    </div>
  </section>

  <section id="videos">
    <div class="card">
      <h2>Watch Me in Action</h2>
      <div class="video-container">
        <iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/9bZkp7q19f0" allowfullscreen></iframe>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="card">
      <h2>Contact Me</h2>
      <p>Email: <a href="mailto:your@email.com">your@email.com</a></p>
      <p>Connect: <a href="#">Instagram</a> | <a href="#">LinkedIn</a> | <a href="#">YouTube</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Your Name. Designed with color + purpose.</p>
  </footer>
</body>
</html>
