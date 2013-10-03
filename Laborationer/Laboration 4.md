 
## Inledning
Denna laboration fokuserar helt och hållet på att göra justeringar av din sajt så att den kommer att fungera på mobila enheter. 

## Mål
Efter laborationen ska du:
- Kunna anpassa befintliga sajter för mobila enheter.

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
Denna handledning ligger på [GitHub](https://github.com/1ik415/Kursmaterial/blob/master/Laborationer/Laboration%204.md) om du vill föreslå ändringar eller hålla koll på vad de senaste uppdateringarna innebar.

## Uppgift 4.1 – En mobilare portal
Du ska i denna uppgift stila om din laborationsportal så att den lämpar sig att användas på en enhet med "mindre" skärm, exempelvis en iPhone eller en Androidtelefon. 

Går man in på sidan med en enhet som har en skärm som identifierar sig om smalare än 481 pixlar så ska man få en annan layout än vad som är fallet på en vanlig skärm. Tänk på att exempelvis iPhone och Androidtelefoner inte använder handheld-stilmallar utan identifierar sig som en skärm så du kommer att behöva jobba med CSS3 media queries för att kunna skapa en stilmall lämpad för smartphonen. 

![Liggande layout][mobile-landscape]

- Du ska skapa en anpassad stilmall för skärmar smalare än 481 pixlar.
- Samtliga sidor på din laborationsportal ska ha den anpassade stilmallen.
- Allt innehåll ska vara lika tillgängligt som tidigare. Det är designen som ska göras om. Dock kan du fundera på om visst innehåll ska tonas upp eller ner beroende på om man sitter på en mobil enheter eller inte.
- Den ordinarie stilmallen ska fortfarande användas om man går in med en enhet bredare än 480px.
- När användaren surfar in med en smartphone så ska man inte behöva zooma på sidan.
- Användaren ska inte behöva scrolla i x-led (horisontellt).
- Om användaren väljer att spara din sajt som en genväg från hemskärmen i iOS så ska du erbjuda en speciell ikon för detta.
- Arbeta igenom formuläret så att det lämpar sig för mobila 	enheter. 
- Utöver ovanstående ska din sida förses med en så kallad "favicon". ![Favicon][favicon]

![Menu][mobile-menu]

När du kodar ska du se till att göra flera commits. Gör en commit per problem som du löser i laborationen.

## Hur testa?

### Testa din webbsida med telefon
Har du en handhållen enhet är det givetvis enkelt att testa din webbsida.

### Testa din webbsida med en emulator
Om du sitter på en egen dator kan du installera en emulator för exempelvis Windows Phone, Android eller iPhone. 

* Windows Phone: [http://create.msdn.com](http://create.msdn.com) (Windows)
* Android: [http://developer.android.com](http://developer.android.com)
* iPhone: [http://developer.apple.com/technologies/tools/](http://developer.apple.com/technologies/tools/) (OS X)

Du kan sedan lägga upp din webbsida på en webserver och surfa in till sidan via emulatorns inbyggda webbläsare. Du får då se sidan så som den kommer att se ut på en skarp enhet.

Ingen emulator finns installerad på skolans datorer.


### Testa din webbsida utan telefon och emulator
Har du ingen telefon att testa på i närheten så kan du testa att allt fungerar någorlunda genom att temporärt plocka bort ordet "device" ur media querien:

Då kommer stilmallen istället att användas då webbläsarfönster är smalare än 481px. Du kan nu testa sidan genom att ändra storlek på ditt webbläsarfönster. När fönstret blir smalare än 481 pixlar bör din layout ändras.

Tyvärr kan du inte här se vad som händer om du inte anger metataggen för att styra viewport, men denna ska vara med ändå.

När uppgiften är slutförd så skriver du ett blogginlägg på förstasidan om hur du resonerat när du gjort om designen. 
Lägg in en bild i inlägget som visar sidan i sin "mobila" version.

## Postludium
Du har nu genomfört laboration 4 och du ska nu skapa en release för detta på GitHub.
Se till att "Tag version" blir `l04` (Ludvig, nolla, fyra).
Välj en lämplig titel.

Var så god att påbörja arbetet med laboration 5!

[mobile-landscape]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/mobile-landscape.png

[mobile-menu]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/mobile-menu.png

[favicon]: https://github.com/1ik415/Kursmaterial/raw/master/Laborationer/pics/favicon.png

