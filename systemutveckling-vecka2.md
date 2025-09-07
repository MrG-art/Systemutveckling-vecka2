# Systemutveckling – vecka 2

## Fråga 1: Skillnaden mellan vattenfall och agil metodik

När det kommer till Vattenfall så gör man en färdig plan som är detaljerad från början. Där alla funktioner i appen som till exempel inloggning, flöde, bilder, kommentarer och gilla knappar bestäms innan man ens börjar koda så att säga. 

Sen processen i sig då sker arbetet i fasta steg som följer varandra. Först till exempel samlar man in krav, sedan gör man sin design, efter det så är det utveckling, testning och till sist så levererar man produkten. Man går aldrig tillbaka och ändrar något i tidigare steg om man upptäcker problem eller nya idéer senare. 

Resultatet blir att appen blir färdig när allt är klart och testat, vilket är bra i sig. Men det finns nackdelar. Det kan ta lång tid innan appen kommer ut i Google App Store eller Apple Store, och appen riskerar att inte passa användarnas behov om dessa hinner ändras under projektets gång. Fördelen är att allt är tydligt planerat och dokumenterat.  

---

När det gäller Agile gör man en mer enkel och flexibel plan, där man delar upp appen i små delar, till exempel först logga in, sedan kunna lägga upp bilder och efter det kanske gilla-knappar. 

En flexibel plan innebär att man kan ändra saker under arbetets gång, till exempel om man får nya idéer eller feedback. Detta skiljer sig från Vattenfall. Processen sker i korta omgångar, så kallade sprintar. Man bygger och testar en liten del av appen åt gången. 

Man upprepar processen flera gånger: man bygger, testar, ändrar och förbättrar steg för steg. Detta gör att användare och utvecklare kan samarbeta nära med varandra och justera funktionerna under tiden. Resultatet blir att man får en enkel version av appen snabbt, som sedan utvecklas vidare bit för bit. På så sätt blir slutprodukten mer anpassad efter vad användare faktiskt behöver, även om man inte har lika mycket detaljerad dokumentation som i Vattenfallsmetoden.

(Denna text la jag till i branchen Agile-Vattenfall)

## Fråga 2: Vad är ett Git-commit och varför är det viktigt?

När det gäller ett Git commit så kan man säga att det är som att spara en version av sitt arbete. När man gör ett commit sparas alla de ändringar man har gjort tillsammans med ett kort meddelande där man skriver vad man har ändrat och så. Detta gör så att man alltid kan gå tillbaka till en tidigare version om något går fel och det gör också att man kan se vem som har ändrat vad i projektet. Det gör det enklare att vara flera personer som jobbar tillsammans och på samma sak utan att krocka. Ett exempel är om jag råkar ta bort en fil av misstag då kan jag gå tillbaka till ett tidigare commit och få tillbaka den filen igen.

(Denna rad lades till i branchen (Fråga-2-Commit)


## Fråga 3: Vad innebär samarbete med GitHub? Vad är pull requests, branches och merge?

När man samarbetar på GitHub kan flera personer arbeta på samma projekt utan att störa/förstöra varandras arbete. Man skapar en branch för att jobba på en egen del av projektet utan att röra main delen (Huvuddelen). När man är klar med sina ändringar så öppnar man en pull request, vilket betyder att man föreslår att ändringarna man har gjort ska läggas in i main såkallade huvuddelen då. Andra kan då läsa igenom, kommentera och sedan godkänna ändringarna. När alla är överens gör man en merge, alltså att man slår ihop branchen (mina ändringar) med main (Huvuddelen). På det här sättet kan flera personer jobba samtidigt, granska varandras arbete och hålla ordning på ändringarna i projektet utan att störa varnadras arbete.

(Denna rad lades till i branchen Q3-Samarbete)

