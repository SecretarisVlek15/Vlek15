<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WTC Vlek15 Gouda</title>
    <style>
        /* Verbergt het menu standaard */
#mobile-menu {
  display: none;
  background-color: silver; /* Zilvergrijze achtergrond */
  width: 100%;
  text-align: center;
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

/* Media query voor schermen kleiner dan 768px */
@media (max-width: 768px) {
  .menu-icon {
    display: block;
  }

  nav ul {
    display: none;
  }
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

<div class="menu-icon" onclick="toggleMenu()">☰</div>
<nav id="mobile-menu">
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="spelregels.html">Spelregels</a></li>
    <li><a href="toerprogramma.html">Toerprogramma</a></li>
    <li><a href="#routeboek">Routeboek</a></li>
    <li><a href="#nieuws">Het Laatste Nieuws</a></li>
  </ul>
</nav>
    
    <main>
        <section class="content">
        <h1>Welkom bij Vlek15</h1>
        <p>Vlek15 uit Gouda is een open en informele wielerclub voor iedereen. Om mee te kunnen fietsen heb je alleen een goed functionerende racefiets en een fietshelm nodig. Vervolgens kun je lid worden door je aan te melden bij de secretaris van Vlek15 via <a href="mailto:wtcvlek15@gmail.com">wtcvlek15@gmail.com</a></p>

        <p>De groepsritten hebben een sociaal karakter, er wordt gefietst volgens het principe SUST: Samen Uit, Samen Thuis!</p>

        <p>Van februari t/m oktober vertrekken we afwisselend op zaterdag- en zondagochtend vanaf wijkcentrum Van Noord aan de Lekkenburg in Gouda. Zie voor vertrektijden en afstanden het toerschema. Vanaf een kwartier voor de start ben je welkom voor inloop met een kop koffie. We vertrekken stipt op het tijdstip van het toerprogramma.</p>

        <p>Vanaf eind maart t/m eind september rijden we ook op dinsdag-en woensdagavond. Zie voor vertrektijden het toerschema.</p>

        <h2>Nieuw bij Vlek15?</h2>
        <p>Tijdens je eerste ritten leer je onze gebaren/signalen, daarnaast bespreken we de onderlinge afspraken. Je hoeft je niet vooraf aan te melden (mag zeker wel), je kunt gewoon langskomen en vragen naar de dienstdoende ritmeester.</p>

        <h2>Het Routeboek</h2>
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

        <h2>Kleding en contributie</h2>
        <p>Vlek15 is een vereniging met leden. De contributie bedraagt in 2025 € 45 per jaar. De contributie wordt gebruikt voor de huur van onze startpositie van de weekendritten (inclusief koffie voor de start), de pontjes onderweg, het literaire clubblad “Het Laatste Nieuws” en enkele losse activiteiten gedurende het jaar.</p>

        <p>Vlek15 kleding kan je aanschaffen via <a href="https://vlek15.36cycling.com/nl/shop/" target="_blank">https://vlek15.36cycling.com/nl/shop/</a></p>

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
