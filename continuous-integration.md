# Continuous integration
L'intégration continue est une pratique qui consiste à fusionner régulièrement les modifications du code réalisées par plusieurs développeurs au sein d'un projet, afin de détecter rapidement les éventuels problèmes d'incompatibilité et de garantir une qualité constante du logiciel


#### Basic git commands
**Description**: Les commandes Git de base sont des instructions utilisées pour gérer un référentiel Git. Elles incluent "git init" pour initialiser un nouveau référentiel, "git add" pour ajouter des fichiers à l'index de suivi, "git commit" pour créer un instantané des modifications, "git branch" pour créer une nouvelle branche, "git push" pour envoyer les modifications vers un référentiel distant, "git pull" pour récupérer et fusionner les modifications d'un référentiel distant vers le référentiel local, et git merge pour fusionner les modifications d'une branche vers une autre branche.

**Ressources**:
[Git cheat sheet - 40 commands](https://dev.to/ruppysuppy/git-cheat-sheet-with-40-commands-concepts-1m26)
[Git cheat sheet education](https://education.github.com/git-cheat-sheet-education.pdf)
[Freecodecamp Git cheat sheet](https://www.freecodecamp.org/news/git-cheat-sheet/)


#### Advanced git commands
**Description**: Les commandes avancées de git offrent des fonctionnalités puls fines pour manipuler l'historique des commits, effectuer des recherches de bugs et gérer finement les modifications dans un référentiel Git.: interactive rebase, bisect, squash, fixup, cherry pick etc...

**Ressources**:
[13 advanced Git Techniques and shortcuts](https://www.youtube.com/watch?v=ecK3EnyGD8o&ab_channel=Fireship)
[Gitkraken - Advanced Git techniques](https://www.gitkraken.com/learn/git/commands)

#### Trunk based development
**Description**: Méthode de développement logiciels où tous les devs travaillent sur une seule branche principale, appelée "trunk" ou "main", en effectuant des commits très fréquents et en évitant les longues branches de fonctionnalités pour minimiser les conflits de merge.

**Ressources**:
[Trunk Based Development - Official doc](https://trunkbaseddevelopment.com/)
[Google Cloud - Trunk Based Development](https://cloud.google.com/architecture/devops/devops-tech-trunk-based-development)

#### Feature based branching (gitflow)
**Description**: GitFlow est une stratégie de gestion de branches dans Git qui définit un modèle de flux de travail plutôt rigide, conçu autour des versions de projet, en utilisant des branches spécifiques pour les fonctionnalités, les versions, les correctifs de bugs et la maintenance.

**Ressources**:
[Branching Strategies Explained](https://www.youtube.com/watch?v=U_IFGpJDbeU&pp=ygUXdHJ1bmsgYmFzZWQgZGV2ZWxvcG1lbnQ%3D)
[Workflow Gitflow](https://www.atlassian.com/fr/git/tutorials/comparing-workflows/gitflow-workflow)

#### Clean commit
**Description**: Un "clean commit" fait référence à une pratique de développement de logiciels consistant à effectuer un commit qui est clair, concis et ne contient que des modifications liées à une fonctionnalité ou à une tâche spécifique, sans inclure de modifications inutiles ou non liées. Cela contribue à maintenir la propreté et la traçabilité du code source, facilitant ainsi la collaboration et la gestion du projet. L'utilisation d'outils comme husky ou commitizen permettent de créer un format type clair de commit

**Ressources**:
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
[How To Write Good Commit Messages](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)
[4 Tips To Write Clean Commits History](https://levelup.gitconnected.com/4-tips-to-write-clean-commit-history-51155f7f23b9)

#### Clean PR
**Description**: Un "clean PR" est une demande de fusion qui est claire, bien organisée et qui contient uniquement les modifications nécessaires pour résoudre un problème ou implémenter une fonctionnalité spécifique. Cela facilite la révision et la compréhension du code par les pairs, en maintenant un niveau élevé de lisibilité, de qualité et de cohérence dans le processus de collaboration du développement logiciel.

**Ressources**:
[Make Clean Pull Requests](https://hackernoon.com/make-clean-pull-requests-version-control-and-collaboration-420ecff2e7b5)
[A Github Pull Request Template For Your Projects](https://embeddedartistry.com/blog/2017/08/04/a-github-pull-request-template-for-your-projects/)
[Writing A Great Pull Request Description](https://www.pullrequest.com/blog/writing-a-great-pull-request-description/)

#### Clean PR
**Description**: Une "clean review" désigne une revue de code méthodique et approfondie effectuée par un développeur ou un pair afin d'identifier et de signaler les problèmes, les erreurs ou les améliorations potentielles dans le code source. Une "clean review" se caractérise par une analyse précise, des commentaires clairs et constructifs, et une attention particulière accordée à la lisibilité, à la qualité et aux bonnes pratiques de programmation. L'objectif est d'améliorer la qualité du code et de favoriser une collaboration efficace entre les membres de l'équipe de développement.

**Ressources**:
[How To Make Good Code Reviews](https://stackoverflow.blog/2019/09/30/how-to-make-good-code-reviews-better/)
[How We Do A Code Review At Google](https://google.github.io/eng-practices/review/reviewer/)
[Powerful Code Reviews](https://medium.com/geekculture/how-to-do-a-good-code-review-1598497849e0)

#### CI servers
**Description**: Un serveur d'intégration continue (CI server) est un outil logiciel utilisé dans le développement de logiciels pour automatiser le processus d'intégration du code. Il permet de compiler, tester et déployer automatiquement le code source à chaque modification, assurant ainsi une intégration régulière et une détection précoce des erreurs. Les plus populaires sont Github Actions, Gitlab CI, Jenkins, Travis ou encore Azure Devops.

**Ressources**:
[Comment mettre en place une CI/CD ?](https://www.youtube.com/watch?v=5PDm7AY_-FA&pp=ygUbcXUnZXN0IGNlIHF1J3VuIGNkIHBpcGVsaW5l)
[CI Server: How It Works](https://about.gitlab.com/topics/ci-cd/continuous-integration-server/)
[Github Actions Step By Step Guide](https://codefresh.io/learn/continuous-integration/ci-server-how-it-works/)

#### Linter
**Description**: Outil utilisé dans le développement de logiciels pour analyser le code source et signaler les erreurs, les problèmes de style et les violations des conventions de programmation. Il applique un ensemble de règles prédéfinies ou personnalisables pour détecter les erreurs courantes, les pratiques non recommandées et les incohérences dans le code. Les linters aident à améliorer la qualité du code, à renforcer la cohérence du style de programmation et à identifier les problèmes potentiels avant l'exécution du code.

**Ressources**:
[What is a Linter and Why you should use one](https://www.youtube.com/watch?v=HDQXWr5TOnI&pp=ygUQd2hhdCBpcyBhIGxpbnRlcg%3D%3D)
[What is a Linter ? Quick start guide](https://www.testim.io/blog/what-is-a-linter-heres-a-definition-and-quick-start-guide/)
[Github Super Linter in 5 minutes](https://www.youtube.com/watch?v=fL8de_m8imY&pp=ygUQd2hhdCBpcyBhIGxpbnRlcg%3D%3D)

#### Test coverage
**Description**: Le "test coverage" (ou couverture de test) fait référence à la mesure de la proportion du code source d'un programme qui est exercée par les tests automatisés. Il indique le pourcentage de lignes de code, de branches conditionnelles ou d'autres éléments couverts par les tests par rapport à l'ensemble du code source. Attention à ne pas considérer que le test coverage est suffisant pour garantir la qualité d'écriture des tests!

**Ressources**:
[Test Coverage - Comprehensive Guid with Best Practices](https://www.lambdatest.com/learning-hub/test-coverage)
[Test Coverage Techniques - The Ones You Need](https://www.testim.io/blog/test-coverage-techniques/)
[How To Ensure Test Coverage](https://www.testim.io/blog/how-to-ensure-test-coverage/)

#### Semantic versionning
**Description**: Le versionnage sémantique est un système de versionnage qui associe un sens spécifique à différentes parties du numéro de version, généralement structuré comme MAJEUR.MINEUR.CORRECTIF. Le changement du numéro de version MAJEUR indique des modifications incompatibles, un changement du numéro MINEUR indique l'ajout de fonctionnalités compatibles avec les versions antérieures, et un changement de CORRECTIF indique des corrections de bugs compatibles avec les versions antérieures.

**Ressources**:
[SemVer Official Specs](https://semver.org/)
[What Is Semantic Versioning](https://www.howtogeek.com/devops/what-is-semantic-versioning)
[Undertsanding Semantic Versioning (real world examples)](https://www.youtube.com/watch?v=1zBzkT7QCmA&pp=ygUZcHJhY3RpY2FsIGd1aWRlIHRvIHNlbXZlcg%3D%3D)
