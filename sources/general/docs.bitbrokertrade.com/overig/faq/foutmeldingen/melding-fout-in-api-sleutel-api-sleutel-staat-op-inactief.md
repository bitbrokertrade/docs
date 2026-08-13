# Source: https://docs.bitbrokertrade.com/overig/faq/foutmeldingen/melding-fout-in-api-sleutel-api-sleutel-staat-op-inactief

For the complete documentation index, see [llms.txt](https://docs.bitbrokertrade.com/llms.txt). This page is also available as [Markdown](https://docs.bitbrokertrade.com/overig/faq/foutmeldingen/melding-fout-in-api-sleutel-api-sleutel-staat-op-inactief.md).

Nadat de gebruiker de API sleutel heeft geactiveerd, zijn er een aantal oorzaken mogelijk waarom de API toch weer inactief wordt:

1\. De gebruiker doet dat zelf in het dashboard van de exchange.

2\. De exchange maakt de sleutel of een functie daarin ongeldig om hen moverende redenen (Binance maakt bijvoorbeeld iedere 30 dagen de instelling “Enable spot & margin trading” ongeldig bij gebruikers van de API vebinding als er geen IP adres op de IP whitelist van dezelfde gebruiker staat).

3\. Er is een foutmelding in de verbinding.

**In alle drie de gevallen maakt het BBT systeem de API verbinding inactief**. Er is nu geen verbinding meer met de exchange totdat de API sleutel hersteld is.

Indien de API sleutel inactief wordt gemaakt ontvangt de gebruiker een mail van ons met daarin de reden van de blokkade en een overzicht van welke traders nu niet meer actief zijn

**De gebruiker kan de API sleutel herstellen** door in het dashboard van de betreffende exchange in te loggen en daar de instellingen na te lopen en opnieuw te activeren.

Voor Binance staat hier wat de API-instellingen zijn: [https://docs.bitbrokertrade.com/exchanges/binance-toevoegen-als-beurs](https://docs.bitbrokertrade.com/exchanges/binance-toevoegen-als-beurs)

Voor Bitvavo: [https://docs.bitbrokertrade.com/exchanges/bitvavo-exchange-toevoegen](https://docs.bitbrokertrade.com/exchanges/bitvavo-exchange-toevoegen)

Voor Bitstamp: [https://docs.bitbrokertrade.com/exchanges/bitstamp-toevoegen-als-beurs](https://docs.bitbrokertrade.com/exchanges/bitstamp-toevoegen-als-beurs)

Voor Coinbase: [https://docs.bitbrokertrade.com/exchanges/coinbase-toevoegen-als-beurs](https://docs.bitbrokertrade.com/exchanges/coinbase-toevoegen-als-beurs)

Nadat je de API instellingen bij de exchange hebt hersteld dien je in het dashboard van BitBrokerTrade nog **naar het menu Instellingen/beurzen te gaan en de inactieve beurs te selecteren (door erop te klikken)**. In het nieuw geopende scherm voer je de nieuwe API sleutels op en klik je vervolgens op **‘opslaan’.**

Nu test de BBT software de verbinding. Als de API-instellingen goed zijn verwerkt zal de verbinding weer op **actief** staan.

[PreviousFoutmeldingen en overige vragen](https://docs.bitbrokertrade.com/overig/faq/foutmeldingen) [NextDe transactie wordt niet verkocht terwijl het winstpercentage wel gehaald is](https://docs.bitbrokertrade.com/overig/faq/foutmeldingen/de-transactie-wordt-niet-verkocht-terwijl-het-winstpercentage-wel-gehaald-is)

Last updated 3 years ago