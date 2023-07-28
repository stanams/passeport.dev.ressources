# API Design
L'API design (conception d'interface de programmation) se réfère à la création et à la définition des interfaces et des contrats d'une API pour faciliter l'interaction entre différentes parties logicielles. Cela implique de concevoir des points d'entrée, des structures de données, des méthodes et des comportements cohérents, intuitifs et bien documentés afin de fournir une expérience d'utilisation optimale et une intégration facile pour les développeurs utilisant l'API.

#### API REST
**Description**: Une API REST (Representational State Transfer) est un style d'architecture de services web qui utilise les principes et les protocoles du web pour créer des interfaces d'API. Elle utilise des méthodes HTTP standard telles que GET, POST, PUT, DELETE pour permettre aux clients de communiquer avec les ressources d'une application, en utilisant des représentations de données basées sur des formats tels que JSON ou XML pour transférer les données. On préferera aujourd'hui le format JSON au XML.

**Ressources**:\
[Best Practice for REST API Design](https://stackoverflow.blog/2020/03/02/best-practices-for-rest-api-design/)\
[How to use REST API](https://www.freecodecamp.org/news/how-to-use-rest-api/)\
[RESTful Web API Design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)


#### GraphQL APIs
**Description**: Une API GraphQL est une interface d'API qui permet aux clients de demander spécifiquement les données dont ils ont besoin et de recevoir des réponses structurées en fonction de ces demandes. Elle offre une flexibilité accrue en évitant le surchargement de données inutiles, permettant ainsi une récupération efficace des données et une communication optimisée entre les clients et les serveurs.

**Ressources**:\
[The Fullstack Tutorial for GraphQL](https://www.howtographql.com/)\
[The Biggest Misconceptions About GraphQL](https://xuorig.medium.com/the-biggest-graphql-misconceptions-df597ce5f0f5)\
[REST to GraphQL in minutes](https://medium.com/backstagewitharchitects/rest-to-graphql-in-minutes-44f3b86cf79f)

#### Handling Errors
**Description**: Le "error handling" (gestion des erreurs) dans les API concerne la manière dont les erreurs sont détectées, gérées et communiquées aux clients lorsqu'une requête échoue. Cela inclut la définition de codes d'erreur appropriés, la fourniture de messages d'erreur descriptifs et la prise en charge de mécanismes tels que les réponses HTTP avec les codes d'état correspondants ou les structures de données JSON contenant des informations sur l'erreur. L'objectif est de fournir aux clients des informations claires et précises sur les erreurs survenues afin de faciliter le débogage, la résolution de problèmes et l'amélioration de l'expérience utilisateur.

**Ressources**:\
[REST API Error Handling Best Practices](https://josipmisko.com/posts/rest-api-error-handling)\
[Best Practices For REST API Error Handling](https://blog.apilayer.com/best-practices-for-rest-api-error-handling/)\
[Guide To GraphQL Errors](https://xuorig.medium.com/a-guide-to-graphql-errors-bb9ba9f15f85)

#### Authentication strategies
**Description**: L'authentification d'API avec JWT (JSON Web Token) est un mécanisme de sécurité permettant de vérifier l'identité des clients ou des utilisateurs qui accèdent à une API en utilisant des jetons cryptographiquement signés. Les clients envoient un JWT dans chaque requête pour prouver leur authentification, ce qui permet au serveur de vérifier et de valider l'identité de l'utilisateur sans nécessiter de stockage de session côté serveur.

**Ressources**:\
[Basics of Authentication](https://roadmap.sh/guides/basics-of-authentication)\
[Understand user authentication](https://swoopnow.com/user-authentication/)\
[Learn Using JWT with Passeport Authentication](https://medium.com/front-end-weekly/learn-using-jwt-with-passport-authentication-9761539c4314)

#### Authorization strategy
**Description**: Une stratégie d'autorisation d'API est une approche basée sur les ACL (Access Control Lists) qui définit les autorisations d'accès pour contrôler les actions des utilisateurs ou des clients sur une API. Elle spécifie les règles et les restrictions d'accès attribuées à des utilisateurs ou à des groupes spécifiques, permettant ainsi de déterminer qui est autorisé à accéder à quelles ressources et quelles actions sont autorisées pour chaque entité.

**Ressources**:\
[What Is Authorization?](https://auth0.com/intro-to-iam/what-is-authorization)\
[Differences between Authorization & Authentication](https://www.sailpoint.com/identity-library/difference-between-authentication-and-authorization/)\
[AAA explained](https://www.youtube.com/watch?v=BQMp-HjAyCk&pp=ygUbYXV0aG9yaXphdGlvbiBhY2wgZXhwbGFpbmVk)

#### gRPC
**Description**: gRPC est un framework open-source basé sur le protocole RPC (Remote Procedure Call) qui permet la communication efficace et interopérable entre des services distribués. Il utilise le protocole HTTP/2 pour le transport de données, offre une sérialisation binaire compacte et prend en charge la génération automatique de code dans différents langages, offrant ainsi des performances élevées, une scalabilité et une facilité de développement pour la création de systèmes distribués.

**Ressources**:\
[Official Docs](https://grpc.io/)\
[gRPC introduction](https://www.youtube.com/watch?v=gnchfOojMk4&pp=ygUYZ3JwYyBleHBsYWluZWQgZXhwbGFpbmVk)\
[Why gRPC was invented](https://www.youtube.com/watch?v=u4LWEXDP7_M&pp=ygUYZ3JwYyBleHBsYWluZWQgZXhwbGFpbmVk)\

#### Security Principles
**Description**: Au delà de l'authentification des requêtes, il est essentiel de mettre en place des mesures de validation et de filtrage des données, de prévenir les attaques courantes telles que les injections SQL ou les attaques de déni de service, et de garder l'API à jour avec des correctifs de sécurité réguliers pour maintenir un niveau de sécurité optimal.

**Ressources**:\
[API Security Checklist: What You Need To Know](https://www.apisec.ai/blog/api-security-checklist)\
[API Security Checklist](https://github.com/shieldfy/API-Security-Checklist)\
[API Security Checklist](https://salt.security/blog/api-security-checklist)\

#### 3rd Party APIs
**Description**: La gestion des API de tiers (3rd party API) implique la gestion et l'intégration des interfaces de programmation fournies par des fournisseurs externes dans une application ou un système. Cela comprend la gestion des autorisations et des clés d'API, la configuration des appels API, le suivi des quotas d'utilisation, la gestion des erreurs, la synchronisation des versions et la gestion des dépendances externes pour assurer une intégration fluide et fiable avec les API tierces.

**Ressources**:\
[5 Best Practices To Integrate With 3rd Party APIs](https://hackernoon.com/5-best-practices-for-integrating-with-external-apis)\
[When You Integrate with Third-Party APIs](https://medium.com/ichef/when-you-integrate-with-third-party-apis-some-best-practices-1dcc13100a24)\
[Awesome List - Open Public APIs](https://github.com/public-apis/public-apis)\

#### API Gateway
**Description**: Une API gateway est un composant centralisé qui agit comme point d'entrée unique pour les requêtes provenant de clients externes. Elle permet de gérer l'authentification, l'autorisation, la transformation des données, la mise en cache et d'autres fonctionnalités communes liées aux API, facilitant ainsi la création, la gestion et la sécurisation des services API.

**Ressources**:\
[What is an API Gateway](https://www.youtube.com/watch?v=NKKzMEmashw&pp=ygURYXBpIGdhdGV3YXkgZ3VpZGU%3D)\
[What is an API Gateway by Nginx](https://www.nginx.com/learn/api-gateway/)\
[AWS API Gateway Guide](https://hands-on.cloud/aws-api-gateway-guide/)\

#### Gestion des CORS
**Description**: La gestion des CORS (Cross-Origin Resource Sharing) est un mécanisme de sécurité dans les navigateurs web qui contrôle les requêtes HTTP entre des origines différentes. Elle permet aux ressources d'être partagées de manière contrôlée entre des domaines différents, en définissant les autorisations d'accès via les en-têtes HTTP, afin de prévenir les attaques d'injection de scripts et de protéger la confidentialité des utilisateurs.

**Ressources**:\
[CORS en 100 secondes](https://www.youtube.com/watch?v=4KHiSt0oLJ0&pp=ugMICgJmchABGAHKBRNjb21wcmVuZHJlIGxlcyBjb3Jz)\
[What is CORS ?](https://www.youtube.com/watch?v=UjozQOaGt1k&pp=ygUddW5kZXJzdGFuZGluZyBjb3JzIHByaW5jaXBsZXM%3D)\
[Cross-Origin Resource Sharing (CORS) | Complete Guide](https://www.youtube.com/watch?v=t5FBwq-kudw&pp=ygUddW5kZXJzdGFuZGluZyBjb3JzIHByaW5jaXBsZXM%3D)\

#### Idempotency
**Descriptpion**: L'idempotence est une propriété d'opérations dans les mathématiques et l'informatique où l'application multiple d'une opération ne change pas le résultat après la première application. Par exemple, dans une requête HTTP, une opération est dite idempotente si envoyer la même requête plusieurs fois produit le même effet que l'envoyer une fois.

**Ressources**:\
[What is API Idempotency and Why Is It Important?](https://www.youtube.com/watch?v=I08syTslan8&pp=ugMICgJmchABGAHKBQtpZGVtcG90ZW5jeQ%3D%3D)\
[How Important Is Idempotency](https://www.youtube.com/watch?v=4OuaONkZw1I&pp=ugMICgJmchABGAHKBRhpZGVtcG90ZW50IG1pY3Jvc2VydmljZXM%3D)\
[Idempotent API for Payments](https://www.youtube.com/watch?v=J2IcD9FZvZU&pp=ygULaWRlbXBvdGVuY3k%3D)