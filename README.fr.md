[🇬🇧 English](README.md)

# Préparation (data wrangling) et validation des données ouvertes

[![DOI](https://zenodo.org/badge/253458856.svg)](https://zenodo.org/badge/latestdoi/253458856)

L'expression "données ouvertes" s'entend généralement des données qui sont mises à la disposition du public gratuitement, accesible sans authentification ni licence restrictive, à quelque fin que ce soit (y compris à des fins commerciales), dans des formats électroniques exploitables par des machines (machine-readable) qui garantissent que les données sont faciles à trouver, à télécharger et à utiliser. 
 
Les initiatives en matière de données ouvertes prises par les institutions publiques ou privés, telles que les gouvernements et les organisations intergouvernementales reconnaissent que ces données sont produites avec des fonds publics et doivent donc, à quelques exceptions près, être traitées comme des biens publics.
 
La réutilisation des données, tant par les experts en données que par le grand public, est essentielle pour créer de nouvelles opportunités et de nouvelles connaissances à partir des données gouvernementales. La réutilisation ouverte des données requiert deux critères de base :
 
1. Les données doivent être légalement ouvertes, ce qui signifie qu'elles sont placées dans le domaine public ou dans des conditions d'utilisation libérales avec un minimum de restrictions. Cela garantit que les politiques gouvernementales ne créent pas de barrières ou d'ambiguïtés quant à la manière dont les données peuvent être utilisées.
2. Les données doivent être techniquement ouvertes, ce qui signifie qu'elles sont publiées dans des formats électroniques exploitables par des machines et non propriétaires. Cela garantit que les citoyens ordinaires peuvent accéder aux données et les utiliser à peu de frais, voire gratuitement, en utilisant des outils logiciels courants.

L'objectif de ce programme d'études dans _Préparation et validation de données ouvertes_ est de guider les participants vers la confiance dans la fourniture de données techniquement ouvertes : des données bien structurées, exploitable par des machines, validées selon un schéma de métadonnées défini et standard.

## Leçon 1 : Préparation de données - données désordonnées

_Objectifs d'apprentissage_ :

- Comprendre et avoir une expérience pratique de la structure et de la conception des fichiers de données exploitables par les machines.
- Utiliser Excel pour étudier et manipuler les données sources afin de connaitre leurs métadonnées, leur forme et leur robustesse, et utiliser ces méthodes pour développer un schéma de métadonnées structurelles.
- Apprendre et appliquer un ensemble de méthodes de base pour restructurer des données source désordonnées en fichiers CSV exploitables par une machine à l'aide de Microsoft Excel.
- Apprendre, et avoir une expérience pratique de l'écriture, la syntaxe de base et l'approche du codage en Python.
- Intégrer et appliquer les méthodes des bibliothèques d'analyse de données de base de Numpy, Pandas et Matplotlib pour étudier et manipuler les données sources.
- Effectuer des techniques d'analyse et de codage, en utilisant le package de préparation de données Whyqd, pour créer une méthode structurée, au format JSON, pour restructurer les données dans un schéma standard.

_Projet_ :

Chaque participant se verra attribuer une feuille de calcul de [données de formation](https://drive.google.com/open?id=0B8eZRkdFGaEHfnlwU25vdVRUOFNOdnNfWnMwb3IwYXJ3QU9BeTU0ZmlTNlpaRmZFZE5iM28) et devra la restructurer à la fois dans Excel et en utilisant Python/Whyqd.

## Leçon 2 : Validation des données restructurées par rapport à un schéma

_Objectifs d'apprentissage_ :

- Comprendre et utiliser des définitions standard pour écrire un schéma JSON pour la validation des données.
- Effectuer la validation des données à l'aide de Microsoft Excel.
- Apprendre à valider des données exploitables par les machines dans des applications en ligne par rapport à un schéma défini.
- Écrire et utiliser des fonctions modulaires pour valider automatiquement des fichiers de données en utilisant Python.
- Appliquer des techniques de publication de données ouvertes pour préparer les données, les schémas et les résultats de validation en vue de leur publication.

_Projet_ :

En utilisant la feuille de calcul créée dans la leçon 1, développer un schéma JSON, et valider les données en utilisant ce schéma sur [CSV Lint](https://csvlint.io/). Ensuite, importez [whyqd](https://whyqd.readthedocs.io/) et effectuez la même tâche en Python.

## Leçon 3 : Anonymisation des données personnelles avant la publication

_Objectifs d'apprentissage_ :

- Reconnaître les problèmes de respect de la vie privée et de la confidentialité lors du stockage des données et de la sécurité des données personnelles.
- Reconnaître les responsabilités et les mécanismes de sécurisation des données stockées (data-at-rest) ou en transit (date-in-motion).
- Utiliser des méthodes d'anonymisation des données, y compris le floutage géospatiale, la suppression des adresses et des noms, et l'obscurcissement des champs.
- Étudier et appliquer des techniques d'agrégation appropriées pour anonymiser les données personnelles qui ne peuvent pas être enlevées des fichiers.

_Projet_ :

Utiliser un échantillon de fichier de données fabriqué contenant des informations personnelles et expurger ces données pour éviter la désanonymisation.

## Projet : Préparation des données COVID-19 en vue de leur publication

Comme sujet d'actualité, une discussion générale sur les sources de données probables pour la diffusion, et les préparations. Nous pourrions avoir besoin de dossiers de patients fabriqués pour l'agrégation, les préparations et la diffusion.

---

## Le Formateur

Je m'appelle [Gavin Chait](https://gavinchait.com), et je suis un scientifique indépendant spécialisé dans le développement économique et la conservation des données. J'ai passé plus de dix ans dans des initiatives de développement économique et de développement en Afrique du Sud. J'ai été le responsable commercial de projets de données ouvertes à l'Open Knowledge Foundation, dirigeant l'équipe de développement du logiciel open source CKAN, et j'ai dirigé la mise en œuvre de nombreux projets techniques et de recherche de données ouvertes dans le monde entier. Récemment, j'ai développé [Sqwyre.com](https://sqwyre.com), une initiative pour développer un moteur de recherche complet d'intelligence économique pour les entrepreneurs. Les données sont basées sur des données ouvertes et des demandes de liberté d'information.

J'ai une grande expérience dans la direction de projets de recherche, la mise en œuvre d'initiatives de logiciels libres, et l'élaboration et l'animation de séminaires et d'ateliers. J'ai enseigné pendant 25 ans, notamment pour les étudiants de premier cycle, la formation des adultes et l'enseignement technique et analytique à tous les niveaux.

Je travaille depuis 2016 avec [SBC4D](http://www.sbc4d.com) sur de nombreux projets de formations ou de déploiements de portail open data dans divers pays comme le Ghana, le Maroc, la Tunisie, l'Ile Maurice ou la Tanzanie. Ce syllabus a été développé pour le projet [Des Chiffres et des Jeunes](https://www.dcdj.ci/) en Côte d'Ivoire.

## Licences et diffusion

Le contenu, le matériel et l'approche du cours sont protégés par les droits d'auteur de Gavin Chait et sont publiés sous les licences [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) et [MIT](https://opensource.org/licenses/MIT).

L'objectif est d'assurer la réutilisation et je recommande - mais n'exige pas - que toute modification ou adaptation du matériel source soit publiée sous une licence équivalente.