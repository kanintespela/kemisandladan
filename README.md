# Kemisandlådan

En interaktiv partikelsimulator för gymnasiets kemiundervisning – kör direkt i webbläsaren, ingen installation krävs.

**[Öppna Kemisandlådan ➜](https://kanintespela.github.io/kemisandladan/)**

## Vad är det?

Kemisandlådan visualiserar atomer och molekyler i realtid: eleven placerar ut atomer och ser vad som händer. Bindningar bildas och bryts, vatten kondenserar och fryser till ett hexagonalt isgitter, syror protolyserar, salter löser sig och kristalliserar. Temperatur och volym kan justeras medan manometer, koncentration och pH följs löpande.

Utöver den fria sandlådan finns sexton guidade uppdrag – stökiometri och begränsande reaktant, VSEPR och polaritet, fasövergångar, syra–bas, jonbindning, diffusion – i huvudsak byggda som förutsäg–observera–förklara, där eleven gissar först och sedan ser utfallet.

Tanken är att fylla glappet mellan den symboliska nivån (formler och reaktioner på tavlan) och den submikroskopiska (vad partiklarna faktiskt gör).

## Status: betaversion

Detta är ett pågående bygge, inte en färdig produkt. Det fungerar bra på en vanlig dator men blir segt med många partiklar i rummet, och är ännu inte anpassat för surfplattor eller mindre skärmar. Modellen är medvetet förenklad – till exempel visas temperatur på en relativ skala eftersom fenomenen inte går att kalibrera mot riktiga kelvin samtidigt. Där modellen har en gräns försöker appen skriva ut den för eleven i stället för att dölja den.

Feedback och synpunkter tas gärna emot – öppna gärna ett [issue här på GitHub](https://github.com/kanintespela/kemisandladan/issues).

## Teknik

Kemisandlådan är en enda fristående HTML-fil utan externa beroenden, byggberoenden eller installation. Den öppnas direkt i webbläsaren och fungerar även offline. Ingen inloggning, inget konto och ingen spårning.

## Licens

© 2026 Christian Broselid. Alla rättigheter förbehållna – se [LICENSE](LICENSE). Koden är öppet tillgänglig här för att kunna testas och köras, men får inte kopieras, modifieras eller återanvändas utan tillstånd från upphovspersonen.
