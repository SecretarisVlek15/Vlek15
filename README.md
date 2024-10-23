<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WTC Vlek15 Gouda</title>
     <link rel="stylesheet" href="styles.css"> <!-- Verwijst naar de CSS -->
    <style>
        body {
            font-family: 'Calibri', sans-serif;
            background-color: #282CFF; /* Blauw kleurcode */
            color: white;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #282CFF;
            padding: 10px;
            text-align: center;
            color: white;
        }
        .banner {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #0057b7;
            padding: 20px;
        }
        .banner img {
            width: 150px;
        }
        .banner .circle {
            width: 150px;
            height: 150px;
            background-color: gray;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: black;
            font-weight: bold;
            font-size: 18px;
        }
        .menu {
            display: flex;
            justify-content: center;
            background-color: #004494;
            padding: 10px;
        }
        .menu a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }
        .menu a:hover {
            text-decoration: underline;
        }
        .content {
            padding: 20px;
            text-align: left;
        }
        h1 {
            text-align: center;
            font-size: 36px;
            color: white;
        }
        p {
            font-size: 18px;
            line-height: 1.6;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            font-size: 18px;
            margin-bottom: 10px;
        }

/* Algemene stijlen voor de body */
body.homepage {
  background-color: green; /* Groene achtergrond voor de homepage */
}

body.doorklik {
  background-color: blue; /* Blauwe achtergrond voor doorklikpagina's */
}

/* Verbergt het menu standaard op mobiel */
#mobile-menu {
  display: none;
  background-color: silver; /* Zilvergrijze achtergrond voor het uitklapmenu */
  width: 100%;
  text-align: center;
}

/* Stijlen voor knoppen */
button, .btn {
  background-color: silver; /* Zilvergrijze achtergrond voor knoppen */
  color: black; /* Zwarte tekst */
  font-weight: bold; /* Vetgedrukt */
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  text-decoration: none;
  cursor: pointer;
}

button:hover, .btn:hover {
  background-color: #d3d3d3; /* Donkerder grijs bij hover */
  color: black; /* Zorgt ervoor dat de tekst zwart blijft */
}

/* Stijlen voor tussenkopjes (h1, h2, h3, etc.) */
h1, h2, h3, h4, h5, h6 {
  color: yellow; /* Gele kleur voor tussenkopjes */
  font-weight: bold;
}

/* Stijlen voor hyperlinks */
a {
  color: yellow; /* Gele kleur voor links */
  text-decoration: none; /* Geen onderstreping */
  font-weight: bold;
}

a:hover {
  color: orange; /* Oranje kleur bij hover */
}

/* Stijlen voor menu-items */
#mobile-menu ul {
  list-style-type: none;
  padding: 0;
  margin: 0;
}

#mobile-menu ul li {
  padding: 15px;
  border-bottom: 1px solid black; /* Zwarte lijnen tussen opties */
}

#mobile-menu ul li a {
  text-decoration: none;
  color: black; /* Zwarte tekst */
  font-weight: bold; /* Vetgedrukt */
  font-size: 18px;
}

#mobile-menu ul li a:hover {
  background-color: #d3d3d3; /* Donkerder grijs bij hover */
  color: black; /* Zorgt ervoor dat de tekst zwart blijft */
}

/* Het menu-icoon stijlen */
.menu-icon {
  font-size: 30px;
  cursor: pointer;
  display: none; /* Verborgen op desktop */
  padding: 15px;
  background-color: #333;
  color: white;
  text-align: center;
}

/* Stijlen voor desktop menu */
nav ul {
  display: flex;
  justify-content: center;
  background-color: #333;
  padding: 15px;
}

nav ul li {
  margin-right: 20px;
}

nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  font-size: 18px;
}

nav ul li a:hover {
  color: #ddd;
}

/* Media query voor schermen kleiner dan 768px */
@media (max-width: 768px) {
  .menu-icon {
    display: block;
  }

  nav ul {
    display: none; /* Verbergt het menu op mobiel, wordt vervangen door het uitklapmenu */
  }
}
    </style>
</head>
<body>


  <!-- Navigatie voor desktop  -->
  <nav>
    <ul id="desktop-menu">
    <li><a href="index.html">Home</a></li>
    <li><a href="spelregels.html">Spelregels</a></li>
    <li><a href="toerprogramma.html">Toerprogramma</a></li>
    <li><a href="#routeboek">Routeboek</a></li>
    <li><a href="#nieuws">Het Laatste Nieuws</a></li>
    </ul>
  </nav>

  <!-- Menu-icoon voor mobiel -->
  <div class="menu-icon" onclick="toggleMenu()">☰</div>

  <!-- Navigatie voor mobiel -->
  <nav id="mobile-menu">
    <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="spelregels.html">Spelregels</a></li>
    <li><a href="toerprogramma.html">Toerprogramma</a></li>
    <li><a href="#routeboek">Routeboek</a></li>
    <li><a href="#nieuws">Het Laatste Nieuws</a></li>
    </ul>
  </nav>


    <div class="banner">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/Wapen_van_Gouda.svg/200px-Wapen_van_Gouda.svg.png" alt="Wapen van Gouda">
        <div class="circle">
            <p>  Vlek15 Gouda - sinds 1984 </p>
        </div>
    </div>

    
    <main>
        <section class="content">
        <h1>Welkom bij Wielertoerclub Vlek15</h1>
        <p>WTC Vlek15 uit Gouda is een open en informele wielerclub voor iedereen. Om mee te kunnen fietsen heb je alleen een goed functionerende racefiets en een fietshelm nodig. Vervolgens kun je lid worden door je aan te melden bij de secretaris van Vlek15 via <a href="mailto:wtcvlek15@gmail.com">wtcvlek15@gmail.com</a></p>

        <p>De groepsritten hebben een sociaal karakter, er wordt gefietst volgens het principe SUST: Samen Uit, Samen Thuis!</p>

        <p>Van februari t/m oktober vertrekken we afwisselend op zaterdag- en zondagochtend vanaf wijkcentrum Van Noord aan de Lekkenburg in Gouda. Zie voor vertrektijden en afstanden het toerschema. Vanaf een kwartier voor de start ben je welkom voor inloop met een kop koffie. We vertrekken stipt op het tijdstip van het toerprogramma.</p>

        <p>Vanaf eind maart t/m eind september rijden we ook op dinsdag-en woensdagavond. Zie voor vertrektijden het toerprogramma.</p>

        <h2>Nieuw bij Vlek15?</h2>
        <p>Tijdens je eerste ritten leer je onze gebaren/signalen, daarnaast bespreken we de onderlinge afspraken. Je hoeft je niet vooraf aan te melden (mag zeker wel), je kunt dus gewoon langskomen en vragen naar de dienstdoende ritmeester.</p>

        <h2>Ons routeboek</h2>
        <p>Vlek15 beschikt over een fantastisch routeboek met meer dan 100 routes voor de racefiets. Een rit organiseren, een uitnodiging plaatsen en aanmelden kan in het routeboek.</p>

        <p>Zie <a href="https://routeboek.cc/club/vlek15" target="_blank">https://routeboek.cc/club/vlek15</a></p>

        <h2>Niveaus</h2>
        <ul>
            <li>Weekendrit Masters » gemiddelde snelheid 25 km/h</li>
            <li>Weekendrit Doortrappers » gemiddelde snelheid 28-30 km/h</li>
            <li>Avondrit Masters » gemiddelde snelheid 27 km/h</li>
            <li>Avondrit Doortrappers » gemiddelde snelheid 31 km/h</li>
            <li>Avondrit Buffels » gemiddelde snelheid 35 km/h</li>
        </ul>

        <h2>Whatsapp</h2>
        <p>De uitnodigingen voor de ritten worden geplaatst in het routeboek en vaak ook in de verschillende WhatsApp groepen. Er zijn ook handige groepen voor technische vragen, een Vlek15 marktplaats en nog veel meer. De groepen zijn te vinden op het WhatsApp Vlek15 Informatiekanaal.</p>

        <h2>Contributie</h2>
        <p>Vlek15 is een vereniging met leden. De contributie bedraagt in 2025 € 45 per jaar. De contributie wordt gebruikt voor de huur van onze startpositie van de weekendritten (inclusief koffie voor de start), de pontjes onderweg, het literaire clubblad “Het Laatste Nieuws” en enkele losse activiteiten gedurende het jaar.</p>

        <h2>Vlek15 kleding</h2>
        <p>Vlek15 kleding kan je aanschaffen via <a href="https://vlek15.36cycling.com/nl/shop/" target="_blank">https://vlek15.36cycling.com/nl/shop/</a></p>

        <h2>Aandachtspunt</h2>
        <p>Meerijden is altijd op eigen risico. Van alle deelnemers wordt verwacht dat er veilig gereden wordt. Na afloop wordt de rit geëvalueerd met speciale aandacht voor incidenten en onveilige situaties. Ondanks alle aandacht voor veiligheid kan het misgaan. Realiseer je dat schade die veroorzaakt wordt door andere renner over het algemeen niet valt onder een WA verzekering omdat er sprake is van een sport – en spelsituatie. Schade aan de fiets kun je verzekeren bij de NFTU of KNWU.</p>
    </section>

<script>
  function toggleMenu() {
    var menu = document.getElementById("mobile-menu");
    if (menu.style.display === "block") {
      menu.style.display = "none";
    } else {
      menu.style.display = "block";
    }
  }
</script>
</body>
</html>
