<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chemie Mach Mit - Farbstoffe</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400&display=swap">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-image: linear-gradient(to bottom, #f0f0f0, #d6d6d6);
        }
        header {
            background-color: #ccc;
            color: #000;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #0056b3;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }
        main {
            padding: 20px;
            margin-bottom: 50px; /* Platz für den fest positionierten Footer */
        }
        section {
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 5px;
        }
        section h2 {
            font-size: 24px;
            margin-bottom: 10px;
            padding: 10px;
        }
        section p {
            font-size: 18px;
            line-height: 1.6;
        }
        .toggle-text {
            display: none;
        }
        .show-less {
            color: #007bff;
            cursor: pointer;
        }
        img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
            margin-top: 20px;
            border-radius: 5px;
        }
        footer {
            background-color: #00cccc;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        /* Farbstoff-Überschriften */
        #anthocyan {
            background-color: #ffc0cb; /* Pink */
        }
        #azurobin {
            background-color: #ffa07a; /* Light Salmon */
        }
        #beta-carotin {
            background-color: #87ceeb; /* Sky Blue */
        }
        /* Farben für die Überschriften */
        #anthocyan h2 {
            color: #8b0000; /* Dunkelrot */
        }
        #azurobin h2 {
            color: #0000ff; /* Blau */
        }
        #beta-carotin h2 {
            color: #ffcc00; /* Gelb */
        }
    </style>
</head>
<body>
    <header>
        <h1>Chemie Mach Mit</h1>
        <p>Informationen über Farbstoffe</p>
    </header>
    <nav>
        <a href="#anthocyan">Anthocyan</a>
        <a href="#azurobin">Azurobin</a>
        <a href="#beta-carotin">Beta-Carotin</a>
    </nav>
    <main>
        <section id="anthocyan">
            <h2>Anthocyan</h2>
            <p>Anthocyane sind wasserlösliche Pflanzenfarbstoffe, die den Pflanzen ihre rote, blaue oder violette Farbe geben. Sie kommen in vielen roten, blauen und violetten Früchten und Gemüsesorten vor, wie z.B. Trauben, Blaubeeren, Rotkohl und Auberginen. Anthocyane sind auch für ihre gesundheitlichen Vorteile bekannt, da sie starke Antioxidantien sind und entzündungshemmende Eigenschaften haben.</p>
            <span class="show-less toggle-text" onclick="toggleText(this)">Weniger anzeigen</span>
            <img src="Screenshot 2024-05-01 134039.png" alt="Anthocyan">
        </section>
        <section id="azurobin">
            <h2>Azurobin</h2>
            <p>Azurobin ist ein synthetischer blauer Farbstoff, der häufig in der Lebensmittel- und Textilindustrie verwendet wird. Er verleiht Lebensmitteln wie Süßigkeiten, Getränken und Backwaren eine intensive blaue Farbe. Azurobin wird auch in der Textilindustrie zum Färben von Stoffen verwendet.</p>
            <span class="show-less toggle-text" onclick="toggleText(this)">Weniger anzeigen</span>
            <img src="Screenshot 2024-05-01 154653.png" alt="Azurobin">
        </section>
        <section id="beta-carotin">
            <h2>Beta-Carotin</h2>
            <p>Beta-Carotin ist ein natürlich vorkommendes Pigment, das in vielen gelben, orangfarbenen und grünen Früchten und Gemüsesorten vorkommt, wie z.B. Karotten, Süßkartoffeln, Mango und Spinat. Es wird auch als Nahrungsergänzungsmittel verwendet und ist eine Vorstufe von Vitamin A.</p>
            <span class="show-less toggle-text" onclick="toggleText(this)">Weniger anzeigen</span>
            <img src="Screenshot 2024-05-01 143540.png" alt="Beta-Carotin">
        </section>
    </main>
    <footer>
        <p style="color: aqua; font-size: 14px;">Diese Seite wurde von Jameson, Mohamed und Timeo erstellt</p>
    </footer>
    <script>
        function toggleText(element) {
            var textElement = element.parentNode.querySelector('.toggle-text');

            if (textElement.style.display === "none") {
                textElement.style.display = "inline";
                element.textContent = "Weniger anzeigen";
            } else {
                textElement.style.display = "none";
                element.textContent = "Mehr anzeigen";
            }
        }
    </script>
</body>
</html>
