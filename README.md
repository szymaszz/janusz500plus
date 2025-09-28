<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Partia Janusz500+</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #b30000;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section, main {
            padding: 30px;
            text-align: center;
        }

        h1, h2, h3 {
            color: #b30000;
        }

        img {
            max-width: 90%;
            height: auto;
            border: 2px solid #333;
            margin-top: 20px;
            border-radius: 8px;
        }

        /* Aktualności */
        .news {
            background: white;
            margin: 20px auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            max-width: 800px;
        }

        .news img {
            width: 40%;
            display: block;
            margin: 10px auto;
        }

        /* Formularz kontaktowy */
        form {
            margin-top: 20px;
        }

        input, textarea {
            padding: 10px;
            width: 80%;
            max-width: 400px;
            margin: 10px auto;
            display: block;
            border: 1px solid #aaa;
            border-radius: 5px;
        }

        input[type="submit"] {
            background-color: #b30000;
            color: white;
            border: none;
            cursor: pointer;
        }

        /* Stopka */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }

        footer a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1>Partia Janusz500+</h1>
        <p>Każdemu się należy – z piwem do Sejmu!</p>
    </header>

    <section id="onas">
        <h2>O nas</h2>
        <p>
            Partia Janusz500+ powstała w październiku 2023 roku. Walczymy o to, żeby 500+ było 1000+, 
            a każda rodzina miała prawo do darmowej kiełbasy, passata i darmowego piwa.
        </p>
        <img src="janusz500plus.png" alt="Logo Partii">
    </section>

    <main>
        <h2>Aktualności</h2>

        <div class="news">
            <h3>📢 Rozwieszanie ulotek</h3>
            <img src="ulotkapartii.jpg" alt="Rozwieszanie ulotek">
            <p>W przyszłym tygodniu będziemy rozwieszać ulotki zachęcające do dołączenia do partii. Jeśli chcesz nam pomóc, skontaktuj się z nami.</p>
            <small>Data: 29.09 – 05.10.2025</small>
        </div>
    </main>

    <section id="kontakt">
        <h2>Kontakt</h2>
        <p>Masz pytania? Chcesz dołączyć do partii? Skontaktuj się z nami!</p>

        <p><strong>Email:</strong> janusz500plus@gmail.com</p>
        <p><strong>Telefon:</strong> 720-444-244</p>

        <form>
            <input type="text" name="name" placeholder="Twoje imię" required>
            <input type="email" name="email" placeholder="Twój email" required>
            <textarea name="message" rows="5" placeholder="Twoja wiadomość"></textarea>
            <input type="submit" value="Wyślij">
        </form>
    </section>

    <footer>
        &copy; 2025 Partia Janusz500+ | Wszelkie prawa zastrzeżone
        <br>
        <a href="https://www.facebook.com/people/Janusz500/100089054617236" target="_blank">📘 Facebook</a>
        <a href="https://x.com/PartiaJanusz500/status/1874083948009316792" target="_blank">🐦 X (Twitter)</a>
    </footer>

</body>
</html>
