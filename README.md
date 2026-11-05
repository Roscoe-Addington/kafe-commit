## Kafé Commit — Grupp 6

## Roller
- Scrum Master: Roscoe Addington
- Utvecklare: Adam Skauby, Meriem Mehamednur Abdu, Oliwier Nith och Roscoe Addington

## Tavla
Länk till Google Kalkylark/Docs: 
https://docs.google.com/spreadsheets/d/1XjG5ejIh38ODOgbafnrCVyD-qMCwSQjKaaqveQOJi-s/edit?gid=1000163782#gid=1000163782

## Sprintmål
Kunderna ska kunna se Kafé Commits webbsida tydligt och den ska visa kaféets adress, vad en kopp kaffe kostar och att det finns wifi, så att man kan hitta dit, bedöma priset och jobba eller plugga på plats. Det ska också finnas ett telefonnummer för frågor som inte besvaras på sidan eller i menyn, och information om nötter hanteras i lokalen, så att föräldrar till allergiker kan avgöra om kaféet passar familjen. Kunderna vill dessutom se om det finns gratis parkering, aktuella erbjudanden, eventkvällar och dagens vegetariska soppa, samt vilka betalningsmöjligheter som finns och om det finns ett kundkort med rabatter eller gratis kaffe. Slutligen ska sidan visa att lokalen är rullstolsanpassad, med möjlighet att välja en tillgänglig sittplats, och att uteserveringen bara är öppen maj–september.

## Daily standups

### [Datum: 3/11/26 - Tisdag]

- Adam: Formulerade user stories igår. Gör idag: 1-2 User stories från backlog till granskning. Han ser inga hinder. 
- Oliwier: Formulerade user stories igår. Gör idag: 1-2 User stories från backlog till granskning. Han ser inga hinder. 
- Roscoe: Formulerade user stories igår. Gör idag: 1-2 User stories från backlog till granskning. 
- Meriem: Ej närvarande! Hennes dotter var sjuk. 

### [Datum: 4/11/26  - Onsdag]
- Adam: Har gjort två funktioner och godkänt pull request. Gör idag: 1-2  funktioner och tittar på pull request. Har ej några hinder.
- Oliwier: Gjorde alla sina funktioner och mergerade. Gör idag: Gör om delar av sina funktioner och merger ej. 
Han har ej några hinder.
Meriem: Har skapat branches. Pushat till GitHub, skapat pull requests. Gör idag: Gör om felet som uppstod vid branch skapandet. Har inga hinder inför detta. 
- Roscoe: 1-2 funktioner. README dokumentation. Gör idag: 1 funktion, PR och merger.
Har inga hinder. 
### [Datum: 5/11/26  - Torsdag]
- Oliwier: Fixade branches. Gör idag: Har haft problem med branches och försöker få ordning på dem. Det som skulle vara ett hinder är om han ej fick assistans för att åtgärda problemen med GitHub. 
- Meriem: Problem med repo/GitHub. Försökte reda ut det utan framgång. Gör idag: Fixa user stories så att de kommer på rätt plats i repot. Hinder, det är fel på repo.
- Adam: Pratat med Linus om problem med GitHub och repo. Gör idag: Försöker bli klar med user stories och retrospektiv ikväll. Hinder: Om vi inte får hjälp tidigt. 
Roscoe: Stötte på problem med GitHub. Försökte åtgärda problemet utan framgång.  Gör idag: Fortsätter felsöka, åtgärda problem med GitHub, få user stories på rätt plats i repot på GitHub.
Hinder: Om jag inte får hjälp att förstå vad felet är med GitHub. 
## Retrospektiv
- Start: Ska skydda main för att minimera fel. Att det uppstår fel på main upplevde vi fördröjde sprinten. 
- Stop: Se ovan. Det gjordes pushar i fel branch.
- Continue: Vi hade en väldigt bra dialog i gruppen, ingen var otrevlig, alla fick komma till s
- Konkret förbättring: Det är viktigt med tydlig och kontinuerlig kommunikation. 

## Teorifrågor
1. “Agil utveckling är att bygga mjukvara i små steg, få feedback ofta och anpassa arbetet till situationen. Till exempel fick vi problem med GitHub och behövde be läraren om hjälp, så vi prioriterade om och fixade repot innan vi fortsatte med featurerna. Vårt arbete delades upp efter användarens behov i form av user stories som vi delade upp i ett flöde på en tavla med ansvariga utvecklare, vi hade daily standups för att få uppdateringar om hur arbetet gick. Varje feature byggdes separat på sin egen branch och lades in i main när den var klar, vilket gjorde att vi levererade i små steg. Vi fick snabb feedback genom samarbete och kodgranskning i teamet.  I slutet av arbetet hade vi ett retrospektiv för att utvärdera hur arbetet i teamet hade gått, till exempel insåg vi att det vore bra att skydda main branch om man arbetar i team, vilket visar hur vi skulle förbättra arbetssättet till nästa gång. 
2. Den enda Scrum-roll vi använde var Scrum Master, vi övriga var “bara” utvecklare, de moment vi använde oss av var Daily, Sprint, samt Retrospektiv, detta fungerade bra i vår grupp, Daily Stand-up gav oss bra info om hur vi låg till och om de fel som uppstod, Sprinten var lagom för det arbete vi skulle utföra, Retrospektivet 
3. För svar på denna fråga använder vi oss av user story 3: Som kund vill jag kunna se kaféets adress för att veta hur jag tar mig dit. Denna berättelse kopplades ihop med en ansvarig utvecklare under statusen "att göra". Den flyttades sedan till "pågår", där utvecklaren skapade en egen branch från main med `git switch main` , `git pull`, `git switch -c feature`. Lade till ändringar i koden och trackade ändringarna genom `git add file name`, sparade en ögonblicksbild av ändringarna i historiken med ett meddelande med `git commit -m`, och körde `git push -u origin feature`. Skapade en pull request (PR) på GitHub från utvecklarens branch till main. Koden granskades av en kollega som tittade efter fel, men det uppstod tekniska problem med GitHub på main innan vi kunde merge. Det var filer som inte skulle vara där. Vi tog bort dem, mergade in på  main och kortet flyttades till klart.
4. Merge-konflikt är när det händer att två eller flera personer har ändrat på samma filen samtidigt, då blir det merge-konflikt. Hur löser man det man löser det genom att öppna filen på GitHub och vilken text som ska vara kvar,ta bort de extra markeringarna och spara ändringar.

## Personlig reflektion

### Adam
Det var lärorikt med de fel som uppstod, både de bitar där vi behövde be om hjälp och de bitar som vi lyckades klura ut på egen hand. Framgent ser jag gärna att alla vi som är nybörjare tänker efter, och kollar att vi är på rätt ställe, ett varv extra innan vi pushar upp eller mergar något.
### Roscoe
Det är viktigt med kommunikation och att hålla en god ton. Jag upplevde att samarbetet fungerade bra. Vi löste problem som uppstod tillsammans. Team work makes the dream work! 🙂
### Meriem
Det var jättejobbigt att skicka rätt mapp. Det största felet som jag gjorde var att jag kopplade först till min egen repo och ta tid tills vi fixade allt tillsammans. Annars tycker jag att allt gick bra med kommunikationen och tar ansvar för arbetet. Examinationen var verkligen lärorik och givande tycker jag. 

### Olwier
Det var viktigt med att läsa instruktioner och anpassa så att man inte jobbar för snabbt så att man förstör för sig själv och andra. Det är bra att kompensera till sina jobbkamrater och veta vad man ska jobba mot. 





