# Specifications techniques

## Sommaire

- [Définition](#définition)
- [Intérêts](#intérêts)
- [Contenu](#contenu)
  - [Étude du besoin](#étude-du-besoin)
  - [Étude des utilisateur.ices](#étude-des-utilisateurices)
    - [Personae](#personae)
  - [État de l'art](#état-de-lart)
  - [Solution retenue](#solution-retenue)
    - [Liste des fonctionnalités](#liste-des-fonctionnalités)
    - [Architecture logicielle](#architecture-logicielle)
    - [Choix des langages](#choix-des-langages)
    - [Choix des dépendances / librairies](#choix-des-dépendances-librairies)
    - [Modélisation](#modélisation)
      - [MCD](#mcd)
      - [Diagrammes de classes](#diagrammes-de-classes)
      - [Diagrammes de séquence](#diagrammes-de-séquence)
      - [Contrats d'interface](#contrats-dinterface)
    - [Design interface utilisateur](#design-interface-utilisateur)
  - [Coûts](#couts)
  - [Déploiement](#déploiement)
- [Adapter à différentes échelles](#adapter-à-différentes-échelles)
  - [User story](#user-story)
  - [Ticket](#ticket)


## Définition

> a description of software created to facilitate analysis, planning, implementation, and decision-making

- spécification technique === technical specs === sofware design document
- document texte
- description de la procédure pour résoudre un problème, répondre à un besoin
- document vivant
  - mettre à jour en fonction des retours utilisateurs et l'évolution de la demande

## Intérêts

- réfléchir en amont au problème posé, aux solutions possibles, à leurs implémentations
- permet de tester si les solutions conviennent avec les utilisateur.ices
- servir de cahier des charges
  - contrat passé entre la partie exécutante et la partie donneuse d'ordre
  - délimiter le scope de la solution
- servir de documentation à posteriori
- servir à l'onboarding de nouvelles personnes dans l'équipe
- servir à la rédaction de tests

## Contenu

### Étude du besoin

- ce qui sera résolu
  - tout comme ce qui ne le sera pas

### Étude des utilisateur.ices

#### Personae

- qui va utiliser l'application
  - âge, genre, situation sociale/professionnelle, intérêts
  - comment l'application sera utilisée
  - ce que la personne va gagner de cette application

### État de l'art

- si rajout de fonctionnalité dans une application existante
  - description de l'application
- si nouvelle application
  - quel est le process actuel
  - quelles sont les données
  - quelles sont les limitations
- expliquer en quoi le besoin n'est pas répondu avec l'existant

### Solution retenue

- également citer les alternatives
  - et pourquoi elles n'ont pas été choisies

#### Liste des fonctionnalités

- nom
- description
- autorisations
- 

#### Architecture logicielle

- monolithe vs backend + frontend vs micro architecture
- ssr, ssg, csr, spa, ...

#### Choix des langages

#### Choix des dépendances / librairies

#### Modélisation

##### MCD

- permet de connaître le design des données

Extrait du cours sur l'introduction aux bases de données :

> Le MCD, ou Modèle Conceptuel des données, est la première étape de la méthode Merise et celle qui nous intéresse ici.
>
> C'est une représentation graphique permettant de comprendre quels éléments composent un système, quelles sont les données qu'ils gèrent, et comment ces éléments intéragissent entre eux.
>
> Pour produire un MCD, la personne en charge devra se fier à des spécifications techniques qu'on lui aura fournies, des interviews avec les clients/utilisateurs, des règles de gestion du métier, un ou des systèmes existants, ...
>
> Un MCD se compose :
>
> - d'entités (en rectangle)
> - de relations (en oval et avec des traits reliant les entités)
> - de propriétés dans les entités et parfois les relations
> - de cardinalités (chiffres au dessus des traits entre les entités et relation)

##### Diagrammes de classes

- quelles fonctions sont gérées par quelles classes

##### Diagrammes de séquence

- comment une fonctionnalité se déroule
  - quels sont les acteurs nécessaires
  - quels sont les inputs
  - quelles sont les routes possibles
  - quelles classes et fonctions intéragissent ensemble

##### Contrats d'interface

- détails sur les inputs et output possibles du programme
- le fonctionnement n'est pas intéressant
- se concentrer uniquement sur ce qui est nécessaire au bon fonctionnement du programme

### Design interface utilisateur

- wireframe, low res, mockup
- charte graphique
- le comportement à l'utilisation
  - animations
  - présences/absences des CTA

### Coûts

- estimation de temps
  - permet d'estimer le budget
  - seulement une indication, à ne pas prendre comme deadline fixe

### Déploiement

- quand
- sur quels services
- avec quels accès
- à quelle fréquence

## Adapter à différentes échelles

### User story

### Ticket

- permet de décrire une tâche atomique
  - ou plusieurs petites tâches reliées ensembles
- permet d'avoir un suivi et une planification
- titre contient
  - résumé du besoin
  - tags permettant d'identifier / trier rapidement le scope
    - quel environnement, quelle user story, ...
- description contient
  - explication du besoin
  - quels sont les bloqueurs à ce besoin
  - quelles sont les données concernées
  - quel est l'environnement concerné
  - quel est le résultat souhaité
  - quelles sont les actions à réaliser pour obtenir le résultat
  - quel est le scope
- fournir un maximum de data
  - chiffres
  - exemples d'input et d'output
  - exemples d'affichages, d'animations
  
