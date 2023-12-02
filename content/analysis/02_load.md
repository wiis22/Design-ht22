---
Title: LOAD_02
Description: Detta är en rapport från kmom05

---

Laddningstid
=======================

Utvärdering av 3 nyhets webbplatsers laddningstider och andvändbarhet.

Urval
-----------------------

jag valde att jämföra 3 nyhetssidor och deras val är expressen.se, aftojbladet.se och svt.se. Då var de mest besökta webbplatserna som har med nyheter att göra enligt data från Semrush.

Metod
-----------------------

Webb Analysen kommer att utföras i ett inkognitofönster så att ingen personlig data påvekar mätningen. Mätningarna kommer att göras i ett fullstort läge via en dator och en emulerad telefon. Datan skulle kunna skilja sig åt om den återskapas på en telefon då mätdatan är från en emulerad telefon.
Datan kommer från inspektionsverktygen som medföljer i Chrome och hittas via nätvärk fliken.

Pagespeed.web.dev används även för att samla in mer data såsom LCP, FID och tillgänglighet.

###Largest Contentful Paint (LCP):
Mäter hur snabbt huvudinnehållet tar för att ladda in på en webbsida och är synlig för användaren.(1)

###First Contentful Paint (FCP):
Mäter tiden från att sidan börjar laddas tills någon del av sidans innehåll renderas på skärmen. (2)

###First Input Delay (FID):
Mäter tiden från att en användare första gången interagerar med en sida till den tidpunkt då webbläsaren faktiskt kan börja bearbeta händelsehanterare som svar på den interaktionen. (3)

###Tillgänlighet:
Ett mått i procent som visar hur tillgänglig  sidan är för användare med nedsatt förmåga.

Resultat
-----------------------

<img src="%base_url%/assets/img/kmom05/SVT.png" alt="SVT Hemsida" style="margin: 1em 1em 1em 1em; width: 50%;">
###SVT
Laddade in 49 resurser (0,731 MB) på 0,547 sekunder och har en tillgänglighet på 100% i ett datorläge. SVT laddade också in 49 resurser (0.713 MB) på 0,532 sekunder och den har också en tillgänglighet på 100% i telefon läge. Är snabb och optimerad vilket gör den till den bästa av webbplatserna.

<img src="%base_url%/assets/img/kmom05/Aftonbladet.png" alt="Aftonbladet Hemsida" style="margin: 1em 1em 1em 1em; width: 50%;">
###Aftonbladet
Laddade in 79 resurser (1,6 MB) på 5,43 sekunder och har en tillgänglighet på 86% i ett datorläge. Aftonbladet laddade in 64 resurser (1,2 MB) på 5,22 sekunder och en tillgänglighet på 89% i telefon läge. Lite segare än SVT men är ändå hyfsat snabb, det som verkar ta och dra upp laddningstiden är annonser då FCP ligger på 0,5/0,8 och LCP ligger på 2,2/3,2 (Dator/Mobil).

<img src="%base_url%/assets/img/kmom05/Expressen.png" alt="Expressen Hemsida" style="margin: 1em 1em 1em 1em; width: 50%;">
###Expressen
Laddade in 324 resurser (0,989 MB) på 15,99 sekunder och har en tillgänglighet på 93% i ett datorläge. Expressen laddade in 164 resurser (0.804 MB) på 2,54 sekunder och har en tillgänglighet på 89% i telefon läge.
De är snabba på att ladda in FCP och LCP då båda ligger under 2 sekunder. Men det tar en väldigt lång tid innan allt har laddats in i webbläsaren när det är i datorläge.


<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTa27WI6gcUOaTNoT0hasPsTaNyxL4ijxuyFL7Zncn8prxT6T_v0h4GxTCvGOArJ5Uk1_jd_CntaEFr/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" style="width: 100%;height: 10em">
</iframe>


Analys
-----------------------

Det märks att alla tre av webbsidorna är ofta besökta då det ser ut som alla försöker optimera att innehållet ritas in snabbt.

Av dessa webbsidor så vinner SVT enkelt enligt mig då de laddas in väldigt fort och har 100% i tillgänglighet. Sen lägger jag Aftonbladet då det både är snabbare och har en högre procentuell tillgänglighet än Expressen. Däremot så är tillgängligheten något de måste försöka få upp. På tredje plats lägger jag Expressen mest för att det tar så lång tid att ladda in alla resurser, även om tillgängligheten är högre än Aftonbladet.

Den absoluta laddningstiden för mig får inte överstiga mycket mer än 5 sekunder, så som Expressen har att det tar så lång tid att ladda in alla resurser är inte något jag gillar. Men som alla sidorna ändå hade var att de laddade in huvudinnehållet snabbt. Men det bör inte överstiga mycket mer än 2 sekunder då det börjar kännas segt efter det. Och det klarade alla sidorna men Aftonbladet var lite segt i jämförselse i mobilt läge.


Referenser
-----------------------

[SVT.se](https://www.svt.se/)

[Aftonbladet.se](https://www.aftonbladet.se/)

[Expressen.se](https://www.expressen.se/)

https://web.dev/articles/lcp (1)

https://web.dev/articles/fcp (2)

https://web.dev/articles/fid (3)


Övrigt
-----------------------
Skriven av Wiktor Isaksson