# Projektrapport - [Food Rescue](https://github.com/Nettan86/lecture-code/blob/master/Datalagring/Inl%C3%A4mningsuppgifter/projektarbete.md)

<br />

## Planering

***Hur gick planeringen? Varför? Vad kan göras bättre?***

Jag tycker att det har gått relativt bra. Vi har ständigt haft kontakt via discord 
och har försökt att träffas alla vardagar utanför lektionsdagarna. Vi har då suttit 
ett par timmar tillsammans och därefter jobbat var och en för sig. 

Det märks dock en väldig skillnad när man går från att jobba två stycken till att vara 
fyra stycken med att hitta tider som passar alla jämfört med vårt första projektarbete. 
Vi har nog bara suttit alla fyra vid ett tillfälle. Det negativa med att inte kunna sitta 
allihop mer ofta blir ju att det blir mycket tid som ägnas åt att uppdatera någon om dom 
senaste ändringarna i projektet om dom missade ett tillfälle. 

Vet inte riktigt hur man skulle kunna hantera detta bättre då man inte riktigt kan 
hjälpa om det händer något som kommer i vägen för att man ska kunna vara med. Jag 
själv blev sjuk hela andra veckan på projektarbetet och missade därav en hel förmiddag 
där resten av gruppen träffades och arbetade tillsammans. Något man möjligtvis skulle 
kunna göra bättre är att vi i början av projektet kanske skulle ha lite bättre 
framförhållning och bestämt fasta tider då vi skulle pratas vid istället för att varje 
dag jaga varandra och försöka bestämma en tid för morgondagen.

<br />

## Implementering

***Hur gick implementeringen? Motivera lösningar/beslut. Vad kan göras bättre?***

Vi bestämde oss för att använda oss av Sofiias lösning på uppgift 2. Vi skapade sedan 
en [kanban](https://github.com/Nettan86/Datalagring-Projektarbete/projects/1) 
för att lätt kunna se vem som skulle arbeta på varje del. Då vi var 4 i vår grupp
fick vi även lägga till en `LoginManager` så att alla fick var sin del att arbeta på.
Vi har självklart gjort lite ändringar i Sofiias backend så att den bättre skulle 
passa projektarbetet. 

Var tvungen att seeda lite mer in i databasen så att informationen 
i databasen skulle passa med de uppgifter som fronten skulle kunna genomföra. Jag lade 
även en `FindRestaurant()` hjälpmetod i RestaurantBackend för att kunna välja vilken 
restaurang som ska kunna t.ex. titta på sina sålda matlådor. Denna metoden blev sedan 
utbytt till `Weitress()` metoden när `LoginManager` lades in i programmet och ändringar 
fick göras i frontend. Fick även ändra i dom testerna jag redan hade skrivit så dom även 
testade inlogget.

Vi hade planerat att försöka oss på att skapa oberoende tester men kände tyvärr att 
tiden inte riktigt fanns. Vill ju helst inte riskera att göra fel och sabba programmet 
som fungerar som det ska när man inte riktigt har tiden att hinna fixa det.

<br />

## Utvärdering

***Vad blev du mest nöjd med och varför?***

Det jag blev mest nöjd med är att vi faktiskt fick till en vad jag anser vara en relativt
bra "slutprodukt" trots lite svårigheter att få ihop hela gruppen. Jag är också nöjd över 
att jag rätt så lätt lyckades att få till fungerande tester då jag blev sjuk och inte riktigt 
hade energi att sitta framför datorn så mycket.



<br />

Jeanette Ljungkvist 3/12-2021
