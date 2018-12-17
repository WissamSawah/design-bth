---
views:

    flash:
        region: flash
        template: anax/v2/image/default
        data:
            src: "image/load.jpeg?q=100&width=1800&height=150&crop-to-fit&area=0,0,-40,0"
---


Laddningstid
=========================

I den här rapporten kommer jag att välja ut tre olika webbplatser och testa hur snabbt respektive webbplats laddas på dator och mobile enheter och analysera om de innehåller några saker som kan förbättras med tanke på laddningstid och användbarhet.


Jag valde att göra undersökningen på samma webbplatser som jag jobbade med på färgschema rapporten. webbplatserna är :

1. <a href= "https://antagning.se">Antagning.se</a>
, är en välkänd webbplats bland alla studenter i Sverige.
2. <a href= "https://aftonbladet.se">Aftonbladet.se</a>, är en av de bästa webbaserade tidningar i Sverige.
3. <a href= "https://www.dropbox.com/business">Dropbox.com</a>, är en bra webbplats som erbjuder användaren en förvaringstjänst.

I verktyg använder jag mig av Google PageSpeed Insights och Firefox network(devtools) för att undersöka Laddningstid, storlek och antalet requests för respektive webbplats. Jag kommer även att redovisa de optimeringsmöjligheter som jag får av google PageSpeed Insights för varje webbplats.

Här är ett excelark för <a href= "https://docs.google.com/spreadsheets/d/1TLqHhUtFPW53D-28IK0hQDLAxEeblty-_USSdLArH2M/edit?usp=sharing">resultaten</a> av alla mätningar som gjordes under undersökningen.

<a href= "https://antagning.se"><h2>Antagning.se</h2></a>

<a href= "../img/antagning.png"><img src="img/antagning.png?w=100" alt="Antagning"/></a>

Antagning.se är den snabbaste och som fick bästa resultat i mätnings-testet med devtools. webbplatsen fick inte så bra betyg för mobil versionen men var den som fick bästa laddningstid bland de tre webbplatserna med 1.56 sek i snitt. Det som kan förbättras är mobile versionen. Några av optimeringsmöjligheter som Antagning.se fick enligt Google PageSpeed Insights är :
<ol>
<li> Aktivera komprimering, Google PageSpeed Insights anser att antagning kan göra webbplatsen mycket snabbare om de komprimerar alla textbaserade resurser som används i webbplatsen. </li>
<li> Ta bort CSS och JavaScript-kod som blockerar renderingen från innehåll  ovanför mitten i webbplatsen. </li>
<li> ta bort oanvänd CSS-kod och förminska HTML-koden.  </li>
</ol>


<a href= "https://dropbox.com/business"><h2>Dropbox.com/business</h2></a>
<a href= "../img/aftonbladet.png"><img src="img/dropbox.png?w=100" alt="Dropbox"/></a>

Dropbox fick lite sämre betyg på den mobila versionen men fortfarande lika bra betyg som antagning på desktop version.
 Den här webbplatsen fick i princip samma optimeringsmöjligheter som Antagning och några till. Några av optimeringsmöjligheter som Dropbox fick enligt Google PageSpeed Insights är:
 <ol>
<li>Optimera bilder, använd andra bildformat än PNG och JPEG för snabbare laddningstid</li>
<li> Ta bort CSS och JavaScript-kod som blockerar renderingen från innehåll  ovanför mitten i webbplatsen. </li>
<li> Utnyttja cachelagring i webbläsaren.</li>
<li> Använd Font-display i CSS-koden för att säkerställa att texten är synlig när typsnitten laddas.</li>
</ol>


<a href= "https://aftonbladet.se"><h2>Aftonbladet.se</h2></a>
<a href= "../img/aftonbladet.png"><img src="img/aftonbladet.png?w=100" alt="Aftonbladet"/></a>

Aftonbladet fick det sämsta betyget på laddningstiden. däremot fick den det bästa betyget på den mobila versionen med 52/100. och lika bra betyg som de andra på desktop versionen med 99/100. Det som kan förbättras är mobile versionen.
Några av optimeringsmöjligheter som Aftonbladet.se fick enligt Google PageSpeed Insights är :
  <ol>
<li>Förminska storleken på DOM-elementen.  </li>
<li> Ta bort CSS och JavaScript-kod som blockerar renderingen från innehåll  ovanför mitten i webbplatsen. </li>
<li> Utnyttja cachelagring i webbläsaren.</li>
</ol>


<h1>Rangordning</h1>

Rangordnad från Bäst till Sämst:  

- Mobil: Aftonbladet, Dropbox, Antagning.
- Desktop: Aftonbladet, Antagning, Dropbox.
- Laddningstid: Antagning, Aftonbladet, Dropbox.

<h1>Analys och sammanfattning</h1>

Några av vanligast förekommande optimeringsmöjligheter som alla webbplatser fick från Google PageSpeed Insights, att de behöver ta bort CSS och JavaScript-kod som blockerar renderingen från innehåll  ovanför mitten. Samtliga webbplatser fick denna kommentaren och anledningen att den gör att renderingen tar mycket längre tid.

En annan optimeringsmöjlighet är att de behöver ta bort den oanvänd CSS-koden och förminska HTML-koden. Google PageSpeed Insights förklarar detta på att oanvänd Css-kod kan orsaka mycket onödiga bytes och längre laddningstid i varje omladdning för webbplatsen.

 Alla webbplatser fick också en optimeringsmöjlighet om att de kan utnyttja cachelagring i webbläsare. Detta för att minska antal resurser  webbläsaren läser in i varje omladdning genom att läsa tidigare hämtade resurser från hårddisken istället för att läsa dem via nätverket.

 De vanligaste förbättringar som alla tre webbplatserna fick finns på den mobila versionen. Samtliga webbplatser fick ganska dåliga betyg på mobil versionen därför behöver de jobba och fokuserar på allt som gör att den versionen blir sämre än desktop version.

 Personligen anser jag att den acceptabla laddningstiden beror oftast på webbplatsens innehåll och om den har många resurser som läsas in av webbläsaren i varje laddning.  Men en rimlig gräns  för laddningstid av en webbplats borde inte ta längre än 2–5 sekunder. Antagning.se klarade denna gränsen väldigt lätt när jag mätte laddningstiden med devtools.

  Om vi tittar på Google PageSpeed resultat av laddningstiden för de tre webbplatser anser vi att Aftonbladet fick det högsta betyget för den mobila versionen, medan antagning fick det sämsta. Men när jag mätte laddningstiden med devtools så fick aftonbladet det sämsta och längsta laddningstid av all dem tre och antagning fick det bästa resultatet. så därför vill jag nu presentera Antagning.se som vinnaren i den här undersökningen.

  <h1>Referenser</h1>

  <a href="https://developers.google.com/speed/pagespeed/insights/">PageSpeed Insights</a>  
  Firefox devtools

  Utvärderingen gjord av Wissam Sawah.
