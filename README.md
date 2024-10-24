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
  color: #FFD700; /* Goudgele kleur voor tussenkopjes */
  font-weight: bold;
}

/* Stijlen voor hyperlinks */
a {
  color: #FFD700; /* Goudgele kleur voor links */
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


        /* Menu voor desktop */
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

        /* Menu voor mobiel */
        #mobile-menu {
            display: none;
            background-color: silver;
            width: 100%;
            text-align: center;
            position: absolute;
            top: 50px;
            left: 0;
            z-index: 999;
        }

        #mobile-menu ul {
            list-style-type: none;
            padding: 0;
        }

        #mobile-menu ul li {
            padding: 15px;
            border-bottom: 1px solid black;
        }

        #mobile-menu ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
            font-size: 18px;
        }

        #mobile-menu ul li a:hover {
            background-color: #d3d3d3;
        }

        .menu-icon {
            display: none;
            font-size: 30px;
            padding: 15px;
            background-color: #333;
            color: white;
            text-align: center;
        }

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
        <div class="banner">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e5/Wapen_van_Gouda.svg/200px-Wapen_van_Gouda.svg.png" alt="Wapen van Gouda">
            <div class="circle">
                <p>WTC Vlek15 Gouda sinds 1984</p>
            </div>
        </div>
        <!-- Menu voor desktop -->
        <nav>
            <ul class="menu">
                <li><a href="index.html">Home</a></li>
                <li><a href="spelregels.html">Spelregels</a></li>
                <li><a href="toerprogramma.html">Toerprogramma</a></li>
                <li><a href="#nieuws">Het Laatste Nieuws</a></li>
            </ul>
        </nav>
        <!-- Menu voor mobiel -->
        <div class="menu-icon" onclick="toggleMenu()">☰</div>
        <nav id="mobile-menu">
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="spelregels.html">Spelregels</a></li>
                <li><a href="toerprogramma.html">Toerprogramma</a></li>
                <li><a href="#nieuws">Het Laatste Nieuws</a></li>
            </ul>
        </nav>
    </header>

    
    
    <main>
        <section class="content">
        <h1>Welkom bij Wielertoerclub Vlek15</h1>
        <p>WTC Vlek15 uit Gouda is een open en informele wielerclub voor iedereen. Om mee te kunnen fietsen heb je alleen een goed functionerende racefiets en een fietshelm nodig. </p>

        <p>Van februari t/m oktober vertrekken we afwisselend op zaterdag- en zondagochtend vanaf wijkcentrum Van Noord (adres: Lekkenburg 1, 2804 XJ te Gouda). Zie voor vertrektijden en afstanden het toerprogramma. Vanaf een kwartier voor de start ben je welkom voor inloop met een kop koffie. </p>
        
        <p>Vanaf eind maart t/m eind september rijden we ook op dinsdag-en woensdagavond. Zie voor vertrektijden het toerprogramma.</p>

        <p>Alle groepsritten hebben een sociaal karakter, er wordt gefietst volgens het principe SUST: Samen Uit, Samen Thuis!</p>

        <h2>Nieuw bij Vlek15?</h2>
        <p>Lijkt het je leuk om met ons mee te fietsen ? Je bent van harte welkom om geheel vrijblijvend één of meerdere keren op proef met ons mee te fietsen.Tijdens je eerste ritten leer je onze gebaren/signalen, daarnaast bespreken we de onderlinge afspraken. Je hoeft je hier niet vooraf voor aan te melden. </p>
        
        Wil je graag enige informatie vooraf?  Neem dan contact op met de secretaris van Vlek15 via <a href="mailto:wtcvlek15@gmail.com">wtcvlek15@gmail.com</a> Of kom spontaan langs voor het vertrek van een rit. Zie voor vertrektijden het toerprogramma. </p>

                <h2>Niveaus</h2>
        <ul>
            <li>Weekendrit Masters » gemiddelde snelheid 25 km/h</li>
            <li>Weekendrit Doortrappers » gemiddelde snelheid 28 km/h</li>
            <li>Avondrit Masters » gemiddelde snelheid 27 km/h</li>
            <li>Avondrit Doortrappers » gemiddelde snelheid 31 km/h</li>
            <li>Avondrit Buffels » gemiddelde snelheid 35 km/h</li>
        </ul>

        <h2>Ons toerprogramma</h2>
        <p>Vlek15 stelt elk jaar een prachtig toerprogramma samen. Voor de weekendritten zijn afzonderlijke ritten opgenomen voor de Masters en de Doortrappers. Ook is er een (beperkt) aantal ritten waarbij de Masters en de Doortrappers gezamnelijk opfietsen. Dat zorgt voor extra gezelligheid en verbondenheid binnen onze club. Het actuele toerprogramma vind je via de menubalk van de website </p>

        <h2>WhatsApp</h2>
        <p>Wekelijks versturen we via WhatsApp een toelichting op de komende weekendritten naar onze leden. Ook andere relevante nieuwtjes voor Vlek15 worden via WhatsApp gedeeld. Alle leden van Vlek15 maken onderdeel uit van deze WhatsApp-groep, maar alleen de beheerders  kunnen berichten versturen (of nieuwe leden toelaten). Op deze manier voorken we onnodige spam in je WhatsApp-box. </p>

        <h2>Contributie</h2>
        <p>Vlek15 is een vereniging met leden. De contributie bedraagt in 2025 € 45 per jaar. De contributie wordt gebruikt voor de huur van onze startpositie van de weekendritten (inclusief koffie voor de start), de pontjes onderweg, het literaire clubblad “Het Laatste Nieuws” en enkele losse activiteiten gedurende het jaar.</p>

        <h2>Vlek15 kleding</h2>
        <p>Vlek15 kleding kan je aanschaffen via <a href="https://vlek15.36cycling.com/nl/shop/" target="_blank">https://vlek15.36cycling.com/nl/shop/</a></p>

        <h2>Aandachtspunt</h2>
        <p>Meerijden is altijd op eigen risico. Van alle deelnemers wordt verwacht dat er veilig gereden wordt. Na afloop wordt de rit geëvalueerd met speciale aandacht voor incidenten en onveilige situaties. Ondanks alle aandacht voor veiligheid kan het misgaan. Realiseer je dat schade die veroorzaakt wordt door andere renner over het algemeen niet valt onder een WA verzekering omdat er sprake is van een sport – en spelsituatie. Schade aan de fiets kun je verzekeren bij de NFTU of KNWU.</p>
    </section>
</main>

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
