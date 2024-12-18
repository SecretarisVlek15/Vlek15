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

/* Globale stijlen voor kopjes met een lijn eronder */
h1, h2, h3, h4, h5, h6 {
  color: #FFD700; /* Goudgele kleur */
  font-weight: bold;
  border-bottom: 2px solid #FFD700; /* Lijn onder elk kopje */
  padding-bottom: 10px;
  margin-bottom: 20px;
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

/* Alleen het mobiele menu tonen voor schermen kleiner dan 769px */
@media (max-width: 768px) {
    .menu {
        display: none; /* Verberg desktopmenu */
    }
    #mobile-menu {
        display: block; /* Toon mobiele menu */
    }
}

/* Alleen het desktopmenu tonen voor schermen groter dan 768px */
@media (min-width: 769px) {
    #mobile-menu,
    .menu-icon {
        display: none; /* Verberg mobiele menu en menu-icoon */
    }
}

/* Stijlen voor het uitklapmenu */
.dropdown {
    position: relative;
    display: inline-block;
}

.dropbtn {
    background-color: #004494; /* Dezelfde kleur als het oude menu */
    color: white;
    padding: 10px;
    font-size: 16px;
    border: none;
    cursor: pointer;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9; /* Achtergrondkleur van het dropdownmenu */
    min-width: 160px;
    z-index: 1;
}

.dropdown-content a {
    color: #000; /* Kleur van de links in het menu */
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {
    background-color: #d3d3d3; /* Hover-effect voor links */
}

.dropdown:hover .dropdown-content {
    display: block; /* Toont het menu bij hover */
}

/* Mobiel menu zichtbaar maken bij klikken */
.menu-icon {
    display: block;
    background-color: #004494; /* Achtergrond voor het menu-icoon */
    color: white;
    text-align: center;
    padding: 10px;
    font-size: 20px;
}

@media (min-width: 769px) { /* Verbetering voor desktop */
    .menu-icon {
        display: none;
    }
    .dropdown-content {
        display: block; /* Toont het menu op desktop */
        position: static; /* Laat het menu niet absolute positioneren */
    }
}

       /* Mobiele weergave: zorg voor consistente lettergrootte */
@media (max-width: 768px) {
  h1 {
    font-size: 24px;
  }
  h2 {
    font-size: 22px;
  }
  h3 {
    font-size: 20px;
  }
  }
    </style>
</head>
<body>

    <header>
        <!-- Menu voor desktop en mobiel -->
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

        <div class="image-container">
        <img src="Groepsfoto.jpeg" alt="Vlek15 kleding afbeelding">
    </div>

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
