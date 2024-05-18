# CURRICULUM VITAE

- *Identité et âge :*	Jérémy DOMARIN, 33 ans (né en juin 1990)
- *Expérience :* 11 ans d’expérience en développement et intégration de logiciels (R&D)
- **Coordonnées :**
	- *Adresse :* Le Vauban A – 136 chemin du Puy – 06600 ANTIBES – France
	- *Courriel :* jdomarin at gmail.com
	– *Téléphone :* me demander
- *Nationalité :* Française
- **Profils en ligne :**
	- *LinkedIn :* https://www.linkedin.com/in/j%C3%A9r%C3%A9my-domarin/
	- *GitHub :* https://github.com/jdomarin
	- *Facebook :* https://www.facebook.com/jdomarin
	- *Instagram :* https://www.instagram.com/jdomarin
	- *Stack Overflow :* https://stackoverflow.com/users/8272767/j%c3%a9r%c3%a9my-domarin
- **Langues :**
	- *Français :* maternelle
	- *Anglais :* courant, score obtenu au TOEIC de 880 en avril 2010
	- *Espagnol :* notions
- *Domaines de prédilection :* Cybersécurité, big data, traitement de données, REST API, applications web, sciences industrielles
- *Mobilité :* Titulaire du permis B. Rayon de 70 km autour d’Antibes. Maximum 2 heures par jour de trajet domicile-travail aller-retour. Courts déplacements ponctuels et réguliers acceptés au-delà de cette distance.
- *Télétravail :* pleinement ouvert

# DOMAINES DE COMPÉTENCES

- Ethical hacking, hacker de type « white hat », passionné de cybersécurité
- Intégration logicielle et livraison applicative : packaging, releasing
- Développement Python/Django, NodeJS, Java/J2EE, Web et écriture de scripts
- Test et déploiement d’applications logicielles
- Maintenance applicative, investigation et résolution d’anomalies logicielles, support
- Animation de groupe de développeurs, partage de connaissances, veille technologique
- Développement en environnement cloud

# CONNAISSANCES TECHNIQUES
- Langages de programmation : Python, Shell, JavaScript, NodeJS, Java, HTML5/CSS3
- Outils de cybersécurité : Qualys WAS, Burp Suite, Acunetix, Netsparker
- Frameworks de développement : Django, J2EE, ZK, Spring, Hug, JQuery, Play, Scala
- Bases de données relationnelles : Oracle, PostgreSQL, MySQL/XtraDB cluster, IBM DB2
- Bases de données NoSQL : Elasticsearch, MongoDB, Redis/Dynomite
- Formats de présentation : XML, EDIFACT, JSON, CSV, YAML
- Outils DevOps : Docker (avec Swarm), Ansible, Kubernetes
- Outils cloud : PaaS (CloudFoundry)
- Méthodes : Agile Scrum, Kanban, Waterfall ou cycle en V
- Environnements de développement intégrés : Pycharm, Eclipse, VS Code, Visual Studio
- Gestion de code source : Git, CVS, Mercurial (hg), Subversion (svn)
- Frameworks de test et intégration continue : JUnit, Pytest, Sélénium, Jenkins, Gitlab CI
- Autres outils : JIRA, Maven, Sonar, Pylint, FindBugs, Checkstyle, Jacoco, Buildbot, Stash/ Bitbucket, GitLab, Nexus, VirtualBox, Vagrant
- Documentation technique : Doxygen, JavaDoc, Markdown/README.md
- Documentation fonctionnelle : SharePoint, Confluence, MediaWiki

# EXPÉRIENCES PROFESSIONNELLES

## Ekinops France (06) | depuis septembre 2023 (en cours)

R&D Engineer successivement dans les équipes GitOps puis Cloud SRE
Déploiement automatisé d'applications de virtualisation réseau et de validations de function réseau dans le cloud Azure.
Télétravail : jusqu’à trois jours par semaine

### Environnement technique

Terraform, Azure, Ansible, WSL, Jinja, Docker, Kubernetes, AKS, MariaDB/MySQL, ProxySQL, Apache 2
PC sous Windows 11

### Contexte et objectifs

Aider la branche Access d'Ekinops à migrer dans le cloud, les applications délivrées aux clients et utilisées par eux

### Réalisations

- Création d'un playbook Ansible pour valider le bon déploiement des applications dans le cloud
- Activation du protocole mTLS pour une application déployée dans le cloud utilisant Apache 2
- Transformer les playbooks Ansible pour qu'ils soient idempotents
- Rendre les playbooks capables de déployer une infrastructure légère ou lourde avec la possibilité de migrer de la plus légère à la plus lourde

### Résultat

Diminution des coûts de l'infrastructure déployée dans le cloud

## ALTEN / Orange (06) | octobre 2020 - septembre 2023 (3 ans)
Offres automatisées d’instances de services de bases de données aux développeurs de l’entité Hébergement et d’Exploitation de la Digital Factory à Orange France

Une partie de la mission s'effectue en télétravail.
### Environnement technique
- Python, Shell Unix, Go
- Docker, Swarm, Kubernetes as a service (KaaS), cloud privé, container as a service (CaaS), CloudFoundry (Platform as a Service, PaaS)
- Ubuntu (sur WSL et machine virtuelle)
- Git, Gitlab, Gitlab CI
- Redis, Dynomite, MongoDB, Percona XtraDB cluster (MySQL avec réplication et redondance)
- Outils de monitoring : Prometheus, Alert manager, Consul, Xymon, ...
### Contexte et objectifs
Entité Hébergement et Exploitation d’Orange (300 personnes) en charge de l’hébergement des données des applications et services grand public d’Orange France (site orange.fr, sosh.fr, Espace client…)

Équipe Scrum de 8 développeurs, 1 scrum master, 1 product owner, 1 lead développeur et gérée par un manager fonctionnel

Fourniture et maintien en condition opérationnelle d’instances de bases de données sur cloud privé Orange à l’intention des développeurs de la Digital Factory (1800 personnes)
### Réalisations
*Cette liste n'est pas exhaustive*
- Écriture d’un script qui permet de vérifier l’état d’un cluster de nœuds MongoDB, Redis, Dynomite ou XtraDB
- Importation dans Prometheus de métriques exportées par Docker Swarm pour intégration dans Grafana
- Amélioration de l’image Unix de Percona XtraDB cluster en termes de stabilité, performance, traçabilité, facilité d’investigation des incidents
- Migration de plusieurs centaines d’instances de bases de données à une nouvelle API réseau sans interruption de service pour les utilisateurs
- Implémentation d’une application web permettant d’afficher les dernières versions d’une centaine de projets Gitlab développés par l’équipe
- Tâches récurrentes (astreinte aux heures de bureau) : réponse aux demandes des clients, supervision opérationnelle, traitement des demandes entrantes hors Scrum ou sprint en cours

### Résultats
- Amélioration de la stabilité des instances de bases de données des clients
- Raccourcissement du délai de mise à disposition des instances aux clients
- Migration des instances d'une technologie d'équilibrage de charge à une plus moderne, rapide et efficace
- Mise à disposition de la consommation de mémoire des instances en quasi temps réel
- Bases de données XtraDB qui tournent sur Kubernetes

## ALTEN / Naval Group (83)| janvier – juillet 2020 (6 mois)
Développement d’une application de cartographie de navires de la Marine nationale

Une partie de la mission a été effectuée en télétravail, à partir de mars 2020 à cause du confinement dû à la pandémie de coronavirus
### Environnement technique
- REST API, Postman, JSON
- Python, Django, REST framework
- Elastic Stack : Elasticsearch, Kibana
- Outils géographiques : GeoServer, WMS : web map service, WMTS : web map tile service
- Traitement d’images : GDAL, Inkscape, QGIS
- Git, GitLab
- Pycharm Community, tests unitaires Python, PyLint
- Ansible, YAML
- Environnement Linux : Ubuntu 18.04, Debian 9

### Contexte et objectifs
Naval Group (ex DCN/DCNS), société dans le domaine du naval de défense, construction et maintien en condition opérationnelle de navires (bateaux et sous-marins militaires)

Membre d'une équipe de développeurs et d’ingénieurs en cybersécurité de 7 personnes

Données et environnement sensible quant à la sécurité de la défense nationale

Mise en place d’une solution logicielle de cartographie physique de navires de la Marine nationale française, capable d’interagir avec d’autres applications auxquelles cette solution sera associée

### Réalisations
- Prise en main de GeoServer, OpenStreetMap, WMS et du Django REST framework
- Choix des outils adéquats pour l’application à développer
- Développement de l’API REST en Python, Django et REST framework
- Installation et configuration de l’environnement de GeoServer
- Mise en place d’une procédure de mise à disposition d’images utilisables par Kibana
- Tests unitaires de l’application
- Rédaction de la documentation technique, fonctionnelle et du dossier d’architecture
- Écriture de la première version des scripts Ansible de déploiement
- Participation et support à l’intégration et la phase de recette de l’application
- Démonstration de la solution logicielle au management

### Résultats
- Application mise en place, testée et fonctionnelle, prête à être déployée en production
- Documentation technique et fonctionnelle rédigée et disponible
- Client satisfait du résultat

## ALTEN / Mane et Fils (06) | novembre – décembre 2019 (2 mois)
Développeur Python back-end d’une application de gestion de projets (Abou Simbel)
### Environnement technique
- REST API : Swagger, Postman
- Python, Django, REST framework
- Angular v4
- Docker, micro services, Azure
- Agile : Scrum, JIRA et Confluence
- Git, GitLab
- VS Code
- LDAP
- Environnement Windows 10

### Contexte et objectifs
Mane (laboratoire de développement technologique) : société industrielle de fabrication de substances chimiques, d’arômes, de colorants, de parfums pour l’industrie pharmaceutique, alimentaire ou cosmétique. Siège social : Le Bar-sur-Loup (06)

Inclusion à une équipe encadrée par un chef de projet, composée de 4 développeurs back-end, 2 développeurs front-end et un ingénieur QA Scrum master. Cette équipe a pour mission la livraison d’une application web de gestion de projets créée à partir de zéro. J’ai rejoint cette équipe pour l’aider à tenir les délais

Projet au forfait, méthodologie Agile Scrum, sprints de trois semaines, six sprints entre mi-septembre et fin janvier pour la première livraison du logiciel

### Réalisations
Proposition, estimation et implémentation d’améliorations techniques de l’application : mise en place d’un système de journalisation, implémentation de la persistance de sessions utilisateur, ajout de la prise en charge du protocole LDAP pour l’authentification d’utilisateurs Windows côté client final

Architecture logicielle : diagrammes de classes, de séquence

Planification et priorisation des tâches à implémenter pour la première livraison de l’application fin janvier 2020

### Résultats
- Journalisation mise en place dans Abou Simbel (nom de cette application)
- Authentification des utilisateurs via LDAP fonctionnelle
- Architecture de l’application définie et/ou améliorée

## ALTEN / K-City Labs (06) | septembre – octobre 2019 (2 mois)
Développeur Python back-end d’une application exposant des API REST
### Environnement technique
- Elastic Stack : ElasticSearch
- REST API : Hug, Postman
- Python et bibliothèques de manipulation de fichiers Excel : Pandas, NumPy...
- Mongo, PostgreSQL
- Docker
- Agile : Scrum, JIRA et suite Atlassian (Bitbucket, Confluence)
- Git
- IntelliJ PyCharm
- Pytest
- Environnement Windows 10

### Contexte et objectifs
K-City Labs est la société informatique du groupe Kinaxia, spécialisé dans les solutions technologiques pour les acteurs de l’immobilier et de l’urbanisme. Produits phares : CityScan et Preventimmo. Siège social : Sophia Antipolis (06)

Au sein d'une équipe de développeurs multi-langages de 6 personnes : contribuer au développement en Python d’une application de récupération automatisée de données sur le web et de recoupage de différentes sources de données pour construire des indicateurs pour l’immobilier. Produire des données stockées dans des collections Mongo. 
Exposer ces données sur une API REST utilisée par les développeurs front-end de K-City Labs

### Réalisations
- Étude de l’existant, analyse des besoins des utilisateurs finaux
- Estimation des tâches confiées : maintenance applicative et/ou évolution logicielle
- Développement selon la méthodologie Scrum et/ou maintenance évolutive, des récits utilisateur provenant du backlog du produit et ajoutés au sprint par le leader technique. Sprints d’une semaine

### Résultats
Indicateurs sur la France métropolitaine créés ou mis à jour :
- Présence de radon et risque sismique par ville
- Identification des taux de réussite au baccalauréat 2018 par commune, par lycée
- Identification des hôpitaux généraux en France à partir des cartes IGN et du fichier national des établissements de santé (FINESS)
- Identification des communes INSEE selon les partis politiques vainqueurs des élections municipales de 2014
- Identification des communes INSEE selon les taux d’imposition relatifs à l’immobilier : taxe d’habitation, taxe foncière (bâti et non bâti) par année depuis 2009

## ALTEN / Amadeus SGB (06) | novembre 2016 – août 2019 (33 mois)
Développeur d'outils communautaires et white hat pour ingénieurs QA
### Environnement technique
- Elastic Stack : ElasticSearch, Kibana, Logstash
- JavaScript, NodeJS, VS Code
- Sélénium (scripts au format XML ou HTML) et framework associé en Java/J2EE
- Python et bibliothèques de manipulation de fichiers Excel (Pandas, NumPy…), Pycharm
- Qualys WAS, Burp Suite, Acunetix, Netsparker
- SQL Server Management Studio et Oracle pour certaines bases de données relationnelles
- Agile : Scrum, Kanban, JIRA et suite Atlassian : Bitbucket, Confluence, HipChat
- Git
- Java, Eclipse, Maven, Junit 4, WebLogic server
- Environnement Windows 7, Windows 2012 pour les serveurs et machines virtuelles et Ubuntu pour le projet d’inner source sur PTRReport (en 2019)

### Contexte et objectifs
Amadeus est le leader européen des technologies pour l’industrie du voyage, principalement pour les réservations : aérien, rail, hôtel, location de voitures, ferry...)
Au sein d'une équipe transverse de 4 puis 6 personnes :

Fournir du support technique et du logiciel répondant aux besoins de la communauté d'ingénieurs QA et des développeurs de SGB (Strategic Growth Businesses), les clients finaux des applications développées par SGB étant les aéroports, les compagnies ferroviaires, les chaînes hôtelières.

Veiller à ce que le cycle de vie de développement des applications respecte les standards et exigences de sécurité applicative : pour cela, effectuer des tests automatisés ou manuels des applications web de SGB, et animer la communauté de white hats. Délivrer des sessions annuelles de sensibilisation aux ingénieurs QA.

### Réalisations
Étude de l’existant, collecte et analyse des besoins des utilisateurs finaux

Estimation du travail, que ce soit de la maintenance applicative ou une évolution logicielle

Développement et maintenance évolutive, sous Kibana ou autres solutions équivalentes, de rapports montrant des métriques sur des anomalies logicielles ou campagnes de tests.

Administration de la plate-forme Kibana : installation, configuration, mises à jour du cluster, mise en production des changements. Documentation sous Confluence

**D’avril à novembre 2017**
Création et déploiement de rapports budgétaires sous Kibana grâce au traitement en Python de données exportées au format Excel.

Planification, exécution et suivi de scans d'une soixantaine d'applications web et de web services REST/SOAP dans Qualys WAS et Burp Suite. Notification aux équipes applicatives des vulnérabilités trouvées. Assure la surveillance de la résolution de ces vulnérabilités

**De septembre 2017 à janvier 2018**
Développement en Java sur un framework de tests automatisés basé sur Sélénium.

**D’octobre 2018 à juin 2019**
Développement en open source interne à Amadeus sur PTRReport, une application web de reporting d’anomalies logicielles. Technologies : Python, Django, Redis, PostgreSQL, Docker, HTML, JavaScript, CSS.

**De 2017 à 2019**
Délivrance de sessions annuelles de sensibilisation à la sécurité applicative à plusieurs dizaines d'ingénieurs QA dans le cadre du renouvellement de la certification PCI-DSS d’Amadeus

### Résultats
- Une trentaine de rapports sous Kibana, exploités régulièrement par le management
- Un millier de vulnérabilités trouvées sur une soixantaine d'applications web ou API REST, une centaine d'anomalies en cours de résolution
- Amélioration des performances et nouvelles fonctionnalités disponibles dans PTRReport

## ABYLSEN / Caisses Sociales de Monaco (98) | mai - août 2016 (3 mois)
Consultant en développement Java/J2EE d’applications web orientées santé
### Environnement technique
- Java 8/J2EE, Spring, ZK 7, AspectJ, MVVM : Modèle-Vue-Vue Modèle et framework maison servant à la logique métier et d’abstraction à Spring
- ZUL : fichiers HTML du framework ZK, avec annotations et data binding (lien de données)
- DB2, le système de gestion de bases de données d’IBM, DBeaver, JDBC
- SQL
- Apache Tomcat 8.0
- SVN (Subversion)
- Eclipse, Jenkins, Maven, FindBugs, Checkstyle
- JUnit 4
- Environnement Windows 7 : Windows Server pour les serveurs de base de données et d’intégration

### Contexte et objectifs
Au sein du Pôle Réalisation de Projets du service informatique des Caisses Sociales de Monaco, développement en Java/J2EE d’applications web basées sur le framework ZK, utilisées par des médecins, des agents comptables, des agents du service retraite, etc.

### Réalisations
Étude de l’existant, analyse des besoins des utilisateurs finaux

Estimation des tâches confiées : maintenance applicative et/ou évolution logicielle

Développement en Java pour le back-end et ZK en front-end avec Éclipse et de nombreux plugins :

Feuille de soins électronique pour les médecins : implémentation de la persistance de données tout au long de la même session applicative du site web ; notion de « view state ». Communication d’informations entre deux onglets

Gestion des suspens de retraite : changements de structure et de contenu de bases de données comme l’ajout de tables, la suppression, modification ou l’ajout de lignes en base de données ; des modifications sur l’interface graphique d’une application web ; l’implémentation de nouveaux algorithmes pour des batches, qui sont des applications Java en lecture ou écriture en base de données produisant des rapports à intervalles fréquents ou à la demande

Débogage, livraison logicielle avec Jenkins et Maven, déploiement sur serveur d’intégration avec Tomcat manager, support à la phase d’acceptation de l’application en environnement de recette

Correction d’anomalies reportées par les utilisateurs finaux ou les testeurs

### Résultats
- Application de feuille de soins électronique mise en production avec les nouvelles fonctionnalités requises par les clients
- Application de gestion des suspens de retraite : 70 % des fonctionnalités développées, 100 % d’exécution des tests unitaires, projet migré à Maven

## Abylsen / Amadeus R&D-AIR (06) | janvier 2013 - avril 2016 (39 mois)
Ingénieur R&D C++/Java et intégration logicielle
### Environnement technique
- Côté serveur : 5 applications codées en C++ pour Unix, basé sur un framework transactionnel (requête/réponse), à haut débit : jusqu’à 50k transactions par seconde
- Côté client : une interface graphique utilisateur (GUI) en Java natif (framework maison basé sur Swing), basée sur une vingtaine de bibliothèques Java middleware, incluant des écrans web aussi accessibles de manière indépendante par internet
- Divers scripts en Shell Unix, Perl, Ruby, Python, des sites web de monitoring et de changements de configuration des applications : variables OTF, airline parameters...
- Outils tels que Git, Maven, Jira, Jenkins, Nexus, Buildbot...
- Langages tels que Java, C++, HTML, CSS, JavaScript, Bootstrap
- Environnements Windows et Unix, via connexion SSH à un terminal pour les machines de développement et de compilation

### Contexte, objectifs et réalisations
- Centre de R&D d’Amadeus d’abord à Sophia Antipolis, bâtiment Clara, puis, à partir de 2015, à Villeneuve-Loubet, sur le site de Bel Air
- Application d’inventaire de vols et de réservations pour compagnies aériennes qui est utilisée par plus de 120 compagnies aériennes dans le monde, et sur laquelle travaille plusieurs centaines de développeurs, analystes et chefs de projet à travers la société

### Réalisations
- Support en production : s'assurer que les applications côté serveur fonctionnent correctement sur les plates-formes de production et de test accessibles aux clients, surveiller les mises en production avec les opérateurs d’exploitation à Munich
- Support au développement : s'assurer que les développeurs aient un environnement stable et solide leur permettant de mener à bien les projets de développement qui leur sont confiés

**2014, 7 mois**
Pilote de la migration de la GUI d'Altéa Inventory à « Software Factory » : Étudier la faisabilité de la migration du code et des processus d'intégration et de livraison continues de la GUI d'Altéa Inventory grâce à Jenkins

Gestion des versions du code : Étudier la faisabilité de la migration de CVS à Git/Stash

Compilation du code : Étudier la faisabilité de la migration d'un système de compilation fait sur mesure, vers Maven

Transfert et exploitation des dépendances middleware de la GUI Java sous Nexus

Modernisation des processus et transfert de connaissances : Adaptation en Shell Unix du script de compilation de la GUI d'Altéa Inventory et réunions bimensuelles avec mon coéquipier à Bangalore

Utilisation quotidienne de JIRA pour gérer les tickets de maintenance, grâce à Kanban

Architecture et composants communs à l’application : effectuer les développements sur les composants communs à toutes les applications d'Altéa Inventory soit en C++, soit en Java

**Jusqu’en 2014**
Intégration des changements dans le code de l'application, construction et livraison des nouvelles versions d'Altéa Inventory, à la fois côté serveur et côté client. Travail transféré progressivement à Bangalore à partir de la fin 2014.

**2015, 8 mois**
ParamWeb : Développement en Python 2.7/HTML5/CSS3/JavaScript suivant le framework Django d'un site web visant à documenter les paramètres et variables d'activation d'Altéa Inventory. Développement et gestion du projet selon la méthodologie Agile Scrum avec 3 collègues

**Fin 2015, 3 semaines**
Recensement de tous les scripts automatisés (crontabs) qui s’exécutent sur les machines de développement afin de déterminer la propriété et la pertinence de chacun, et de supprimer ceux qui sont obsolètes

**Début 2015, 3 mois**
Conception et développement d’un programme d’installation de la GUI Java sur mesure pour les compagnies aériennes, en C++ pour la partie auto-extraction de l’exécutable, d’après le code de 7-Zip et Java pour l’installation proprement dite

**2013, 3 mois**
Rédaction d’un guide de support aux opérations pour les personnes d’astreinte

**A partir de juin 2015, jusqu’à la fin de la mission**
animation d’un groupe de développeurs de la GUI Java, une fois par mois pour parler des évolutions, des nouvelles versions du logiciel, des changements d’architecture et améliorer la qualité du code, unifier le style de code sur toute l’application

### Résultats
- ParamWeb déployé en production et utilisé par les analystes et ingénieurs d’implémentation pour gérer le cycle de vie de leurs paramètres d’activation
- Programme d'installation de la GUI d'Altéa Inventory : en production
- Groupe de développeurs Java sur place et opérationnel

### Bilan personnel
- Une première expérience dans une entreprise prestigieuse et un environnement international et très compétitif
- Retour très positif de mes managers
- Rencontre et collaboration avec divers profils : développeurs, analystes, testeurs, chefs de projet, chefs d’équipe, opérateurs, gestionnaires de service client, de langues et nationalités différentes
- J'ai travaillé sur beaucoup de projets et ai acquis beaucoup de compétences sur des domaines variés

## ABYLSEN / Startup anonyme (06) | 10 - 24 mars 2016 (2 semaines)
Consultant en développement Java d’applications web
### Environnement technique
- *Back-end :* Java/J2EE, Play framework, Ebean
- *Front-end :* Bootstrap, Ajax, Scala, HTML, CSS, JavaScript, Ajax
- Git
- Activator, qui est un outil de compilation et démarrage du serveur web
- SBT
- *Environnement Unix :* Poste de travail Mac OS X et machine virtuelle Ubuntu
- Eclipse
- VirtualBox
- Fichiers CSV et Excel, pas de base de données proprement dite

### Contexte et objectifs
Startup anonyme basée à Nice Ouest, effectif : 8 personnes

Secteur d’activité : développement et promotion/vente d’algorithmes et de produits liés à l’allocation et la fructification d’actifs ; PAS de l’asset management

Seul consultant et développeur dans l’équipe composée principalement d’analystes financiers

Intervention de 2 semaines pour améliorer un prototype, Robo Advisor, à présenter à un client final de la startup anonyme

### Réalisations
- Étude de l’existant
- Prise en main de l’environnement
- Développement de l’interface web en Java, HTML/Scala, CSS, JavaScript et Ajax, ajout de formulaires permettant d’effectuer des simulations financières
- Développement en Java d’algorithmes d’allocations d’actifs déjà existants de simulation de projets financiers
- Développement d’un agrégateur de simulation de projets financiers d’allocations d’actifs, rendu graphique de cette agrégation

### Résultats
- Travail inachevé, résultat non conforme aux attentes du client
- Trop de pression, journées longues, mission ayant duré un jour de plus que prévu
- Ce devait être une sorte de période d'essai pour une mission plus longue avec cette startup plus tard, qui n'a jamais eu lieu bien sûr...

## LGM / PSA Peugeot Citroën (78) | avril - septembre 2012 (6 mois)
Ingénieur stagiaire en développement Visual C++ (stage de fin d’études)
### Environnement technique
- Visual Studio 2005
- C++
- .NET Framework
- XML
- UML
- Enterprise Architect
- Windows Vista

### Contexte et objectifs
- Usine PSA Peugeot-Citroën de Vélizy B, centre technique national
- Rattaché au département « Boîtier de Servitude et Logiciel Embarqué »
- Sujet : Outil de génération automatique de listes d’exécution de tests sur structure d’accueil BSI (boîtier de servitude intégré), i.e. calculateur embarqué automobile
- Projet par itérations, livrables à fournir tous les mois

### Réalisations
- Prise en main de Visual Studio 2005
- Planification du développement des fonctionnalités et des itérations
- Conception objet, utilisation d'UML et d’Enterprise Architect
- Extraction d'information depuis les spécifications techniques au format Word
- Lecture et modification de *fiches de test* : fichiers XML décrivant les tests
- Développement en Visual C++ d’une interface graphique pour mettre à jour les fiches de tests à partir des spécifications
- Développement en Visual C++ d’une interface graphique pour créer et mettre à jour des listes de tests selon des critères de recherche : nature des tests, matériel, etc.
- Génération de la documentation technique avec Doxygen aux formats HTML et PDF

### Résultats
- Applications fonctionnelles
- Rapport de stage rédigé
- Soutenance effectuée
- Documentation technique rédigée

# DIPLÔMES ET FORMATIONS
## Niveau master
2012
	Diplôme d’ingénieur en informatique, spécialisation logiciels embarqués
	TELECOM Nancy, Université de Lorraine à Nancy, 54
## Niveau bac + 2 (L2)
2009 :
	Classe préparatoire aux grandes écoles, PCSI/PSI
	Lycée Jacques Decour à Paris 9ème arrondissement, 75
## Niveau bac
2007 :
	Baccalauréat général, S option sciences de l'ingénieur
	Lycée Simone de Beauvoir à Garges-lès-Gonesse, 95
