 
## Inledning
Du har nu under ett antal laborationer i webbteknik fått relativt styrda uppgifter där du ensam fått lösa problem. Du kommer nu att gå steget längre och ensam eller i grupp om två till tre personer ta dig an en större uppgift. Du kommer själv att i stor grad få styra över innehållet i laborationen men några mindre krav kommer att ställas.

## Mål
Efter genomförd laboration kommer du att kunna planera och genomföra ett mindre webbprojekt ensam eller i grupp. Du kommer att få tillämpa vissa av de kunskaper som du tidigare enbart tillägnat dig i teori. 

Du kommer även att få träna på att presentera din lösning inför en mindre grupp människor på campus eller på distans.

## Genomförande
Innan du sätter i gång med ditt arbete är det viktigt att du noggrant läser igenom hela denna handledning så att du är väl införstådd i uppgiften och ser till att få med alla krav på projektet redan i projektbeskrivningen. 

Under projektets gång ska ett antal dokument redovisas. Dessa dokument ska skickas in innan en viss deadline, om inte deadlinen uppfylls så kommer du att få skicka in ytterligare dokument med fylligare innehåll som komplettering. Information om deadlines hittar du längre ner på sidan.

## Presentation av uppgiften
Ni kommer själva att få utforma er uppgift. Det enda som regleras i detta dokument är några detaljer.
Ni ska skapa en webbplats för ett speciellt syfte. Vad detta syfte är väljer ni själva men några exempel skulle kunna vara:

- Webbplats åt idrottsföreningen X
- Felrapporteringssystem för ett företags nätverk. Inklusive administrationsgränssnitt.
- Fotoalbum för evenemangsföretaget Y.
- Intranät för företaget Z.
- Sida som visar upp nyheter i CSS3 och HTML5
- Produktvisningssida för produkten Å.

Ni har stor valfrihet i att själva styra vad projektet ska behandla. Några krav ställs dock på projektet.

## Krav:
- Ni ska arbeta utifrån principen "Mobile First". Alltså ska webbplatsen först och främst skapas för mobila enheter i åtanke för att sedan skalas upp att även fungera på enheter med större skärmar. Detta arbetssätt blir alltså det motsatta mot hur ni arbetat på laborationerna.
- Projektet bör innehålla minst 5-6 olika sidor eller delsidor. Det är tillåtet att göra en så kallad "Single-page webpage" där allt innehåll finns i samma html-dokument. Dock ska det i så fall finnas en tydlig navigation. Se exempel på: [One Page Love](http://onepagelove.com/)
- På webbsajten ska det någonstans finnas ett formulär. 
- Bilder som enbart används för sidans layout ska läsas in via CSS.
- Då stilmallar är avaktiverade ska sidan ändå presenteras på ett enkelt och bra sätt. Menyer ska vara lätta att hitta med mera.
- Sidor som kan vara aktuella att skriva ut ska ha en separat genomarbetad stilmall för ändamålet.
- Tabeller ska enbart användas för att presentera tabelldata, inte för att styra layouten!
- Ni ska lägga tonvikt vid att göra en "snygg" hemsida. Vi förväntar oss inga underverk men ni ska kunna försvara er layout och stå för den.
- Koden ska vara snyggt skriven, välindenterad och kommenterad där det behövs.
- Sidan ska ha en responsiv layout. Sidans layout ska alltså anpassa sig efter bredden på webbläsaren/enheten.
- ALLA sidor ska följa och valideras enligt HTML5. Avsteg från detta ska kunna motiveras
- Sidan ska uppfylla kraven för WCAG 2.0 AA. 

## Observera
Många av de saker som ni skulle vilja göra går långt utanför ramarna för denna kurs, så som att t.ex. behandla data som skickas från ett formulär, läsa data från databaser med mera. I de fall ni skulle behöva denna funktionalitet får ni utelämna den eller fejka den genom statisk information. Exempelvis kan det finnas ett inloggningsformulär men när man klickar på "logga in" så blir användaren "inloggad" som en exempelanvändare oavsett vilka uppgifter som skrivs in.

## Steg 1 – Projektbeskrivning med tidsplan
Det första ni ska göra är att skapa en kort projektbeskrivning. I denna projektbeskrivning ska ni ge en kort introduktion till projektet, vad projektet handlar om i stort samt ge en tidsplan som ger en uppfattning om hur arbetet ska struktureras.

Efter genomläst projektdokumentation ska läsaren veta varför ni valt att göra detta projekt, vad projektet behandlar, vilka tekniker som kommer att användas och vilket syfte produkten, webbplatsen, kommer att tillgodose.

Följande ska finnas med i projektbeskrivningen:

- Ett kort, beskrivande namn på ert projekt. Exempelvis: "Administrationssystemet NICE"
- Vad är det för produkt, webbplats, ni ska skapa.
- Hur ska webbplatsen skapas? Vilka tekniker kommer att användas?
- Eventuella begränsningar av projektet.
- Eventuellt redan existerande prototyp som projektet grundar sig på. Beskriv även eventuella förstudier som gjorts utanför ramarna för denna kurs.
- Namn, personnummer och användarnamn på de studenter som ingår i projektgruppen.
- Någon form av tidsplanering. När ska ni göra vad?
- Länk till GitHub-repro. Se nedan.

Projektbeskrivning ska lämnas in **INNAN den deadline** som är definierad på kursens webbplats.

Språkbruket i projektbeskrivningen ska vara bra. Låt gärna en tredje person läsa igenom projektbeskrivningen innan ni skickar in den.
Projektbeskrivningen ska skrivas på svenska eller engelska.

### Tidsplanen:
För att arbetet ska flyta smidigt och för att ni ska slippa att hamna i tidsnöd dagarna innan projektet ska vara slutfört ska ni skapa en tidsplan.

Eftersom ni enbart har tre veckor på er att utföra projektet är det lämpligt att tidsschemat har upplösningen 1 dag. Det vill säga, att ni specificerar vad som ska göras varje dag snarare än varje vecka. Lördagar och söndagar behöver inte visas i schemat om ni kommer att ha dessa lediga.

Exempel på detaljer som kan skrivas i tidsschemat:

- Planeringsarbete
- Skiss
- Sidans struktur
- Formulärskapande
- Stilmall
- Detaljjusteringar
- Tillgänglighetsanalys
- Förberedelse inför presentation
- Presentation

Tidsplanen publiceras tillsammans med projektbeskrivningen. Skapa gärna tidsplanen som ett kalkylblad i Google Drive ([https://drive.google.com](https://drive.google.com)). När tisplanen lämnas in ska detta vara i pdf-format.

Tidsplanen ska vara i form av ett GANTT-schema. Wikipedia beskriver till exempel GANTT-schema:
[http://en.wikipedia.org/wiki/Gantt_chart](http://en.wikipedia.org/wiki/Gantt_chart)

### GitHub-repro
Projektet tillsammans med projektdokumentationen ska versionshanteras via Git och hanteras på GitHub.

Reprot som ska användas ska vara en fork (se laboration 3) av: [1ik415/ProjektskelettHT13](https://github.com/1ik415/ProjektskelettHT13)
Arbetar ni i en grupp så forkar en av er projektet och sätter de andra projektmedlemmarna som "Collaborators" (se laboration 1). 

### Inlämning
I den fork ni gjort ovan så finns katalogen "doc" och i den hittar ni filen "Projektbeskrivning.md". Det är i denna fil ni ska skriva projektbeskrivningen i så kallad "Mark Down". Kort information om detta hittar ni i filen "doc/README.md".

När projektbeskrivningen är klar så skickar ni följande i ett mail till [1ik415@lnu.se](mailto:1ik415@lnu.se) senast deadline:

* Personuppgifter på samtliga projektdeltagare (Personnummer, användarnamn, för- och efternamn)
* Länk till projektets GitHub-repro.

Eventuella kommentarer kommer ni att få direkt via GitHub.
 
### Observera
En viktig del i detta projekt är att projektgruppen slutför och "levererar" det som skrivs i projektbeskrivningen. Ta med andra ord inte på er för mycket utan begränsa arbetet till en rimlig nivå. Om ni redan nu känner att ni inte kommer att kunna genomföra så mycket som ni skulle vilja så skriver ni in de delar som inte hinns med, under begränsningar.

En bedömning kommer att göras av kursansvarig och det kan vara som så att ni måste göra lite mer eller mindre av det ni tagit på er i projektbeskrivningen. Kursansvarig kommer i så fall att kontakta er angående detta.
 
## Steg 2 – Implementation
I detta steg skapar ni er webbplats enligt de instruktioner som gavs tidigare. Detta steg kan påbörjas utan att ni fått godkännande för STEG 1. Observera att några mindre tillägg eller begränsningar kan komma att behöva göras beroende på kursansvarigs åsikter om er projektbeskrivning.

Se noggrant till att följa det tidsschema ni skapat i förra uppgiften. Om ni följer schemat bör ni följaktligen bli klara i tid.

### Tips
När ni nu börjar implementera er kod är det bra om ni börjar med det stora för att sedan gå till det lilla. Tänk med andra ord inte allt för mycket på detaljerna i början utan spara dessa till sist. Det är inte hela världen om en liten detalj inte hinner fixas till redovisningen, men mycket värre om sidans struktur inte är klar.
 
## Steg 3 – Redovisning
Observera att projektet enbart bedöms med U eller G och räknas in i kursens laborationsmoment.

Er uppgift ska redovisas inför klassen på ett av redovisningstillfällena i sista kursveckan. Ni [bokar själv vilket pass ni vill redovisa](//coursepress.lnu.se/kurs/webbteknisk-introduktion/laborationer/webbsideprojekt-redovisningstider/) på.

Ni ska förbereda en presentation på 5-10 minuter och ni ska vid detta tillfälle vara beredda att svara på frågor angående era lösningar. 
Ni ska se denna redovisning som er chans att sälja in produkten. En dålig presentation kommer antagligen få en bra produkt att verkar halvdålig, medan en bra presentation kan sälja en sämre produkt. Se därför till att lägga ner lite tid på att förbereda presentationen, den är alltid mycket viktig.

### Campus
Vid redovisningstillfället kommer ni att ha tillgång till en dator med Internet Explorer, Google Chrome, Mozilla Firefox installerat. Upplösningen på projektorn är 1440x900 (16:10).
Det är inte säkert att ni kommer att få tillgång till era personliga filer på p: så se till att göra de filer ni behöver tillgängliga via exempelvis GitHub-reprot. Detta gäller även eventuella presentationer som lämpar sig att lägga i katalogen "doc".

### Distansstudenter:
Som distansstudent har gruppen två val. Ni kan redovisa på plats i Kalmar tillsammans med campusstudenterna eller genom Adobe Connect.
Ni kommer med andra ord att få möjlighet att dela ut en skärmbild och samtliga studenter i gruppen kommer att kunna prata och synas via webbkamera/headset, på samma sätt som föreläsningarna i kursen genomförts.
Klassrummet kommer att vara öppet under sista projektveckan så att ni kan gå in där och testa webbkamera/headset och skärmdelningen samt genomföra en testredovisning om ni önskar.

**Observera!** För att du som distansstudent ska ha möjlighet att redovisa på distans krävs det att du har tillgång till webbkamera och headset. Har du inte det får du ta dig till Kalmar för att redovisa tillsammans med campusstudenterna.
