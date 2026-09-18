# Dolle Mina's - Team Squad Page
Ontwikkeld door Sophie, Sun en Ahmet.

# Inhoudsopgave
<a href="#beschrijving">Beschrijving</a>
</br><a href="#gebruik">Gebruik</a>
</br><a href="#kenmerken">Kenmerken</a>
</br><a href="#bronnen">Bronnen</a>

# Beschrijving
Voor de Klas K van het eerste jaar in de opleiding Frontend Design & Development moet er een archiefpagina worden ontwikkeld, waar alle ontwikkelde visitekaartjes worden weergeven. Verder moet de Amstelcampus en de bijbehorende faciliteiten ook uitgelicht worden. Dit is een team opdracht die via GitHub uitgevoerd en geplaatst dient te worden.

Link naar site: https://edu.nl/3cpeq

# Gebruik
Op de omgeving kan de gebruiker wegens scrollen de volledige content bekijken, hierbij zijn geen klikken vereist. Bij de visitekaartjes kan de bezoeker over de kaarten hoveren en klikken om een voorvertoning te krijgen van de ontwikkelde kaarten van de desbetreffende persoon, waarbij deze via de knop eronder bereikbaar zijn.

De gehele sectie waarin de visitekaartjes zich bevinden is horizontaal te scrollen, door simpelweg binnen de sectie naar beneden te scrollen zonder onverwachte handelingen. Het verlaten van deze sectie gebeurt automatisch zodra de lengte van de sectie ten einde is gekomen.

De Amstelcampusbevat een simpelere interactie, waarbij een klik voldoende is om te navigeren naar de bijbehorende HvA pagina.

# Kenmerken
De website is gebouwd met uitsluitend HTML en CSS.

**Head**
</br>In de head staan een aantal Google Fonts imports voor de font families 'Carter One' en 'Inter'. Zie de regels hieronder:
https://github.com/SophieeDiepenmaat/your-tribe-squad-page/blob/7f92bf40dbc42c085596e6428cd52efd50db870d/index.html#L6-L8

De verwijzing naar het algemene stijling bestand staat er direct onder binnen de head:
https://github.com/SophieeDiepenmaat/your-tribe-squad-page/blob/7f92bf40dbc42c085596e6428cd52efd50db870d/index.html#L9

**Body**
</br>De structuur van de body is MAIN en FOOTER, er is namelijk geen header navigatie ontwikkeld voor de website.

**Main**
De main bevat vier secties en een svg element. De svg heeft uitsluitend een decoratief doeleinde, en staat tussen de hero banner en de sectie van de visitekaartjes.

De eerste sectie bevat een grid container waarin alle elementen zijn geordend via grid-areas. De foto's zijn hiermee ten alle tijden gemakkelijk te vervangen en verplaatsen door de namen of bronnen te wijzigen, zonder dat er met specifieke child volgorde rekening gehouden hoeft te worden.
https://github.com/SophieeDiepenmaat/your-tribe-squad-page/blob/7f92bf40dbc42c085596e6428cd52efd50db870d/index.html#L14-L59

De tweede sectie weergeeft alle visitekaartjes die getoond worden via een horizontale scroll. Hiervoor hoeft de gebruiker geen Apple Magic Mouse te hebben, of via een scrollbalk te slepen, maar kan de bezoeker simpelweg naar beneden blijven scrollen. Dit is gerealiseerd door de sectie via de CSS property 'rotate' op z'n zij te draaien en de elementen hierbinnen visueel te corrigeren, zodat de scroll ervaring simpel en toegankelijk blijft.

Zie hieronder de toegepaste CSS:
https://github.com/SophieeDiepenmaat/your-tribe-squad-page/blob/28a4a30bb14e4d4e5ef42e57d185ca96e3422c0b/styles/style.css#L132-L160

De visitekaartjes bevatten verder een simpele hover animatie waarbij een kleine preview wordt vrijgegeven die de mugshot van de personen vervangt. Vervolgens kan je op de knop onder de personen direct navigeren naar de achterliggende visitekaartjes, die geopend worden in een nieuw tabblad. Zo behouden we gebruikers op de website, zonder ze definitief weg te sturen. Zie hieronder de toegepaste HTML en CSS.
https://github.com/SophieeDiepenmaat/your-tribe-squad-page/blob/5c0ebaa503754f478ff4b677fb150c2ceb26d62e/index.html#L74-L81
https://github.com/SophieeDiepenmaat/your-tribe-squad-page/blob/5c0ebaa503754f478ff4b677fb150c2ceb26d62e/styles/style.css#L175-L207

De derde sectie bevat de Amstelcampus die weergeven wordt via een masonry grid systeem. Via de kaarten krijgt de gebruiker een korte preview per locatie en de bijbehorende faciliteiten, waarbij deze ook gelijk kan navigeren naar de desbetreffende locatie wegens de knop met een pijl die in de kaarten staan. Op de kaarten staan ook hover states om extra te benadrukken dat er interactie mogelijkheden zijn, zodat deze gestimuleerd worden om te ondernemen.

# Bronnen
https://fonts.google.com/specimen/Carter+One
</br>https://fonts.google.com/specimen/Inter
</br>https://css-tricks.com/almanac/properties/g/grid-area/
</br>https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Values/transform-function/rotate
</br>https://css-tricks.com/pure-css-horizontal-scrolling/
