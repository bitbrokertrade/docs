# Source: https://docs.bitbrokertrade.com/trader-instellingen

For the complete documentation index, see [llms.txt](https://docs.bitbrokertrade.com/llms.txt). This page is also available as [Markdown](https://docs.bitbrokertrade.com/trader-instellingen.md).

![](https://docs.bitbrokertrade.com/~gitbook/image?url=https%3A%2F%2F845056123-files.gitbook.io%2F%7E%2Ffiles%2Fv0%2Fb%2Fgitbook-x-prod.appspot.com%2Fo%2Fspaces%252F-Ly4NKRJzL8JZvlE5PJs-887967055%252Fuploads%252FC4Z9sD7xGLPH5iuxdhwN%252FTrader%2520instellingen%25202-2-2022.JPG%3Falt%3Dmedia%26token%3Dba627fb6-2b80-43f2-aa4b-cb2b7ce4507d&width=768&dpr=3&quality=100&sign=c0895c03&sv=2)

#### Trader bewerken

_Naam_ Geef je trader een naam. Deze naam wordt door het dashboard gebruikt in je overzichten. Een voorbeeld voor een naam is: "Bitvavo BTC" In je naam is nu duidelijk welke exchange en welke munt worden gebruikt.

_Beurs_ Kies de beurs waaraan je de trader wil koppelen.

_Markt_ Kies de munt waarmee de trader moet handelen.

_Handelsstrategie_ Kies de te volgen strategie:

_Bitbrokertrade_ volgt een koerstrend (MACD) en doet alleen een _aankoop_ als de koerstrend omslaat van dalen naar stijgen. De strategie _verkoopt_ alleen als de koerstrend omslaat van stijgen naar dalen. BitBrokerTrade strategie handelt met candles van 15 minuten, dat houdt in dat maar eens per 15 minuten een aan- of verkoopmoment gegenereerd kan worden. Zie ook ons **YouTube** kanaal voor een toelichting hierop. _Updownstrategie_ handelt met candles van 1 minuut en volgt geen koerstrendberekening. Iedere minuut wordt een koers bepaald. Is deze koers hoger dan de vorige minuut, dan is het een aankoopmoment. Is de koers lager dan de vorige minuut, dan is het een verkoopmoment. De overige traderinstellingen bepalen of er ook echt aangekocht of verkocht wordt.

#### **Aankopen**

_Minimumpercentage tussen transacties_ Deze instelling geeft aan hoeveel koersverschil er tussen de individuele aankopen moet zitten. Simulaties wijzen uit dat een hoog percentage (standaard instelling = 6%) voorkomt dat in een dalende markt onnodig veel posities worden ingenomen. In een zijwaartse en opgaande markt heeft dat hoge percentage geen nadelige invloed.

_Stop aankopen boven_ Als je niet wil dat er boven een bepaalde koers wordt aangekocht, geef je hier een koersplafond in. Hoe doe je dat: Je kijkt als voorbereiding naar de huidige koers en naar de historische koersontwikkeling van de betreffende crypto munt. Als JOUW verwachting is of jij hebt het gevoel dat de koers van bijv. Bitcoin boven een bepaald bedrag een eenmalige piek is, dan wil je niet dat de trader posities inkoopt mocht de koers naar dat niveau stijgen. Je geeft dan een koersplafond van 3% daaronder als koersplafond op. Als je rendement nu lager is ingesteld dan 3% zal de trader zijn laatste inkoop altijd nog verkopen bij zo'n piekkoers en heb je maximaal rendement. Dat is de theorie achter de plafondkoers.

_Gemiddeld aankoopbedrag_ Normaal gesproken koopt de trader 18% van je vrije eurosaldo als positie in. Heb je 1.000 euro beschikbaar, dan is de eerste aankoop dus 180 euro. Vind je die bedragen te hoog of te laag, dan kun je hier het gewenste bedrag ingeven wat de trader mag aankopen. Bijvoorbeeld € 200. De trader koopt dan altijd gelijke bedragen van 200 euro in. _De minimum transactiegrootte is € 25,-._

_Maximum open aankopen_ Je kunt per trader ingeven dat er een maximum aantal posities voor de desbetreffende munt open mag staan. In combinatie met "het gemiddelde aankoop bedrag" kun je dus een precieze limiet zetten op hoeveel geld je per munt wilt investeren. **Je kunt deze optie ook gebruiken om de trader opdracht te geven een munt ‘leeg’ te verkopen zonder nieuwe aankopen te doen.** Je doet dat **door een 'nul' in te vullen**. De trader verkoopt dan nog wel, maar doet geen nieuwe aankopen meer.

#### Verkopen

_Minimum winstpercentage_ De trader gebruikt dit percentage om te beoordelen wanneer hij een positie mag verkopen. Als er vanuit de gekozen strategie een verkoopsignaal wordt gegenereerd, dan kijkt iedere trader individueel of het signaal voor hem van toepassing is. Dit percentage moet dus hoog genoeg zijn om winst te maken. Geef je 5% in, dan zal de trader relatief weinig transacties doen. Immers, koersschommelingen van 5% zijn minder frequent. Geef je hier 1% in, dan profiteer je van een groter volume aan transacties en heb je misschien wel een beter totaalrendement. Hou er rekening mee dat bijna alle beurzen 0,25% aankoop en 0,25% verkoopkosten berekenen. Dus dat betekent dat je pas vanaf een rendementspercentage van 0,5% ook echt winst maakt.

_Winststrategie_ Je kunt hier kiezen tussen "Herinvesteren" en "HODL" **Herinvesteren** betekent dat als je positie verkocht wordt, het volledige bedrag terugvloeit naar je eurosaldo en weer gebruikt gaat worden om nieuwe posities in te nemen. **HODL** betekent dat bij verkoop van de positie alleen het oorspronkelijk aankoopbedrag wordt omgezet naar euro's. De winst op de positie blijft in de cryptovaluta staan.

_Stoploss percentage_ De stoploss functie is een soort noodrem. Je geeft hier het percentage verlies in waarop jij de positie niet meer wil aanhouden. Zodra het negatieve rendement op de positie dit percentage bereikt, neemt de trader verlies en verkoopt de positie. **Let op**: Wij bieden deze functie aan omdat gebruikers erom vragen. In **alle** testen op historische data (tot 12 maanden terug) zorgt deze functie voor een veel lagere rentabiliteit, en vaak zelfs tot verlies op je totaal investering.

[PreviousWat is een Trader?](https://docs.bitbrokertrade.com/traders/wat-is-een-trader) [NextInlezen exportbestand in Excel](https://docs.bitbrokertrade.com/overig/inlezen-exportbestand-in-excel)

Last updated 2 years ago