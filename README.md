# Praktisk-Examination-Filip-Wretner
 Praktisk examantion för kursen "Boot camp för Fullstackutvecklare"

Instruktioner för att öppna och navigera på webbplatsen:
Börja med att klona main repot och välj att öppna 'main' branchen i VS Code, detta görs antingen via Github.com eller via skrivbordsappen Github Desktop

När 'main' är uppe i VS Code se först till att tillägget 'Live Server' är installerat på din enhet.

För att få upp hemsidan högerklicka en av html filer, alla är länkade så spelar inte jättestor roll vart man börjar men home.html är en lämplig start.

När home.html är uppe kan webbplatsen navigeras via navigerings menyn längst upp på sidan eller via direktnavigering via korten längst ned på home.html. På reviews.html fungerar även bilderna som länkar till respektive sida.

För att testa responsivitet kan du, i webbläsaren, högerklicka någonstans på sidan och trycka på 'Inspektera' för att få upp DevTools. Längst upp till vänster i den menyn som kommer upp finns en knapp som aktiverar 'Device Toolbar' som sedan låter dig ändra upplösning för att se hur webbplatsen ser ut på mindre skärmar. 

Kortfattad teknisk beskrivning av hur kraven är uppfyllda:

1. HTML-struktur - Semantiska element som header, footer, nav, main, section och article har använts i samtliga HTML filer. Webbplatsen har totalt 14 sidor, men varje recensionssida är mer eller mindre likadana och navigeringsmenyn är konsekvent och finns med på alla dessa.  

2-3. CSS-styling och responsiv design - Alla sidor är fullt responsiva genom att flex, grid och clamp används tillsammans med media queries. Flex har använts får att designa alla kort samt för att placera ut färre antal kort medans grid har använts för mer strukturkrävande jobb, exempelvis reviews.html som visar alla uppladdade recensioner. Clamp har använts för att försäkra att text alltid är läsbar. Media queries har använts för att göra tillgängliga designer för små, mellanstora och stora skärmar. I media queries har exempelvis grid layout och flex direction ändrats för passa bättre på olika skärmstorlekar. Kodkommentarer finns också med för att tydliggöra CSS struktur. 

4. Tillgänglighet - Följt tillgänglighetsprinciper enligt WCAG 2.1 AA standarder. Detta innebär att webbplatsen är responsiv, har tillräcklig kontrast mellan text och bakgrund, har semantisk HTML struktur samt att alla bilder, länkar och knappar har alt respektive aria-label beskrivningar. 

5. Webbläsarverkyg - Under arbetetsgång har DevTools använts. Främst för att se responsiviteten och säkerställa att all text är läsbar och att det finns tillräckliga avstånd. För att säkerställa att webbplatsen uppfyller tillgänglighets- och SEO-kraven så har Chrome-tillägget Lighthouse använts för att t.ex. hitta bilder som saknar alt-attribut, göra knappar tillräckligt stora och göra texten tillräckligt stor. 

6. Versionshantering med Git - För att öva på versionshantering gjorde jag en branch där jag designade home.html och reviews.html, och en branch där jag designade header, nav och footer vilket skulle vara gemensamt på alla HTML filer. Detta funkade bra men vid merging insåg jag att jag behövde ändra designen och eftersom allt då var i main valde jag att forstätta arbetet endast i main branch.