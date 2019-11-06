# Resources

- https://techbeacon.com/security/security-testing-unlike-other-qa-what-you-need-know

Successful quality control begins at the unit test level, right on the developer's laptop, where bugs are the easiest to spot and the least expensive to fix. Developers are already in a defensive programming mindset as they create unit tests, thinking of abuse cases alongside use cases.

- https://techbeacon.com/enterprise-it/how-machine-learning-boosts-application-security-testing
- https://techbeacon.com/security/owasp-top-ten-update-what-your-app-sec-team-needs-know

- https://www.owasp.org/images/1/1b/Webservice_and_Microservice_Security_-_Jim_Manico.pdf

# SSL TLS
- https://en.wikipedia.org/wiki/Diffie–Hellman_key_exchange

# a deplacer 
SLA pour micro services
- https://team.goodeggs.com/writing-microservice-slas-eb7cfa387b31
- https://www.microservice-api-patterns.org/quickstart

Ecrire une SLA est une pratique utile dans la mesure ou elle va permettre de se poser des questions encore ignorées.
Est ce que j'assure une haute disponibilité ?
Quelles sont les performances que je dois garantir pour mes consumers ?
Si mon nombre de consumer augmentent significativement, puis-je assurer a nouveau la performance garantie en effectuant un scaling vertical/horizontal ?
Est ce que l'architecture de mon projet me permet un scaling horizontale ? (base de données)

Autre point a inclure dans la SLA :
 - heures de fonctionnement mandatory a cause de copie de données d'un système externe vers la bdd du micro-service
 - les requirements de sécurité : token d'authentication, encryption de la connection via SSL


- https://docs.newrelic.com/docs/apm/new-relic-apm/apdex/apdex-measure-user-satisfaction
