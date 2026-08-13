# Source: https://docs.bitbrokertrade.com/overig/faq/foutmeldingen/hoe-komt-het-dat-bij-de-updown-strategie-de-koers-soms-boven-het-doelpercentage-komt-maar-de-trader

For the complete documentation index, see [llms.txt](https://docs.bitbrokertrade.com/llms.txt). This page is also available as [Markdown](https://docs.bitbrokertrade.com/overig/faq/foutmeldingen/hoe-komt-het-dat-bij-de-updown-strategie-de-koers-soms-boven-het-doelpercentage-komt-maar-de-trader.md).

Bij de UpDown strategy moet de slotkoers boven de doelkoers sluiten (slotkoers wordt telkens na 1 minuut bepaald), waarbij aankoopkoers + rendement = doelkoers.

Als de koers binnen de minuut boven de doelkoers komt maar onder de doelkoers sluit, neemt de trader geen actie. In deze minuut wordt namelijk de zogenaamde candle gevormd. Deze candle bepaald na een minuut de eindkoers van die minuut. Die koers is dus bepalend voor de doelkoers.

Bij BBT strategie worden candles van 5 minuten gevormd en de slotkoers dus iedere 5 minuten vastgesteld.

[PreviousMijn transactieregel in het scherm Aankooptransacties heeft een rood kruis als status ?!](https://docs.bitbrokertrade.com/overig/faq/foutmeldingen/mijn-transactieregel-in-het-scherm-aankooptransacties-heeft-een-rood-kruis-als-status) [NextWaarom wordt er niet verkocht?](https://docs.bitbrokertrade.com/overig/faq/foutmeldingen/het-rendement-van-een-transactie-stond-even-boven-de-2-8-en-ondanks-dat-mijn-rendementspercentage-o)

Last updated 5 years ago