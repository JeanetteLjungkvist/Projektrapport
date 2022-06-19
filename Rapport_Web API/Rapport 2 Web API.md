## Rapport 2 Web API

<br>

### **Beskriv hur du löste att olika GeoComment versioner behövde föras in i databasen. Hade man kunnat lösa det på något annat sätt?**

Man skulle kunna ha lagt till en modell-klass för den andra versionen.
Jag valde att modifiera min Comment-model så att den även innehöll en Title-property och har sedan användt mig av DTO-klasser för att få dom olika versionerna att fungera som dom ska. 

<br>

### **Beskriv ett annat sätt du hade kunnat versionera i stället för att använda en query parameter. På vilket sätt hade det varit bättre/sämre för detta projekt?**

Det som är bra med query-versionering är att det lätt syns i url:en vilken version man kollar på. Det kan dock lätt se väldigt stökigt ut då inte url:en blir lika "ren". Vill man ha lite finare uri så hade man kunnat lägga till verisionerna i headern. Nackdelen med det är att det är inte lika lätt att manuellt få tillgång till sin data då man inte skriver in sökvägen i browsern och istället måste använda ett program som t.ex. postman. 

<br>

### **Ge exempel och förklaring på när man vill ha behörighetskontroll för en webbapi och när man inte vill ha det.**

Man vill göra en behörighetskontroll när svaret som skickas från servern ska bero på användarens behörighet. Det kan t.ex behövas för att skydda känslig information. I detta programmet så ska man kunna titta runt som man vill men så fort man vill göra något t.ex lägga till en post så krävs authentication för att en användare ska få rätt authorization.







