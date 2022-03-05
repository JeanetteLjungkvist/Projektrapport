# Projektrapport - [Food Rescue](https://github.com/Nettan86/lecture-code/blob/master/Datalagring/Inl%C3%A4mningsuppgifter/projektarbete.md)

<br />

## Planering

***Hur gick planeringen? Varf�r? Vad kan g�ras b�ttre?***

Jag tycker att det har g�tt relativt bra. Vi har st�ndigt haft kontakt via discord 
och har f�rs�kt att tr�ffas alla vardagar utanf�r lektionsdagarna. Vi har d� suttit 
ett par timmar tillsammans och d�refter jobbat var och en f�r sig. 

Det m�rks dock en v�ldig skillnad n�r man g�r fr�n att jobba tv� stycken till att vara 
fyra stycken med att hitta tider som passar alla j�mf�rt med v�rt f�rsta projektarbete. 
Vi har nog bara suttit alla fyra vid ett tillf�lle. Det negativa med att inte kunna sitta 
allihop mer ofta blir ju att det blir mycket tid som �gnas �t att uppdatera n�gon om dom 
senaste �ndringarna i projektet om dom missade ett tillf�lle. 

Vet inte riktigt hur man skulle kunna hantera detta b�ttre d� man inte riktigt kan 
hj�lpa om det h�nder n�got som kommer i v�gen f�r att man ska kunna vara med. Jag 
sj�lv blev sjuk hela andra veckan p� projektarbetet och missade d�rav en hel f�rmiddag 
d�r resten av gruppen tr�ffades och arbetade tillsammans. N�got man m�jligtvis skulle 
kunna g�ra b�ttre �r att vi i b�rjan av projektet kanske skulle ha lite b�ttre 
framf�rh�llning och best�mt fasta tider d� vi skulle pratas vid ist�llet f�r att varje 
dag jaga varandra och f�rs�ka best�mma en tid f�r morgondagen.

<br />

## Implementering

***Hur gick implementeringen? Motivera l�sningar/beslut. Vad kan g�ras b�ttre?***

Vi best�mde oss f�r att anv�nda oss av Sofiias l�sning p� uppgift 2. Vi skapade sedan 
en [kanban](https://github.com/Nettan86/Datalagring-Projektarbete/projects/1) 
f�r att l�tt kunna se vem som skulle arbeta p� varje del. D� vi var 4 i v�r grupp
fick vi �ven l�gga till en `LoginManager` s� att alla fick var sin del att arbeta p�.
Vi har sj�lvklart gjort lite �ndringar i Sofiias backend s� att den b�ttre skulle 
passa projektarbetet. 

Var tvungen att seeda lite mer in i databasen s� att informationen 
i databasen skulle passa med de uppgifter som fronten skulle kunna genomf�ra. Jag lade 
�ven en `FindRestaurant()` hj�lpmetod i RestaurantBackend f�r att kunna v�lja vilken 
restaurang som ska kunna t.ex. titta p� sina s�lda matl�dor. Denna metoden blev sedan 
utbytt till `Weitress()` metoden n�r `LoginManager` lades in i programmet och �ndringar 
fick g�ras i frontend. Fick �ven �ndra i dom testerna jag redan hade skrivit s� dom �ven 
testade inlogget.

Vi hade planerat att f�rs�ka oss p� att skapa oberoende tester men k�nde tyv�rr att 
tiden inte riktigt fanns. Vill ju helst inte riskera att g�ra fel och sabba programmet 
som fungerar som det ska n�r man inte riktigt har tiden att hinna fixa det.

<br />

## Utv�rdering

***Vad blev du mest n�jd med och varf�r?***

Det jag blev mest n�jd med �r att vi faktiskt fick till en vad jag anser vara en relativt
bra "slutprodukt" trots lite sv�righeter att f� ihop hela gruppen. Jag �r ocks� n�jd �ver 
att jag r�tt s� l�tt lyckades att f� till fungerande tester d� jag blev sjuk och inte riktigt 
hade energi att sitta framf�r datorn s� mycket.



<br />

Jeanette Ljungkvist 3/12-2021
