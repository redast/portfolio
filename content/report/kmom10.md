---
Title: Kmom10
Description: My report for kmom10.
Template: kmom
---

Kmom10
==========================
<div class="sidebar">
<a href="../report/kmom01"><h1 class="sidebar">Kmom01</h1></a>
<a href="../report/kmom02"><h1 class="sidebar">Kmom02</h1></a>
<a href="../report/kmom03"><h1 class="sidebar">Kmom03</h1></a>
<a href="../report/kmom04"><h1 class="sidebar">Kmom04</h1></a>
<a href="../report/kmom05"><h1 class="sidebar">Kmom05</h1></a>
<a href="../report/kmom06"><h1 class="sidebar">Kmom06</h1></a>
<a href="#"><h1 class="sidebar">Kmom10</h1></a>
</div>
<div class="kmom" markdown="1">
Jag har valt kund 1, Styrelseordförande Ludviga Af Solstråle med kompanjoner och valt att de är management- och buisnesskonsulter.
Jag har valt att börja ifrån grunden med en helt ny installation från example/portfolio med  me/portfolio som referens. Jag valde det sättet  för att undvika massa onödiga filer och kod. Jag ville ha bättre kontroll på det jag skapar, samt repetera det jag har lärt mig, eftersom det har gått ganska mycket tid sedan jag höll på med designkursens uppgifter. Om jag hade bara kopierat och modifierat hade jag missat repetitionsmöjligheten.
Jag skapade home-, about- och projectsidorna. I about finns även länken till dokumentation om theman/style. Jag har valt att använda mig av flash-bilden genom hela webbsidan, för att skapa sammanhang och undvika för många färgändringar. Jag har lagt till logan och favicon som är minifierat version av loggan, för samanhangs skull. I footern har jag lagg till låtsas kontaktinformation och iconer för att byta theman och förstöra sessionen. För att navigeringen ska fungera även i mobiltläge ändrar jag där till hamburgarmeny och gör grid till span 1, samt tar bort negativa spaces som gjordes med grid i desktopläge. Jag har kopierat texterna från annan företag som håller på med buisnessmanagement för att det var svårt att hitta på själv. Med bilderna försökte jag förstärka textensinnehåll.


I min huvudtema (default) använder jag en variation av guld och blå färger. Det blev en complementary färgschema med en gul/guld basfärg och en komplementfärg (blå) på motsvarande sida av färghjulet. Blå färg brukar symbolisera stabilitet, kompetens och tydligthet. Guldfärg associeras med rikedom och glädje och ger hemsidan en varmare känsla som kempenserar blåafärgens kalla känslan.
I huvudteman använder jag fonten 'Titillium Web' för huvudrubriker. Jag valde denna fonten för att jag tyckte att den såg elegant ut och för att den var utvecklat i Accademia di Belle Arti di Urbino som didaktik projektas Course Type design of the Master of Visual Design Campi Visivi. För 'p' elementer har jag valt att använda mig av 'Lato' för att den ser ut elegant, harmonisk och passar bra med 'Titillium Web'. Jag behövde dock göra p elementerna större och höja mellanrum mellan raderna så att det ska underlätta läsning. Och alla är självklart sans serif för att det ska, igen, vara lättare att läsa. 
Jag valde att göra tydliga övergångar mellan header, huvuddelen och footern, så att ska vara lättare att navigera för användaren och för att skapa balans.
Tydlig design element är indelning i grid för att ge balans och för att skapa naturliga negativa utrymmerna (negative space), så att sidan ser ut elegant och harmoniskt med innehållet i fokus. Jag använder mig av unity, genom att använda samma färger igenom hela webbsidan. Min SASS kod har jag valt att dela up i variabel för boda temana, så att jag kan ändra de när jag vill. Dessutom har jag basfilerna som gäller för alla sidor samt en fil för varje md fil (där det behövdes) så att jag kan lättare ändra stylingen på bilder, grid eller någon annan element.


För att uppnå responsivitet har jag använt mig av gridd i de flesta sidorna (föutom dolda dokumentationssidan). I displaylägen använder jag mid 2-3 columner och två rader, menans i mobiltläge gör jag det till en column så att man kan läsa tydligare och för att undvika horisontella scrollbars. För bilderna använder jag mig av cimage och 'picture/srcset' för att anpassa bilder för olika storlekar. Jag har dessutom laggJag märker dock att bilderna laddas upp långsamt och inte på en gång i publicerade versionen. 
Tillgänglighet har jag uppnått med att först kontrollera med 'toptal' om konstrasten och färgerna fungerar för färgblinda, sedan kontrollerade jag med lighthouse. Där behövde jag ändra koontrast i mörkatemans footern och ta bort länkarna från samtliga sidor i header för att uppnå accessibility på 100.


I min andra teman (style-dark), som nås via halvmånen i footern, har jag vald lugna mörka färger. Lila färgen associeras traditionsmässigt med kungar, prestige och kraften. Varmare guldaktiga toner kompenserar kalla känslan från lila färgen och utstrålar rikedom. Här med används en complementary färgschema med en lila basfärg och en komplementfärg (guld) på motsvarande sida av färghjulet.I denna teman valde jag använda mig av 'Open Sans' för rubrikerna och 'Roboto' för bröttextet. Jag tycker att de fonterna är läsvänliga, har bra spacing i och runt bokstäverna. På bilderna har jag dessutom lagt filter för att göra de mörkare och mörkare samt med bättre kontrast för att anpassa för mörka backgrunden.


Projektet fick ganska lätt att genomföra, för att jag hade bra grunder och annars kunde utan svårigheter goggla mig fram information om det jag inte visste. Det tog ändå mycket tid, jag jobbade nästan två veckor för att göra det klart. Svårast var nog få in både text och bilder i projekts-sidan. Eftersom jag har först gjort grid med text i divar i md fil, när jag ville lägga till bilder hittade jag ingen information hur man kan få cimage fungera i html, så jag behövde ändra allt henom att lägga bilderna och texten i meta och hämta metadata på twig filen. det var en rimlig projekt för denna kursen. Jag hade velat föra det mer kreativ och fint som på exempel i kravbeskrivningar, men behövde avgränsa mig till det jag kan i nuläge för att hinna i tid.


Jag tycker att materialet och handledningen var bra. Jag särskild tyckte om Emils föreläsningar med inslag från forskningar. Det har jag saknat lite grann i andra kurser. Jag tyckte om guiden, artiklarna och boken vi fick läsa. Generellt måste jag erkänna att denna kursen var jättekul och roligt. I början var det lite svårt med pico och portfolio filer som vi fick, för att det var massa kod som jag inte ens visste vad det gör. Men Niklas gjorde en riktigt bra jobb med korta videos där han gick igenom principer för pico och mappstrukturen i filerna som vi fick. Jag vet inte ens om det finns något man kan förbättra. Allt verkade vara på en bra nivå. Jag är riktigt nöjd med kursen och skulle rekomendera det till andra. Jag skulle ge betyg 9.
</div>