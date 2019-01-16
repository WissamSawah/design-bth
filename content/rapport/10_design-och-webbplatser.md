Analys valfri
=============
Här kommer jag att välja ut tre olika webbplatser för att testa hur fort de laddas och vad de kan göra för att förbättra laddningstiden.

Urval av webbplatser
=====================
Jag valde att göra undersökningen på samma webbplatser som jag jobbade med på Webbplatsdesign rapporten anledningen att jag tycker det kan vara intressant att se hur snabbt de tre webbplatserna kan laddas med tanken att de har ganska mycket resurser och bilder med hög kvalite. webbplatserna är :Booking.com, Expedia.com och Skyscanner.se.

Metod
=======
Jag kommer att använda mig av Google PageSpeed Insights och Firefox network(devtools) för att undersöka Laddningstid, storlek och antalet requests för respektive webbplats. Jag kommer även att redovisa de optimeringsmöjligheter som jag får av google PageSpeed Insights för varje webbplats.

Här är ett excelark för <a href= "https://docs.google.com/spreadsheets/d/1qVArBgy0K3sT_Rc2qRBXQAk9DIcs1baKU_ViCXz8sjE/edit?usp=sharing">resultaten</a> av alla mätningar som gjordes under undersökningen.




Resultat
=========
<a href= "http://www.booking.com"><h2>Booking.com</h2></a>

<a href= "../img/booking.png"><img src="img/booking.png?w=100" alt="booking"/></a>

Booking.com är den snabbaste webbplatsen och som fick bästa resultat på både mobile och desktop versionen enligt Google PageSpeed Insights. Webbplatsen fick inte så bra betyg på den mobila versionen den fick 38% men den var bästa betyget bland de andra webbplatserna. Den fick även bästa resultat på desktop versionen jämfört med de andra två webbplatserna.

Webbplatsen fick även bästa laddningstid bland dem tre webbplatserna med 3.27 sek i snitt enligt Firefox devtools. Den som kan förbättras är den mobila versionen och antal resurser som laddas i varje omladdning till webbplatsen. de behöver även ta bort CSS och JavaScript-kod som blockerar renderingen från innehåll ovanför mitten i webbplatsen för snabbare omladdning.



<a href= "http://www.skyscanner.se"><h2>Skyscanner.se</h2></a>

<a href= "../img/sky.png"><img src="img/sky.png?w=100" alt="sky"/></a>
Skyscanner fick lite sämre betyg på desktop versionen och det sämsta betyget på den mobila versionen enligt Google PageSpeed Insights. En av de viktigaste anledningar att webbplatsen har betydligt mycket mer resurser och bilder med hög kvalite än booking.com webbplatsen. Webbplatsen fick även en ganska bra laddningstid på 3.81 sekunder i snitt enligt mätnings-testet med Firefox devtools.

Det som kan förbättras är den mobila versionen och storleken på bilderna som finns i webbplatsen, de gör att laddningstiden till webbplatsen blir mycket längre och långsammare. Några av bilderna tog lång tid och var inte komprimerade. En av bilderna fick även statuskod 204 och bromsade upp laddningen. De behöver också förminska storleken på DOM-elementen och ta bort CSS och JavaScript-kod som blockerar renderingen från innehåll ovanför mitten i webbplatsen för bättre och snabbare laddningstid.

<a href= "http://www.expedia.com"><h2>Expedia.com</h2></a>

<a href= "../img/expedia.png"><img src="img/expedia.png?w=100" alt="expedia"/></a>

Expedia är den webbplatsen som fick sämsta betyget på både mobile och desktop version. Anledningen att de använder sig av många bilder med väldigt hög kvalite vilket gör att webbplatsen tar så mycket längre tid att laddas. De har även rätt så många resurser som laddas ner i varje omladdning av webbplatsen.

Det som kan förbättras enligt Google PageSpeed Insights är både mobile och desktop versionen de behöver ta bort Css koden som inte används. Förminska Javascript koden och förminska storleken på DOM-elementen. de kan även utnyttja cachelagring i webbläsare  för att minska antal resurser webbläsaren läser in i varje omladdning genom att läsa tidigare hämtade resurser från hårddisken istället för att läsa dem via nätverket.

Analys
======
Som vi ser i undersökningen så alla tre webbplatser fick nästan lika optimeringsmöjligheter. De vanligaste var att de behöver ta bort CSS och JavaScript-kod som blockerar renderingen från innehåll ovanför mitten men även  utnyttja cachelagring i webbläsare för att minska antal resurser webbläsaren läser in i varje omladdning. Alla tre webbplatser fick tips på förbättringar på den mobila versionen utom Expedia som fick optimeringsmöjligheter på både desktop och mobila versionen pga de stora och flera resurser som webbplatsen innehåller.

Rangordning
===========
Rangordnad från Bäst till Sämst:

Mobil: Booking, Expedia, Skyscanner.  
Desktop: Booking, Skyscanner, Expedia.  
Laddningstid: Booking, Skyscanner, Expedia  


Referenser
===========
Firefox devtools
PageSpeed Insights

Utvärderingen gjord av Wissam Sawah.
