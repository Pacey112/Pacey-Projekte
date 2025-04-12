# testtest

<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meine Beispiel-Webseite</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Header -->
  <header>
    <div class="container">
      <h1>Willkommen auf meiner Webseite!</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#about">Über mich</a></li>
          <li><a href="#services">Dienstleistungen</a></li>
          <li><a href="#contact">Kontakt</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Main Content -->
  <main>
    <section id="home" class="section">
      <div class="container">
        <h2>Startseite</h2>
        <p>Dies ist die Startseite meiner Beispiel-Webseite. Hier findest du alles über mich und meine Dienstleistungen.</p>
      </div>
    </section>

    <section id="about" class="section">
      <div class="container">
        <h2>Über mich</h2>
        <p>Ich bin ein Webentwickler mit Leidenschaft für Design und Technologie. Ich arbeite an verschiedenen Projekten und biete Dienstleistungen in den Bereichen Webdesign und Entwicklung an.</p>
      </div>
    </section>

    <section id="services" class="section">
      <div class="container">
        <h2>Unsere Dienstleistungen</h2>
        <ul>
          <li>Webdesign</li>
          <li>Webentwicklung</li>
          <li>SEO-Optimierung</li>
        </ul>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2>Kontakt</h2>
        <p>Du kannst mich über das folgende Formular kontaktieren:</p>
        <form action="#" method="POST">
          <label for="name">Name:</label>
          <input type="text" id="name" name="name" required><br><br>
          
          <label for="email">E-Mail:</label>
          <input type="email" id="email" name="email" required><br><br>
          
          <label for="message">Nachricht:</label><br>
          <textarea id="message" name="message" rows="4" required></textarea><br><br>
          
          <button type="submit">Absenden</button>
        </form>
      </div>
    </section>
  </main>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 Meine Webseite. Alle Rechte vorbehalten.</p>
    </div>
  </footer>

</body>
</html>

<nav style="position: sticky; top: 0; background: #222; color: white; padding: 10px; z-index: 1000;">
  <a href="#start" style="margin-right: 20px; color: white;">Start</a>
  <a href="#über" style="margin-right: 20px; color: white;">Über mich</a>
  <a href="#kontakt" style="color: white;">Kontakt</a>
</nav>

<header style="padding: 60px; background: linear-gradient(to right, #0077ff, #00c6ff); color: white; text-align: center;">
  <h1>Willkommen auf meiner Webseite!</h1>
  <p>Hier findest du Projekte, Ideen und mehr.</p>
  <a href="#projekte" style="padding: 10px 20px; background: white; color: #0077ff; border-radius: 5px; text-decoration: none;">Mehr erfahren</a>
</header>

<section id="über" style="padding: 40px; text-align: center;">
  <h2>Über mich</h2>
  <img src="https://via.placeholder.com/150" alt="Profilbild" style="border-radius: 50%;">
  <p>Ich bin ein Webentwickler mit Fokus auf kreative Frontend-Projekte.</p>
</section>

<section id="projekte" style="padding: 40px;">
  <h2>Meine Projekte</h2>
  <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
    <div style="width: 300px; background: white; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); padding: 20px;">
      <h3>Projekt 1</h3>
      <p>Kleiner Beschreibungstext zum Projekt.</p>
      <a href="#">Ansehen</a>
    </div>
    <div style="width: 300px; background: white; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); padding: 20px;">
      <h3>Projekt 2</h3>
      <p>Ein weiteres cooles Projekt!</p>
      <a href="#">Ansehen</a>
    </div>
  </div>
</section>

<section id="kontakt" style="padding: 40px; background-color: #f9f9f9;">
  <h2>Kontakt</h2>
  <form action="https://formspree.io/f/YOUR_ID" method="POST" style="max-width: 500px; margin: auto;">
    <input type="text" name="name" placeholder="Dein Name" required style="width: 100%; margin-bottom: 10px; padding: 10px;">
    <input type="email" name="email" placeholder="Deine E-Mail" required style="width: 100%; margin-bottom: 10px; padding: 10px;">
    <textarea name="nachricht" placeholder="Deine Nachricht" required style="width: 100%; margin-bottom: 10px; padding: 10px;"></textarea>
    <button type="submit" style="padding: 10px 20px; background-color: #0077ff; color: white; border: none; cursor: pointer;">Absenden</button>
  </form>
</section>

<footer style="text-align: center; padding: 20px; background: #222; color: white;">
  <p>© 2025 Deine Webseite</p>
  <a href="https://github.com/deinname" target="_blank" style="color: white; margin: 0 10px;">GitHub</a>
  <a href="https://instagram.com/deinname" target="_blank" style="color: white; margin: 0 10px;">Instagram</a>
</footer>

<script>
  document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
      e.preventDefault();
      const target = document.querySelector(this.getAttribute('href'));
      if (target) {
        target.scrollIntoView({ behavior: 'smooth' });
      }
    });
  });
</script>

