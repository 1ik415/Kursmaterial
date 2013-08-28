## Inledning
Denna inledande laboration syftar i mångt och mycket till att du ska känna dig bekväm med den laborationsmiljö som skolan erbjuder eller få möjlighet att skapa dig en egen miljö hemma. 

De inledande uppgifterna kommer inte att vara allt för svåra och har du sysslat med html tidigare så kommer du troligtvis få en behaglig resa så här i början.

Samtliga uppgifter görs som en del i en större webbsajt som du kommer att kunna använda som en laborationsportal i denna och kommande kurser. Portalen kommer att byggas på i de kommande laborationerna så om du är noggrann nu i början så kommer du att tjäna på det i slutändan.

I mitten av laborationen finns en teoretisk uppgift kring absoluta och relativa URL:er. Det är av största vikt att du förstår hur detta fungerar för att kunna genomföra denna laboration och kommande laborationer.

Du som är ny på html kan finna mycket hjälp i de inspelade demonstrationer som du hittar via kursens webbplats.

## Mål
Efter genomförd laboration ska du kunna skapa enklare html-dokument som du kan ladda upp till en webbserver för publicering. Du kommer vidare att kunna valideras dessa uppladdade dokument.
Du kommer att få lära känna de enklaste html-taggarna så som p, h, ul lite bättre.
Du kommer vidare att öva på att länka mellan dokument med hjälp av a-taggen, lägga in olika typer av media, skapa tabeller och formulär.

## Förberedelse
Innan du kommer till laborationstillfället bör du vara så förberedd att du känner att du hinner genomföra och redovisa laborationen under det handledda tillfället. Du får givetvis göra laborationen helt klar i förväg och du har då möjlighet att utnyttja handledningstillfället för frågor och redovisning. 

Läs igenom **hela** laborationshandledningen innan du påbörjar laborationen.

## Genomförande
Utför laborationens uppgifter och moment samt dokumentera vad du kommer fram till på de olika delarna. Vid redovisning av laborationen ska du kunna besvara frågor om hur du har löst de olika delarna och varför de är lösta på det sätt du löst dem på.
När du anser dig vara klar med laborationen kontrollerar du att din källkod uppfyller laborationens samtliga krav.
Efter (minst) varje uppgift i denna handledning ska du göra en commit till ditt GIT-repositorie. (Se kursens webbplats för mer information kring GIT)

## Plagiat
Laborationen ska genomföras enskilt. Du får givetvis fråga klasskamrater om hjälp men du ska skriva din egen kod och kunna svara för varför du skrivit din kod på det sätt du gjort. Vid fuskmisstanke lämnas misstankar samt berörda dokument över till universitetets disciplinnämnd.

 
## Uppgift 1.1 – GIT FÖRÄNDRA

1. Skapa gh-pages-branch.
Vänta lite i klienten och byt sedan till gh-branchen. 

*Vi ska börja med att bekanta oss med laborationsmiljön.*

*Beroende om du sitter på campus eller på distans så kommer denna uppgift att skilja sig åt något.* 

*Det du ska göra är att kontrollera att du på nätverksenheten p: har en katalog som heter www.*

Campus
Sitter du inloggad på en dator på campus kan du öppna en filhanterare (win+e) och navigera dig till p:

Väl där kontrollerar du att katalogen www existerar och att du har en fil, default.htm, i denna katalog.

Distans
På distans så har du inte direkt tillgång till nätverksenheten p:. Det finns dock flera olika möjligheter för dig att koppla upp dig mot denna enhet för att föra över filer. 

Bästa sättet för att lyckas bra med laborationerna i denna kurs är att använda ett separat ftp-program, alternativt använda en editor med inbyggt stöd för ftp. På kursens webbplats finns inspelade demo som visar hur du använder ftp.

Alternativ två är att använda http://wfm.lnu.se. Denna webbklient låter dig få tillgång till p: och du kan då på samma sätt som campus kontrollera om du har tillgång till www-katalogen.

Om du inte har någon www-katalog
Om du inte har någon www-katalog så ska du inte själv heller skapa denna katalog. Kontakta i så fall kursansvarig så fort som möjligt så ser vi till att denna katalog skapas till dig. Anledningen till att du inte har en www-katalog är att du troligtvis studerat någon icke it-relaterad utbildning eller kurs vid LNU, HIK eller VXU tidigare och ditt konto är då inte uppgraderat.
 
## Uppgift 1.2 – Ett första dokument
Under kursens laborationer kommer du steg för steg att bygga upp en blogg, eller enklare hemsida som ska kunna användas för att bland annat presentera laborationer på. 

Det första steget vi ska ta nu är att skapa ett första html-dokument som kommer att innehålla en presentation över dig, vad du gjort tidigare etc. 
Du är fri att själv forma innehållet men det vore intressant att bland annat få veta följande:
•	Intressen
•	Familj
•	Vad du är bra respektive mindre bra på
•	Tidigare utbildning?
•	Arbetslivserfarenhet?
•	Har du programmerat tidigare?
•	Vad fick dig att söka utbildningen?
•	Tankar inför framtiden?

Denna sida döper du till ”presentation.html”. Sidan ska placeras i en katalog som du döper till ”pages” och som du lägger i ditt lokala repositorie (Den katalog som du skapade i uppgift 1). 
 
I presentation.html ser du nu till att skapa ett html-dokument med de delar som detta innebär. 

För att uppgiften ska vara godkänd ska ditt dokument minst innehålla följande:
* Två rubriknivåer
* Text separerad med hjälp av paragraftaggar. 
* Samtliga listor. (ol, ul, dl)
* Minst en lista som ligger inuti en annan lista.
* Minst en kommentar
* Texten ”Ansvarig för materialet på denna sida är” följt av ditt namn.

När du testat sidan och känner dig klar så ska du:
1. Göra en commit i git.
2. Göra en synkning mot GitHub.
3. Publicera ditt dokument. 
### Publicera ditt dokument
#### Publicera ditt dokument på p:
Om du följt instruktionerna och lagt filen presentation.html i katalogen pages som ligger i katalogen www, så når du denna fil genom webbadressen:
http://homepage.lnu.se/student/xx222yy/pages/presentation.html
där xx222yy byts ut mot ditt användarnamn.

Om det redan finns filer i din www-katalog så kan du radera dessa (speciellt default.htm)

#### Publicera ditt dokument på GitHub-pages
#### Publicera ditt dokument på valfritt webbhotell
Du kan välja att publicera dina dokument på valfritt webbhotell. Du följer du instruktionerna för detta specifika webbhotell.



4. Testa att validera ditt dokument. 

### Validera
Du validerar ditt dokument genom att skriva in adressen till dokumentet i validatorn på http://validator.w3.org/

Ta till vana att validera ditt dokument ofta, speciellt om du inte kodat speciellt mycket HTML tidigare. Då kan du fånga upp fel tidigt, innan din kodbas blir stor. Det gör det lättare för dig att fånga upp felen. Ju mer van vid HTML du blir, desto mer sällan behöver du validera.

 
## Uppgift 1.3 – Startsidan
Du ska nu göra din startsida som kommer att fungera som en form av blogg för att presentera uppgifter som du gör i kursen. 

Skapa dig en ny html-sida som du döper till index.html och som du publicerar direkt i root-katalogen på ditt lokala repositorie. 

Detta gör att webbservern nu kommer att servera filen index.html om man skriver in adressen:
http://homepage.lnu.se/student/xx222yy/
om du publicerat på P:/www, eller:
http://xx222yy.github.io/Laborationer/
om du publicerat på GitHub-pages. 
_(xx222yy byts ut mot ditt användarnamn)_

Skapa nu en lämplig rubrik för din sajt och skriv ett första blogginlägg, komplett med rubrik och stycken. Tänk redan nu på att du kommer att skapa flera inlägg under kursens gång.

Ett exempel på hur detta kan se ut:
![alt text][rubriker] 

Observera! Tänk inte i detta skede alls på presentationsdetaljer. Kanske vill man ändra färg på texten, ändra typsnitt, ha kursiv text etc. **Detta är inget vi ska bry oss om i detta skede.** Det viktiga nu är att vår kod är så semantisk och välskriven som möjligt.

**Validera nu och gör en commit till git.**
 
### Vanliga problem så här långt:
**P:** Filen heter presentation.html och ligger i katalogen ”pages” i  www-katalogen på p: men jag kommer inte åt den genom att skriva in adressen ovan.
**L:** Det är mycket möjligt att du råkat döpa filen till presentation.html.html om du sitter i Windows eftersom Windows normalt sett döljer filtilläggen. Kontrollera därför noga att du inte har döpt filen till .html.html, alternativt .html.txt
**L:** Har du skapat din www-katalog själv för att den inte fanns från början? Kontakta i så fall kursledningen. Katalogen www kan man inte skapa själv.

**P:** Svenska tecken, ÅÄÖ och andra specialtecken ser lustiga ut.
**L:** Du använder inte samma teckenuppsättning på ditt dokument som du angivit i meta-taggens charset. Se demo på kurswebben för lösning.


### Vanliga frågor:
**F:** Måste jag använda de filnamn som används ovan? 
**S:** Ja. Det finns en poäng med att vi döpt filerna som vi gjort och lagt dem i underkataloger. 

**F:** Får jag redan nu använda andra taggar eller css? 
**S:** Ja, så länge som resten av kraven är uppfyllda är detta okej.

## Uppgift 1.4 – Absoluta/Relativa sökvägar
Det är nu dags att bekanta sig med sökvägar och länkar.

Givet är följande katalogstruktur (fiktivt scenario):

![Filträdsstruktur][filtrad]

För att nå katalogen www tänker vi oss att vi skriver http://www.server.se

Utifrån förutsättningarna ovan ska du nu svara på nedanstående frågor. Gör detta till och börja med genom att skriva ner dem på ett papper eller som en kommentar i valfritt html-dokument.

1.4.1. Vilken är den absoluta sökvägen till filen bottom.html?
1.4.2. Vilken är den relativa sökvägen från filen default.html till filen top.html?
1.4.3. Vilken är den relativa sökvägen från filen bottom.html till filen index.html?
1.4.4. Vilken är den absoluta sökvägen till filen index.html?
1.4.5. Vilken är den relativa sökvägen från filen top.html till bottom.html?
1.4.6. Vilken är den relativa sökvägen från filen index.html till top.html:

## Uppgift 1.5 – Länkar och mer listor
Laborationerna i denna kurs kommer att gå ut på att skapa en egen websajt på vilken du bland annat kan presentera laborationsresultat i denna och kommande kurser. 

För att lyckas med detta behöver vi en struktur för våra sidor. 
![Föreslagen filstruktur][lankstruktur]

Sidorna presentation.html och index.html har du förhoppningsvis redan gjort i och med de första uppgifterna. 

Skapa nu html-dokumenten enligt strukturen ovan så att du har följande struktur:



[rubriker]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/1.png

[filtrad]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/filetree.png

[lankstruktur]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/linkstrukture.png