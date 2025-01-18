<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deine Erfolgswebsite</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;700&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: radial-gradient(circle, #1e1e2f, #15151f);
            color: #eaeaea;
        }
        header {
            background: linear-gradient(90deg, #ff7eb3, #ff758c);
            color: white;
            padding: 50px 20px;
            text-align: center;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
        }
        header h1 {
            margin: 0;
            font-size: 3.5em;
            letter-spacing: 2px;
            text-transform: uppercase;
        }
        header p {
            margin: 20px 0 0;
            font-size: 1.5em;
            opacity: 0.9;
        }
        .container {
            max-width: 1200px;
            margin: 50px auto;
            padding: 30px;
            background: rgba(255, 255, 255, 0.05);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
        }
        .cta {
            text-align: center;
            margin: 40px 0;
        }
        .cta button {
            background: linear-gradient(90deg, #ff758c, #ff7eb3);
            color: white;
            padding: 15px 40px;
            border: none;
            border-radius: 25px;
            font-size: 1.5em;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .cta button:hover {
            transform: scale(1.1);
            box-shadow: 0 5px 15px rgba(255, 118, 137, 0.5);
        }
        section {
            margin-bottom: 40px;
        }
        section h2 {
            color: #ff7eb3;
            font-size: 2em;
            margin-bottom: 20px;
        }
        section p {
            line-height: 1.8;
            font-size: 1.2em;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            background: rgba(255, 255, 255, 0.1);
            margin: 10px 0;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }
        ul li strong {
            color: #ff758c;
        }
        footer {
            background: #15151f;
            color: #a5a5a5;
            text-align: center;
            padding: 20px 10px;
            margin-top: 50px;
            border-top: 1px solid #2e2e38;
        }
        footer p {
            margin: 0;
            font-size: 0.9em;
        }
        .contact-form {
            margin: 40px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3);
            max-width: 600px;
        }
        .contact-form h2 {
            text-align: center;
            color: #ff7eb3;
            margin-bottom: 20px;
        }
        .contact-form label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
            background: rgba(255, 255, 255, 0.2);
            color: #eaeaea;
            font-size: 1em;
        }
        .contact-form input::placeholder, .contact-form textarea::placeholder {
            color: #c2c2c2;
        }
        .contact-form button {
            display: block;
            width: 100%;
            padding: 10px;
            background: linear-gradient(90deg, #ff758c, #ff7eb3);
            border: none;
            border-radius: 25px;
            font-size: 1.2em;
            color: white;
            font-weight: bold;
            cursor: pointer;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .contact-form button:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(255, 118, 137, 0.5);
        }
    </style>
</head>
<body>
    <header>
        <h1>Deine Erfolgswebsite</h1>
        <p>Dein Schritt in die digitale Zukunft</p>
    </header>
    <div class="container">
        <section>
            <h2>Warum eine professionelle Website entscheidend ist</h2>
            <p>Wusstest Du, dass über 70% der Kunden Unternehmen online suchen, bevor sie eine Kaufentscheidung treffen? Ohne eine moderne Website kannst Du diesen potenziellen Kunden entgehen lassen. Lass uns gemeinsam Deine perfekte Website erstellen, die Deine Marke widerspiegelt und Deine Umsätze steigert.</p>
        </section>
        <section>
            <h2>Was wir Dir bieten</h2>
            <ul>
                <li><strong>Modernes Design:</strong> Wir gestalten Deine Website so, dass sie ins Auge fällt und einen bleibenden Eindruck hinterlässt.</li>
                <li><strong>Benutzerfreundlichkeit:</strong> Deine Kunden finden schnell und einfach, wonach sie suchen.</li>
                <li><strong>Mobile Optimierung:</strong> Perfekte Darstellung auf Smartphones, Tablets und PCs.</li>
                <li><strong>SEO-Optimierung:</strong> Wir sorgen dafür, dass Deine Website bei Google gefunden wird.</li>
            </ul>
        </section>
        <section>
            <h2>Verpasse keine Kunden mehr!</h2>
            <p>Die meisten Kunden entscheiden innerhalb weniger Sekunden, ob sie auf Deiner Website bleiben. Mit uns machst Du diese entscheidenden Sekunden zu Deinem Vorteil. Überzeuge und verwandle Besucher in Kunden!</p>
        </section>
        <div class="cta">
            <button onclick="document.getElementById('contact-section').scrollIntoView({ behavior: 'smooth' });">Jetzt kostenloses Beratungsgespräch anfragen</button>
        </div>
        <section id="contact-section" class="contact-form">
            <h2>Kontaktformular</h2>
            <form action="#" method="POST">
                <label for="name">Name des Unternehmens:</label>
                <input type="text" id="name" name="name" placeholder="Gib Deinen Unternehmensnamen ein" required>

                <label for="email">E-Mail-Adresse:</label>
                <input type="email" id="email" name="email" placeholder="Deine E-Mail-Adresse" required>

                <label for="message">Nachricht:</label>
                <textarea id="message" name="message" rows="5" placeholder="Wie können wir Dir helfen?" required></textarea>

                <button type="submit">Absenden</button>
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2025 Deine Erfolgswebsite. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>

