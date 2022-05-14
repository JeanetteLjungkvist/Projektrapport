# Projektrapport

Behörighetshanteringen tror jag fungerar som den ska. Hade från början endast tilldelat `[Authorize(Roles = "")]` 
till organizer sidorna men insåg att det fortfarande gick att lägga till events när man var inloggad
som organizer. Fick då lägga till `[Authorize(Roles = "")]` för attendee sidorna också så att en organizer
inte kommer åt do sidorna när man manuelt skriver in adresses och även ta bort join länken på Events 
sidan så att en organizer inte kan länkas vidare till join events m.m.

Jag tycker nog att jag har en bra struktur för att bygga vidare. Alla filer är bra organiserade 
för att man lätt skulle kunna lägga på mer features på hemsidan. Möjligtvis att jag skulle kunna 
dela upp view sidorna så att man har en mapp för de gemensamma views sidorna och separata mappar 
för attendee views och organizer views för att sen lätt skapa fler mappar för mer views med ny 
användningsfunktion.

Jag vet att jag har lite småfel i mitt program t.ex. så läggs inte TicketsAvailable till i eventlistan
när man lägger till ett nytt event. Vet inte heller hur man gör för att även kunna lägga till en tid med
datumet i formen på AddEvent sidan. Finns säkert fler småfel som jag själv inte upptäckt ännu.

Sen det stora felet jag har är att när man loggar in eller registrerar sig så redirectas sidan till 
en tom sida. Registreringen och inlogget fungerar som dom ska och man måste gå tillbaka för att komma
till hemsidan. Detta felet har varit sedan jag lade till Identitypaketet och vad jag förstår så ska 
detta automatiskt fungera. Vad jag har kunnat se så skulle man inte behöva lägga till någon kod eller 
ändra på nån inställning för att få det att fungera. Har inte lyckats att hitta hur jag fixar den buggen.