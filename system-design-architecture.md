# System Design & Architecture
Processus de création d'une structure efficace pour un système logiciel, en définissant les composants, les interactions et les choix de conception. L'objectif est de créer un système robuste, évolutif et performant, répondant aux besoins spécifiés et favorisant la maintenabilité.

#### Clean architecture
**Description**: La Clean Architecture est un style d'architecture logicielle qui favorise la séparation des préoccupations en organisant le code en couches concentriques, avec le domaine métier au centre et des couches externes indépendantes des détails techniques. Elle vise à obtenir une conception modulaire, testable et maintenable en appliquant des principes tels que la dépendance inversée et l'indépendance des frameworks.

**Ressources**:\
[L'article original de "Uncle Bob"](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)\
[The Future of Programming](https://www.youtube.com/watch?v=ecIWPzGEbFc&ab_channel=PaulStringer%27sMobileTech)\
[Using Clean Architecture for Microservice APIs](https://www.youtube.com/watch?v=CnailTcJV_U&ab_channel=DevMastery)


#### Architecture Hexagonale
**Description**: L'Architecture Hexagonale, également connue sous le nom de Ports and Adapters (Ports et Adaptateurs), met l'accent sur la découpe des applications en domaines et en couches distinctes. Elle promeut l'idée que le cœur de l'application, le domaine métier, doit être isolé et indépendant des détails techniques tels que les frameworks et les technologies externes. Les adaptateurs sont utilisés pour connecter le cœur de l'application avec les éléments externes, tels que les interfaces utilisateurs ou les bases de données.

**Ressources**:\
[Glossaire Architecture Hexagonale](https://thetribe.io/glossaire-architecture-hexagonale-clean-architecture/)\
[Architecture Hexagonale : 3 principes et un exemple d’implémentation](https://blog.octo.com/architecture-hexagonale-trois-principes-et-un-exemple-dimplementation/)\
[There Are Always Two Sides To Every Story](https://medium.com/ssense-tech/hexagonal-architecture-there-are-always-two-sides-to-every-story-bc0780ed7d9c)

#### DDD
**Description**: Le DDD (Domain-Driven Design) est une approche de conception logicielle qui met l'accent sur la modélisation du domaine métier au cœur du développement. Il encourage une compréhension approfondie du domaine, une collaboration étroite entre experts du domaine et développeurs, et la création de modèles riches et expressifs pour résoudre les problèmes complexes liés au domaine.

**Ressources**:\
[What Is DDD by Eric Evans](https://www.youtube.com/watch?v=pMuiVlnGqjk&pp=ygUNZGRkIGV4cGxhaW5lZA%3D%3D)\
[An Introduction to DDD](https://learn.microsoft.com/en-us/archive/msdn-magazine/2009/february/best-practice-an-introduction-to-domain-driven-design)\
[Concepts of Domain Driven Design](https://medium.com/microtica/the-concept-of-domain-driven-design-explained-3184c0fd7c3f)

#### CQRS
**Description**: CQRS (Command Query Responsibility Segregation) est un modèle architectural qui préconise la séparation des opérations de lecture (queries) et d'écriture (commands) dans les systèmes logiciels. Il propose d'avoir des modèles de conception distincts pour la modification des données et la récupération des données, permettant une meilleure évolutivité, une optimisation des performances et une conception plus claire des systèmes.

**Ressources**:\
[CQRS Global Introduction by Udi Dahan](https://www.youtube.com/watch?v=EkEz3pcLdgY&ab_channel=UPM)\
[Clarified CQRS](https://udidahan.com/2009/12/09/clarified-cqrs/)\
[CQRS Pitfalls and Patterns](https://www.youtube.com/watch?v=Lw04HRF8ies)

#### Microservices
**Description**: L'architecture en microservices est un style d'architecture logicielle dans lequel une application est décomposée en plusieurs services autonomes et indépendants, appelés microservices. Chaque microservice est conçu pour effectuer une fonction spécifique, communique généralement via des API et peut être déployé et mis à l'échelle de manière indépendante, favorisant ainsi la flexibilité, la scalabilité et la résilience des applications distribuées.

**Ressources**:\
[What are Microservices](https://microservices.io/)\
[Microservices by AWS](https://aws.amazon.com/microservices/)\
[What Are Microservices Really All About](https://www.youtube.com/watch?v=lTAcCNbJ7KE)

#### Modular Monolith
**Description**: Un monolithe modulaire fait référence à une architecture monolithique où le code est organisé de manière modulaire pour faciliter la maintenance, la compréhension et la réutilisation du code. Bien que le monolithe lui-même ne soit pas divisé en services distincts, les modules internes sont conçus pour être indépendants et interagissent à travers des interfaces claires, permettant une certaine séparation des préoccupations et une meilleure gestion du code à l'intérieur du monolithe.

**Ressources**:\
[Modular Monolith by Simon Brown](https://www.youtube.com/watch?v=5OjqD-ow8GE&ab_channel=GOTOConferences)\
[The Majestic Monolith by DHH](https://m.signalvnoise.com/the-majestic-monolith/)\
[How To Recover From Microservices](https://world.hey.com/dhh/how-to-recover-from-microservices-ce3803cc)

#### Caching strategies
**Description**: Une stratégie de mise en cache (caching) est une approche pour améliorer les performances et réduire la charge d'un système en stockant temporairement les résultats de certaines opérations coûteuses. Elle consiste à enregistrer les données ou les résultats calculés dans un cache, généralement basé sur la mémoire, afin de les récupérer plus rapidement lors de demandes ultérieures. Les stratégies de mise en cache incluent la gestion du cycle de vie du cache, l'invalidation des données obsolètes, la détermination de la durée de conservation des données en cache, ainsi que la gestion des politiques d'éviction pour garantir une utilisation efficace et pertinente du cache.

**Ressources**:\
[Top Caching Strategies](https://blog.bytebytego.com/p/top-caching-strategies)\
[Caching Strategies in High Throughput Systems](https://medium.com/outbrain-engineering/caching-strategies-in-high-throughput-systems-733189e62a4d)\
[Choosing The Right Caching Strategies](https://www.youtube.com/watch?v=ZCVgDKjtgl0&pp=ygUSY2FjaGluZyBzdHJhdGVnaWVz)

#### Event Driven Architecture
**Description**: L'architecture orientée événements (Event-Driven Architecture) est un style d'architecture logicielle dans lequel les composants communiquent entre eux par le biais d'événements. Les événements, qui peuvent être des actions, des notifications ou des changements de statut, sont émis par les producteurs et consommés par les récepteurs de manière asynchrone. Cela permet un découplage des composants, une extensibilité et une réactivité accrues, ainsi qu'une meilleure gestion des flux de données et des interactions entre les différentes parties du système.

**Ressources**:\
[The Many Meanings Of Event Driven Architecture by M.Fowler](https://www.youtube.com/watch?v=STKCRSUsyP0&pp=ygUUcHViIHN1YiBhcmNoaXRlY3R1cmU%3D)\
[Event Driven Architecture](https://herbertograca.com/2017/10/05/event-driven-architecture/)
[Understanding The Basics](https://www.youtube.com/watch?v=LHgCA3XVNkw&ab_channel=ExecuteAutomation)

#### Pub/sub architecture
**Description**: La pub/sub (publication/abonnement) est un modèle d'architecture où les producteurs publient des messages ou des événements sur un canal central, et les consommateurs s'abonnent à ces canaux pour recevoir les messages pertinents. Cela permet une communication décentralisée et asynchrone, où les producteurs et les consommateurs ne sont pas directement couplés, offrant ainsi une grande extensibilité et une meilleure scalabilité.

**Ressources**:\
[Architecture Pub/Sub par l'exemple](https://www.youtube.com/watch?v=O1PgqUqZKTA&pp=ugMICgJmchABGAHKBRRwdWIgc3ViIGFyY2hpdGVjdHVyZQ%3D%3D)\
[The Pros & Cons of the Pub/Sub Architecture](https://www.redhat.com/architect/pub-sub-pros-and-cons)\
[Architectural Overview of Pub/Sub](https://cloud.google.com/pubsub/architecture)

#### Messaging Queues
**Description**: Les files d'attente de messages sont des structures de données qui permettent la communication asynchrone entre les composants d'un système distribué en stockant temporairement les messages émis par les producteurs jusqu'à ce qu'ils soient consommés par les destinataires. Cela permet une déconnexion temporelle entre les producteurs et les consommateurs, favorisant ainsi une meilleure gestion des charges, une résilience accrue et une évolutivité du système.

**Ressources**:\
[Message Queue Explained](https://www.youtube.com/watch?v=5-Rq4-PZlew)\
[How Message Queues Work In Distributed Systems](https://www.freecodecamp.org/news/message-queues-in-distributed-systesms/)\
[Microservices & Message Queues](https://www.youtube.com/watch?v=r5byURobuaQ&pp=ugMICgJmchABGAHKBRltZXNzYWdlIHF1ZXVlcyBleHBsYWluZWQg)