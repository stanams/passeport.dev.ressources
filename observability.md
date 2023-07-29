# Observability
L'observabilité est une pratique de développement logiciel qui vise à rendre un système compréhensible et diagnostiquable en temps réel. Cela implique la collecte, la surveillance et l'analyse des données liées aux performances, à l'état et au comportement du système. L'objectif de l'observabilité est de permettre aux développeurs et aux équipes opérationnelles d'identifier rapidement les problèmes, de déboguer les erreurs et d'améliorer les performances du système.

#### RUM
**Description**: RUM (Real User Monitoring) est une méthode de surveillance qui collecte et analyse des données en temps réel sur les interactions des utilisateurs avec une application web ou un site web. Il fournit des informations précieuses sur les performances, la convivialité et l'expérience utilisateur réelle, permettant ainsi d'optimiser et d'améliorer la qualité de l'application ou du site.

**Ressources**:\
[Real User Metrics - Mozilla](https://habr.com/en/articles/737508/)\
[Qu'est ce que le RUM ?](https://www.uptrends.fr/qu-est-ce-que/real-user-monitoring)\
[Supporting RUM In OpenTelemetry (Proposal)](https://github.com/open-telemetry/oteps/issues/169)


#### Disk memory / RAM
**Description**: La gestion de la mémoire disque et de la mémoire vive (RAM) en observabilité consiste à surveiller et analyser les métriques relatives à l'utilisation de l'espace disque et de la mémoire par un système informatique. Cela permet de détecter les problèmes de saturation, de planifier les besoins en ressources et de prendre des mesures pour optimiser l'efficacité et la stabilité du système.

**Ressources**:\
[Monitoring CPU/RAM/disk metrics with OpenTelemetry](https://habr.com/en/articles/737508/)\
[What is a Memory Bottleneck ?](https://sematext.com/glossary/memory-bottleneck/)\
[Memory Leak Detection](https://raygun.com/blog/memory-leak-detection/)

#### Logging
**Description**: Les logs sont des enregistrements chronologiques des événements et des actions se produisant dans un système. Ils fournissent des informations détaillées sur l'état et le comportement du système, et sont utilisés pour le débogage, la surveillance et l'analyse des problèmes.

**Ressources**:\
[Observability : Logs vs Traces vs Metrics!](https://medium.com/@surfd1001/things-to-know-about-observability-mechanisms-a52876e421c7)\
[Writing Best Practices For Application Logs](https://devcenter.heroku.com/articles/writing-best-practices-for-application-logs)\
[Logging Best Practices](https://medium.com/israeli-tech-radar/logging-best-practices-e26d0a3e2697)

#### Tracing
**Description**: Le tracing (ou suivi) est une technique qui permet de suivre le parcours d'une requête ou d'une transaction à travers un système distribué. Il permet de visualiser et d'analyser les temps de traitement, les délais et les interactions entre les différents composants du système.

**Ressources**:\
[Distributed Tracing: Everything You Need To Know](https://coralogix.com/blog/what-is-tracing-everything-to-know/)\
[The role of APM and distributed tracing in observability](https://www.sumologic.com/blog/the-role-of-apm-and-distributed-tracing-in-observability/)\
[Intro To Tracing: OpenTelemetry & Opentracing](https://www.youtube.com/watch?v=idDu_jXqf4E&pp=ygUTZGlzdHJpYnV0ZWQgdHJhY2luZw%3D%3D)

#### Monitoring
**Description**: Le monitoring est le processus de collecte, de surveillance et d'analyse continue des métriques et des données relatives à un système ou à une application, afin de détecter les anomalies, de surveiller les performances, d'identifier les problèmes potentiels et de prendre des mesures pour assurer le bon fonctionnement et l'optimisation du système.

**Ressources**:\
[How is monitoring different than observability?](https://www.youtube.com/watch?v=rL33J-X9_u0&pp=ygUYb2JzZXJ2YWJpbGl0eSBtb25pdG9yaW5n)\
[Observability vs Monitoring - The difference explained with an example](https://signoz.io/blog/observability-vs-monitoring/)\
[A Three-Phased Approach to Observability](https://newrelic.com/resources/ebooks/3-phased-approach-to-observability)

#### Alerting
**Description**: Les alertes sont des notifications déclenchées lorsqu'un événement ou une condition prédéfinie se produit dans le système. Elles permettent de détecter et de réagir rapidement à des problèmes potentiels, en envoyant des avertissements aux équipes d'exploitation ou aux administrateurs système.	

**Ressources**:\
[Effective Alerting in Practice](https://newrelic.com/resources/ebooks/effective-alerting-guide)\
[9 Steps to Prevent Alert Storms](https://www.youtube.com/watch?v=FfpBGATG_6c&ab_channel=LogicMonitor%2CInc.)\

#### Web Vitals
**Description**: Les Web Vitals sont un ensemble de métriques de performance clés qui mesurent l'expérience utilisateur sur le web, notamment la vitesse de chargement, la réactivité et la stabilité visuelle. Ils fournissent des indications sur la qualité de l'expérience utilisateur, permettant aux développeurs de détecter les problèmes de performance et d'optimiser leurs sites web en conséquence.

**Ressources**:\
[Understanding Core Web Vitals](https://developers.google.com/search/docs/appearance/core-web-vitals#:~:text=Core%20Web%20Vitals%20is%20a,a%20great%20user%20experience%20generally.)\
[Web Vitals](https://web.dev/vitals/)\
[Performance testing with Google Lighthouse and Cypress](https://techbeacon.com/app-dev-testing/how-do-web-performance-testing-google-lighthouse-cypress)

#### DORA Metrics
**Description**: Les DORA Metrics (DevOps Research and Assessment Metrics) sont un ensemble de métriques utilisées pour évaluer et mesurer les pratiques et la performance des équipes de développement et d'exploitation dans le cadre de l'adoption des pratiques DevOps. Elles incluent des mesures telles que le délai de déploiement, la fréquence des déploiements, le temps de rétablissement en cas d'incident et le taux de changement échoué, fournissant ainsi des indicateurs clés pour évaluer l'efficacité des pratiques DevOps et l'agilité de l'équipe.

**Ressources**:\
[DORA Metrics](https://www.leanix.net/fr/wiki/vsm/dora-metrics)\
[DORA Metrics - User Analytics](https://www.youtube.com/watch?v=lM_FbVYuN8s&ab_channel=GitLab)
[The Ultimate Guide to DORA Metrics](https://devcycle.com/blog/the-ultimate-guide-to-dora-metrics)