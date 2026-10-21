# Présentation du Portfolio de Kiyane MEHAH

Ce projet consiste à créer un site web personnel permettant de présenter mon parcours, mes compétences, mes projets et mes expériences professionnelles. Il est réalisé dans le cadre de ma **3e année de BUT Sciences des données**.

## 1. Analyse des besoins

### a. Objectif du site

Le portfolio a pour objectif de présenter mon profil et de valoriser les compétences acquises au cours de ma formation et de mes expériences. Il servira de support pour mes candidatures en master et pourra être consulté par des recruteurs, des employeurs ou des responsables de formation.

Le site doit permettre aux visiteurs de comprendre rapidement mon parcours, de découvrir mes réalisations et de me contacter.

### b. Besoins principaux

- **Présenter** mon parcours et mes compétences
- **Mettre en valeur** mes projets et les technologies utilisées dans ces projets
- **Décrire** ma formation et mes expériences professionnelles
- **Faciliter** la navigation entre les différentes pages
- **Permettre** aux visiteurs de consulter mes coordonnées et de me contacter
- **Stocker et organiser** les informations du site dans une base de données

## 2. Fonctionnalités

Le site sera organisé autour d’une page principale, avec une navigation vers les différentes rubriques du portfolio. Les visiteurs pourront consulter les informations sans se connecter.

Les principales fonctionnalités attendues sont :

- **Naviguer** entre les sections du portfolio
- **Consulter** ma présentation, mes compétences, mes projets, ma formation et mes expériences
- **Accéder** aux informations de contact
- **Consulter** les informations liées à la base de données dans la section dédiée

## 3. Organisation du contenu et arborescence du site

### 3.1 Accueil

- Photo, nom et prénom
- Présentation brève : alternance, âge, localisation
- Formation : BUT Science des données, IUT de Dole
- Bouton **« Voir mes projets »**
- Bouton **« Télécharger mon CV »**
- Lien **« En savoir plus sur moi »**, vers la page À propos

### 3.2 À propos de moi

- Parcours scolaire : ensemble des formations, dans l'ordre chronologique
- Parcours professionnel
- Alternance : missions réalisées, entreprise d'accueil
- Centres d'intérêt et loisirs

### 3.3 Projets (SAÉ)

- Navigation : BUT 1, BUT 2, BUT 3, puis semestres 1-2, 3-4, 5-6
- Liste des projets du semestre choisi
- Fiche d'un projet :
  - **Objectif et étapes**
  - **Dates**
  - **Durée** : nombre de semestres couverts, nombre de semaines, nombre d'heures
  - **Soft skills** : 1 ou 2 mots
  - **Hard skills** : 1 ou 2 mots
  - **Technologies utilisées**
  - **Résultat**
  - **Preuves associées**

### 3.4 Technologies

Pour chaque logiciel ou langage :

- **Niveau de maîtrise**
- **Nombre d'heures**
- **SAÉ où il a été utilisé** (liens vers les fiches projet)
- **Utilisation en alternance** : oui ou non

### 3.5 Compétences

- **BUT 1** : traiter, analyser, valoriser
- **BUT 2 et BUT 3** : traiter, analyser, valoriser, développer
- Pour chaque compétence et chaque année :
  - **Description brève de la compétence**
  - **Description brève des AC**
  - **Projets liés**
  - **Preuves téléchargeables**, avec lien vers la SAÉ correspondante

### 3.6 Notes

- **Filtre année** : BUT 1, BUT 2, BUT 3 ou les trois
- **Filtre compétence** : une seule à la fois (« développer » indisponible en BUT 1)
- **Affichage** :
  - Moyenne du semestre
  - Courbe d'évolution
  - Valeur chiffrée lisible

## 4. Technologies envisagées pour le projet

- **HTML et CSS** pour la structure et la mise en forme
- **JavaScript** pour les interactions
- **PostgreSQL** pour la base de données
- **Git et GitHub** pour le versionnement du projet
- **Une technologie côté serveur**, qui reste à définir

## 5. Base de données

Un schéma relationnel sera réalisé afin de définir la structure de la base de données. Celle-ci sera ensuite créée avec **PostgreSQL** et contiendra les informations nécessaires au fonctionnement du site, comme les données relatives aux projets, aux compétences ou aux expériences.

## 6. Suivi du projet

Le projet est versionné avec **Git**. Des commits réguliers seront réalisés afin de suivre son évolution et de conserver un historique des différentes étapes de développement.
