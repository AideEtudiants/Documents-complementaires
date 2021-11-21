# Projet collaboratif DEVOPS sur une application web d'aide aux Étudiants : Studenity

La crise liée au Covid19 a eu pour conséquence un manque d’emploi important qui a engendré une précarité financière pour certains jeunes étudiants.
Ces jeunes ont également été confrontés à un manque de lien sociaux du fait d’avoir cours à distance.
Nous cherchons donc à leur apporter une aide afin de leur fournir un outil d'entraide basé sur le partage.
Avec pour second objectif de favoriser le recyclage et de réduire la surconsommation et le gaspillage.

## Pour commencer

Afin de bien compiler et executer notre projet, il est nécessaire d'installer un environnement Java sous Spring Boot et aussi un environnement Angular.

### Pré-requis

- Installation d'un IDE (VScode ou IntelliJ)
- Installation des extentions Java sur l'IDE
- Installation de l'extention SpringBoot sur L'IDE (Visual Studio Code ou IntelliJ)
- Installation de NodeJS
- Installation de Angular en utilisant la ligne de commande NodeJS 
### Installation

Pour clonner notre projet au niveau local, vous trouverez les url sur gitHub aux adresses suivantes:
-  https://github.com/AideEtudiants 
-  La documentation liée au projet se trouve dans le repo https://github.com/AideEtudiants/Documents-complementaires.
-  Vous y trouverez le Scrum board ainsi que l'architecture de l'application.
-  Le front end se trouve dans le repo https://github.com/AideEtudiants/ProjetAngular et vous y trouverez tous les fichiers necessaires pour lancer le projet Angular.
-  Le back end se trouve dans le repo https://github.com/AideEtudiants/ProjetSpringBoot et contient les fichiers necessaires pour lancer le projet springboot.
- Il faut télécharger ensuite l'ensemble des fichiers contenus dans le front et ceux du back et les ouvrir dans l'IDE dans des fenetres differentes, de ce fait vous avez deux fenêtres ouvertes dans votre IDE contenant respectivement le front et le back.

## Démarrage
* API entre Spring Boot et Angular.
* Lorsque vous clonner le projet , Tapper "npm install" afin d'installer les dépendances nécessaires de Angular et par la suite "npm run build" afin de compiler, ensuite lancer le serveur avec la ligne de commande "ng serve" (de préférence sur une ligne de comande git hash).
* Si la commande ng n’est pas reconnue sur le terminal, ouvrez PowerShell en tant qu'administrateur et taper "Set-ExecutionPolicy ExecutionPolicy Unrestricted".
* Clonner le projet spring boot sur votre IDE en s'assurant que votre IDE a bien un compiler Java.
* Lancer le projet Spring Boot avec le bouton run sur votre IDE.
* Ensuite entrer cette url http://localhost:4200 afin d'afficher le résultat de l'API.

##  Angular Material 
* Afin de compiler le projet Angular sans erreur , il faudra ajouter les materiaux de design angular avec cette commande :
  ng add @angular/material
* pour ajouter la bibiotheque qui gere les teast en Angular , il faudra ajouter les services nécessairees avec les commandes suivantes :
  npm install ngx-toastr --save
  npm install @angular/animations --save


## Fabriqué avec

* HTML, CSS
* Java 
* Framework Angular
* Framework Spring Boot
* Éditeur VScode


## Versions
Java : 11.0.0
Angular CLI: 12.2.6
Spring Boot : 1.28.0
Node: 14.17.6
Package Manager: npm 6.14.15
Éditeur VScode : 1.60.2

**Dernière version stable :**  0.0.1

## Auteurs

* Akkoura Aniesse : https://github.com/AKKOURA
* Barry Aissatou : https://github.com/aissatoubarryfab
* Kende Emmanuela : https://github.com/Emmakende
* Le Phong-Sac : https://github.com/LEphongsac
* Smahi Lydia : https://github.com/LydiaSM
