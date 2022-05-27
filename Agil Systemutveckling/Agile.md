# Agile


- [Agile](#agile)
  - [Den agila arbetsprocessen](#den-agila-arbetsprocessen)
  - [Roller](#roller)
  - [User Stories](#user-stories)
  - [Tidsestimering](#tidsestimering)

<br>

## Den agila arbetsprocessen

Den agila arbetsprocessen är en som drivs in små iterationer. Man arbetar på en liten bit i taget av projektet där man konstant utvecklar, testar, releasar och utvärderar. Anledningen till att man jobbar i små iterationer är för att man ska kunna vara anpassningsbar till förändringar och för att det lättare ska gå att snappa upp eventuella buggar under projektets gång.

Det börjar med ett **sprintplaneringsmöte**. Här bestämmer product ownern vilka user stories som ska prioriteras inför den kommande sprinten. Stories delas upp till mindre features för att bli lättare att tackla. 

Sedan påbörjar man den så kallade **sprinten**. Sprinten är "timeboxad" ock kan vara så lång man vill, men ofta 2-4 veckor. Vissa projekt kanske kräver längre sprintperiod. Under sprintperioden så har man **dagliga scrum** möten. Ett kort litet möte där alla i utvecklingsteamet får göra en snabb liten uppdatering på vad dom gjort sedan senast, vad dom ska arbeta på under dagen och eventuella problem dom stött på. När sprintperioden är klar så ska det finnas ett fungerande inkrement som ska kunna uppvisas för stakeholdern. 

Sedan gör man en **sprint review** där stakeholdern blir inbjuden och man går igenom inkrementet. Man sammlar in feedback. Behövs redigering med backloggen göras så görs det här. 

Efter det så gör man en **sprint retrospective**. Detta mötet är endast mellan scrum mastern och utvecklingsteamet. Man reflekterar över arbetsprocessen och eventuella ändringar sker. Kanske var sprinten för lång eller det kanske var för många features teldelade till sprinten.

Sen börjar man processen på nytt med en ny sprint och fortsätter tills igenom dom olika stegen så många gånger det behövs tills man har en bra slutprodukt.


<br>

## Roller

**Stakeholder**: Är den person som är upphovsman till projektet. Kan vara en kund som anlitar ett företag för att bygga den produkt dom vill ha. Är ofta en person som ej kan programmera och saknar kunskapen om vad som faktiskt krävs för att bygga produkten. Det är dom som avgör om inkrementen går åt rätt håll.

**Product Owner**: Product ownerns största ansvar är att hålla iordning på backloggen. Det är den person som bestämmer vad som ska fyllas på i backloggen utefter shareholdens önskemål. Hen bestämmer sedan vilken ordning backloggen ska arbetas efter och vilka backloggs som ska ingå i varje sprint. Endast en person har denna rollen.

**Scrum Master/Project Manager**: Är den person som ansvarar för att scrum följs. Det kan vara en person som endast arbetar som Scrum Master och ansvarar över flera teams på ett företag, men det kan också vara en person som kanske bara jobbar på ett team och är kanske även en developer. Scrum Masters ser till att alla i teamt kan scrum och ser till att projektet följer scrum arbetssättet. Hen ser till att alla scrum eventen hålls.

**Developer**: Är de personerna som som bygger produkten. Det är en liten grupp med t.ex. programmerare av olika expertis och även kodtestare och analytiker. 

<br>

## User Stories

User stories formulerar rent praktiskt vad en feature i produkten har för värde från kundens synpunkt. Den ska beskriva ett sammanhang för de developers som arbetar på projektet så att dom lätt ska förstå vad som ska byggas, varför det ska byggas och vad för betydelse det har. 

Man börjar med att fylla backloggen med en massa User Stories. Dom läggs i ordning så att de viktigaste stories ligger överst. Vid varje sprintmöte väljs ett par av stories ut som ska arbetas på under sprintprocessen, oftast tas de stories som ligger överst först. User stories bryts ner i mindre features för att programmerarna lättare ska kunna tackla storyn. I slutet av sprintprocessen så har man en färdig user story om den uppfyller "Definition of Done". Om man inte lyckas bli klar med en story så flyttas den tillbaka till backloggen för utvärdering.

<br>

## Tidsestimering

Det är bra att tidsestimera sina stories så att man har en god idee om hur många stories man hinner tackla under en sprint period. Ett väleteblerat team har oftast ett bättre hum om hur mycket man hinner med i sitt team än vad en grupp med nyetablerat team har.

Ett sätt att tidsestimera är att sätta ett värde på alla stories man har. Det kan vara att man estimerar hur lång tid det tar att göra en viss feature. Tar det timmar eller kanske dagar att göra den?. Man kan även estimera dens svårighetsgrad utefter en skala man väljer, ofta Fibonacci skala (1, 2, 3, 5, 8, 13). Det blir lättare att välja vilka issues man ska arbeta på då så att man inte väljer för många issues med för hög svårighetsgrad och då riskerar att inte hinna med så mycket. Helst ska det finnas en bra blandning mellan olika svårighetsgrader.

<br>

Jeanette Ljungkvist 27/5-2022