# Kemiappar

Interaktiva kemiappar för gymnasiet – kör direkt i webbläsaren, ingen installation krävs.

**[Öppna samlingssidan ➜](https://kanintespela.github.io/kemisandladan/)**

| App | Adress | Status |
|---|---|---|
| Kemisandlådan | [/sandladan/](https://kanintespela.github.io/kemisandladan/sandladan/) | beta 0.5 |
| Bindningsverkstan | [/bindningsverkstan/](https://kanintespela.github.io/kemisandladan/bindningsverkstan/) | 0.13 |
| Kemiska reaktioner och energi | [/reaktioner/](https://kanintespela.github.io/kemisandladan/reaktioner/) | prototyp 0.3 |

Kemisandlådan låg tidigare direkt på [kanintespela.github.io/kemisandladan/](https://kanintespela.github.io/kemisandladan/). Där finns nu samlingssidan, med en länk till sandlådan.

## Kemisandlådan

Kemisandlådan visualiserar atomer och molekyler i realtid: eleven placerar ut atomer och ser vad som händer. Bindningar bildas och bryts, vatten kondenserar och fryser till ett hexagonalt isgitter, syror protolyserar, salter löser sig och kristalliserar. Temperatur och volym kan justeras medan manometer, koncentration och pH följs löpande.

Utöver den fria sandlådan finns sexton guidade uppdrag – stökiometri och begränsande reaktant, VSEPR och polaritet, fasövergångar, syra–bas, jonbindning, diffusion – i huvudsak byggda som förutsäg–observera–förklara, där eleven gissar först och sedan ser utfallet.

Tanken är att fylla glappet mellan den symboliska nivån (formler och reaktioner på tavlan) och den submikroskopiska (vad partiklarna faktiskt gör).

## Bindningsverkstan

Fem moduler om varför atomer håller ihop: attraktion och repulsion i en molekyl och i ett jongitter, potentialkurvan när två atomer dras ihop, elektronegativitet som ett kontinuum, energitrappan från natrium och klor till natriumklorid, och metallbindning (elektronhavet, ström, böj metallen).

## Kemiska reaktioner och energi

Eleven förutsäger om en reaktion tar upp eller avger energi och går sedan energitrappan via fria atomer, steg för steg, med en partikelbild för varje steg. Tio reaktioner, från is som smälter till fotosyntesen.

## Ljust och mörkt tema

Alla appar och samlingssidan har ett ljust och ett mörkt tema. Utan eget val följer de datorns inställning. Temaknappen uppe till höger byter, och valet sparas i webbläsaren och gäller då i alla apparna.

## Status

Apparna är pågående byggen, inte färdiga produkter. De fungerar bra på en vanlig dator men är ännu inte anpassade för surfplattor eller mindre skärmar. Modellerna är medvetet förenklade – till exempel visas temperaturen i Kemisandlådan på en relativ skala eftersom fenomenen inte går att kalibrera mot riktiga kelvin samtidigt. Där en modell har en gräns försöker appen skriva ut den för eleven i stället för att dölja den.

Feedback och synpunkter tas gärna emot – öppna gärna ett [issue här på GitHub](https://github.com/kanintespela/kemisandladan/issues).

## Teknik

Varje app är en enda fristående HTML-fil utan externa beroenden, byggberoenden eller installation. Den öppnas direkt i webbläsaren och fungerar även offline. Ingen inloggning, inget konto och ingen spårning.

```
index.html                    samlingssidan
bilder/                       skärmbilderna på samlingssidan, ljust och mörkt tema
sandladan/index.html          Kemisandlådan
bindningsverkstan/index.html  Bindningsverkstan
reaktioner/index.html         Kemiska reaktioner och energi
```

## Licens

© 2026 Christian Broselid. Alla rättigheter förbehållna – se [LICENSE](LICENSE). Koden är öppet tillgänglig här för att kunna testas och köras, men får inte kopieras, modifieras eller återanvändas utan tillstånd från upphovspersonen.
