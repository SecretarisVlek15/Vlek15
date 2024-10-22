<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WTC Vlek15 Gouda</title>
    <style>
        body {
            font-family: Calibri, sans-serif;
            background-color: #282C;
            color: white;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #1B1E3D;
            color: white;
            padding: 10px;
            text-align: center;
        }

        .banner {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #1B1E3D;
            padding: 20px;
        }

        .banner img {
            width: 150px;
        }

        .circle {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            background-color: grey;
            display: flex;
            justify-content: center;
            align-items: center;
            color: black;
            font-size: 20px;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }

        nav a:hover {
            background-color: #575757;
        }

        main {
            padding: 20px;
        }

        h1, h2, h3 {
            color: #FFD700; /* Goudkleur voor koppen */
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #1B1E3D;
        }
    </style>
</head>
<body>

    <header>
        <h1>Wielertoerclub Vlek15 Gouda</h1>
    </header>

    <div class="banner">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/Wapen_van_Gouda.svg/200px-Wapen_van_Gouda.svg.png" alt="Wapen van Gouda">
        <div class="circle">
            <p>Vlek15 Gouda - sinds 1984</p>
        </div>
    </div>

    <nav>
        <a href="#">Home</a>
        <a href="#toerprogramma">Toerprogramma</a>
        <a href="#spelregels">Spelregels</a>
        <a href="#routeboek">Routeboek</a>
        <a href="#nieuws">Het Laatste Nieuws</a>
    </nav>

    <main>
        <section id="home">
            <h2>Welkom bij Vlek15</h2>
            <p>Vlek15 uit Gouda is een open en informele wielerclub voor iedereen. Om mee te kunnen fietsen heb je alleen een goed functionerende racefiets en een fietshelm nodig. Vervolgens kun je lid worden door je aan te melden bij de secretaris van Vlek15 via wtcvlek15@gmail.com.</p>
            <p>De groepsritten hebben een sociaal karakter, er wordt gefietst volgens het principe SUST: Samen Uit, Samen Thuis!</p>
            <p>Van februari t/m oktober vertrekken we afwisselend op zaterdag- en zondagochtend vanaf wijkcentrum Van Noord aan de Lekkenburg in Gouda...</p>
            <!-- Voeg hier de volledige tekst van de club toe zoals in je vraag -->
        </section>

        <section id="toerprogramma">
            <h2>Toerprogramma</h2>
            <p>Hier komt het toerprogramma dat je verder kunt aanpassen...</p>
        </section>

        <section id="spelregels">
            <h2>Spelregels</h2>
            <p>Etiquette op de weg en signalen komen hier...</p>
        </section>

        <section id="routeboek">
            <h2>Routeboek</h2>
            <p>Bekijk het volledige routeboek van Vlek15 hier: <a href="https://routeboek.cc/club/vlek15" target="_blank">Routeboek Vlek15</a></p>
        </section>

        <section id="nieuws">
            <h2>Het Laatste Nieuws</h2>
            <p>Bekijk de laatste editie van het clubblad <a href="#">hier</a>.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Vlek15 Gouda</p>
    </footer>

</body>
</html>
