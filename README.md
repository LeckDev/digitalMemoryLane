<a name="readme-top"></a>

<!-- LOGO DU PROJET -->
<br />
<div align="center">
  <a href="https://github.com/LeckDev/digitalMemoryLane">
    <img src="chemin-vers-votre-logo-si-disponible" alt="Logo" width="80" height="80">
  </a>
<h3 align="center">Digital memory lane : Réseau social frise (TODO : à changer)</h3>
  <p align="center">
    Le réseau social pour partager votre frise.
  </p>
</div>

***

<!-- TABLE DES MATIÈRES -->
<details>
  <summary>Table des Matières</summary>
  <ol>
    <li><a href="#description-du-projet">A propos du projet</a></li>
    <li><a href="#fonctionnalites">Fonctionnalités</a></li>
    <li><a href="#technologies-utilisees">Technologies Utilisées</a></li>
    <li><a href="#contribuer">Contribuer</a></li>
    <li><a href="#licence">Licence</a></li>
    <li><a href="#contact">Contact</a></li>
    <!-- Ajoutez d'autres sections selon vos besoins -->
  </ol>
</details>

<!-- A PROPOS DU PROJET -->
<p id="description-du-projet"></p>

# À propos du Projet

Un réseau social permettant à un utilisateur ou à un groupe d'utilisateurs de créer leurs frises personnalisables

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

***

<!-- FONCTIONNALITES -->
<p id="fonctionnalites"></p>

## Fonctionnalités

- Frise : Les utilisateurs créent/modifient une frise
- Profil : Les utilisateurs créent leur profil et postent leurs frises
- Fil d'actualité : Les utilisateurs consultent leur fil d'actualité et voient le détail des évènements

## Fonctionnalités à venir 

- Ami : Les utilisateurs s'ajoutent en ami et voient les frises de ceux-ci dans leur fil d'actualité
- Réaction : Les utilisateurs réagissent sur les frises
- Frise en groupe : Les utilisateurs ajoutent des amis sur une frise et toutes ces personnes peuvent la modifier
- Frise communautaire : Les utilisateurs créent des communautés et peuvent en rejoindre. Les frises des communautés qu'un utilisateur suit se retrouvent dans le fil d'actualité
- Rôle communautaire : Les admins d'une communauté peuvent gérer les rôles des utilisateurs afin que ceux-ci puissent gérer la communauté en fonction de ses droits

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

***

<!-- TECHNOLOGIES UTILISEES -->
<p id="technologies-utilisees"></p>

## Technologies Utilisées (TODO : à voir avec Sten)

- Front-End : React, TypeScript, React Router, Chakra UI.
- Back-End : .NET, Entity Framework Core, LINQ.
- Base de Données : PostgreSQL.
- Qualité du Code : Eslint, Prettier.

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

***

<!-- CONTRIBUER -->
<p id="contribuer"></p>

## Contribuer (TODO : à voir avec Sten)

Voici un guide étape par étape pour contribuer :

1. Prérequis

Avant de commencer, assurez-vous d'avoir installé les logiciels suivants sur votre machine :

  Git: Nécessaire pour cloner le dépôt et gérer les versions. Télécharger Git.
  Docker : A venir
  Autres : A vernir

2. Fork du Projet

Créez une copie du projet sur votre compte GitHub. Cela vous permet d'apporter des modifications sans affecter le projet original.

  1. Visitez le repository GitHub de DuckLift.
  2. Cliquez sur le bouton Fork en haut à droite de la page.

3. Cloner le Fork

Après avoir forké le projet, clonez-le sur votre machine locale pour commencer à travailler dessus.


```bash
git clone https://github.com/Netsbump/DuckLift.git
cd DuckLift
```

4. Configurer un Upstream Remote

Pour garder votre fork à jour avec le projet original, configurez un remote "upstream" pointant vers le dépôt d'origine.

```bash
git remote add upstream https://github.com/Netsbump/DuckLift.git
```

5. Créer une Branche de Fonctionnalité

Pour chaque nouvelle fonctionnalité ou correction, créez une nouvelle branche. Cela facilite le suivi des changements et la gestion des pull requests.

```bash
git checkout -b feature/NomDeVotreFonctionnalité
```

6. Faire des Changements

Apportez vos modifications ou ajouts au code. Assurez-vous de respecter les conventions de codage et les bonnes pratiques du projet.

7. Garder Votre Branche à Jour

Avant de pousser vos changements, assurez-vous que votre branche est à jour avec la branche principale du projet original.


```bash
git fetch upstream
git rebase upstream/main
```

8. Committez vos Changements

Faites des commits clairs et significatifs. Chaque commit doit idéalement représenter une unité logique de changement.

 Chaque commit doit idéalement représenter une unité logique de changement. Voici quelques bonnes pratiques pour les messages de commit :

- Commencez le message par un type de changement comme feat, fix, docs, style, refactor, test, ou chore.
- Utilisez le format type: sujet pour vos messages.
- Le sujet ne doit pas dépasser 50 caractères.
- Utilisez l'impératif présent, par exemple : "Ajoute" plutôt que "Ajouté".

```bash
git add .
git commit -m "feat: Ajoute une fonction de recherche avancée"
```

9. Push Vers Votre Fork

Poussez les changements de votre branche vers votre fork sur GitHub.

```bash
git push origin feature/NomDeVotreFonctionnalité
```

10. Ouvrir une Pull Request

  - Retournez sur le repository GitHub de DuckLift.
  - Vous verrez un bouton Compare & pull request. Cliquez dessus.
  - Remplissez une description claire et détaillée de vos changements.
  - Soumettez la pull request.

11. Bonnes Pratiques

  - Code propre et lisible : Assurez-vous que votre code est bien formaté et suit les conventions du projet.
  - Tests : Ajoutez des tests pour les nouvelles fonctionnalités ou les corrections de bugs.
  - Documentation : Mettez à jour le README et tout autre document nécessaire pour refléter vos changements.

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

***

<!-- LICENCE -->
<p id="licence"></p>

## Licence

Distribué sous la Licence MIT. Voir le fichier LICENSE pour plus d'informations.
<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

***

<!-- CONTACT -->
<p id="contact"></p>

## Contact

Twitter - [@votre_twitter] - email@example.com
Linkedin 

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>