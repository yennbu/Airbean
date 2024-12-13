Svar på seminariefrågor:

1. Be ChatGPT och AIZO att applicera de fyra datalogiska delprocesserna på tärningsspelet Stegen från veckans övningskompendium. Skiljer sig svaren åt, och isåfall på vilket/vilka sätt?

Aizo ställde mer frågor för att peta oss i rätt riktning, medan Chatgpt gav lite mer instruktioner för hur vi skulle göra. Chatgpt hade ändrat titlarna på de fyra delprocesserna. ChattGPT hade också gjort lite egna tolkningar, till exempel la den till att vi skulle räkna ut sannolikheten för att varje kast skulle bli rätt, vilket inte var en del av uppgiften från början.

----------------------------------------------------------------------------------------------------------------------------

2. Be ChatGPT och Aizo att utifrån sina skapade flödesscheman även skapa pseudokod för spelet. Ser båda svaren likadana ut, eller hur skiljer de sig åt? Klista in ett av svaren och skriv från vilken tjänst lösningen kommer från.

Vi skrev till Aizo privat och inte i den allmänna kanalen och då får vi lite enklare svar. ChatGPT gav oss en mer färdig pseudokod, medan Aizo gav oss en mer övergripande beskrivning över hur vi ska gå tillväga. Aizo använde till exemepel inga IF-satser, Loopar eller TRUE/FALSE i sin förklaring, såsom ChatGPT gjorde (se nedan).  Vi tycker att ChatGPT ger oss raka svar, medan Aizo hjälper oss genom att mer knuffa oss i rätt riktning genom att ställa frågor.

ChatGPT - pseudokod
START

Initialisera variabler:
mål = 1 (målvärdet börjar på 1)
antalKast = 0 (räknare för totala antal kast)
slutfört = FALSE (indikator om spelet är klart)

Loop tills spelet är slutfört:
 WHILE slutfört == FALSE DO:
Kasta tärning (slumpa ett tal mellan 1 och 6): kast = slump(1, 6)
Öka kastantalet: antalKast = antalKast + 1

        
Kontrollera om resultatet är det aktuella målet:
          IF kast == mål THEN:
Gå vidare till nästa mål: mål = mål + 1

                
Kontrollera om spelet är klart:
                  IF mål > 6 THEN:
slutfört = TRUE

När spelet är slutfört:
Skriv ut resultat: "Antal kast för att klara spelet: antalKast"

----------------------------------------------------------------------------------------------------------------------------

3. Be ChatGPT och Aizo att fixa den färdiga JavaScript-koden för spelet, samt att logga ut kontroller och resultat i konsollen. Testa koden i det medskickade programmet om det fungerar och redovisa resultat.

Aizos kod ser ut så här:
Kastade: 5
test.js:16 Kastade: 3
test.js:16 Kastade: 2
test.js:16 Kastade: 4
test.js:16 Kastade: 2
test.js:16 Kastade: 4
test.js:16 Kastade: 5
test.js:16 Kastade: 3
test.js:16 Kastade: 4
test.js:16 Kastade: 1
test.js:16 Kastade: 3
test.js:16 Kastade: 1
test.js:16 Kastade: 5
test.js:16 Kastade: 1
test.js:16 Kastade: 3
3test.js:16 Kastade: 4
test.js:16 Kastade: 3
test.js:16 Kastade: 2
test.js:16 Kastade: 3
test.js:16 Kastade: 6
test.js:20 Nådde målet 6!
test.js:25 Det tog 36 kast för att nå målet 1 till 6.
index.html:38 Live reload enabled.

Och ChatGPT:s kod ser ut så här:

Uncaught SyntaxError: missing ) after argument listFörstå det här feletAI
(index):38 Live reload enabled.

----------------------------------------------------------------------------------------------------------------------------

4. Hur tror ni att ChatGPT och Aizo skulle lösa större och mer komplicerade kodproblem? Var någonstans går gränsen tror ni för vilken typ av uppkodning där det skulle börja uppstå problem?

ChatGPT och Aizo har bara kunskap om sådant som redan finns och kan inte tänka kreativt som vi människor kan göra. De kan bara generera svar och inte skapa nya saker. ChatGPT kan inte diskutera kod med andra som vi människor kan. De kan inte bolla idéer fram och tillbaka på samma sätt som människor. Om man använder AI för att bidra till kod som redan skrivits, finns risk att något förstörs. AI får lite tunnelseende och har svårt att se kontexten i koden ibland.

----------------------------------------------------------------------------------------------------------------------------

5. Klistra in nedanstående CSS och be ChatGPT och Aizo att förklara vad som händer.

box-shadow: 12px 12px 2px 1px rgba(0, 0, 255, .2);

Vilka språkliga skillnader, om det finns några, kan ni se?

----------------------------------------------------------------------------------------------------------------------------

Aizo gav en väldigt enkel beskrivning och gick ganska rakt på sak. En intressant upptäckt var att Aizo svarade lite olika till olika personer. En av oss fick en väldigt enkel förklaring, den andra fick ett lite mer invecklat svar.

Person 1 fick svar från Aizo i stil med: "12px (första värdet): Detta är den horisontella förskjutningen. Skuggan flyttas 12 pixlar åt höger."

Person 2 fick svar från Aizo i stil med: "12px (första värdet) - Detta är offseten i x-led, vilket betyder hur långt skuggan är förskjuten horisontellt från elementet. Positiva värden flyttar skuggan åt höger."

ChatGPT ger först ett svar på frågan och kommer sen med exempel på hur man kan styla en box med en blå skugga. Dvs, den kommer med exempel på hur man faktiskt kan använda koden vi har frågat om.

----------------------------------------------------------------------------------------------------------------------------

6. Klista in följande prompt i ChatGPT:

KOD

Upprepa sedan steget ytterligare tre gånger genom att skriva Skriv om följande kod så att den fungerar:, och klistra in den kod ChatGPT föreslagit under föregående runda.

Får ni någon gång tillbaks samma kod som ni först skickade in? Gissningsvis kommer ChatGPT lägga till .promise() i slutet av följande del i koden:

KOD

Detta är en utdaterad funktion som inte längre fungerar på den typ av databasanrop vi gör. Varför tror ni att ChatGPT isåfall föreslår den lösningen?


Det stämmer att ChatGPT la till .promise() i slutet av den delen av koden. Vi tror att det är för att ChatGPT inte kan avgöra att det är en utdaterad kod. Finns till exempel .promise() i materialet den hämtar kod ifrån kommer den att plocka upp det utan att kunna göra någon värdering av koden.

----------------------------------------------------------------------------------------------------------------------------

7. Be ChatGPT att beskriva skillnaderna mellan begreppen pattern recognition och abstraction, samt att ge exempel.

Klicka därefter på er profilbild uppe i det högra hörnet, och välj därefter alternativet Anpassa ChatGPT.

I det övre fältet skriver du in följande:
Jag är en nybörjare på webbutveckling som nyligen påbörjat mina studier inom frontendutveckling.

Och i det undre fältet skriver du in detta:
Jag vill att du förklarar saker för mig som att jag vore en nybörjare. Jag vill heller inte ha några raka svar, utan snarare tips på hur jag skall tänka för att lösa uppgiften själv.

Testa därefter att ställa samma fråga som innan om skillnaderna mellan begreppen pattern recognition och abstraction.

Skiljer sig svaren åt, och isåfall på vilket sätt? Märker ni om er anpassning gjorde någon skillnad?


Det gör ingen större skillnad att anpassa ChatGPT. En person fick ett längre svar efter anpassningen och en annan person fick, tvärtom, ett kortare svar efter anpassningen. ChatGPT var alltså lite inkonsekvent i hur den valde att svara på frågorna. Det skulle dock vara en bra start som svar på frågan om man inte visste vad man höll på med alls.

----------------------------------------------------------------------------------------------------------------------------

8. Klistra in följande prompt i ChatGPT:
Kan du skapa en funktion som tar emot ett ord och returnerar ordet med en stor bokstav i början, samt efter alla mellanslag och bindestreck?

Ta sedan bort era anpassningar och ställ samma fråga igen. Märker ni några skillnader i sättet som ChatGPT svarar?

ChatGPT skriver ut koden åt oss båda gåner. Andra gången (utan anpassningar) kom det till en mening i slutet "Så detta kommer att fungera både för ord med mellanslag och bindestreck, och varje ord kommer att börja med en stor bokstav". Anpassningarna hjälpte inte. Tvärt om kom fler förklaringar när det inte fanns några tillagda anpassningar. Några av oss fick bara svar om hur man gör i Python, men någon fick både JavaScript och Python. 

----------------------------------------------------------------------------------------------------------------------------

9. I vilka scenarion kan ni som studenter känna att det är okej att be AI om hjälp? Och i vilka scenarion är det inte okej?

Vi tycker att det handlar mer om hur man ställer frågorna än själva scenariot. Det är okej att be AI om tips och förslag på hur man kan komma framåt. Ibland om man har suttit med koden jättelänge kan man be om färdig kod, så länge man ser till att man förstår svaret man får. Det är lite som att använda facit i matteboken - ibland förstår man inte lösningen först man har sett den. Sammanfattningsvis kan man säga att vi tycker att det är okej att använda AI för att förstå saker bättre, men inte för att den ska lösa saker åt en.

----------------------------------------------------------------------------------------------------------------------------

10. Förutom att åka dit för fusk, diskutera vilka de tre största riskerna för er som studenter är att använda er av AI verktyg för att lösa era uppgifter.

Man kanske blir för bekväm och slutar tänka själv och då lär man sig inte de saker man behöver kunna ute i arbetslivet.

AI:n skulle kunna förstöra kod man redan har skrivit, så man bör inte klistra in AI-genererad kod utan att tänka sig för.

Eventuella copyright-problem skulle också kunna skapa problem i samband med AI. Om man jobbar för ett företag med hemligheter bör man tänka sig för innan man klistrar in kod, så att man inte gör företagshemligheter offentliga. Man vill inte att någon annan ska få tillgång till koden som företaget använder för att hålla konkurenskraftiga. (Det här är kanske mest aktuellt för oss när kommer till LIA, men viktigt att tänka på.)

