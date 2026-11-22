# Digital garden van Tolga

## Eigen verkenning

### Wat ik wil maken

Mijn digital garden gaat over mijn groei als ontwerper en als persoon. Je ziet niet alleen wat ik maakte, maar vooral wat ik per periode leerde, waar ik vastliep en hoe ik veranderde. Net als een tuin is hij nooit af. Ik zou hem na dit blok graag blijven bijhouden.

### Wat ik zag en nog niet kan

Bruno Simon heeft van zijn portfolio een game gemaakt waarin je met een auto langs zijn projecten rijdt. Dat kan ik nog niet, maar het spreekt me aan omdat ik veel game. Bij Maggie Appleton heeft elke tekst een groeifase. Dat vind ik een mooi idee voor een digital garden, omdat je dan ziet wat nog groeit.

### Webby dingen die ik zag

Bij Ste Grainer en Mike Mai kan je zelf licht, donker of automatisch kiezen. Dat heb ik vandaag in het practicum geoefend, dus dat is een idee voor mijn eigen garden. Lynn Fisher bewaart oude versies van haar site en Basher heeft een grote eerste letter. Dat vond ik ook interessant.

### Mijn eigen content

Per periode wil ik laten zien wat ik leerde bijvoorbeeld met een schets naast wat het werd of met iets wat eerst mislukte. Bij Maggie Appleton zag ik dat elke tekst een groeifase heeft, zoals zaadje, kiemplant en boom. Dat vind ik een mooie manier om te laten zien wat nog groeit.

### Content van anderen

Mijn garden gaat over mijn eigen werk, dus het meeste is van mij. Laat ik iets van een ander zien, zoals een screenshot van een site, dan hoort daar een bron bij en mijn eigen tekst over wat ik eruit haal.

### Hoe je het kan ervaren

Mijn idee is dat je als in een game langs de periodes loopt van level naar level. Het laatste level zit op slot, omdat ik nog groei. Zelf licht of donker kiezen is ook een idee, omdat ik dat al geoefend heb. In mijn 50 afbeeldingen zag ik veel donkere achtergronden met roze, paars en groen. Dat werden mijn kleuren.

## Learning Log

### 20 nov - Werkgroep 3

Bij opdracht 12 heb ik gekeken hoe ik mijn schetsen ga bouwen. Ik ga uit van schets 5. In de header staat mijn naam als h1, de zin Mijn groei als ontwerper en als persoon als p en een keuze voor licht en donker zoals in het practicum van Vasilis. In de main staan mijn periodes op volgorde als levels. Elk level heeft een kopje, een beeld en een korte tekst over wat ik in die periode leerde. Het laatste level zit op slot en heeft geen link. In de footer staan mijn links naar GitHub en mijn mail. In de CSS komen mijn kleuren als custom properties met light-dark() en mijn lettertype met @font-face.

Deze vragen heb ik nog. Hoe maak ik het kronkelende pad tussen de levels in CSS? Zijn mijn levels een lijst of losse articles? Laat ik de schets zien bij hover of bij een klik? Die heb ik nog niet aan een docent gesteld.

Als laatste iteratie bouw ik eerst een recht pad van boven naar beneden, zoals de tijdlijn in schets 1. Het kronkelende pad probeer ik later als het rechte pad werkt.

Bij opdracht 13 heb ik net als in het voorbeeld op DLO naar schets 5 gekeken en bij alles gevraagd wat het is. Bovenaan staat mijn naam. Dat is het belangrijkste kopje, dus de h1. De zin eronder is geen kopje maar uitleg dus een p. De levels op het pad staan op volgorde van jaar 1 tot nu en die volgorde is belangrijk. Daarom is het een geordende lijst, een ol met een li per level en geen losse articles. Elk level heeft een h2, een img en een p. Het slotje is de laatste li. Onderaan staan twee links dat is een ul in de footer. De knop voor licht en donker is een keuze, net als de keuzeknoppen in het practicum van Vasilis.

Bij opdracht 14 heb ik verder gewerkt aan de mobiele versie van mijn garden. In de HTML heb ik van mijn levels een ol gemaakt en per level mijn eigen tekst gezet over wat ik in die periode leerde. Die teksten komen uit mijn productbiografieën en design rationales van vorige blokken. Daarna ben ik begonnen met mijn CSS in normal.css. Mijn kleuren uit mijn mini style guide staan als custom properties met light-dark() in de html selector. De pagina is één kolom van maximaal 30em in het midden van het scherm. Mijn naam en de kopjes staan in Bungee en de tekst in Rubik met @font-face. Ik koos Rubik omdat het ook vierkante vormen heeft maar met ronde hoeken. Het past bij Bungee en is rustiger om te lezen. De links in de nav en de footer staan naast elkaar en langs mijn levels loopt een paarse lijn als recht pad.

![Mijn garden in één kolom op een smal scherm](readme-images/20nov-one-column-mobiel.png)

![Mijn garden in één kolom op een breed scherm](readme-images/20nov-one-column-breed.png)

Twee keer verdwenen er regels uit mijn CSS, omdat ik bij het vervangen van mijn body blok meer selecteerde dan alleen dat blok. Eerst de reset en daarna de kleuren van mijn links. Daardoor waren mijn links paars van de browser in plaats van blauw. Ik heb ze wel weer terug.

In het voortgangsgesprek zei Sanne dat mijn garden op een portfolio leek. Hij zag in mijn HTML mijn projecten per blok met een plaatje en een tekst. Ik heb gezegd dat andere docenten mijn onderwerp goed vonden. Opnieuw beginnen wilde ik niet, omdat mijn onderzoek, schetsen en kleuren al bij mijn onderwerp passen. Daarom heb ik mijn idee aangepast. Mijn garden gaat over mijn groei als ontwerper en als persoon. Per periode laat ik zien wat ik leerde en waar ik vastliep en niet alleen wat ik maakte. Mijn eigen verkenning bovenaan mijn README heb ik daarop aangepast.

Diederik was positief over mijn onderzoek. Hij vond dat mijn keuzes een goede reden hebben en niet uit de lucht komen. Over mijn schetsen was hij ook positief en hij dacht tijdens het gesprek met me mee.

Welke feedback heb je gehad? Sanne vond dat mijn garden op een portfolio leek. Daarom gaat hij nu over wat ik per periode leerde. Diederik was positief over mijn onderzoek en mijn schetsen.

Bronnen zijn de opdrachten van werkgroep 3 op DLO, de intro CSS grid van Sanne op DLO, mijn eigen productbiografieën en design rationales en Bungee en Rubik van Google Fonts.

## Grid oefening 1

### Wat ik heb gedaan

Ik heb de pen "code voor jou" geforkt en in style.css de elf sommetjes één voor één gemaakt. Na elk sommetje heb ik gecheckt of de preview klopte, opgeslagen en een screenshot gemaakt van de code en de preview naast elkaar. De algemene styling van de articles heb ik niet aangepast.

### Wat ik heb geleerd

Met `display: grid` op `main` maak je van de pagina een grid. De articles worden dan automatisch de vakjes.
Met `grid-template-columns: 1fr 1fr 1fr` maak je drie even brede kolommen. `fr` betekent een deel van de ruimte die over is.
Met `gap` zet je ruimte tussen de vakjes, zonder margin te gebruiken.
Met `grid-column-start` bepaal je in welke kolom een article begint.
Met selectoren als `:first-child`, `:nth-of-type(2n)` en `:nth-of-type(2n + 1)` kan je meerdere articles tegelijk aansturen, zonder elk article een eigen class te geven.

### Screenshots

**Sommetje 1**
![Grid oefening 1, sommetje 1](readme-images/grid/grid-oefening-1-sommetje-01.png)

**Sommetje 2**
![Grid oefening 1, sommetje 2](readme-images/grid/grid-oefening-1-sommetje-02.png)

**Sommetje 3**
![Grid oefening 1, sommetje 3](readme-images/grid/grid-oefening-1-sommetje-03.png)

**Sommetje 4**
![Grid oefening 1, sommetje 4](readme-images/grid/grid-oefening-1-sommetje-04.png)

**Sommetje 5**
![Grid oefening 1, sommetje 5](readme-images/grid/grid-oefening-1-sommetje-05.png)

**Sommetje 6**
![Grid oefening 1, sommetje 6](readme-images/grid/grid-oefening-1-sommetje-06.png)

**Sommetje 7**
![Grid oefening 1, sommetje 7](readme-images/grid/grid-oefening-1-sommetje-07.png)

**Sommetje 8**
![Grid oefening 1, sommetje 8](readme-images/grid/grid-oefening-1-sommetje-08.png)

**Sommetje 9**
![Grid oefening 1, sommetje 9](readme-images/grid/grid-oefening-1-sommetje-09.png)

**Sommetje 10**
![Grid oefening 1, sommetje 10](readme-images/grid/grid-oefening-1-sommetje-10.png)

**Sommetje 11**
![Grid oefening 1, sommetje 11](readme-images/grid/grid-oefening-1-sommetje-11.png)

### 18 nov - Practicum kleuren en gradients

Ik heb het practicum mooie kleuren en gradients van Sanne gedaan in CodePen. Bij oefening 1 heb ik twaalf blokjes nagemaakt met de zes soorten gradients, linear, radial, conic en de repeating versies, met de kleuren als custom properties in :root. Ik heb ook background-size, background-position en background-repeat gebruikt, en twee gradients over elkaar met een komma ertussen. Bij oefening 2 heb ik acht vlaggen gemaakt met harde lijnen in gradients, zoals Japan met een radial-gradient en Tsjechië met een conic-gradient. Bij oefening 3 heb ik gradients geanimeerd met @property, met hover, transition en keyframes.

Oefening 1, de zes gradients

![Start van oefening 1 met lege blokjes](readme-images/gradients/gradients-oefening-1-start.png)

![Blokje 1 tot en met 4, deel 1](readme-images/gradients/gradients-oefening-1-blokjes-01-tot-04-deel-1.png)

![Blokje 1 tot en met 4, deel 2](readme-images/gradients/gradients-oefening-1-blokjes-01-tot-04-deel-2.png)

![Blokje 5 tot en met 8, deel 1](readme-images/gradients/gradients-oefening-1-blokjes-05-tot-08-deel-1.png)

![Blokje 5 tot en met 8, deel 2](readme-images/gradients/gradients-oefening-1-blokjes-05-tot-08-deel-2.png)

![Blokje 9 tot en met 12, deel 1](readme-images/gradients/gradients-oefening-1-blokjes-09-tot-12-deel-1.png)

![Blokje 9 tot en met 12, deel 2](readme-images/gradients/gradients-oefening-1-blokjes-09-tot-12-deel-2.png)

![Blokje 9 tot en met 12, deel 3](readme-images/gradients/gradients-oefening-1-blokjes-09-tot-12-deel-3.png)

![Alle twaalf blokjes klaar](readme-images/gradients/gradients-oefening-1-alle-twaalf-blokjes.png)

Oefening 2, vlaggen

![Start van oefening 2](readme-images/gradients/gradients-oefening-2-start.png)

![Vlaggen met strepen, deel 1](readme-images/gradients/gradients-oefening-2-strepen-deel-1.png)

![Vlaggen met strepen, deel 2](readme-images/gradients/gradients-oefening-2-strepen-deel-2.png)

![Zweden met twee gradients](readme-images/gradients/gradients-oefening-2-zweden-twee-gradients.png)

![Vlag met schuine strepen met repeating-linear-gradient](readme-images/gradients/gradients-oefening-2-anker-repeating.png)

![Japan met radial-gradient en Tsjechië met conic-gradient](readme-images/gradients/gradients-oefening-2-japan-radial-tsjechie-conic.png)

![Alle acht vlaggen klaar](readme-images/gradients/gradients-oefening-2-alle-acht-vlaggen.png)

Oefening 3, animeren met @property

![Start van oefening 3](readme-images/gradients/gradients-oefening-3-start.png)

![Move it met hover](readme-images/gradients/gradients-oefening-3-move-it-hover.png)

![Een rondje tijdens de transition](readme-images/gradients/gradients-oefening-3-een-rondje-tijdens-transition.png)

![Animate it met keyframes](readme-images/gradients/gradients-oefening-3-animate-it-keyframes.png)

![Het centerpunt beweegt](readme-images/gradients/gradients-oefening-3-centerpunt-beweegt.png)

![De starthoek draait](readme-images/gradients/gradients-oefening-3-starthoek-draait.png)

![Moeilijk met eigen ringen](readme-images/gradients/gradients-oefening-3-moeilijk-eigen-ringen.png)

![Alle zes blokjes klaar](readme-images/gradients/gradients-oefening-3-alle-zes-blokjes.png)

Bronnen zijn de randvoorwaarden schetsen, de Deep Dive schetsen en de opdracht mini styleguide op DLO, [Adobe Color](https://color.adobe.com/create/color-wheel), [Adobe Fonts](https://fonts.adobe.com) en [Google Fonts](https://fonts.google.com), het practicum mooie kleuren en gradients van Sanne op DLO, de intro CSS kleuren en de intro CSS gradients van Sanne en de oefeningen van Sanne op [CodePen](https://codepen.io).

### 18 nov - Zelfstudie schetsen

Voor vrijdag heb ik vijf mobile first schetsen gemaakt van de voorpagina van mijn garden. Ik heb ideeën uit mijn Crazy 8 gebruikt. Schets 1 is mijn naam in losse letters met een tijdlijn. Schets 2 is een rank met mijn projecten eraan. Schets 3 is een game level met een slotje voor wat nog komt. Schets 4 laat de schets achter een project zien als je erop tikt. Schets 5 combineert de losse letters, het game pad en de verstopte schets met een knop voor licht en donker en een footer met links. Bij schets 3, 4 en 5 heb ik ook getekend wat er gebeurt als je tikt.

![Schets 1 met losse letters en tijdlijn en schets 2 met de rank](oefeningen/schetsen/schetsen-mobile-1-en-2.jpg)

![Schets 3 met het game level en schets 4 met de verstopte schets](oefeningen/schetsen/schetsen-mobile-3-en-4.jpg)

![Schets 5 die alles combineert](oefeningen/schetsen/schets-mobile-5.jpg)

Daarna heb ik voor de mini style guide een kleurpalet gemaakt voor donker en voor licht. De kleuren komen uit mijn onderzoek, felle kleuren zoals roze, blauw en paars op een donkere achtergrond. In donker is de achtergrond #15111F en de tekst #F3EFFA. Blauw #5B7CFF is voor links en knoppen, roze #FF5FA8 voor hover en paars #A77BFF voor de tijdlijn en de rank. In licht is de achtergrond #F7F4FB en de tekst #1E1A2B, met donkerdere accenten, blauw #2F45C8, roze #C2185B en paars #6B3FB8. Alle kleuren hebben minstens 4.5 : 1 contrast met de achtergrond, dus ze zijn goed te lezen.

![Mijn donkere kleurpalet in Adobe Color](readme-images/kleurpalet-donker.png)

![Mijn lichte kleurpalet in Adobe Color](readme-images/kleurpalet-licht.png)

Daarna heb ik naar lettertypes gekeken. Ik heb de Seftel poster in Adobe Fonts geüpload. Adobe zag er een geometrisch, zwaar schreefloos lettertype in. Die lettertypes zitten alleen in Adobe en mag ik niet zomaar op mijn site zetten. Net als bij de kleuren ben ik begonnen met voorstellen en die heb ik op Google Fonts vergeleken, want die mag ik gratis als bestand gebruiken zoals in mijn practicum.

![Adobe Fonts analyse van de Seftel poster](readme-images/lettertype-adobe-seftel.png)

Ik heb een lettertype nodig voor mijn naam en kopjes en een voor gewone tekst. De kop mag opvallen en speels zijn. Gewone tekst moet op een telefoon goed leesbaar zijn bij 16px.

Voor de kop heb ik Unbounded, Bungee en Space Grotesk geprobeerd met TOLGA. Unbounded heeft brede ronde zware letters, net als de grote letters op Seftel. Bungee lijkt op letters uit arcade games, dat past bij mijn game level. Space Grotesk is ook geometrisch maar rustiger, als de andere twee te druk worden.

![Unbounded met mijn naam](readme-images/lettertype-unbounded.png)

![Bungee met mijn naam](readme-images/lettertype-bungee.png)

![Space Grotesk met mijn naam](readme-images/lettertype-space-grotesk.png)

Voor gewone tekst heb ik DM Sans en Rubik geprobeerd met de zin Mijn groei als ontwerper en als persoon. DM Sans heeft dezelfde geometrische vormen als de koppen maar is open en goed te lezen. Rubik heeft licht ronde hoeken, daardoor voelt het vriendelijk en blijft het leesbaar.

![DM Sans met een zin](readme-images/lettertype-dm-sans.png)

![Rubik met een zin](readme-images/lettertype-rubik.png)

Ik heb nog geen keuze gemaakt.

Daarna ben ik begonnen met de HTML structuur van mijn garden in [index.html](index.html). Ik ben uitgegaan van schets 5. In de header staat mijn naam als h1 met de zin Mijn groei als ontwerper en als persoon eronder en een nav met een link naar mijn learning log. In de main staat elk project als article met een h2, een collage uit mijn presentatie en een korte tekst. Ze staan op volgorde van jaar 1 tot nu en het laatste article is Binnenkort het level dat nog op slot is. In de footer staan links naar mijn GitHub en mijn mail.

### 18 nov - Werkgroep 2

Vandaag heb ik mijn HTML presentatie in een tweetal gepresenteerd. Daarna heeft mijn medestudent mij de vragen van DLO gesteld.

Wat is voor jou de essentie van je onderwerp en content? Mijn digital garden is een plek waar ik mijn werk als ontwerper verzamel en waar je kan zien hoe ik groei. Nu is het vooral schoolwerk. Later kan ik het laten zien aan een stagebedrijf of werkgever.

Heeft de ander een aanvulling op je onderwerp? Ik vroeg of het een goed onderwerp is. Mijn medestudent vond het goed en nuttig, omdat ik dan al mijn werk op een rijtje heb. Welk karakter of gevoel past bij je onderwerp? Het karakter ben ik zelf, een student met al wat ervaring die nog groeit. Het gevoel moet inspirerend zijn, zodat mensen zin krijgen om zelf iets te maken.

Welke woorden uit de kwaliteitenlijst passen bij je onderwerp? Expressief en leuk of verrassend.

Welke inspiratie haal je uit je afbeeldingen? Groeiend en speels. Groeiend zie ik in mijn eigen schetsen die later een prototype worden. Speels zie ik in sites als Bruno Simon en tamaNOTchi, die voelen als een game.

Wat wil je een ander vertellen over je onderwerp? Ik wil laten zien hoe ik werk, van eerste schets tot eindresultaat. Zo zie je wat ik kan en raak je misschien zelf geïnspireerd.

Ik wil mijn digital garden laten gaan over mijn werk als ontwerper en wil dat laten zien door schetsen, prototypes en eindresultaten van mijn projecten aan content te tonen. Ik begin met een stukje eigen content over mijn eerste project uit jaar 1, de app en het 3D stadion. Dan begint mijn garden bij het begin. Als het begin is gemaakt kan ik mijn garden verder uitbreiden door elk blok een nieuw project toe te voegen.

Daarna heb ik de visual research gedaan in Miro. Mijn onderwerp is mijn groei als ontwerper en als persoon. Mijn sfeerwoorden zijn speels, nieuwsgierig en groeiend. Hier is [mijn Miro bord](https://miro.com/app/board/uXjVEPuW9bg=/?moveToWidget=3458764690739779210&cot=14).

![Mijn onderwerp en sfeerwoorden in Miro](readme-images/vr-miro-sfeerwoord.jpg)

![Stap 1 met mijn beelden en steekwoorden](readme-images/vr-miro-stap-1.jpg)

![Stap 2 met mijn posters van typographicposters.com](readme-images/vr-miro-stap-2.jpg)

![Stap 3 met mijn vier posters en uitgangspunten](readme-images/vr-miro-stap-3.jpg)

![Mijn Crazy 8 in Miro](readme-images/vr-miro-crazy-8.jpg)

Wat zijn de beste ideeën en waarom? En waarom de andere minder?

Het sterkst zijn de losse letters, de rank, de groeiende tijdlijn, de verstopte schets en het game level. De letters zijn mijn naam en voelen speels. De rank en de tijdlijn laten mijn groei zien. De verstopte schets maakt nieuwsgierig. Het game level past bij gaming en het slotje laat zien dat mijn garden nog niet af is. De gloeiende cirkel zegt niks over mijn werk. Het plantje is te letterlijk. De draaiende kaart lijkt te veel op de verstopte schets.

Zijn je uitgangspunten terug te zien in de schetsen?

Ja. De letters komen uit Seftel, de rank uit Designers for Glaser en de tijdlijn uit Rhizom.

Is het idee online te vertalen?

Ja. De tijdlijn en de rank lopen van boven naar beneden, dat past op mobiel. Mijn naam wordt de kop bovenaan, op een donkere achtergrond met roze, blauw en paars.

Is het idee expressief? Zit er genoeg uitdaging in?

Ja. De letters kunnen draaien met rotate en transition, dat ken ik van Sanne. Hoe ik de golvende rank en het pad maak moet ik nog uitzoeken.

Is het idee leuk en verrassend? Heb je zin om dit ontwerp te maken?

Ja, vooral de losse letters en het game level, omdat die bij mij passen.

Check-out

Waar werkt de visual research in drie stappen naartoe?

Naar uitgangspunten waarmee ik kan schetsen. Ik begon met beelden die direct bij mijn sfeerwoorden passen, daarna zocht ik abstracte posters en uit vier posters haalde ik kenmerken die ik echt kan gebruiken.

Waar gaat je garden over en met welke content?

Mijn garden gaat over mijn groei als ontwerper en als persoon. Ik laat mijn projecten zien vanaf jaar 1, met schetsen, prototypes en eindresultaten.

Welk Crazy 8 idee wil je het liefst uitwerken?

Ik wil meerdere ideeën samen uitwerken. Bovenaan staat mijn naam in losse letters. Daaronder loopt een rank of tijdlijn met mijn projecten, die je ook als game level met een slotje kan zien. Bij een project kan een schets verstopt zitten die je pas ziet als je beter kijkt.

Bronnen zijn de opdrachten en slides van werkgroep 2 op DLO, [Unsplash](https://unsplash.com) en [typographicposters.com](https://www.typographicposters.com).

### 17 nov - Practicum Light & Dark

Bij oefening 3 heb ik van een foto met hardlopers een responsive afbeelding gemaakt met het picture element. Er zijn vier versies van de foto. Groot is de hele foto en klein is een uitsnede van de schoen. De donkere versies zijn dezelfde foto's maar donkerder. Die vier versies heb ik gemaakt met een fotobewerking. De img onderaan is licht en klein. Daarboven staan met source donker en klein, licht en groot en donker en groot. Met een media query met and kies je de foto voor een breed scherm in donker.

![Oefening 3 in licht op een breed scherm](readme-images/17nov-oefening3-licht-breed.png)
![Oefening 3 in licht op een smal scherm](readme-images/17nov-oefening3-licht-smal.png)
![Oefening 3 in donker op een breed scherm](readme-images/17nov-oefening3-donker-breed.png)
![Oefening 3 in donker op een smal scherm](readme-images/17nov-oefening3-donker-smal.png)

Bij oefening 1 en 2 van Vasilis heb ik met custom properties een licht en donker thema gemaakt in CodePen. Eerst heb ik de pen geforkt. Ik keek de code op DLO, Ik heb die gelezen, in mijn fork gezet en na elk stuk getest.

Bij oefening 1 heb ik in de html selector custom properties gemaakt voor de achtergrond, de tekst, de rand en de kop. In body en h1 gebruik ik ze met var(). Om te testen heb ik de rand naar oranje veranderd. De rand veranderde meteen mee terwijl ik alleen de custom property bovenaan had aangepast.

![Oefening 1 zoals hij begon](readme-images/17nov-oefening1-start.png)
![Oefening 1 met kleuren uit de custom properties](readme-images/17nov-oefening1-kleuren.png)
![Oefening 1 met de rand naar oranje veranderd](readme-images/17nov-oefening1-oranje-rand.png)

Daarna heb ik color-scheme light dark aangezet en elke custom property twee kleuren gegeven met light-dark(). De eerste kleur is voor licht en de tweede voor donker. Ik heb het getest door mijn Mac in Systeeminstellingen van donker naar licht te zetten.

![Oefening 1 met mijn Mac op donker](readme-images/17nov-oefening1-donker.png)
![Oefening 1 met mijn Mac op licht](readme-images/17nov-oefening1-licht.png)

Oefening 2 was een kattenwinkel die helemaal grijs begon. Die heb ik in drie stukken gedaan. Eerst de achtergrond, de tekst en de header. Daarna de keuze tussen auto, licht en donker in de header. Als laatste de kaartjes en de knoppen met een andere kleur bij hover en active. Omdat ik light-dark() gebruik werken de keuzeknoppen in de header meteen.

![De kattenwinkel zoals hij begon](readme-images/17nov-oefening2-start.png)
![De kattenwinkel in donker na het eerste stuk](readme-images/17nov-oefening2-basiskleuren-donker.png)
![De kattenwinkel in licht met de gekozen optie paars](readme-images/17nov-oefening2-opties-licht.png)
![Een knop die roze wordt bij hover](readme-images/17nov-oefening2-knop-hover.png)
![Een knop die donkerblauw wordt als je erop klikt](readme-images/17nov-oefening2-knop-active.png)

Bronnen zijn het practicum Light & Dark van Vasilis op DLO en de CodePens van de docenten.

### 16 nov - Presentatie digital garden

Mijn onderwerp is ik als ontwerper. Ik wil een portfolio bouwen waarin je kan zien hoe ik groei als ontwerper.

Voor de 50 afbeeldingen heb ik mijn oude werk van DLO gebruikt. Daaruit komen 29 afbeeldingen van jaar 1 blok 1, 3 en 4 en jaar 2 blok 1. De andere 21 zijn screenshots van sites. 15 komen uit de lijst met voorbeelden op DLO en 6 heb ik erbij gezocht, zoals Bruno Simon en de site van GTA 6. Ik heb de bestanden gedownload, de screenshots gemaakt en er 8 collages van gemaakt, omdat je maar 15 slides mag hebben.

![Titelslide van mijn presentatie](readme-images/17nov-titelslide.png)
![Slide met de collage van mijn werk uit jaar 1 blok 1](readme-images/17nov-collage-eigen-werk.png)
![Slide met de collage van speelse sites als inspiratie](readme-images/17nov-collage-inspiratie.png)

Remark kende ik nog niet. De slides zijn gewoon Markdown, net als mijn README. Een nieuwe slide begin je met `---` en een titel met `#`. Een afbeelding zet je erin met `![alt tekst](pad)`. De presentatie heb ik in vier stappen gebouwd en na elke stap getest en gecommit.

Eerst vielen de collages buiten de slide. Met `img { max-width: 100%; }` uit de reset van praktische CSS passen ze wel.

![Collage zonder max-width, hij valt buiten de slide](readme-images/17nov-zonder-max-width.png)
![Collage met max-width, hij past in de slide](readme-images/17nov-met-max-width.png)

Bronnen zijn de opdracht op DLO, de Remark template van de docenten en de 21 sites die in de presentatie staan.

### 16 nov - Sprintplanning en verkenning onderwerp

Vandaag begon sprint 1. De opdracht is de eerste versie van mijn digital garden ontwerpen, bouwen en online zetten. Mijn planning voor het huiswerk heb ik in mijn notities gezet. Ik heb mijn fork gesynct met de repository van de docenten. Daardoor kwam de map oefeningen met de presentatie in mijn repository.

In mijn expertgroep heb ik Digital Garden Terms of Service van Shawn Wang gelezen. Dat gaat over wat je als lezer kan verwachten van een digital garden, bijvoorbeeld dat teksten nog niet af zijn en later nog veranderen.

Een gewone website is vaak af als hij online staat en een blog zet alles op datum. Een digital garden groeit. Je zet er ook dingen op die nog niet af zijn en je werkt ze later bij. Het is meer een verzameling die met links aan elkaar zit dan een tijdlijn.

Op DLO staat wanneer iets webby is. Fluïde, interactief, toegankelijk, volwassen, expressief en leuk of verrassend. Voor mij is een site webby als hij iets doet wat alleen op het web kan, zoals meebewegen met je scherm of zelf licht en donker kiezen. De sites die mij het meeste inspireren zijn Bruno Simon, Maggie Appleton en Mike Mai.

Mijn eerste idee is een portfolio over mij als ontwerper, waarin je mijn groei kan zien. Dat kan nog veranderen.

Bronnen zijn de opdrachten op DLO en het artikel van Shawn Wang.

### 13 nov - Praktische CSS en CSS fonts

Deze twee deep dives heb ik in het weekend gemaakt.

Bij Praktische CSS van Vasilis heb ik in CodePen een lelijke HTML pagina gemaakt over het wachten op GTA 6. Daarna heb ik hem met CSS leesbaar gemaakt. Eerst deed mijn CSS niks. Mijn index.html had geen link naar style.css. Toen ik die regel bovenaan zette werkte het wel.

![CodePen waarin de CSS nog niet werkt, de foto is veel te groot](readme-images/13nov-codepen-css-werkt-niet.png)

Voor de witruimte en de grootte van de koppen heb ik custom properties gebruikt. Ik heb --factor getest met 1.2, 1.3 en hoger. Dan werden de koppen te groot naast de gewone tekst en klopte de verhouding niet. Ik heb 1.1 gekozen. Daarna heb ik een link met hover en focus en een formulier toegevoegd. De rand om het formulier heb ik weggehaald omdat het er zo beter uitziet.

Bij CSS fonts van Sanne heb ik lettertypen toegevoegd met @font-face. Ik heb steeds mijn versie naast het voorbeeld van Sanne gelegd en getallen aangepast. Bij oefening 1 was de eerste letter met 3em veel te groot, met 1.5em leek hij. Bij oefening 2 was de gloed met .5em te verspreid, met .2em zit hij strak om de letters. De letters en regels stonden te dicht op elkaar, dus ik heb line-height 1.1 en letter-spacing .1em gebruikt. De schaduw heb ik steeds van .2 naar .5 veranderd om te vergelijken. Ik vond .2 er beter uitzien.

![Oefening 2 met het eerste blokje af en het tweede nog wit](readme-images/13nov-oefening2-stap1.png)
![Oefening 2 met beide blokjes, de letters staan nog te dicht op elkaar](readme-images/13nov-oefening2-stap2.png)
![Oefening 2 na het aanpassen van de gloed, de ruimte en de schaduw](readme-images/13nov-oefening2-aangepast.png)

Bij oefening 3 heb ik het blokje Myst nagemaakt. Met 3em waren de letters kleiner dan bij Sanne, 4em klopte beter. Bij oefening 4 heb ik een transitie toegevoegd. Als je over het blokje gaat schuift de schaduw verder weg en draait de tekst 180 graden. Die draai heb ik zelf toegevoegd omdat het blokje er speelser door wordt.

![Blokje Myst met letters op 3em](readme-images/13nov-myst-3em.png)
![Blokje Myst met letters op 4em](readme-images/13nov-myst-4em.png)
![Blokje Myst bij hover, de tekst is 180 graden gedraaid](readme-images/13nov-myst-hover.png)

Bronnen zijn de deep dives van Vasilis en Sanne.

### 11 nov - Interactie en Schetsen

Bij Interactie van Nicky heb ik het Wok to Walk menu geschetst als online formulier voor laptop en tablet. Eerst de drie kolommen los, daarna het hele scherm. Ik heb ook getekend hoe een rij eruitziet als default, bij hover en als hij actief is. In de laatste versie heb ik de gekozen opties oranje gemaakt en het totaal onderaan gezet.

![Schets van het Wok to Walk formulier met drie kolommen en de staten van een rij](readme-images/11nov-wok-formulier.png)

Bij Schetsen van Charley heb ik de basisoefeningen gedaan. Ik heb rechte lijnen, vierkanten en een iPhone op ware grootte getekend. Twee iPhones heb ik ingekleurd met schaduw en kleur. Daarna heb ik een mi-fi schets gemaakt van Instagram, een app die ik vaak gebruik.

![Oefening met rechte lijnen](readme-images/11nov-lijnen.png)
![Oefening met vierkanten](readme-images/11nov-vierkanten.png)
![Vier iPhones op ware grootte, twee ingekleurd](readme-images/11nov-iphones.png)
![Mi-fi schets van Instagram](readme-images/11nov-instagram.png)

### 9 nov Kickoff

Ik heb GitHub gekozen als source hosting platform. Daar staat mijn code en van daaruit gaat mijn site online. Ik heb de model repository geforkt en GitHub Pages aangezet.

Mijn domein is tolgakece.nl. Ik heb mijn eigen naam gekozen omdat dit mijn portfolio wordt en ik het wil houden. Ik heb het gekocht bij TransIP. Daar heb ik de standaard instellingen uitgezet en 4 A-records en een CNAME voor www gemaakt die naar GitHub wijzen. Op GitHub heb ik bij Pages mijn domein ingevuld. Toen de DNS check groen was heb ik HTTPS aangezet.

Op mijn MacBook heb ik VSCodium en Prettier geïnstalleerd en mijn repository gecloned. Ik pas dingen aan in VSCodium en sla op. Daarna commit ik en klik ik op Sync Changes. Dan staat het op GitHub en zet GitHub Pages het online. Mijn eerste aanpassing was de titel van de pagina.
