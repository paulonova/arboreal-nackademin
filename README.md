# arboreal-nackademin
Inlämningsuppgift HTML &amp; CSS - Nackademin

<a href="https://paulonova.github.io/arboreal-nackademin/">Link till GitPages</a>

<h2>Individuell examination 1</h2>
Hemsida & peer review


<h2>Krav</h2>
Sidan använder sig av en fler-kolumns-layout.
Du använder dig av semantisk HTML för att strukturera upp ditt innehåll. <div> ska enbart användas för styling-syfte.
Du använder dig inte av id för att styla din sida. Styling ska ske med _class_ eller <tag>. Det ska heller inte förekomma inline styling med style-attributet i HTML.
Du använder dig huvudsakligen utav flexbox för att positionerna ditt innehåll men andra positioneringstekniker får även förekomma (såsom float).
Du använder i majoritet relativa måttenheter: % och rem/em. Användandet av enheterna ska vara konsekvent, dina marginaler och padding ska inte ha massor av spridda px-värden (såkallade magic numbers).
Sidan har en meny där man kan gå till de olika undersidorna. Sidan får vara en one page där det inte finns några undersidor (pricing, themes, about, contact t.ex.) men då ska menyn länka till de olika rubrikerna på sidan (scrolla till rubriken).
Sidan innehåller all information ovan om företaget, logotyp, slogan, pricing etc. Hur det är strukturerat är dock upp till dig. Tabellen behöver t.ex. inte se exakt ut som den ser ut i detta dokument utan det viktiga är att man tydligt ser innehållet och att det är väl grupperat så man ser vilken information som hör till vad. Tabellen behöver inte heller vara av typen table.
Sidan innehåller ett korrekt formaterat kontaktformulär som ska vara en <form> där man kan fylla i namn, telefonnummer, email, företag och meddelande. Inputfälten ska vara av rätt type och ha labels.
<br>
Projektet ska ha en README.md i rootmappen som beskriver projeket och som du även ska använda för att skriva ner återkopplingen i.
Sidan får innehålla JavaScript men det ger inget extra, sidan examineras utifrån html och css.
HTML och CSS är korrekt indenterad.
HTML och CSS är validerad via W3C HTML Validator/W3C CSS Validator och ska inte innehålla varken fel eller varningar. Du ska bifoga den output du får utav valideringen i din README.md.

<h2>Feedbackpunkter</h2>
<h3>Förslag på feedbackpunkter:</h3>
<ol>
  <li>Är HTMLen logiskt upplagd, korrekt indenterad och lättläst?</li>
  <li>Är CSSen logiskt upplagd, korrekt indenterad och lättläst?</li>
  <li>Tydlig namngivning av klasser så att man förstår vad det är som stylas?</li>
  <li>Finns det överflödig CSS? För många selektorer eller för specifika selektorer? Upprepande av egenskaper i CSSen?</li>
  <li>Är gränssnittet (designen) tydligt indelad och lättanvänd?</li>
  <li>Finns det ändringar i designen som skulle kunna underlätta användandet av sidan? Öka kontrasterna på sidan? Använd mer marginaler/padding för att göra saker luftigare? Finns det element som är ojämnt centrerade etc.?</li>
  <li>Övriga synpunkter</li>
  
  <p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

<br><br>
<h1>Brandom feedback</h1>
<p>Feedback:
Fantastiskt bra jobbat! Bra responsivitet med navigationen, bra användning av flexbox för att låta innehållet placeras över varandra. Inga onödiga px-värden, och fint designat! 

Här är några punkter på förbättringar som jag kunde hitta efter att ha använt din sida några minuter:

* "a-taggarna ovanför dina div" (t.ex. rad 36, 60 etc.) är överflödiga!  Jag misstänker att du tänkt använda de för navigation? Då kan du istället bara lägga ett id på den <div> eller <section> du vill länka till, istället.
* En hel del tom yta mellan din <form> och innehållet bredvid(ikonen, adress etc).
* I din form har du lagt type=“number” på telefonnummer. Det gör att det kommer upp en liten scroll när man ska fylla i det fältet. Det är nog bättre använda en annan type.</p>
