---
Title: Loading time and usability.
Description: My loading time and usability analysis for kmom05.
# Template: kmom
---

Utvärdering av webbplatsers laddningstid och användbarhet
=======================

Uppgiftens syfte är att välja ut några webbplatser och mäta deras laddningstid och om de innehåller någonting som kan förbättras ur laddningstidens och användbarhets synvinkel.


Urval
-----------------------

För analysen valdes tre bank-webbplatser:
* https://www.swedbank.se/
* https://seb.se/
* https://danskebank.se/privat


Jag valde bank-webbplatser för att de alla ingår i samma kategori och har samma syfte samt riktar sig till samma grupp av användare, vilket innebär att man kan mer objektivt jämföra och analysera deras laddningstid och möjliga förbättrinsomroderna gällande användbarhet. 

Metod
-----------------------

För analysen användes två olika vekrtyg:
* Google PageSpeed (https://developers.google.com/speed/pagespeed/insights/) för att analysera laddningstid och förslag på utvecklingsmöjligheter.
* Google chromes inbyggd verktyg "network" för att mäta laddningstid och hur många resurser som laddas ner.

Först analyserar jag varje sida med Google PageSpeed både på desktop och på mobilen för att se om det finns skillnader i laddningstid och sparar resultater i Google Kalkyl-filen. Sedan använder jag mig av verktyg "network" för att se laddningstid och hur många resurser som laddas ner samt hur många resurser hela webbsidan innehåller. Med "network" mäter jag resultater tre gånger och skriver i allt i Google Kalklyl-filen, sedan räknar jag ut genomsnitt på laddningstiden. 

Resultat
-----------------------

Analys av swedbank.se:

<img src="../assets/img/swe1.png" class="bank" alt="swedbank">

PageSpeed Desktop analys ger betyg 40 av 100. Speed intex 7,7 s. PageSpeed Mobile ger betyg 37 och speed index 8,5 s.
Som förbättringsmöjligheter anges: 
* Ta bort resurser som blokerar renderingen, som kan spara 5,32 s.
* Använda bilder i rätt storlek, som kan spara 2,1 s.
* Ta bort oanvänd CSS, som kan spara 2,1 s.
* Skicka bilder i modernare format (byta ut PNG mot JPEG eller WebP), som kan spara 1,8 s.


Analys med inbygda devop funktion "network" visar att genomsnitliga laddningstid är 1,19 s och det ladas ner 2,1MB av resurser och hela sidan består av 2.8 MB resurser.

Analys av seb.se:

<img src="../assets/img/seb1.png" class="bank" alt="seb">

PageSpeed Desktop analys ger betyg 11 av 100. Speed index 9,5 s. PageSpeed Mobile ger betyg 10 och speed index 10,3 s.
Som förbättringsmöjligheter anges:
* Läs in viktiga resursser i förväg, som kan spara 15,21 s.
* Aktivera textkomprimering, som kan spara 7,5 s.
* Ta bor JavaScript som inte används, som kan spara 4,8 s.
* Skjut upp inläsning av bilder som inte används på skärmen, som kan spara 4,38 s.
* Ta bort resursersom blokerar renderingen, som kan spara 3,28 s.
* Använd bilder med rätt storlek, som kan spara 3,15 s.
* Ta bort oanvänd CSS, som kan spara 2,55 s.
* Skicka bilder i modernare bildformat, som kan spara 1,5 s.
Analys med devop funktion "network" visar att genomsnitliga laddningstid är 1,6 s och det ladas ner 4,4 MB resurser av 4,4 MB resurser, d.v.s. alla resurser som finns på webbsidan.


Analys av danskebank.se:

<img src="../assets/img/dansk1.png" class="bank" alt="danskebank">

PageSpeed Desktop analys ger betyg  53 av 100 och speed index 4,7 s. Webbsidan får bättre betyg för att den har snabbt "first kontent paint" som är 2 s. PageSpeed Mobile ger betyg 47 och speed index 5,1 s.
Som förbättrinsmöjligheter anges:
* Läs in viktiga resurser i förväg, som kan spara 1,47 s.
* Ta bor JavaScript som inte används, som kan spara 1,05 s.
* Ta bort resursersom blokerar renderingen, som kan spara 0,81 s.
* Skicka bilder i modernare bildformat, som kan spara 0,6 s.
* Ta bort oanvänd CSS, som kan spara 0,45 s.
* Minifiera JavaScript, som kan spara 0,15 s.
Analys med devop funktion "network" visar att genomsnitliga laddningstid är 3,6 min och det ladas ner 2,5 MB resurser av 2,6 MB resurser. Ovanligt lång ladningstid beror på att det ladas ner stort antal av json filer.

Rådatan kan ses i <a href="https://docs.google.com/spreadsheets/d/1w6NwtIttO7r7MFzVE2XWotL_Ifmq-3j4420F6vGu4dQ/edit?usp=sharing">Google Kalkyl.</a>


Analys
-----------------------

Enligt resultat de vanligaste förbätringsåtgärderna är att använda bilderna i rätt storlek och i en modernare variant. Alla webbsidor fortfarande använder PNG bilder, vilket gör att laddningstiden förlängs. De andra vanliga åtgärderna är att ta bort resurser som blockerar renderingen, ta bort CSS som inte används och att lada in viktiga resurser i förväg.


Bästa ladningstid enligt PageSpeed hade danskebank, på andra platsen var swedbank och sista var seb. Seb har riktigt låg resultat, vilket kan hänga ihop med att man laddar inte in viktiga resurser i förväg och hela sidan tar 4,4 MB. 


Utifrån "network" resultat kan man se att danskebank hamnar på sista platsen, medans swedbank är snabbast. Seb hamnar på andra platsen. Det kan bara betyda att en av vektyg som man mäter med är inte tillräckligt pålitlig eller att de mäter olika saker. Under mätning av laddningstid med "network" en av orsakerna varför danskebank hamnar på sista platsen är att det laddas stor mängd av json filer, vilket är inte fallet på andra hemsidor.


Alla tre webbsidor har sämre resultat i Mobile version. Det tar i genomsnit 0,7 s längre tid att ladda upp sidan på mobilversionen än desktopsversionen.


Absolut laddningstid borde inte överstiga 3,5 s, för att det är den tiden man oftast orkar vänta och skaffa sig uppfattning om vad sidan innehåller och om man vill stanna kvar på sidan. Utifrån min subjektiv uppfattning tycker jag att swedbank och seb har snabba webbsidor och laddas upp nästan direkt. Medans danskebank tar lite längre tid att laddas upp och vissa bilder laddas bara när man skrollar ner. Det sistnämnda kan vara bra för att om man inte vill skrolla ner, då slipper man ladda det som finns längs ner i sidan, vilket kan möjligen ha gjort att sidan fick hög betyg i PageSpeed. 


Övrigt
-----------------------

Utvärdering är gjort och skriven av Reda Stanislovaviciene.