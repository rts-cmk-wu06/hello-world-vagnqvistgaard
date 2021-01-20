# Hello World!
HTML og CSS introduktion Webudvikler grundforløb 2021
<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/0_4ty0Adbdg4dsVBo3.png" /><br>
</p>

## Formål
Formålet med opgaven Hello World! er helt enkelt at ”ramme skærmen”. Det betyder at vi skal arbejde med et HTML dokument i en kode editor og efterfølgende se vores HTML dokument renderet som en webapplikation i Browseren. I arbejdet med at ”ramme skærmen” vil I stifte bekendtskab med en kode editor og få en grundlæggende forståelse for helt fundamental webteknologi.  


## Markup
HTML eller **Hyper Text Markup Language** benyttes til at definere struktur på en hjemmeside. Strukturen defineres ved brug af forskellige HTML tags. Hvert HTML tag repræsenterer et bestemt område i vores webapplikation, hvilket for eksempel kunne være området for applikationens overskrift. HTML består af flere forskellige semantiske tags. Hver enkelt tag repræsenter et specifikt formål, taggets navn beskriver tydeligt for både udvikler og browser hvilket formål der er talt om.

> NOTE: Når vi skriver semantisk markup, bruger vi HTML-tags til at fortælle browseren om elementernes indhold!

Et eksempel på et formål kunne være webapplikationens overskrift. For at definere applikationens overskrift, skal vi bruge et specifikt HTML tag. Den semantiske navngivning af tags hjælper os med at finde det korrekte tag til formålet. I dette eksempel vil det være tagget h1, som er en forkortelse af Heading 1, som I måske allerede kender fra for eksempel Microsoft Word.  

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/HTMLTags.jpg" /><br>
</p>

I dette afsnit skal vi se lidt nærmere på HTML tags. HTML tags har som regel både et åben(start)-tag og lukke(slut)- tag, med undtagelse af nogle få tags, som åbner og lukker i et og samme tag. Lad os tage et nærmere kig på hvordan det tidligere omtalte Heading 1(h1) tag er opbygget

> NOTE: <!-- … --> Kommentar tagget bruges til at kommenterer kildekoden. Kommentar vises ikke i browseren!

## HTML Heading 1 tag

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/Heading.jpg" /><br>
</p>

Karakteren imellem mindre end tegnet og større end tegnet indikerer taggets formål. I eksemplet oven for er h1 en forkortelse for Heading 1. Den overskrift som vi ønsker at vise i vores webapplikation, skal placeres imellem h1 elementets åben- og lukketag. Se grafik umiddelbart herunder.

## HTML element

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/HTMLElement.jpg" /><br>
</p>

Når et HTML element bliver renderet i browseren vises det indhold som er placeret imellem åben og lukke tagget.

I ovenstående eksempel vil det derfor alene være teksten HELLO WORLD!, der vil blive vist i browseren.

> NOTE: Et HTML element omfatter et åbentag, et lukketag og hvilket som helst indhold placeret herimellem!

## Markup

I dette afsnit skal vi se nærmere på følgende seks semantiske HTML tags: Header, Nav, Main, Article, Section og Footer.  
Vi skal bruge de seks udvalgte tags i praksis, til at definere struktur for hello world applikationen. Før vi kan begynder at skriv markup, skal der oprettes en projektmappe og heri en index.html fil.

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/VSCode.jpg" /><br>
</p>

Den første opgave består i at skrive den samme markup, som der
ses på skærmbilledet herover. Vær omhyggelig, syntaksen er vigtig og selv den mindste tastefejl, kan betyde at applikationen ikke
renderes som det forventes. Indryk mellem tags er vigtig for dokumentets læsbarhed og ’debug-og-samarbejds-venlighed’ og er derfor en helt essentiel del af arbejdet med at skrive kode. Når I er færdige med at skrive ovenstående markup, er det tid til at eksekverer dokumentet i browseren.

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/WhatWeWant.jpg" /><br>
</p>

Måden vi gør vores applikations userinterface mere indbydende, tilgængeligt og fleksibelt på, er ved at tilføje et præsentations lag. Det kommer vi nærmere ind på, men først en forklaring af de seks tag, som vi skal arbejde med.

> NOTE: Vi benytter HTML til struktur, CSS til præsentation og JavaScript til interaktion i vores applikationer!

## Tags forklaring
***Mange tags er designet til specifikke typer af indhold eller bruges i en specifik kontekts. Disse tags kaldes specifikke tags***

**Header**   
Elementet bruges til introducerende indhold, hvilket eksempelvis kan være en overskrift eller et logo. Elementet vil også kunne bruges som placering for eksempelvis en søge- eller loginformular, navigation etc.

**Nav**   
Elementet bruges hovedsageligt til at præsenterer applikationens navigations som kan bestå af både interne og eksterne links.

**Main**   
Elementet bruges til at præsenterer indhold som relaterer sig direkte til applikationens centrale emne eller funktionalitet.

**Article**   
Elementet bruges til at præsenterer selvstændigt indhold som vil kunne genanvendes i andre sammenhæng hvilket eksempelvis kunne være; en blog post, en artikel eller en nyheds historie.

**Section**   
Elementet bruges til at repræsenterer fritstående indhold som ikke kan repræsenteres af et mere specifikt semantisk element.

**Footer**   
Elementet bruges som ofte til at præsenterer information omkring applikationens ophavsmænd, copyright information eller links til relevant information.

## Layout

CSS eller **Cascading Style Sheets** bruges til at definere hvordan et HTML dokument skal præsenteres i Browseren. Start med at oprette en style.css fil og placerer den i roden af projektmappen. Når css filen er oprettet skal den linkes til vores index dokument. Dette foregår i filen index.html. Se nedenstående eksempel linie 9.

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/Index.jpg" /><br>
</p>

Link tagget definerer et link imellem det aktuelle HTML dokument og en eksterne ressource. I dette tilfælde er denne eksterne ressource vores stylesheet. Når vi bruger CSS til at ændre udseende på vores HTML elementer, gør vi det ved at definerer regler for hvordan HTML elementet skal præsenteres. I eksemplet herunder fremgår det hvordan en css-regel defineres.

## CSS-Regel eksempel

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/Css-regel.jpg" /><br>
</p>

En CSS regel anvender en **selektor** som indikation for hvilket HTML element der skal tilføjes style til. I eksemplet herover defineres en regel for alle img tags i HTML dokumentet. I deklarationen er angivet en **egenskab** for width med en **værdi** på 100%. Det betyder, at alle billeder skal vises med en bredde på 100% af det element, de er placeret i.

## CSS regler i praksis

For at opnå det ønskede layout, skal der definere CSS regler for flere af de HTML elementer vores applikations markup består af. Prøv at definere css reglerne fra skærmbilledet umiddelbart herunder en af gangen. Test applikationen i Browseren for hver gang du har defineret en ny regel. På den måde undgår vi at skulle fejlfinde et helt stylesheet, fordi vi er klar over hvilken CSS regel vi aktuelt arbejder på, hvis noget mod forventning ikke skulle virke.  

Happy Hacking!

<p align="center">
  <img src="https://github.com/rts-cmk-opgaver/HelloWorld/blob/main/Media/Stylesheet.jpg" /><br>
</p>

