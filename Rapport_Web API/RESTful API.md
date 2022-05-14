# Rapport - RESTful API

Denna API är delvis **RESTful**. 

Den har inte en **Uniform Interface** då den använder 
sig av 

`/test/reset-db`,

`/api/geo-comments` och 

`/api/geo-comments/{id}`.

Den uppfyller **Client-Server** kravet då klienten är avskilt från servern och endast behöver 
känna till api url:en för att komma åt servern. Både klienten och servern kan utvecklas oberoende av varandra.

Den är **Stateless** då requesten inte behöver någon sparad information för att fullgöras.

APIn uppnår inte kravet för **Cacheable** då jag inte har någon metod för att hantera caching.

Den har ett litet **Layered System** då jag använder mig av två DTO klasser `DTOComment` och `PostComment` vid sidan av databasen.