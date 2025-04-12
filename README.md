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
