 
## Inledning
I din framtida yrkesroll och roll som samhällsmedborgare kommer du i olika sammanhang att få presentera lösningar, produkter eller projekt för en varierande publik. Som en avslutande del i kursen så ska du få träna dessa färdigheter. Du kommer vidare att få repetera stora delar av kursinnehållet i och med att din presentation ska genomföras i ett befintligt presentationssystem som kräver att du skapar presentationen i HTML/CSS.

## Uppgiften
Uppgiften går ut på att du ska ta fram en presentation inom ett ämne som är intressant för kursen. Du kommer sedan att med hjälp av ett presentationsverktyg skapa en presentation av detta ämne som du sedan kommer att redovisa muntligt inför en mindre grupp i kursens sista vecka.

Presentationen ska vara mellan 6-10 minuter lång vilket gör att det kan vara smart att välje ett ganskas smalt ämne eftersom tiden är knapp.

Exempel på ämnen skulle kunna vara:
- Hur utfomrar man bra alt-texter till bilder?
- Presentation av semantic grid system
- Hur fungerar CSS tabell-layout?
- Vad är en Static Site Generators?
- article-taggen i HTML5, en djupdykning
- ...

## Krav:
- Ämnet ska ha relevans för kursen. Är du osäker? Stäm av med kursansvarig genom att ställa en fråga i kursens diskussionsgrupp.
- Använd anvisat presentationsverktyg. (Vill du testa något annat verktyg så stäm av med kursansvarig)

### GitHub-repro och Reveal.js
Presentationen skapar du i ett nytt repository på GitHub. 

Reprot som ska användas ska vara en fork (se laboration 3) av: [1ik415/ProjektskelettHT14](https://github.com/1ik415/ProjektskelettHT14)

Öppna nu detta nya projekt i Cloud9.

Nu ska du hämta in det presentationsverktyg som du ska använda. Detta heter [Reveal.js och hittas på GitHub](https://github.com/hakimel/reveal.js). För att hämta hem filerna från Reveal.js till ditt repro skriver du i terminalen:

'git pull https://github.com/hakimel/reveal.js.git'

Observera att du nu kommer att få en konflikt. Detta beror på att både ditt forkade repro och Reveal.js har en .gitignore-fil och du blir nu ombedd att åtgärda konflikten. Gör så här:
* Välj att visa "hidden files" i C9. (Kugghjulet ovanför fillistningen)
* Öppna '.gitignore'
* Ta bort de rader som inleds med '<<<<<<<' och '>>>>>>>' samt '======='. (Dessa har git lagt in för att markera vad som tillhör oss, och vad som tillhör Reveal.js. I detta fall vill vi ha kvar både våra och deras kod.)
* Spara
* Lägg till filerna för nästa commit 'git add .'
* Gör en commit: 'git commit -m "Adding reveal.js"
* 'git push' för att trycka till ditt repro på GH.

Nu kan du börja arbeta som vanligt med kontinuerliga commits. Reveal.js är relativt självinstruerade. Du hittar en bra start i README.md. Du behöver inte bry dig om det som står efter rubriken "API" om du inte vill. Detta är lite överkurs.

 
## Redovisning
Observera att presentationen enbart bedöms med U eller G och räknas in i kursens laborationsmoment.

Er uppgift ska redovisas inför klassen på ett av redovisningstillfällena i sista kursveckan. Ni [bokar själv vilket pass ni vill redovisa](//coursepress.lnu.se/kurs/webbteknisk-introduktion/laborationer/webbsideprojekt-redovisningstider/) på.

### Campus
Vid redovisningstillfället kommer ni att ha tillgång till en dator med Internet Explorer, Google Chrome, Mozilla Firefox installerat. Upplösningen på projektorn är 1440x900 (16:10).

### Distansstudenter:
Som distansstudent har gruppen två val. Ni kan redovisa på plats i Kalmar tillsammans med campusstudenterna eller genom Adobe Connect.
Ni kommer med andra ord att få möjlighet att dela ut en skärmbild och samtliga studenter i gruppen kommer att kunna prata och synas via webbkamera/headset, på samma sätt som föreläsningarna i kursen genomförts.
Klassrummet kommer att vara öppet under sista projektveckan så att ni kan gå in där och testa webbkamera/headset och skärmdelningen samt genomföra en testredovisning om ni önskar.

**Observera!** För att du som distansstudent ska ha möjlighet att redovisa på distans krävs det att du har tillgång till webbkamera och headset. Har du inte det får du ta dig till Kalmar för att redovisa tillsammans med campusstudenterna.
