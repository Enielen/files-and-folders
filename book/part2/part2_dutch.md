# Deel 2 - Bestandsnaamconventies opstellen

## 2a. Relevantie:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Waarom naamgevingsregels gebruiken voor bestanden en mappen?
  </div>
</center>
<br>

Een consistente bestandsnaamgeving kan je helpen om alle informatie van je projecten duidelijk te organiseren.

Aan het begin van een project is het handig om een FNC (File Naming Convention) of “schema voor bestandsnaamgeving” te bepalen voor elk type informatie dat je gaat verzamelen, creëren of opslaan om mee te werken. Een FNC is het patroon dat je bepaalt en volgt voor het benoemen van de bestanden die bij een project horen. Zonder een FNC zou je kunnen eindigen met een mysterieuze lijst van bestandsnamen die er ongeveer zo uitziet:

<center>
<img src="../figures/2Aa_documents_cartoon.png" alt="Documents Cartoon" style="width: 200px; height: auto;"/>
<p style="font-size: x-small;"><em>"Documents" by xkcd is licensed under CC-BY-NC.</em></p>
</center>

Conventies voor bestandsnamen helpen je om georganiseerd te blijven zodat je je bestanden snel kunt identificeren. In een samenwerkingsomgeving waarin bestanden moeten worden gedeeld, helpt een duidelijke FNC anderen om makkelijker door je werk te navigeren.

<div style="border: 2px solid orange; padding: 10px; background-color: #fff3cd; border-radius: 5px; display: flex; align-items: center; margin: 10px 0;">
  <span style="font-size: 24px; color: orange; margin-right: 10px;">⚠️</span>
  <span style="margin-left: 5px;">Het is <b>noodzakelijk</b> om een conventie op te stellen <b>voordat</b> je begint met het maken van bestanden of het verzamelen van gegevens en om deze conventie tijdens het onderzoek zo nodig aan te passen en eventuele wijzigingen te documenteren. Het hebben van een duidelijke FNC aan het begin van een project voorkomt een achterstand van ongeorganiseerde inhoud.</span>
</div>

In deze module geven we algemene aanbevelingen voor het benoemen van bestanden die van toepassing zijn op alle academische disciplines. Let op: <b>er is niet één juiste manier om je bestanden een naam te geven</b>. Wees je er ook van bewust dat verschillende studierichtingen hun eigen specifieke conventies kunnen hebben voor het benoemen van verschillende type bestanden. Biologen houden zich bijvoorbeeld aan gestandaardiseerde afkortingen van 4 letters voor soortnamen.

## 2b. Vuistregels voor bestandsnamen:

<center>
  <div style="padding: 10px; background-color: #00BBC8; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000; position: relative;">
    <span style="background-color: white; color: #00BBC8; border-radius: 50%; padding: 5px 10px; font-size: 15px; font-weight: bold; margin-right: 8px; display: inline-block;">?</span>
    Hoe ontwikkel ik een FNC (bestandsnaamconventie) voor mijn bestanden?  </div>
</center>

<br>

Lees de basisvuistregels om meer te leren over aanbevolen bestandsnamen. Daarna wordt je gevraagd om een aantal voorbeelden te analyseren.

### #1 Wees consistent

- Kies aan het begin van een project een naamgevingspatroon voor alle bestanden van hetzelfde type. Houd je er dan aan!

### #2 Wees beschrijvend
- Een FNC moet elementen of attributen bevatten die het bestand het beste beschrijven. Welke trefwoorden zouden jij en medewerkers bijvoorbeeld gebruiken om naar het bestand te zoeken? Welke elementen maken het bestand herkenbaar en verschillend van andere bestanden? Omdat elk project anders is, zullen <b>niet voor elk project dezelfde naamgevingsregels gelden</b>. Wanneer je een FNC ontwikkelt, moet je bestandsbeschrijvingen kiezen die het meest relevant zijn voor de specifieke bestanden en/of het project. Hier zijn een paar voorbeelden van bestandsbeschrijvingen:
    - Titel project
    - Omstandigheden (gebruikt labinstrument, opstelling, getest specimen, temperatuur, variabele die gemeten werd, enz.)
    - Type of doel van het document (bijv. gegevens, voortgangsrapport, vragenlijst of interview).
    - Bij samenwerking, de initialen van de persoon die de test heeft uitgevoerd.
- “Final” is <b>NIET</b> een beschrijvende naam.
- Gebruik afkortingen die niet vaak gebruikt worden door anderen en documenteer deze afkortingen.

<b>Gegevens beschrijven in een reeks</b>

- Als je met gegevens in een reeks werkt, moeten de bestandsnamen aangeven wat elk apart stuk gegevens uniek maakt of moeten ze aangeven waar elk stuk gegevens binnen de verzamelreeks valt. 
Anders kan het moeilijk zijn om je onderzoeksproces te herleiden.

Bijvoorbeeld:
- Run van het experiment (ook wel stijgnummer, proefnummer of opname-ID genoemd). Voeg “voorloopnullen” toe zodat alle bestandsnamen in een serie even lang zijn. Dit maakt het makkelijker om sequentieel naar de gegevens te zoeken. Een voorbeeld:
    - In een experiment met 500 proeven worden de gegevens als volgt genummerd:
    001<br>
    015<br>
    066<br>
    488
    - In een experiment met 2000 proeven worden de gegevens als volgt genummerd:
    0001<br>
    0015<br>
    0066<br>
    0488<br>
    1356

- De datum waarop het bestand is gemaakt of de datum waarop de gegevens zijn verzameld. Het algemeen aanbevolen formaat voor data is: <b>JJJJMMDD</b>.

<b>Controleer of je het begrijpt:</b>
Laten we even pauzeren om deze eerste twee vuistregels te verwerken met twee scenario's.
<div style="height: 2px; background-color: blue;"></div>
<b>Oefening A:</b><br>
Een team onderzoekers is bezig met een vergelijkende studie getiteld “Project Vis”. Het gaat om waarnemingen van vissen in Nederland op verschillende locaties en tijdstippen. Ze stellen deze FNC op voor de datasets die ze in het veld verzamelen:

<b>[Projectnaam]_[locatie van gegevensverzameling]_[datum verzameld]_[initialen van de onderzoeker].bestandstype</b>

<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292355873998431047/embed" aria-label="Practice_A" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>
<div style="height: 2px; background-color: blue;"></div>
<br>
<b>Oefening B:</b><br>
Oefen met het toepassen van de eerste twee vuistregels voor bestandsnamen op een onderzoeksscenario.
<div class="responsive-iframe">
  <iframe src="https://tudelft.h5p.com/content/1292336852411897787/embed" aria-label="Practice_B"  allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

### #3 Houd bestandsnamen kort

- Probeer namen te beperken tot 32 tekens of minder. Korte namen zijn sneller te scannen om te weten te komen wat het bestand inhoud. Een visueel voorbeeld:
<center>
<div style="border: 2px solid #4CAF50; padding: 10px; background-color: #ccff99; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000;">
  32CharactersLooksExactlyLikeThis.ext
</div></center><br>

- Probeer bestandsnamen zoveel mogelijk in te korten door afkortingen of acroniemen te gebruiken (maar zorg ervoor dat andere in jouw vakgebied ze begrijpen).

### #4 Vermijd spaties

- Sommige besturingssystemen en opdrachtregelprogramma's herkennen geen spaties in bestandsnamen. Spaties kunnen problemen veroorzaken bij het overzetten van bestanden tussen systemen.
- Aanrader: gebruik underscores _ of koppeltekens - in plaats van spaties.

### #5 Vermijd “rare” karakters

- <b>Gebruik punten alleen aan het einde van de bestandsnaam</b>, vlak voor de *extensie (*extensie: de laatste 2-3 tekens die het bestandsformaat aangeven).

- Sommige tekens hebben een betekenis binnen een computerprogrammeeromgeving, dus het is beter om ze te vermijden. 

De volgende tekens kunnen verwarrend zijn voor computers:

<center>
<div style="border: 2px solid red; padding: 10px; background-color: #fff; border-radius: 10px; display: inline-block; font-weight: bold; font-size: 16px; color: #000;">
  .&, *%#;()!@$^~'{}[]?<>
</div></center>

### #6 Versiebeheer is belangrijk: Houd de versie van je werk bij

<style>
  td.image-cell {
    width: 30%; /* Sets the image cell to 30% of the table width */
    vertical-align: top; /* Aligns the image to the top */
  }

  td.text-cell {
    width: 70%; /* Sets the text cell to 70% of the table width */
    vertical-align: top; /* Aligns the text to the top */
    padding-left: 50px; /* Optional: Adds some spacing between image and text */
  }

  img {
    width: 100%; /* Ensures the image fills the 30% width of its cell */
    height: auto; /* Maintains the aspect ratio of the image */
    display: block;
  }
</style>

<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/2B_why_versioning_matters.png" alt="Why versioning Matters"/>
      <p style="font-size: x-small;"><em>"Why versioning matters" by TU Delft Library - Education Support is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC BY 4.0</a></em></p>
    </td>
    <td class="text-cell">
      <p>Soms moet je meerdere versies of revisies van hetzelfde bestand bijhouden.<br><br>Zonder een duidelijk systeem voor versiebeheer zou je kunnen vergeten welke versie welke is (zie afbeelding). Dit kan leiden tot ongelukkige fouten. Voor een grote opdracht zou je bijvoorbeeld “Reallyfinal.doc” kunnen inleveren, terwijl je eigenlijk “Finalfinal.doc” had moeten inleveren.</p>
    </td>
  </tr>
</table>

Deze verwarring kan verholpen worden door versie-informatie op te nemen in de bestandsnaam. Dit zal jou en groepsgenoten helpen om de tijdsevolutie van een document te kunnen volgen.

Hier zijn standaardaanbevelingen om de versie aan te geven:
- Gebruik voor significante wijzigingen hele getallen: V1, V2
- Gebruik voor kleine wijzigingen decimalen: V1.1, V1.2

Let op: Opslagsystemen zoals One Drive of versiebeheersystemen zoals GitHub hebben versiebeheer ingebouwd. Als je in deze systemen werkt is het eigenlijk NIET aan te raden om genummerde versies in bestandsnamen te gebruiken.

## 2c. Verwerk de vuistregels voor bestandsnaamgeving: 

Je hebt net de basisvuistregels geleerd voor het ontwikkelen van een FNC. Neem nu een paar minuten de tijd om de basisrichtlijnen voor bestandsnamen toe te passen op deze drie nieuwe scenario's.

<b>FNC Scenario #1:</b>
<div class="responsive-iframe">
<iframe src="https://tudelft.h5p.com/content/1292338726732494147/embed" aria-label="Scenario_1" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<b> FNC Scenario #2:</b>
<div class="responsive-iframe">
<iframe src="https://tudelft.h5p.com/content/1292338765754228157/embed" aria-label="Scenario_2" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

<b>FNC Scenario #3:</b>

<div class="responsive-iframe">
<iframe src="https://tudelft.h5p.com/content/1292339487820332487/embed" aria-label="Scenario_3" allowfullscreen="allowfullscreen" allow="autoplay *; geolocation *; microphone *; camera *; midi *; encrypted-media *"></iframe>
</div>
<script src="https://tudelft.h5p.com/js/h5p-resizer.js" charset="UTF-8"></script>

## 2d. Praktische toepassingen: hoe houd ik bij welke FNC ik heb gekozen?

<table>
  <tr>
    <td class="image-cell">
      <img src="../figures/2D_README_Alice_in_WL.png" alt="Alice in WL" width="200"/>
      <p style="font-size: x-small;"><em>"README Alice in Wonderland" adaped from original image by John Tenniel - John Tenniel, Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=629633">https://commons.wikimedia.org/w/index.php?curid=629633</a></em></p>
    </td>
    <td class="text-cell">
      <p>Om bij te houden welke FNC's ze hebben vastgesteld, maken onderzoekers een stuk documentatie aan dat een “README”-bestand wordt genoemd. Een README is meestal een txt-bestand dat wordt opgeslagen in dezelfde map als de dataset(s). De README.txt fungeert als een korte gids voor je FNC. Het helpt bij het uitleggen en documenteren van het schema dat is gebruikt om die specifieke bestanden een naam te geven. We zijn van plan om een aparte mini-module te ontwikkelen over documentatiestrategieën; deze zal dieper ingaan op stap-voor-stap instructies over het maken van README-bestanden. Wil je in de tussentijd meer leren over README-documentatie? We raden je aan deze link te bezoeken naar <a href="https://datamanagement.hms.harvard.edu/collect-analyze/documentation-metadata/readme-files"> Harvard University’s research data management site</a>  die README sjablonen en gidsen biedt.</p>
    </td>
  </tr>
</table>
