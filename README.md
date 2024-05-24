# Deelopdracht 3: Human Body
*Experimenteel nagaan van positie voor onbeschikbaar scherm tijdens rijden* 

*Projectteam: Luca Poppe; Noah Menschaert*

--/--/--

## Samenvatting
<!---
Max 200 woorden. Beschrijf je project in het kort, waarbij je deze vragen zeker beantwoordt:

- Wat is het probleem?
- Hoe heb je dit onderzocht?
- Wat is jouw oplossing?
- Hoe lost jouw oplossing het probleem op?
- Hero sketch/render/image
-->

### Het probleem
Touchscreenconsoles in auto's zijn gevaarlijk om te gebruiken tijdens het rijden. Er zijn veel handelingen nodig om iets aan te passen en de ogen zijn lang van de baan. 

### De oplossing
In het beste geval is er geen touchscreen aanwezig voor de chauffeur. Uit onze interviews is gebleken dat de passagier een belangrijke co-piloot is. Ook vinden gebruikers een touchscreen zeer handig om te gebruiken en dit kan veilig tijdens wanneer ze stilstaan. Om hier rekening mee te houden maken we een touchscreen dat tijdens het rijden enkel voor de chauffeur beschikbaar is. 
De oplossingen zijn als volgt:
- touchscreeninterface voor de passagier
- touchscreen verschuift naar passagier tijdens het rijden
- touchscreen draait weg van chauffeur
- touchscreen heeft polarisatie zodat het enkel zichtbaar is voor passagier

<p align="center">
  <img src="schets_oplossingen.jpg" width="600" height="auto" />
</p>

> Schets oplossingen met 1: schuivende interface, 2: draaiend scherm, 3: schuivend scherm en 4: gepolariseerd scherm

### Test
Door gebruik te maken van anthropometrische data en een fysieke test wordt nagegaan op welke manier het scherm niet meer beschikbaar is voor de chauffeur en tegelijk makkelijk te gebruiken is voor de passagier. De test wordt uitgevoerd in een auto, waarbij een ipad dient als touchscreen.

## Discovery
### Doelstellingen
De doelstelling van deze proef is om een geschikte methode te vinden die het probleem oplost. Na de test moet duidelijk zijn welk prototype bruikbaar is en hoe die te gebruiken is. Indien geen van de prototypes bruikbaar zijn moeten gerelateerde designrequirements geformuleerd worden en een alternatief voorgesteld.

### Methodologie
#### *Rijkdiepte*
Om het scherm onbruikbaar te maken voor de chauffeur en bruikbaar voor de passagier wordt er rekening gehouden met de reikdiepte wanneer mensen zitten. Voor de bestuurder maken we gebruik van design for the big om zeker te zijn dat het scherm buiten meeste mensen hun bereik ligt. Voor de passagier wordt design for the small gebruikt, zo kunnen passagiers het scherm sowieso gebruiken. Onderstaande tabel toont de data uit DINBelg.

| eenheid mm | P1  | P5  | gem | P95 | P99 | SD  |
|------------|-----|-----|-----|-----|-----|-----|
| reikdiepte | 651 | 685 | 767 | 850 | 884 | 50  |


#### *Draaiing scherm*
Aan de hand van een literatuurstudie wordt gezocht op welke hoeken een scherm gezet kan worden om deze goed/slecht zichtbaar te maken. Volgens een artikel van [TCL USA](https://www.tcl.com/global/en/blog/what-is-the-best-tv-viewing-distance#:~:text=3.,degrees%20from%20left%20to%20right.) is het best om een tv te bekijken op een hoek van maximum 40°. Een [studie van RTINGS](https://www.rtings.com/tv/tests/picture-quality/viewing-angle) toont dat bij 70° problemen als kleur- en gammaverschuiving, kleurverbleking, helderheidverlies en steiging in zwartniveau optreden. Aan de hand van deze bevindingen worden volgende hoeken besturdeerd:
- loodrecht op dashboard
- loodrechts op passagier
- 40° met bestuurder
- 40° met passagier
- 70° met bestuurder
- 90° met bestuurder


#### *Verschuiving*
Voor de schuivende interface wordt positie 0mm (centrum) positie 20mm (voor passagier) en tussenmaat 15 mm bestudeerd. Deze wordt gecombineerd met de draaiing van het scherm.


#### *Analyse schermpositie*
Aan de hand van een tekening wordt de hoek van het scherm ten opzichte van het dashboard berekend voor elke verschuiving en draaiing. Zie onderstaande foto:

<p>
  <img src="schermposities_legende.png" width="25%" height="auto">
  <img src="schermen_finaal 2.png" width="70%" height="auto">
</p>

> linkse foto: legende van analyse schermposities

uit de analyse komen volgende hoeken voor Θ:

| y-waarde | loodrecht op passagier | 40° met chauffeur | 40° met passagier | 70° met chauffeur | 90° met chauffeur |
|:---------|:-----------------------|:------------------|:------------------|:------------------|:------------------|
| centrum  | 24°                    | 10°               | 64°               | 37°               | 55°               |
| 15 cm    | 17°                    | 5.2°              | 53°               | 30°               | 47°               |
| 20 cm    | 0°                     | - 6.4°            | 66°               | 22°               | 43°               |


<br />

#### *uitvoeren test*
Fase 1: passagiersrol

*De testpersoon zit in de passagiersstoel, de interviewer zit in de bestuurdersstoel.*

In deze fase wordt gekeken hoe goed de passagier met het scherm kan werken in de verschillende posities. Alsook welke posities comfortabel zijn.
Voor elke y-waarde doet de passagier een opdracht om het bereik tot het scherm te testen. Voor elke hoek waar het scherm op gezet wordt, evalueert de passagier de zichtbaarheid van het scherm.

Opdrachten in deze fase:
- apps openen
- route ingeven in navigatie-app

Fase 2: Chauffeursrol

*De testpersoon gaat nu in de bestuurdersstoel zitten en de interviewer in de passagiersstoel.* 

In deze fase wordt gekeken wanneer het scherm (niet) leesbaar is en hoe groot de drempel is om het scherm te lezen.
Voor elke y-waarde en corresponderende hoeken:
- Chauffeur probeert scherm te lezen vanuit rustpositie.
- Hoe ver moet de chauffeur het hoofd bewegen om het scherm te lezen?  
 *De afstand van hoofd tot rustpositie wordt gemeten.*
- Vanaf welke exacte hoek kan de chauffeur in rustpositie het scherm lezen?
*De exacte hoek wordt gemeten.*


Te lezen beelden in deze fase (gesorteerd op moeilijkheid):
- Foto met grote pijlen
- Titel krantenartikel
- Namen liedjes in spotify playlist
- Wikipedia Artikel


#### *setup test*
Om de test uit te voeren werd een cabrio gebruikt. Een camera filmt het topview van de auto, een andere filmt het dashboard. 

<p >
  <img src="testsetup.png" width="600" height="auto">
</p>

> setup camera's

### Resultaten
#### *analyse rijkdiepte*

Onderstaande foto's schetsen voor elke verschuiving de rijkdiepte van pasasgier bij design fot the small en van chauffeur bij design for the big.

<p>
  <img src="rijkdiepteanalyse_0.png" width="auto" height="130">
  <img src="rijkdiepteanalyse_15.png" width="auto" height="130">
  <img src="rijkdiepteanalyse_20.png" width="auto%" height="130">
</p>

> y-waarde: (links: 0), (middelste: 15), (rechts: 20)


Het is duidelijk dat het touchscreen pas onbereikbaar is zonder te bewegen als het recht voor passagier staat (y = 20).
Bij y = 15 is het scherm net niet buiten het bereik, maar niet heel het scherm is bereikbaar zonder te verplaatsen.

#### *analyse test passagier*
Onderstaande tabel toont opmerkingen van de gebruikers per positie van het scherm. 

|         | loodrecht op passagier | 40° met chauffeur | 40° met passagier   | 70° met chauffeur | 90° met chauffeur |
|---------|------------------------|-------------------|---------------------|-------------------|-------------------|
| centrum | ok                     | ok                | onhandig            | onhandig          | onhandig          | 
| 15      | ok                     | ok                | onhandig, in de weg | onhandig          | onhandig          |
| 20      | ok                     | -                 | onhandig            | onhandig, vreemd  | onhandig          |

algemene opmerkingen: Onaangenaam als scherm verder weggedraaid is dan recht naar de passagier toe.

#### *analyse test chauffeur* 


## Introductie
Max 300 woorden.
Kader je project. Introduceer het probleem en jouw doelstellingen (inclusief boundary conditions).
Maak gebruik van bronverwijzingen ([zie APA stijl](https://www.scribbr.nl/category/apa-stijl/)).

## Methodologie
Max 400 woorden. Beschrijf je methodologie (enkel SEM1, zie les methodologie). Maak hierbij gebruik van een afbeelding om je tijdlijn weer te geven. Op deze tijdlijn moeten minimaal een tijdsincatie te zien zijn, moeten fasen te zien zijn en moeten activiteiten te zien zijn.

## Discovery
Max. 1000 woorden
### Doestellingen
Wat wilde je bereiken?
### Materiaal & methoden
Hoe onderzocht je dit? Wees volledig.
### Resultaten
Rapporteer over de resultaten (incl. foto's, quotes, analyseframeworks, ...)
### Conclusies & implicaties
Definieer de belangrijkste designbeslissingen

## Kritische reflectie
Max. 500 woorden

## Bronnen
Voeg je volledige bibliografie toe van bronnen naarwaar je verwees.

## Bijlagen
