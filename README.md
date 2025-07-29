<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Specimens Studios Fish Editing Services</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f4f8;
      color: #222;
    }
    header {
      background: linear-gradient(to right, #0f172a, #1e3a8a);
      color: white;
      padding: 3rem 1rem;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.25rem;
      margin-top: 0.5rem;
    }
    section {
      padding: 3rem 1rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      border-bottom: 2px solid #0c4a6e;
      display: inline-block;
    }
    ul {
      padding-left: 1.5rem;
    }
    li {
      margin-bottom: 0.5rem;
    }
    .portfolio {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
      margin-top: 2rem;
    }
    .portfolio img {
      width: 100%;
      max-width: 300px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
      transition: transform 0.2s ease;
    }
    .portfolio img:hover {
      transform: scale(1.03);
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      background-color: #e5e7eb;
      color: #555;
      margin-top: 3rem;
    }
    .button {
      background-color: #2563eb;
      color: white;
      padding: 0.75rem 1.5rem;
      text-decoration: none;
      border-radius: 8px;
      display: inline-block;
      margin-top: 1rem;
      font-weight: bold;
      transition: background-color 0.2s ease;
    }
    .button:hover {
      background-color: #1d4ed8;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.75rem;
      margin-top: 0.25rem;
      border: 1px solid #ccc;
      border-radius: 6px;
      font-size: 1rem;
      margin-bottom: 1rem;
    }
    form button {
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <h1>Specimens Studios Fish Editing Services</h1>
    <p>Professional editing and background removal for ichthyology images</p>
  </header>

  <section>
    <h2>What I Do</h2>
    <p>I specialize in editing fish specimen images for scientific publication. I provide high-quality edits tailored to ichthyologists and taxonomists; contact me if you need clean background removal, subtle enhancement, or full figure assembly for journals.</p>
    <ul>
      <li>Background removal (white, black, or transparent)</li>
      <li>Image enhancement (color, contrast, clarity)</li>
      <li>Figure plate assembly</li>
      <li>Scientific formatting (TIFFs, scale bars, etc.)</li>
    </ul>
    <a class="button" href="#contact">Contact Me</a>
  </section>

  <section>
    <h2>Sample Portfolio</h2>
    <div class="portfolio">
      <img src="Fenerbahce_sp.JPG" alt="Fenerbahce sp" title="Fenerbahce sp">
      <img src="Microctenopoma_ansorgii-1.png" alt="Microctenopoma ansorgii" title="Microctenopoma ansorgii">
      <img src="Pantodon_bucholzi.jpg" alt="Pantodon bucholzi" title="Pantodon bucholzi">
      <img src="Pareutropius_debauwi.jpg" alt="Pareutropius debauwi" title="Pareutropius debauwi">
    </div>
  </section>

  <section>
    <h2>Finished Plates</h2>
    <div class="portfolio">
      <img src="chichlidsplate-1.png" alt="Figure Plate 1" title="Figure Plate 1">
      <img src="killiesplate-1.png" alt="Figure Plate 2" title="Figure Plate 2">
      <img src="idkplate-1.png" alt="Figure Plate 3" title="Figure Plate 3">
    </div>
  </section>

  <section id="contact">
    <h2>Get in Touch</h2>
    <p>Interested in working together? I'd love to hear from you! Email me at <strong>julia@specimensstudio.com</strong> or send me a message below:</p>
    <form action="https://formspree.io/f/mrblkyer" method="POST">
      <input type="hidden" name="_next" value="https://wmanningcat.github.io/Specimens-Studios/thankyou.html">
      <label>Your Name:<br><input type="text" name="name" required></label>
      <label>Your Email:<br><input type="email" name="email" required></label>
      <label>Message:<br><textarea name="message" rows="5" required></textarea></label>
      <button class="button" type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Julia Manning. Fish photo editing by scientists, for scientists.
  </footer>
</body>
</html>

