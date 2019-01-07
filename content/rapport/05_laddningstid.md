---
---
Rapport kmom05
=========================

Jag ska välja ut tre stycken webbplatser och analysera dess laddningstider.

Urval
-----------------------

Mitt urval blev bara av en slump. Jag tog tre stycken webbplatser som jag kom att tänka på först. Den första jag tänker på var vocean.com då min sambo jobbar på det företaget. De andra två blev blocket.se och hemnet.se då jag besöker de webbplatserna väldigt ofta, säkert dagligen och därför kom jag nog att tänka på dem.

Metod
-----------------------

Jag undersökte först de tre webbplatsernas laddningstider samt lite mer information om inläsning av sidan med hjälp av googles PageSpeed Insight, både för dator och mobil samt för tre olika sidor på webbplatsen. All data antecknades i ett excel dokument. Därefter undersökte jag de tre webbplatsernas laddningstid med hjälp av devtools. Varje webbplats analyserades tre gånger och alla värden antecknades, sedan räknade jag ut medelvärdet för alla värden och antecknade dessa.

Resultat
-----------------------

Resultaten av laddningstiderna för mina tre webbplatser lade jag i ett exceldokument som du når via denna länk: https://docs.google.com/spreadsheets/d/1TqOJELr5ejmfu6ZYdCL-soK8txE7haljGTh78g4BbOo/edit?usp=sharing

Generellt för alla webbplatser så laddade sidan snabbare på dator än på mobil vilket vi kan se på värdena i excel dokumentet.

<img src="img/vocean.png" alt="Bild på vocean förstasida" style="width: 600px">

Det som framförallt skulle kunna förbättras på Vocean.com är att skicka bilder i andra format, enligt PageSpeed är det bättre att skicka bilder i JPEG 2000, JPEG XR eller WebP om vi vill att sidan ska kunna ladda snabbare. De kan även optimera deras bilder. Detta kan man göra genom att tex spara bilderna i den storleken som vi vet att de kommer användas, istället för att spara bilderna i full storlek och sedan förminska dem med hjälp av HTML kod.

<img src="img/blocket.png" alt="Bild på blocket förstasida" style="width: 600px">

På blocket.se skulle de kunna minska laddningstiden genom att undvika omdirigeringar till webbplatsen, de använder sig av omdirigering på mobilversionen. Även blocket skulle kunna spara tid genom att ändra formaten på bilderna som de skickar. 

<img src="img/hemnet.png" alt="Bild på hemnet förstasida" style="width: 600px">

Även hemnet omdirigerar användaren när mobilversion används, detta skulle kunna sparas in tid genom att inte omdirigera användaren utan göra webbplatsen responsiv istället. Även hemnet skulle kunna få ned laddningstiden genom att ändra formaten på deras bilder.

Analys
-----------------------

Som jag skrev i resultat så laddar sidan snabbare på dator än på mobil för alla mina webbplatser. Jag tycker ändå att jag fick ganska jämna och bra resultat förutom vid ett tillfälle, när jag kollade i devtools på hemnet.se första gången, då fick jag laddningstid 17.88 sekunder vilket är jättelänge. De andra två analyserna som jag gjorde på hemnet.se 1.59 och 2.28 sekunder så det måste ha blivit något tillfälligt fel med mitt internet eller någonting. 
Generellt verkar alla webbplatser kunna få ned laddningstiden något genom att ändra formaten på bilderna, men framförallt vocean.com skulle kunna få ned laddningstiden ganska mycket om de gjorde ändringar bara på bilderna som de använder.

Jag kommer rangordna mina webbplatser efter följande:
1) BLOCKET.SE
Blocket hade lägst laddningstid på 2.04 sekunder enligt medelvärdet för min analys i devtools och därför hamnar de på förstaplats.
<img src="img/blocket.png" alt="Bild på blocket förstasida" style="width: 600px">

2) VOCEAN.COM
Vocean hade en laddningstid på 3.98 sekunder enligt mitt medelvärde från min analys i devtools. Därför hamnar de på en andraplats.
<img src="img/vocean.png" alt="Bild på vocean förstasida" style="width: 600px">

3) HEMNET.SE
Hemnet fick tyvärr en laddningstid på 7.25 sekunder som medelvärde, detta beror såklart på deras enormt långa första laddningstid som låg på 17 sekunder. Men därför hamnar de på en tredjeplats enligt min analys.
<img src="img/hemnet.png" alt="Bild på hemnet förstasida" style="width: 600px">

Personligen så tycker jag att vocean hade lite för lång laddningstid än vad jag hade önskat, jag kände när jag gick in på deras sida att jag upplevde det som att den laddade sakta, så jag antar då att 3-4 sekunder är för länge för mig personligen. Både blocket och hemnet tyckte jag laddade snabbt.

Frida Lindgren

Referenser
-----------------------

https://developers.google.com/speed/pagespeed/insights/ <br>
http://www.webbmekanikern.se/artiklar/optimera-bilder-for-webben <br>
https://moz.com/learn/seo/page-speed

Övrigt
-----------------------

Frida Lindgren
