## Inledning
Denna inledande laboration syftar i mångt och mycket till att du ska känna dig bekväm med den laborationsmiljö som skolan erbjuder eller få möjlighet att skapa dig en egen miljö hemma. 

De inledande uppgifterna kommer inte att vara allt för svåra och har du sysslat med html tidigare så kommer du troligtvis få en behaglig resa så här i början.

Samtliga uppgifter görs som en del i en större webbsajt som du kommer att kunna använda som en laborationsportal i denna och kommande kurser. Portalen kommer att byggas på i de kommande laborationerna så om du är noggrann nu i början så kommer du att tjäna på det i slutändan.

I mitten av laborationen finns en teoretisk uppgift kring absoluta och relativa URL:er. Det är av största vikt att du förstår hur detta fungerar för att kunna genomföra denna laboration och kommande laborationer.

Du som är ny på html kan finna mycket hjälp i de inspelade demonstrationer som du hittar via kursens webbplats.

## Mål
Efter genomförd laboration ska du vara bekant med den utvecklingsmiljö som du kommer att använda i kursen. Vidare ska du kunna skapa enklare html-dokument som du via en webbserver kan titta på publikt. Du kommer vidare att kunna valideras dessa uppladdade dokument.
Du kommer att få lära känna de enklaste html-taggarna så som p, h, ul lite bättre.
Du kommer vidare att öva på att länka mellan dokument med hjälp av a-taggen, lägga in olika typer av media, skapa tabeller och formulär.

## Förberedelse
Innan du kommer till laborationstillfället bör du vara så förberedd att du känner att du hinner genomföra och redovisa laborationen under det handledda tillfället. Du får givetvis göra laborationen helt klar i förväg och du har då möjlighet att utnyttja handledningstillfället för frågor och redovisning. 

Läs igenom **hela** laborationshandledningen innan du påbörjar laborationen.

## Genomförande
Utför laborationens uppgifter och moment samt dokumentera vad du kommer fram till på de olika delarna. Vid redovisning av laborationen ska du kunna besvara frågor om hur du har löst de olika delarna och varför de är lösta på det sätt du löst dem på.
När du anser dig vara klar med laborationen kontrollerar du att din källkod uppfyller laborationens samtliga krav.
Efter (minst) varje uppgift i denna handledning ska du göra en commit till ditt GIT-repositorie. (Se kursens webbplats och uppgift 1 nedan för mer information kring GIT)

## Plagiat
Laborationen ska genomföras enskilt. Du får givetvis fråga klasskamrater om hjälp men du ska skriva din egen kod och kunna svara för varför du skrivit din kod på det sätt du gjort. Vid fuskmisstanke lämnas misstankar samt berörda dokument över till universitetets disciplinnämnd.

## Föreslå ändringar
Denna handledning ligger på [GitHub](https://github.com/1ik415/Kursmaterial/blob/master/Laborationer/Laboration%201.md) om du vill föreslå ändringar eller hålla koll på vad de senaste uppdateringarna innebar.
 
## Uppgift 1.1 – Utvecklingsmiljön
Du ska i denna uppgift komma igång med den utvecklingsmiljö som du ska använda i kursen. 

Följande krav ställer kursen på utvecklingsmiljön:

* Git ska användas för versionshantering. Ett repositorie för hela laborationskursen.
* Du ska göra **minst** en commit per uppgift.
* GitHub ska användas för att ge kursledningen tillgång till ditt repositorie.
* GitHub-användaren "1ik415" ska vara "Collaborator" på repositoriet.
* GitHub-pages ska användas för att publicera den senaste versionen av dina laborationer.

Följande miljö rekommenderas från kursledningen men är inget krav:

* Cloud9 används som IDE (Integrerad Utvecklingsmiljö)
* Ditt GitHub-repositorie är publikt eller privat.

### Git och GitHub
Det första vi ska göra är att komma igång med git och sätta upp vår utvecklingsmiljö. Läs gärna igenom vår [Git-guide](https://coursepress.lnu.se/info/kom-igang-med-github/) innan du sätter igång.

1. Börja med att skapa ett konto på GitHub, med din "skol-epostadress" och gärna samma användarnamn som du har på ditt skolkonto. *Det går bra att använda ett befintligt GitHub-konto om du vill. Men se begränsningar nedan.* Kontot skaffar du på [http://github.com](http://github.com)
2. Ansök gärna om att få ditt GitHub-konto kopplat till en "utbilningslicens". *Detta kräver att ditt konto har skolans e-postadress.*
3. Skapa ett nytt repositorie, publikt eller privat. Döp det exempelvis till "1ik415-laborationer". *Om ditt användarnamn på GitHub är skilt ifrån ditt användarnamn på skolan behöver du också inkludera användarnamnet i repositorienamnet. Exempelvis: "1ik415-xx222yy-laborationer".*
![Skapa nytt repro, GitHub][github-add-repro]  
4. Lägg till användaren "1ik415" som medarbetare på repositoriet. 
Klicka in på repositoriet -> Settings -> Collaboraters
![Lägg till medarbetare, GitHub][github-add-user]
5. Skapa en README.md-fil i ditt repositorie i vilken du skriver lite kort om vad syftet med repositoriet är.

Du har nu skapat ett repositorie som kursledningen kan komma åt och titta i oavsett om det är publikt eller privat. Nästa steg är att skapa en "branch" som heter "gh-pages" och ta bort vår gren master så att den inte ställer till det för oss i början. Genom att använda grenen gh-pages gör att dina HTML-filer kommer att publiceras via GitHub-pages.

1. Gå in på ditt repositorie och klicka på knappen "branch: master". Lägg till "gh-pages".
![Lägg till branch, GitHub][github-add-ghpages] 
2. Klicka på "Settings" och välj att "gh-pages" ska vara "Default Branch".
![Sätt gh-pages som default branch, GitHub][github-default-branch] 
3. Radera grenen master genom att klicka på fliken "2 branch". Klicka på "View merged branches" och sedan "Delete branch" på raden med Master. ![][github-deletemaster]

Du är nu klar med inställningarna på GitHub och du kan sätta igång att koda. Vilken utvecklingsmiljö du använder nu är helt upp till dig själv, men vi rekommenderar den molnbaserade utvecklingsmiljön "Cloud9" för dig som inte redan har en utvecklingsmiljö igång som du hellre vill arbeta med. Handledningen är skriven utifrån Cloud9, men det är inga problem att göra laborationerna i en annan miljö.

### Cloud9
Cloud9 är en molnbaserad utvecklingsmiljö med stark koppling mot bland annat GitHub. Detta betyder att du kan låta Cloud9 klona ditt repositorie från GitHub och arbeta mot dina filer utan att du behöver hämta hem dessa filer till din lokala dator. Detta ger en stor fördel i att du enkelt kan påbörja arbete på en dator och avsluta på en annan utan att behöva flytta någon fil.

1. Se till att du är inloggad på GitHub. 
2. Gå till [](https://c9.io/) och välj att logga in via GitHub.
![Logga in på Cloud9 via GitHub][c9-login]
3. Acceptera att Cloud9 får komma åt ditt GitHub-konto.
4. Du kommer att klara dig bra på gratisvarianten av Cloud9 för kursernas skulle så klicka bort rutan om att uppgradera till en 
betalningsplan.
5. Du bör nu se ditt GitHub-repositorie i vänstermenyn. Klicka på det.
6. För att klona repositoriet till Cloud9 så att du kan börja editera dina filer så klickar du på "Clone to edit".
Du får välja om du vill ha ditt projekt öppet eller privat. Vilket som går bra.
7. Allt klart. Börja editera genom att klicka på "Start editing".

### Cloud9 och GitHub
Cloud9 har inget stöd i för Git i det grafiska gränssnittet utan du måste arbeta med kommandoprompten, terminalen, när du gör commits och trycker dina ändringar till GitHub. 

Terminalen i Cloud9: ![Cloud 9 - terminalen][c9-terminal]

Eftersom vi valt att arbeta med grenen "gh-pages" i GitHub så bör också denna gren vara förvald när du startar Cloud9. Du kan se vilken gren som är vald genom att se vad som står inom (paranteser) i kommandotolken. Står det 

`….. (gh-pages) $ _` 

så är allting rätt. Har du valt att inte radera din gren "master" så kommer troligtvis denna vara vald av Cloud9. I så fall kan byta gren genom att skriva:

`git checkout gh-pages` och tryck enter.


**TODO:** Lägg till information om .gitignore för att gömma .c9revisions-katalogen

Öppna nu filen "README.md" och gör någon förändring i denna och spara dina ändringar.

Vi ska nu göra en "commit" samt synka våra ändringar till GitHub. 

1. Skriv: `git add .` i terminalen och tryck enter. *Eventuellt nytillagda filer läggs nu till till versionshanteringen. Även några filer från Cloud9s konfiguration läggs till men vi bryr oss inte om det i nuläget.*
2. Gör en commit genom att exekvera (*skriva och trycka enter*) kommandot: `git commit -am 'Min första commit!'`
3. Synkronisera med GitHub-repositoriet genom att exekvera kommandot:
`git push`

Nu kan du gå till GitHub och kontrollera att alla ändringar du gjort i din readme-fil också finns på GitHub. 
Steg 1 till 3 ovan ska du göra efter varje uppgift i denna handledning. Det gör att du får spårbarhet i din kod och enkelt kan gå tillbaka till tidigare versioner av din kod. Du kommer att lära dig mer om versionshantering i kommande kurser, men detta räcker för att komma igång.

Du är nu redo att köra igång och koda! För att testa och se resultatet av ditt kodande så kan du klicka på "Preview" i Cloud9. Då ser du förändringar så fort du sparar ett dokument.

 
## Uppgift 1.2 – Ett första dokument
Under kursens laborationer kommer du steg för steg att bygga upp en blogg, eller enklare hemsida som ska kunna användas för att bland annat presentera laborationer på. 

Det första steget vi ska ta nu är att skapa ett första html-dokument som kommer att innehålla en presentation över dig, vad du gjort tidigare etc. 
Du är fri att själv forma innehållet men det vore intressant att bland annat få veta följande:

* Intressen
* Familj
* Vad du är bra respektive mindre bra på
* Tidigare utbildning?
* Arbetslivserfarenhet?
* Har du programmerat tidigare?
* Vad fick dig att söka utbildningen?
* Tankar inför framtiden?

Denna sida döper du till "presentation.html". Sidan ska placeras i en katalog som du döper till "pages". 
 
I presentation.html ser du nu till att skriva den html-kod som behövs för att uppnå nedanstående krav.

För att uppgiften ska vara godkänd ska ditt dokument minst innehålla följande:

* Element för att dokumentet ska validera enligt HTML5
* Två rubriknivåer
* Text separerad med hjälp av paragraftaggar. 
* Samtliga listor. (ol, ul, dl)
* Minst en lista som ligger inuti en annan lista.
* Minst en kommentar

När du testat sidan och känner dig klar så ska du:

1. Göra en commit i git. (`git add .` följt av `git commit -am 'Meddelande'`)
2. Göra en synkning mot GitHub. (`git push`)

4. Testa att validera ditt dokument. 

### Validera
Du validerar ditt dokument genom att skriva in adressen till dokumentet i validatorn på http://validator.w3.org/

Adressen till ditt dokument hittar du i "Preview-fönstret" i Cloud9. 

Ta till vana att validera ditt dokument ofta, speciellt om du inte kodat speciellt mycket HTML tidigare. Då kan du fånga upp fel tidigt, innan din kodbas blir stor. Det gör det lättare för dig att fånga upp och förstå felen. Ju mer van vid HTML du blir, desto mer sällan behöver du validera.

 
## Uppgift 1.3 – Startsidan
Du ska nu göra din startsida som kommer att fungera som en form av blogg för att presentera uppgifter som du gör i kursen. 

Skapa dig en ny html-sida som du döper till index.html och som du publicerar direkt i root-katalogen på ditt lokala repositorie. 

Skapa nu en lämplig rubrik för din sajt och skriv ett första blogginlägg, komplett med rubrik och stycken. Tänk redan nu på att du kommer att skapa flera inlägg under kursens gång.

Ett exempel på hur detta kan se ut:
![alt text][rubriker] 

Observera! Tänk inte i detta skede alls på presentationsdetaljer. Kanske vill man ändra färg på texten, ändra typsnitt, ha kursiv text etc. **Detta är inget vi ska bry oss om i detta skede.** Det viktiga nu är att vår kod är så semantisk och välskriven som möjligt.

**Validera nu och gör en commit till git.**

### Vanliga frågor:
**F:** Måste jag använda de filnamn som används ovan? 
**S:** Ja. Det finns en poäng med att vi döpt filerna som vi gjort och lagt dem i underkataloger. Det är ok att exempelvis döpa filer till engelska namn och lägga dem i andra underkataloger, men du ska ha en katalogstruktur.

**F:** Får jag redan nu använda andra taggar eller css? 
**S:** Ja, så länge som resten av kraven är uppfyllda är detta okej. De taggar som du eventuellt lägger till ska användas på korrekt sätt!

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
![Föreslagen filstruktur][lankstruktur2]

Som du ser kan du redan nu skapa katalogerna "pics" och "videos" som kommer att användas i senare uppgifter.
### Intern länkstruktur
Du ska nu bygga upp sajtens länkstruktur. För att göra sidan så användarvänlig som möjligt ska vi se till att samtliga sidor i sajten länkar till varandra.

Exempel:
Användaren surfar in till sidan index.html. Denna sida innehåller länkar till "presentation.html", "laborationer.html", "kontakt.html". 
Användaren klickar på länken till sidan "presentation.html" och tas till sidan. Väl där ser användaren samma meny som på startsidan. Se bilder nedan.

Bygg nu upp länkstrukturen på dina sidor enligt beskrivningen ovan. 
Länkarn ska ligga i en osorterad lista.
Menyn ska se likadan ut oavsett vilken sida man besöker. På exempelsidorna har även en "tagline" lagts till under huvudrubriken. 
![Exempel på utseende][lankar]

**Gör en commit till git.**

### Laborationsportal
Du ska nu bygga upp en struktur för presentation av dina laborationer. Detta gör du i filen laborationer.html. 
På sikt ska flera kurser kunna samsas på denna sida. Du behöver alltså tänka på detta när du bestämmer dina rubriknivåer. 

När du skriver denna sida ska du få fortsatt träning på att använda olika listor. Listorna ul, ol och dl ska samtliga användas på sidan. Nedan ser du ett exempel på hur du kan lägga upp din sida:

![Exempel på utseende][labbportal]

Den osorterade listan direkt under kursrubriken ska ha ankarlänkar direkt ner till respektive laborationsrubrik. Alltså: Om man klickar på "Laboration 2" så ska webbläsaren 
scrolla ner till rubriken "Laboration 2". 

Lägg till frågorna och svaren på frågorna från 1.4.

**Gör en commit till git**

### Externa länkar
Du ska nu modifiera din sida presentation.html något. Du ska här lägga in minst tre länkar till externa webbplatser. Detta kan vara länkar till bloggar du följer, företag du arbetat på och så vidare. Lägg till länkarna på ett lämpligt sätt.

**Gör en commit till git**

## Uppgift 1.6 - Bilder
Du ska nu testa på att infoga bilder på din sajt. Du ska lägga till bilder i följande bildformat:

* jpeg
* png
* svg

### Presentation, jpeg
På din presentation ska du nu på lämpligt ställe lägga till ett fotografi, eller motsvarande, på dig. Vill du inte lägga upp en bild på dig själv går det bra med ett annat fotografi, så länge som du själv har rättigheterna till fotot eller använder icke upphovsrättsskyddat material.

Fotot som du ska länka in ska du lägga i katalogen:
*pics*
som du får skapa själv. (Se 1.5)

Bilden ska länkas in med en **relativ sökväg**.

När det är gjort ska du ifrån din laborationsportal göra en **ankarlänk** som tar dig till sidan "presentation.html" och skrollar användarens webbläsare till bilden.

### Startsidan, png
PNG-formatet lämpar sig utmärkt för bilder med statisk grafik så som logotyper, ikoner etc. Du ska nu göra en logotyp till din sajt. Denna logotyp ska du placera på förstasidan, index.html. 

Du är fri att välja vilket grafiskt verktyg som du önskar. Exempelvis lämpar sig det webbaserade http://pixlr.com utmärkt om du vill göra enklare bildbehandling. 

Inget krav på konstnärlig förmåga finns.
Även denna bild placeras i katalogen *pics* och länkas in med en relativ länk.

När du är färdig så ska du ifrån din laborationsportal länka direkt till bildfilen, alltså inte till startsidan.

### Laborationssidan, svg
Du ska även prova på att skapa en bild med hjälp av vektorgrafik. Använd exempelvis det webbaserade verktyget http://code.google.com/p/svg-edit/
Skapa en vektorbaserad bild och länka in i ett nytt blogginlägg på din startsida. Länka till blogginlägget från "Uppgift 1.6" på laborationssidan.

**Gör en commit till git**

## Uppgift 1.7 – Video

Det enklaste sättet att tillhandahålla video till användarna av din sajt idag är att använda externa tjänster som Vimeo eller YouTube. Men i och med HTML5 och video-taggens intåg kommer det bli enklare att infoga video på sajter utan att vara beroende av en tredje part. 

I denna uppgift ska du få testa på att länka in en video med hjälp av video-taggen. På sajten http://www.bigbuckbunny.org finns videofiler i olika format som du kan ladda ner för att testa i denna uppgift. Ge dock en länk tillbaka till Big Buck Bunny som tack för lånet (Se CC-licensen). 
**Obs! Använd de [trailers](http://www.bigbuckbunny.org/index.php/trailer-page/) som finns då dess filstorlek lämpar sig bra för att skicka upp i ditt github-repro.**

Det går även bra att ta egna videoklipp om du så önskar.

Skapa nu ett nytt blogginlägg på startsidan och lägg där upp filmen.
* Det ska gå att starta stoppa filmen med hjälp av inbyggda kontrollerna
* Filmen ska inte starta automatiskt när man går in på sidan
 
![Resultat][video]

Som vanligt och i samtliga kommande uppgifter länkar du sedan till detta inlägg från laborationssidan.

**Gör en commit till git**

## Uppgift 1.8 – Tabeller
Uppgiften går ut på att konstruera en tabell innehållande ditt studieresultat under kursen. Tabellen placeras lämpligtvis på sidan laborationer.html efter ankarlänkarna under rubriken "Webbteknisk introduktion".

Här ser du hur tabellen ska se ut:
![][table]

Observera att nedre raden enbart har en cell samt att exempelvis cellen "2" under rubriken "Laboration" spänner över samtliga uppgifter för den laborationen.

* thead, tbody och tfoot ska användas på korrekt sätt.

Du får använda attributet `border='1'` på tabelltaggen för att få stödlinjer kring tabellen. Detta kan vi sedan byta ut mot stilegenskaper med css. 

**Gör en commit till git**

## Uppgift 1.9 - Formulär
Som sista steg i denna laboration ska vi nu ta oss an sidan "kontakt.html".

Några krav på formuläret:

* Metoden som ska användas är post
* Ett textfält finns
* En grupp med radioknappar eller kryssrutor används 
* En dropdownlista finns 
* En submit-knapp finns
* Fieldsets och tillhörande legend ska användas för att strukturera upp formuläret.

![][form]
 
För att testa formuläret så skickar du formulärdatan till sidan:
[http://voyager.lnu.se/tekinet/kurser/dtt/wp_webbintro/form.php](http://voyager.lnu.se/tekinet/kurser/dtt/wp_webbintro/form.php)

Ovanstående sida skriver automatiskt ut de namn-/värdepar som skickats från formuläret. Detta fungerar bara om du använder rätt metod, det vill säga post.

*(Om du själv har möjlighet kan du skicka formulärdatan till ett eget  serversideskript som läser ut datan och presenterar den.)*

**Gör en commit till git samt en push mot GitHub**

## Postludium
Du har nu genomfört laboration 1. För att du senare enkelt ska kunna gå tillbaka och se hur koden såg ut när genomfört laboration 1 ska du göra något som kallas för en tag eller release. 

1. Logga in på GitHub och gå till repositoriet för laborationen.
2. Kontrollera att dina senaste ändringar finns tillgängliga på GitHub.
3. Klicka på "releases" ovanför fillistningen.
4. Välj att skapa en ny release.
5. Se till att "Tag version" blir `l01` (Ludvig, nolla, etta).
Titel och description fyller du i som du själv vill.
![GitHub Release][github-release]
6. Publicera releasen

Se till att i fortsättningen göra ovanstående för samtliga laborationer (tag: l02, l03 etc.) när de är genomförda. Du kan nu fortsätta att arbete på laboration 2 och du har alltid en genväg för att gå tillbaka och se hur laboration 1 såg ut innan förändringarna som laboration 2 innebär.
Kursledningen kan också på ett enkelt sätt överblicka klassens progression på de olika laborationerna.

Var så god att påbörja arbetet med laboration 2!


[rubriker]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/1.png

[filtrad]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/filetree.png

[lankstruktur]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/linkstructure.png

[lankstruktur2]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/linkstructure2.png

[lankar]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/links.png

[labbportal]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/laborationsportal.png

[video]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/video.png

[table]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/table.png

[form]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/form.png

[github-add-repro]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/github-add-repro.png

[github-add-user]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/github-add-user.png

[github-add-ghpages]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/github-add-ghpages.png

[github-default-branch]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/github-default-branch.png

[github-release]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/github-release.png

[github-deletemaster]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/github-deletemaster.png

[c9-login]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/c9-login.png

[c9-terminal]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/c9-terminal.png
