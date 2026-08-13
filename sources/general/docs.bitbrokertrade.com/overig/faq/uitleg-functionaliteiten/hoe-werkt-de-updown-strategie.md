# Source: https://docs.bitbrokertrade.com/overig/faq/uitleg-functionaliteiten/hoe-werkt-de-updown-strategie

For the complete documentation index, see [llms.txt](https://docs.bitbrokertrade.com/llms.txt). This page is also available as [Markdown](https://docs.bitbrokertrade.com/overig/faq/uitleg-functionaliteiten/hoe-werkt-de-updown-strategie.md).

De trader volgt in deze strategie geen MACD indicator (koerstrend bepaling) maar neemt op basis van 1 minuut candles posities in, zowel in een stijgende als in een dalende markt.

De eerste aankoop onder Updownstrategie is direct na het activeren van de trader, mits de koers (gemiddelde koers van de laatste candle) stijgend is.

De trader doet een aankoop van een positie ter grootte van 18% (minimumbedrag van € 50,-) van je vrije euro saldo in de exchange (tenzij je het gemiddeld aankoopbedrag hebt ingevuld, dan wordt dat bedrag ingekocht), mits er aan alle trader instellingen wordt voldaan.

De trader verkoopt de positie zodra er voldaan wordt aan het minimum rendement wat de gebruiker in zijn instellingen bij de trader heeft ingegeven, op voorwaarde dat de gemiddelde koers in de laatste candle dalend is.

Updown strategie werkt met candles van 1 minuut. Dat wil zeggen dat de gemiddelde koers waarop Updown Strategie stuurt één keer per minuut wordt vastgesteld. Als deze gemiddelde koers hoger is dan de gemiddelde koers van de vorige candle, dan verkoopt de Updown nog niet, dan is er immers sprake van een stijgende koers. Hij verkoopt pas als de laatste candle fundamenteel (in gemiddelde koers) lager is dan de voorgaande candle.

[PreviousHoeveel invloed heeft de hoogte van het rendementspercentage op de uiteindelijke winst ?](https://docs.bitbrokertrade.com/overig/faq/uitleg-functionaliteiten/hoeveel-invloed-heeft-de-hoogte-van-het-rendementspercentage-op-de-uiteindelijke-winst) [NextWat is het verschil tussen Updown strategie en BitBrokerTrade strategie?](https://docs.bitbrokertrade.com/overig/faq/uitleg-functionaliteiten/wat-is-het-verschil-tussen-updown-strategie-en-bitbrokertrade-strategie)

Last updated 2 years ago