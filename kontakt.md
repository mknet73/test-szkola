---
layout: null
title: Kontakt
permalink: /kontakt/
---

<!DOCTYPE html>
<html lang="pl">
<head>
  {% include head.html %}
  <title>Kontakt | {{ site.title }}</title>
</head>
<body>
  <header>
    <h1>Kontakt</h1>
    <nav>
      <a href="/"><i class="material-icons">home</i> Strona główna</a>
      <a href="/aktualnosci"><i class="material-icons">event</i> Aktualności</a>
      <a href="/o-szkole"><i class="material-icons">school</i> O szkole</a>
      <a href="/oferta"><i class="material-icons">menu_book</i> Oferta</a>
    </nav>
  </header>
  <main>
    <section class="mdc-card">
      <p>
        Zespół Szkół im. Bohaterów Narwiku<br>
        ul. Szkolna 1, 00-000 Miasto<br>
        E-mail: <a href="mailto:kontakt@szkola.edu.pl">kontakt@szkola.edu.pl</a><br>
        Telefon: 123 456 789
      </p>
      <form>
        <md-outlined-text-field label="Imię i nazwisko" required></md-outlined-text-field><br><br>
        <md-outlined-text-field label="Adres e-mail" type="email" required></md-outlined-text-field><br><br>
        <md-outlined-text-field label="Wiadomość" textarea rows="4" required></md-outlined-text-field><br><br>
        <md-filled-button type="submit">Wyślij</md-filled-button>
      </form>
    </section>
  </main>
  <footer>
    &copy; 2025 Zespół Szkół im. Bohaterów Narwiku
  </footer>
</body>
</html>
