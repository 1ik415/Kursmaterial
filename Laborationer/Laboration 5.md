## Inledning
I denna avslutande laboration ska du testa att märka upp en sida med de nya strukturtaggarna i HTML5. Mikroformat står dessutom på agendan tillsammans med ytterligare CSS3.

## Mål
Efter laborationen ska du:

- Känna till hur sidor är tänkta att struktureras med HTML5
- Fått en orientering om mikroformat
- Känna till nya egenskaper och selektorer i CSS3, så som, transition, transformation och content.

## Förberedelse
Innan du kommer till laborationstillfället bör du vara så förberedd att du känner att du hinner genomföra och redovisa laborationen under det handledda tillfället. Du får givetvis göra laborationen helt klar i förväg och du har då möjlighet att utnyttja handledningstillfället för frågor och redovisning. 

Läs igenom **hela** laborationshandledningen innan du påbörjar laborationen.

## Genomförande
Utför laborationens uppgifter och moment samt dokumentera vad du kommer fram till på de olika delarna. Vid redovisning av laborationen ska du kunna besvara frågor om hur du har löst de olika delarna och varför de är lösta på det sätt du löst dem på.
När du anser dig vara klar med laborationen kontrollerar du att din källkod uppfyller laborationens samtliga krav.

Efter **minst** varje uppgift i denna handledning ska du göra en commit till ditt GIT-repositorie.

## Plagiat
Laborationen ska genomföras enskilt. Du får givetvis fråga klasskamrater om hjälp men du ska skriva din egen kod och kunna svara för varför du skrivit din kod på det sätt du gjort. Vid fuskmisstanke lämnas misstankar samt berörda dokument över till universitetets disciplinnämnd.

## Föreslå ändringar
Denna handledning ligger på [GitHub](https://github.com/1ik415/Kursmaterial/blob/master/Laborationer/Laboration%206.md) om du vill föreslå ändringar eller hålla koll på vad de senaste uppdateringarna innebar.

## Uppgift 5.1 – Sidstruktur
HTML5 introducerar en uppsättning nya taggar som är tänkta till att ge våra sidor bättre struktur och semantik. Du ska i denna uppgift testa att använda dem. Tanken är att du ska skriva om startsidan på din blogg så att den använder de nya taggarna i HTML5. Vill du hellre skapa en helt ny sida så är det tillåtet. Se då till att länka till sidan från din laborationsportal.

Förutom de delar som du redan har på din startsida så ska du lägga till "kommentarer" till varje skriven bloggpost.

Uppgiften ska lösas genom att använda de nya strukturella taggar som finns i HTML5. Taggarna ska användas i de fall de är lämpliga. Taggar att använda här är exempelvis:

- Header
- Footer
- Article
- Aside
- Main
- Section
- Nav

### Tänk på:
1. För att kunna stila dina element i tidigare webbläsare som inte direkt stödjer taggarna ovan så kan du behöva göra ett javascript-fix. Detta är inget krav för att bli godkänd på laborationen.
1. I webbläsare som inte stödjer taggarna så blir dessa nya elementen inline-element och måste således ställas om till blockelement innan du kan stila dem som du förväntar dig.

## Uppgift 5.2 – Mikroformat
Mikroformat är ett, av flera sätt, för oss som utvecklare av webbplatser att tala om för sökmotorer och andra tjänster vad innehållet på våra sidor egentligen betyder. I denna uppgift ska du testa att lägga till ett hCard, kontaktkort, på din kontaktsida. 

- Infoga ett hCard om dig själv på din blogg. För att underlätta så finns det ett verktyg som man kan använda sig av. [http://microformats.org/code/hcard/creator](http://microformats.org/code/hcard/creator)
- Testa så att googles sökmotor kan se ditt hCard genom att använda dig av [http://www.google.com/webmasters/tools/richsnippets](http://www.google.com/webmasters/tools/richsnippets)


## Uppgift 5.3 – Fotogalleri
De nya egenskaperna och selektorerna som introduceras i CSS3 är kraftfulla och möjliggör att vi med CSS kommer att kunna göra saker som tidigare krävt javascript. 

Du ska i denna uppgift skapa ett fotogalleri där bilder verkar ligga utslängda på en yta. När muspekaren dras över en bild så ska denna förstoras tillsammans med sin bildtext. 

<iframe width="560" height="315" src="//www.youtube.com/embed/_E4lq_IFDlk" frameborder="0" allowfullscreen></iframe>
(Demo: [http://youtu.be/_E4lq_IFDlk](http://youtu.be/_E4lq_IFDlk))

När du kodar ska du se till att göra flera commits. Gör en commit per problem som du löser i uppgiften.

Börja med att skapa en katalog "gallery" i roten på ditt huvudrepro (alltså på samma nivå som "pages", "css").
I katalogen gallery skapar du sedan html-filen "index.html". CSS-filen lägger du sedan på lämpligt ställe.

Det finns några krav på uppgiften:

- HTML-koden ska vara ren och bildtexten får enbart ligga som värde på attributet "title" på lämplig tag. (se film)
- Under respektive bild ska bildtexten synas. 
- Ett externt typsnitt ska laddas in på valfritt sätt och vara det typsnitt som används för att skriva ut texten under bilderna.
- När muspekaren förs över en bild ska bilden förstoras genom en pålagd övergång, transition.
- När användaren använder tangentbordet och "tabbar" till en bild (ger den fokus) ska samma sak hända som då användarens muspekare förs över en bild.
- Bilderna ska ha en skugga.
- Uppgiften ska fungera i minst en webbläsare av senare modell.

CSS-egenskaper och selektorer som du troligtvis kommer att behöva använda (läs på om dessa!):

- :after
- :hover
- :nth-child
- attr()
- content
- transition
- box-shadow
- transform
- z-index
- font-family

### Tips:

- Övergångar med ”transitions” påverkar alla egenskaper som ändras på det objekt som har transition satt.
- Prefixen `–moz-`, `-webkit-`, `-o-`. behöver användas för många av egenskaperna.  Exempelvis: `-moz-transform`
- Förutom att använda webbläsarspecifika prefix ska du använda de CSS3-standardiserade namnen, exempelvis `transform`.
- Troligtvis vill du låta transitionen påverka samtliga egenskaper, det vill säga "all"
- För att få "slumpvis" fontstorlek och rotation kan du använda nth-child-selektorn för att rotera exempelvis var 3e bild -5 grader och var 5e bild 10 grader etc.
-  Du kommer att märka att du inte kan använda pseudoklassen "after" och css-egenskapen "content" på en img-tagg vilket gör att det kan vara lämpligt att lägga title-attributet på en annan tagg än img.
- Sätt `position:relative;` på bilderna så kommer z-index även att fungera i Chrome.
- Tänk på att många av egenskaperna är experimentella i webbläsarna vilket gör att buggar kan förekomma. 


Givetvis har du full konstnärlig frihet att utforma delar av uppgiften som du vill, men se till att nyttja grundkrav som transitions, transformations, typsnitt etc.

## Postludium
Du har nu genomfört laboration 5 och du ska nu skapa en release för detta på GitHub.
Se till att "Tag version" blir `l05` (Ludvig, nolla, femma).
Välj en lämplig titel.