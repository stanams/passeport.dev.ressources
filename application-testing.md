# Application Testing
Une grande partie de la qualité logicielle passe par l’écriture de tests à différents niveaux de ce qu’on appelle la pyramide de tests. Mais les tests servent aussi à aider le développeur à mieux concevoir la logique de son code, de manière incrémentale et itérative.


#### Testing Objects
**Description**: Les objets de tests, également appelés objets de test doubles, sont des implémentations substituées des dépendances réelles utilisées lors des tests unitaires. Ces objets sont créés dans le but de fournir des comportements prévisibles et contrôlés pour isoler le code testé et faciliter les tests en permettant la simulation de certaines interactions ou valeurs de retour spécifiques: mock, spy, double, fixtures

**Ressources**:\
[Test Doubles — Fakes, Mocks and Stubs](https://blog.pragmatists.com/test-doubles-fakes-mocks-and-stubs-1a7491dfa3da)\
[Test Doubles - Martin Fowler](https://martinfowler.com/bliki/TestDouble.html)\
[Test Doubles - The difference between stubs and mocks](https://womanonrails.com/test-doubles)


#### Unit Tests
**Description**: Les tests unitaires sont des tests automatisés effectués sur des composants individuels d'un logiciel pour vérifier leur bon fonctionnement de manière isolée. Ils consistent à valider les entrées, les sorties et les comportements attendus de ces composants, permettant de détecter rapidement les erreurs et de s'assurer de la qualité du code à un niveau granulaire.

**Ressources**:\
[Unit Testing Guide](https://www.guru99.com/unit-testing-guide.html)\
[Arrange, Act and Assert Pattern: The Three A’s of Unit Testing](https://robertmarshall.dev/blog/arrange-act-and-assert-pattern-the-three-as-of-unit-testing/)\
[My Unit Testing Epiphany](https://www.stevefenton.co.uk/2013/05/my-unit-testing-epiphany/)

#### TDD
**Description**: Le TDD (Test-Driven Development) est une approche de développement logiciel où l'on commence par réfléchir au dénouement souhaité afin de faire ressortir l'algorithme ou la logique que l'on souhaite construire. Cela implique de définir les exigences sous forme de tests, puis de développer le code qui répond à ces tests, favorisant ainsi la qualité, la modularité et la réflexion sur la conception du code dès le début du processus de développement.

**Ressources**:\
[TDD par l'exemple](https://www.youtube.com/watch?v=nbSaq_ykOl4&t=18s&pp=ygUXYWxnb3JpdGhtZSBpbmZvcm1hdGlxdWU%3D)\
[TDD Doesn't Work](https://blog.cleancoder.com/uncle-bob/2016/11/10/TDD-Doesnt-work.html)\
[TDD, Where Did It All Go Wrong](https://www.youtube.com/watch?v=EZ05e7EMOLM&ab_channel=DevTernityConference)

#### BDD
**Description**: Le BDD (Behavior-Driven Development) est une méthodologie de développement logiciel qui met l'accent sur la collaboration entre les développeurs, les testeurs et les parties prenantes pour définir le comportement attendu du logiciel à l'aide de scénarios rédigés dans un langage naturel. Il vise à aligner les objectifs métier et les exigences fonctionnelles en encourageant des spécifications plus compréhensibles et une communication claire entre les différentes parties prenantes du projet.

**Ressources**:\
[What is BDD testing?](https://www.browserstack.com/guide/what-is-bdd-testing)\
[Le BDD ce n'est pas ce que vous croyez](https://www.youtube.com/watch?v=3mSajdqhitQ)\
[Demonstration de BDD et TDD en live](https://medium.com/wealcomecompany/d%C3%A9monstration-de-bdd-et-tdd-en-live-bbc3329b39e)

#### Integration tests
**Description**: Les tests d'intégration sont des tests qui vérifient le bon fonctionnement des interactions et des intégrations entre plusieurs composants ou modules d'un système logiciel. Ils permettent de détecter les erreurs potentielles lors de l'assemblage des différentes parties du système, en s'assurant que les composants fonctionnent ensemble de manière cohérente et conforme aux spécifications.

**Ressources**:\
[Integration Testing: What is, Types with Example](https://www.guru99.com/integration-testing.html)\
[First Class Tests](https://blog.cleancoder.com/uncle-bob/2017/05/05/TestDefinitions.html)\
[7 Integration Testing Best Practices](https://research.aimultiple.com/integration-testing-best-practices/)

#### End-to-end tests
**Description**: Les tests end-to-end (E2E) sont des tests qui simulent des scénarios d'utilisation réels et couvrent l'ensemble du flux de travail d'une application, du début à la fin. Ils vérifient la fonctionnalité, la performance et l'interopérabilité du système dans son ensemble, en reproduisant les interactions utilisateur réelles pour s'assurer que tous les composants et systèmes interagissent correctement. Ces tests sont plus longs à executer et en général sont plutôt à réaliser sur les absolument parcours critiques d'une application.

**Ressources**:\
[What Is End-to-End Testing?](https://www.browserstack.com/guide/end-to-end-testing)\
[What Is End-to-End Testing?](https://www.youtube.com/watch?v=wycIcpuLkzU&pp=ygUSZW5kIHRvIGVuZCB0ZXN0aW5n)\
