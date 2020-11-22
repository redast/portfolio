---
Title: Kmom02
Description: My report for kmom02.
Template: kmom
---

Kmom02
==========================
<div class="sidebar">
<a href="../report/kmom01"><h4>Kmom01</h4></a>
<a href="#"><h4>Kmom02</h4></a>
<a href="../report/kmom03"><h4>Kmom03</h4></a>
<a href="../report/kmom04"><h4>Kmom04</h4></a>
<a href="../report/kmom05"><h4>Kmom05</h4></a>
<a href="../report/kmom06"><h4>Kmom06</h4></a>
<a href="../report/kmom10"><h4>Kmom10</h4></a>
</div>
<div class="kmom" markdown="1">
I början kändes SASS mycket förvirrande för mig, hur man behöver dela upp filer och importera de och hur scss-filer kompileras till css-filen som används i webbsidan. Det tog några dagar tills jag äntligen fick någorlunda koll på hur allt fungerar. 


Jag är inte bekant med Node, npm eller npm scripts (t.ex. npm run lint) sedan tidigare. De känns fortfarande lite förvirrande för mig, men nu verkar jag ha föstått hur jag behöver använda npm för att validera scss filer eller kompilera stylingen.


Att  kompilera SASS till CSS var svårt i början. Problemet var att jag försökte återanvända gammal styling som jag kopierade till en ny css-fil. När jag kompilerade scss till css, då, varje gång skrevs över koden från scss till min css-fil, vilket gjorde att hela stylingen försvann varje gång. När jag äntligen fick tipps att undvika css-filer ch lägga allt till scss-filer som jag i sin tur importerar i huvudfilen style.scss, då fick jag det att fungera. Eftersom bara då kompilerades allt till en style.css.


Mitt tema har jag baserad på rosa nyanser, det börjar med ljust och blir mörkare i footern. Flashbilden valde jag ut också, så att den skulle passa färgmässigt. Flashbilden innehåller alla färger som finns på min webbsida och ger mörkare nyans för headern så att den inte ser så blankt ut.  Som fonter har jag bara två: open sans och roboto, för att undvika förmycket intryck.


De ända uppdelningar i min kod har jag i mina scss filer och rapport sidor som nås via report i navbaren. Jag tänker dela upp mina scss filer ännu mer, så att det blir lättare att göra ändringar i de.


Min TIL för detta kmom är att göra tills jag förstår och fråga så mycket jag kan. Närs det känns för frustrerande, är alltid bra idé att pausa och göra något annat, för att sedan återkomma till problemet med nya ögon.</div>