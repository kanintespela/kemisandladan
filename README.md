# Pedagogiska webbappar

Interaktiva webbappar för gymnasiet i kemi och biologi – kör direkt i webbläsaren, ingen installation krävs.

**[Öppna samlingssidan ➜](https://kanintespela.github.io/kemisandladan/)** – välj kemi eller biologi.

| Ämne | App | Adress | Status |
|---|---|---|---|
| Kemi | Kemisandlådan | [/sandladan/](https://kanintespela.github.io/kemisandladan/sandladan/) | beta 0.5 |
| Kemi | Bindningsverkstan | [/bindningsverkstan/](https://kanintespela.github.io/kemisandladan/bindningsverkstan/) | 0.13 |
| Kemi | Kemiska reaktioner och energi | [/reaktioner/](https://kanintespela.github.io/kemisandladan/reaktioner/) | prototyp 0.3 |
| Biologi | Reglerverkstan | [/reglerverkstan/](https://kanintespela.github.io/kemisandladan/reglerverkstan/) | 0.4 |

Kemisandlådan låg tidigare direkt på [kanintespela.github.io/kemisandladan/](https://kanintespela.github.io/kemisandladan/). Där finns nu samlingssidan, där man väljer ämne; kemiapparna ligger samlade på [/kemi/](https://kanintespela.github.io/kemisandladan/kemi/) och biologiapparna på [/biologi/](https://kanintespela.github.io/kemisandladan/biologi/). Adresserna till apparna är oförändrade.

## Kemisandlådan

Kemisandlådan visualiserar atomer och molekyler i realtid: eleven placerar ut atomer och ser vad som händer. Bindningar bildas och bryts, vatten kondenserar och fryser till ett hexagonalt isgitter, syror protolyserar, salter löser sig och kristalliserar. Temperatur och volym kan justeras medan manometer, koncentration och pH följs löpande.

Utöver den fria sandlådan finns sexton guidade uppdrag – stökiometri och begränsande reaktant, VSEPR och polaritet, fasövergångar, syra–bas, jonbindning, diffusion – i huvudsak byggda som förutsäg–observera–förklara, där eleven gissar först och sedan ser utfallet.

Tanken är att fylla glappet mellan den symboliska nivån (formler och reaktioner på tavlan) och den submikroskopiska (vad partiklarna faktiskt gör).

## Bindningsverkstan

Fem moduler om varför atomer håller ihop: attraktion och repulsion i en molekyl och i ett jongitter, potentialkurvan när två atomer dras ihop, elektronegativitet som ett kontinuum, energitrappan från natrium och klor till natriumklorid, och metallbindning (elektronhavet, ström, böj metallen).

## Kemiska reaktioner och energi

Eleven förutsäger om en reaktion tar upp eller avger energi och går sedan energitrappan via fria atomer, steg för steg, med en partikelbild för varje steg. Tio reaktioner, från is som smälter till fotosyntesen.

## Reglerverkstan

Kroppens reglersystem som en levande krets, med blodsockerregleringen som första system. Glukos, insulin och glukagon flödar som partiklar, ventiler öppnas och stängs, och kurvorna följer med. Eleven förutsäger först, kör förloppet och förklarar efteråt, och kan ändra komponenterna: förstöra betacellerna (typ 1), minska receptorerna (typ 2), koppla bort glukagonvägen eller vända tecknet i insulinslingan. Appen räknar själv ut om en slinga är negativ eller positiv återkoppling och visar tävlande vägar.

I byggläget bygger eleven kretsen själv av färdiga delar (blodsocker och kroppstemperatur): lägger till komponenter, kopplar dem med musen och väljer tecken. Kretsen bedöms på hur den beter sig i tre situationer, så flera olika kopplingar kan vara rätt.

I fritt bygge bygger eleven på en tom duk med egna storheter, källor, förluster, ventiler, sensorer och signaler, drar rören själv, lägger in störningar och läser en rapport om vad som hände. Det går också att börja från en färdig krets (blodsocker eller temperatur) och ta sönder eller bygga ut den.

## Ljust och mörkt tema

Alla appar och samlingssidorna har ett ljust och ett mörkt tema. Utan eget val följer de datorns inställning. Temaknappen uppe till höger byter, och valet sparas i webbläsaren och gäller då i alla apparna.

## Status

Apparna är pågående byggen, inte färdiga produkter. De fungerar bra på en vanlig dator men är ännu inte anpassade för surfplattor eller mindre skärmar. Modellerna är medvetet förenklade – till exempel visas temperaturen i Kemisandlådan på en relativ skala eftersom fenomenen inte går att kalibrera mot riktiga kelvin samtidigt. Där en modell har en gräns försöker appen skriva ut den för eleven i stället för att dölja den.

Feedback och synpunkter tas gärna emot – öppna gärna ett [issue här på GitHub](https://github.com/kanintespela/kemisandladan/issues).

## Teknik

Varje app är en enda fristående HTML-fil utan externa beroenden, byggberoenden eller installation. Den öppnas direkt i webbläsaren och fungerar även offline. Ingen inloggning, inget konto och ingen spårning.

```
index.html                    startsidan: val av ämne
kemi/index.html               samlingssidan för kemiapparna
biologi/index.html            samlingssidan för biologiapparna
bilder/                       skärmbilderna på samlingssidorna, ljust och mörkt tema
sandladan/index.html          Kemisandlådan
bindningsverkstan/index.html  Bindningsverkstan
reaktioner/index.html         Kemiska reaktioner och energi
reglerverkstan/index.html     Reglerverkstan
```

## Licens

© 2026 Christian Broselid. Alla rättigheter förbehållna – se [LICENSE](LICENSE). Koden är öppet tillgänglig här för att kunna testas och köras, men får inte kopieras, modifieras eller återanvändas utan tillstånd från upphovspersonen.
