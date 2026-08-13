# Source: https://www.bitbrokertrade.com/support

Vragen?

# Hoe kunnen we je helpen?

![Search Icon](https://www.bitbrokertrade.com/images/zoeken.svg)

Zoek in de kennisbank

![Message Icon](https://www.bitbrokertrade.com/images/bericht.svg)

Bekijk de FAQ’s

![Downloaden icon](https://www.bitbrokertrade.com/images/downloaden.svg)

Download de handleiding

![Mail icon](https://www.bitbrokertrade.com/images/mail.svg)

Mail 
support

## Zoek in de kennisbank

Zoeken

## Bekijk de FAQ’s

[01]()

### Hoe wordt de grootte van een transactie bepaald?

De transacties beslaan altijd 18% van het openstaande euro saldo op jouw beurs. De kleinste transactiegrootte die wij hanteren is € 25,-. Op trader niveau kun je met de instelling "Gemiddeld aankoopbedrag" zelf de grootte van de aankooptransacties ingeven.

[02]()

### Wat is het minimale inleg bedrag in Euro

Om de trader te laten werken kun je al vanaf € 25,- beginnen. De trader kan met dit budget 1 of 2 transacties aankopen (afhankelijk van welke munt je kiest) en daarmee strategische posities innemen. De transacties beslaan altijd 18% van het openstaande euro saldo. De kleinste transactiegrootte die wij hanteren is € 25,-. Dit is per munt verschillend (de exchanges hebben verschillende regels per munt).

[03]()

### Ik wil graag direct al mijn geld uit de exchange halen. Is dat mogelijk en zo ja, hoe werkt dat?

Je hebt in BitBrokerTrade altijd de mogelijkheid om alle pockets handmatig te verkopen middels de daarvoor bedoelde button achter de pocketregel. Als alle pockets verkocht zijn, deactiveer je de trader in het daarvoor bedoelde 'trader aanpassen' scherm. Daarna ga je naar je exchange en boek daar je gelden over naar je eigen bankrekening. Al deze acties kun je binnen een kwartier uitvoeren.

[04]()

### Kan ik ook de werking van de trader eerst uitproberen zonder geld in te zetten?

Ja dat kan! Je maakt een account aan bij BitBrokerTrade en je slaat de stappen m.b.t de exchange over. Je gaat direct naar "Instellingen", "Beurzen" en vervolgens "Beurs toevoegen". Kies daar voor "Simulator". Als naam geef je "Simulator" en als beurs kies je de beurs waar jij normaliter een account zou openen. Als startkapitaal stel je het bedrag in wat jij door de trader wil laten beleggen. Volg daarna het normale stappenplan m.b.t. "Instellen van de trader". BitBrokerTrade gebruikt nu de echte real time handelsdata voor jouw fictieve beleggingskapitaal. Je krijgt gewoon mails van transacties alsof er echt gehandeld wordt. Zo krijg je zonder risico te lopen een goed beeld van wat de trader voor jou kan betekenen. Let op: de simulator werkt maximaal 60 dagen en je moet minimaal 10 credits gestort hebben om hem te kunnen activeren.

[05]()

### De trader doet geen aankopen, wat gaat er fout?

Bij de BBT strategie werkt de trader volgens een vast format: aankoop alleen bij de aanvang van de opwaartse trend, mits binnen een bepaalde bandbreedte (trader instelling: "min. percentage tussen aankopen") er geen andere transactie is en er voldoende saldo ( € 25,- ) op de eurorekening in de exchange is. (Er moeten Euro's op je rekening staan!) Gedurende de koersstijging doet de BBT strategie geen aankopen. Als er niet voldoende euro saldo (minimaal €25,-) beschikbaar is op je exchange account, kan de trader niet aankopen. Het kan ook zijn dat je geen credits hebt. Dat je de API-sleutel niet gekoppeld hebt. Dat je een te groot gereserveerd bedrag hebt ingesteld. (kortom: er is daardoor geen euro saldo beschikbaar) Als de trader geen aankoop doet, wordt aan één van deze criteria niet voldaan.

[06]()

### Ik wil graag geld bijstorten om te traden. Is dat mogelijk en zo ja, hoe werkt dat?

In de exchange kun je vanuit je eigen bankrekeningnummer geld storten op de euro rekening. De trader zal vanaf dat moment met het nieuwe beschikbare saldo in euro gaan rekenen.

[07]()

### Welk rendementspercentage kan ik het beste ingeven bij de trader

De trader gebruikt dit percentage om te beoordelen wanneer hij de transactie mag verkopen. Dit percentage moet dus hoog genoeg zijn om winst te maken. Geef je 5% in, dan zal de trader relatief weinig transacties doen. Immers, koersschommelingen van 5% zijn minder frequent. Geef je hier 2% in, dan profiteer je van een groter volume aan transacties en heb je misschien wel een beter totaalrendement. Hou er rekening mee dat bijna alle beurzen 0,25% aankoop en 0,25% verkoopkosten berekenen. Dus dat betekent dat je pas vanaf een rendementspercentage van 0,5% winst maakt. Onze berekeningen op historische data (24 maanden historie en langer) geven aan dat tussen 0,7% en 0,9% een relatief goed netto rendement (= rekening houdend met transactiekosten) wordt gehaald.

[08]()

### Het rendement van een transactie stond even boven de 2,8% en ondanks dat mijn rendementspercentage op 2,5% staat, heeft de trader toch niet verkocht. Sterker nog: de koers is inmiddels gezakt. Wat gebeurt er?

Bij de BBT strategie verkoopt de trader alleen als de stijgende trend breekt. Deze trend breekt nooit op het hoogste punt. Het rendement op de pocket was dus kleiner dan 2,5% toen de trend brak. En daarna is de koers verder gedaald. De trader wacht op een nieuwe koersstijging.

[09]()

### Hoe werkt de UpDown Strategie

De trader volgt in deze strategie geen koerstrend bepaling maar neemt met een koersrange (traderinstelling: "min. percentage tussen aankopen") posities in. De trader doet een aankoop van 18% (minimumbedrag van € 25,-) van je vrije euro saldo in de exchange (tenzij je het gemiddeld aankoopbedrag hebt ingevuld, dan wordt dat specifieke bedrag ingekocht). De trader verkoopt de positie zodra er voldaan wordt aan het minimum rendement wat de gebruiker in zijn instellingen bij de trader heeft ingegeven. Updown strategie werkt met candles van 1 minuut. Dat wil zeggen dat de gemiddelde koers waarop Updown Strategie stuurt één keer per minuut wordt vastgesteld. Als deze koers hoger is dan de koers van de vorige candle, dan verkoopt de Updown nog niet, dan is er immers sprake van een stijgende koers. Hij verkoopt pas als de laatste candle fundamenteel (in koers en volume) lager is dan de voorgaande candle.

[10]()

### Hoe en aan de hand waarvan bepaal je een ''plafond koers''

Je kijkt als voorbereiding naar de huidige koers en naar de historische koersontwikkeling van de betreffende crypto coin. Als JOUW verwachting is c.q. jij hebt het gevoel dat de koers van bijv. Bitcoin boven € 55.000,- een eenmalige piek is, dan wil je niet dat de trader posities inkoopt mocht de koers naar dat niveau stijgen. Je geeft dan een koersplafond van 3% daaronder als koersplafond op. Als je rendement nu lager is ingesteld dan 3% zal de trader zijn laatste inkoop altijd nog verkopen bij zo'n piekkoers en heb je maximaal rendement. Dat is de theorie achter de plafondkoers.

[11]()

### Mijn transactieregel in het scherm Aankooptransacties heeft een rood kruis als status ?!

Oorzaak 1: De trader heeft een verkoopopdracht geplaatst. De koers van crypto is echter zo snel gedaald dat de verkooporder geen koper vond om volledig verkocht te worden. De trader blijft wachten op de afwikkeling van de totale verkoop. Meestal heeft de exchange al een gedeelte van jouw order verkocht (zij hebben nl het recht om jouw order in stukjes te verkopen (afstemmen vraag en aanbod)). Mocht de koers weer gaan stijgen en het niveau van de verkooporder bereiken, wordt de restorder alsnog verkocht en afgehandeld. Als je daar niet op wil wachten kun je op het rode kruis drukken en de verkooporder af laten handelen. In dat geval knipt de trader jouw order in 2 stukken: het verkochte gedeelte, wat verschijnt in je verkooptransacties enerzijds en het onverkochte gedeelte wat in aankooptransacties verschijnt. Beide orders hebben hetzelfde ordernummer. Dat de order niet (helemaal) verkocht is, komt omdat onze trader marktopdrachten geeft. Dat wil zeggen dat hij een vaste koers geeft waartegen verkocht moet worden. De exchange mag hier niet van afwijken. Bij munten waar niet veel handel in is, kan bij een snelle koersdaling deze situatie van deelverkoop ontstaan. Oorzaak 2: De trader heeft een aankooporder geplaatst, die door het snelle stijgen van de koers niet volledig kan worden ingevuld door de exchange. Zolang de trader wacht op afhandeling van de order staat er een rood kruis in de orderregel. Pas als de koers weer gaat dalen, zal de exchange de restafhandeling doen. Ook hier geldt: je kunt de trader opdracht geven eea af te handelen door op het rode kruis te drukken. Ook nu wordt de transactie opgesplitst in twee transacties: het reeds aangekochte deel verschijnt in het scherm aankooptransacties, en het restant verschijnt als 'nulorder' in het verkoopscherm.

[12]()

### Hoe gaat de berekening van de winst in zijn werk?

De winstbepaling gaat als volgt: Stel: jij hebt ingegeven dat de trader mag verkopen bij 1,5% winst en dat het gemiddeld aankoopbedrag € 100,- per transactie is. Vervolgens ziet de trader een aankoopmoment voor een cryptomunt en doet de transactie. Hij geeft een opdracht voor € 100,- aankoop. De exchange brengt echter 0,25% transactiekosten bij jou in rekening en schrijft dit af van je vrije saldo. In het transactiescherm verschijnt dat je voor € 100,- hebt aangekocht, terwijl de eigenlijke kosten € 100,25 zijn. Wanneer ziet de trader nu 1,5% winst? Zodra de waarde van de transactie € 101,50 is (100 \* 1,015), mag de bot verkopen. De winst die er gemaakt wordt is dus bruto, want de totale transactiekosten (gemiddeld 0,5%) moeten daar nog van af. Je rendementspercentage moet dus hoger zijn dan 0,5% om ook echt winst te maken.

[13]()

### Hoe komt het dat bij de UpDown strategie de koers soms boven het doelpercentage komt, maar de trader dan niet gelijk verkoopt?

Bij de UpDown strategy moet de gemiddelde koers boven de doelkoers sluiten (gemiddelde koers wordt iedere minuut bepaald), waarbij aankoopkoers + rendement = doelkoers. Als de koers binnen de minuut boven de doelkoers komt maar onder de doelkoers sluit, neemt de trader geen actie. In deze minuut wordt namelijk de zogenaamde candle gevormd. Deze candle bepaald na een minuut de gemiddelde koers van die minuut. Die koers is dus bepalend voor de doelkoers. Bij BBT strategie worden candles van 15 minuten gevormd en de slotkoers dus iedere 15 minuten vastgesteld.

[14]()

### Hoeveel invloed heeft de hoogte van het rendementspercentage op de uiteindelijke winst ?

Een hoger of lager rendementspercentage maakt vooral veel uit voor de hoeveelheid transacties die gedaan worden. Daarmee is het heel bepalend voor de hoogte van de transactiekosten. Bij een laag rendementspercentage wordt een transactie eerder verkocht en wordt ook eerder een nieuwe positie ingenomen. Per saldo zien we dat bij een rendementspercentage instelling tussen 0,7% en 0,9% de hoogste netto winst wordt gehaald.

[15]()

### De trader verkoopt een transactie niet, ondanks dat het doelpercentage gehaald is. Als je vervolgens op de button van "handmatig verkopen" drukt, verschijnt een pop up scherm met een foutmeldingscode.

Het saldo op de cryptorekening bij de exchange is niet voldoende om de order uit te voeren. Deze verschillen kunnen ontstaan als gebruikers zelf op de exchange handelen en geen rekening houden met de "voorraad" van de trader. Oplossingen: Je koopt eenmalig de verschillen ‘handmatig’ bij in het dashboard van de exchange. De trader rond dan alle transacties af en de historie blijft bewaard. In de trader zet je de betreffende orderregels op “on hold” (button “II” in het aankoopscherm). De trader negeert de transacties en de historie blijft bewaard. De betreffende traders verwijder je en voer je daarna opnieuw op. Alle posten zijn nu gereset en de trader begint opnieuw. De trader historie is daarmee wel gewist. Pak de optie die jou het meest aanspreekt.

[16]()

### Wat gebeurd er als ik mijn trader (bv XRP) op inactief zet? Ik heb actieve XRP aankoop transacties. Worden deze dan nog wel verkocht?

Bij inactief zetten wordt de historie bewaard en doet de trader niets totdat hij weer geactiveerd wordt. Wil je geen aankopen doen maar wel verkopen laten uitvoeren, zet dat de plafondkoers in de betreffende trader op € 0,01, maar laat hem wel actief.

[17]()

### Instelling: Maximaal open aankopen

Je kunt per trader ingeven dat er een maximum aantal aankopen voor de desbetreffende munt gedaan mag worden. In combinatie met het gemiddelde aankoop bedrag kun je een precieze limiet zetten op hoeveel geld je per munt wilt investeren. Je kunt deze optie ook gebruiken om de trader opdracht te geven een munt ‘leeg’ te verkopen zonder nieuwe aankopen te doen (door ‘0’ (nul) in te vullen).

[18]()

### Instelling: Gereserveerd bedrag

Je kunt bij Beurs/exchange invoeren dat de trader maximaal een X bedrag van het beschikbare saldo niet mag (her)investeren. Dit geeft je de mogelijkheid om, wanneer al je middelen zijn geïnvesteerd, te zorgen dat een bepaald bedrag wat vrijkomt uit de verkoop niet opnieuw wordt geïnvesteerd. Zo hou je het vrij voor bijvoorbeeld een opname of om een reserve aan te houden voor plotselinge koersdalingen (herinvesteren tegen een lagere prijs). Je kunt dit bedrag zo vaak aanpassen als nodig is. Voorbeeld: Je hebt 5.000 euro gestort en alles is belegd. Je geeft 2.000 euro reservering op in de beursinstelling. De trader gaat pas weer aankopen doen als hij meer dan 2.000 euro vrij saldo heeft, en alleen met het bedrag boven de 2.000 euro. Tot dan verkoopt de trader wel, maar worden er geen aankopen gedaan.

[19]()

### ik heb een aantal trades openstaan op BBT waarvan ik de coins niet meer op de exchange heb staan. De trades kunnen dus niet verkocht worden. Is er een manier om deze trades te verwijderen zodat ik een duidelijker overzicht heb?

Oplossingen: 1. Je koopt eenmalig de verschillen ‘handmatig’ bij in het dashboard van de exchange. De trader handelt dan alle transacties af en de historie blijft bewaard. of 2. In de trader zet je de betreffende orderregels op “on hold” (button “II” in het aankoopscherm). De trader negeert de transacties en de historie blijft bewaard. of 3. De betreffende trader verwijder je en voer je daarna opnieuw op. Alle posten zijn nu gereset en de trader begint opnieuw. De trader historie is daarmee wel gewist. Pak de optie die jou het meest aanspreekt.

[20]()

### Hoe werkt referral/doorverwijzing?

Via het menu “Doorverwijzing” in de trader kun je een persoonlijke link aanmaken. Deze link (referral of doorverwijzing) kun je sturen naar mensen die je wilt laten kennismaken met BitBrokerTrade.com Over de verdiensten van gebruikers die zich aanmelden via de door jouw verstrekte referral krijg jij een provisie in credits uitgekeerd (15% van de commissie die BitBrokerTrade ontvangt). Van de tweede lijn referral-gebruikers krijg je 5% van de commissie die BitBrokerTrade ontvangt in credits uitgekeerd. Een tweede lijn referral is een gebruiker die weer door jouw referral is aangebracht. Zolang jij zelf een actief account hebt waarop gehandeld wordt, ontvang je deze beloningen. Wanneer jij er voor kiest om niet meer te handelen worden ook de vergoedingen gestopt. Het is een bonussysteem van en voor actieve BitBrokerTrade gebruikers.