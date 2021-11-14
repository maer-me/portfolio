---
Title: About
Descripition: About the technologies used on this website
---

Om sidan och dess teknologier
=============================

Struktur
-----------------------------
![Lite kod](%assets_url%/img/code.jpg "Kod på en skärm")

Denna sida är byggd med hjälp av ramverket [Pico](https://picocms.org/) vilket är ett så kallat *flat file cms*. Att ramverket är *flat file* betyder att webplatsen inte byggs upp av en databas utan att innehållet finns i filer. Varje sida byggs upp med hjälp av en mall som med html beskriver hur sidan ska struktureras och in i denna mall skickar vi innehållet i form av *markdown*-filer som innehåller text, länkar, sökvägar till bilder och liknande. *Markdown* är ett trevligt språk att skriva innehåll till websidor med, man kan beskriva det som att skriva html-kod utan att behöva bry sig om själva html-biten vilket gör att det går snabbt att producera innehåll. Sidan använder sig av externa bibliotek för ikoner och typsnitt. För ikoner använder jag [Fontawesome](https://fontawesome.com/) och för typsnitt [Google fonts](https://fonts.google.com/). De ikoner som används i kmom02 visas längst ned till höger i sidans footer och länkar till mitt GitHub-repo för projektet och till SASS hemsida. Typsnitten som används beskrivs i avsnittet Design.

Design
-----------------------------
![En banan](%assets_url%/img/design.jpg "En designad banan")

För den övergripande designen av mitt portfolioprojekt valde jag att skapa ett mörkt tema. Sidans stylesheet byggs upp med hjälp av SASS, *Syntactically Awesome Style Sheet* som är en CSS-preprocessor och ger extra funktionalitet till CSS som variabler, nästlade regler och mycket mer. Det är första gången jag stötet på en CSS-preprocessor men jag inser vilket kraftfullt hjälmedel det kan vara vid större projekt eller om man vill skapa en mer avancerad design för sin webplats. För kmom02 byggde jag ett tema och skapade en SASS-struktur för det. Jag har tre stycken undermappar för mitt tema:
<br>
<br>
- content-divs: Här sparar jag regler för sektioner av sidan som exempelvis header, footer, title.
- device: Innehåller mediaqueries och regler som hör till dessa, importeras sist i min style.scss
- main: Övergripande regler för webplatsen, färger och stilar för body, html, osv... Innehåller grundregeler för typografi och en fil där mina variabler sparas.
<br>
<br>

Jag har inte ändrat sidans grundstyle supermycket, förutom att implementera mitt tema så har jag justerat bredden för main lite beroende på skärmbredden. För mina typsnitt så har jag valt att ladda in tre stycken från Google fonts, Roboto för min brödtext (jag gillar Robot så jag lät det vara kvar efter exemplet), för mina rubriker använder jag Lato och till kodsegmenten och rubriken i Title-elementet använder jag Fira Code.
<br>
<br>
Alla bilder, förutom mina privata, är hämtade från [unsplash](https://unsplash.com/) och licensfria.

