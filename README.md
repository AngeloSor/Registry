# Registry
Progetto di Alten con Angular e .NET

Registry consente di tenere traccia delle persone che hanno partecipato o parteciperanno al progetto Alten.
Registrerà dal "primo contatto" del dipendente all'interno di Alten fino all'assunzione o al licenziamento.

Ci saranno due tipi di attori:
- admin, che avrà pieno accesso ai dati dell'utente e potrà modificarli;
- utente, che potrà visualizzare solo i propri dati;

Questo progetto si basa principalmente su Keycloak, integrato con ASP.Net per Web.API, JWTAuthentication per autorizzare / autenticare gli attori, Docker per containerizzare l'immagine del software, Smtp4dev e Angular.

Link backend: https://devops.altenitalia.it/Alten-Sandbox/StagiBox
https://dev.azure.com/Alten-Recruiting/Registry/_git/Registry%20API?version=GBmain

Link frontend: https://dev.azure.com/Alten-Recruiting/Registry/_git/Registry%20Client?version=GBfeature

Link al progetto: https://registryclient-feature.azurewebsites.net/
