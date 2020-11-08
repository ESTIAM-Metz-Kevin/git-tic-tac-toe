# TIC TAC TOE

Le tic-tac-toe, aussi appelé « morpion », est un jeu de réflexion se pratiquant à deux joueurs au tour par tour dont le but est de créer le premier un alignement.

L'objectif est de vous faire manipuler les bases de GIT en gérant des parties des parties de tic tac toe engagée entre Goku & Saitama. Chaque tour de jeu est représenté par 1 `commit`.

# Exercices

## ▶️ Ex. 1

* Pour pouvoir pousser les modifications de chaque exercice, vous devez lier votre dépôt distant github classroom à votre dépôt local avec l'utilisation de la commande `git remote`
* Pousser la base de ce projet sur ce nouveau dépôt à l'aide de `git push`

## ▶️ Ex. 2

Veuillez répondre aux questions suivantes :

| Questions  | Réponses |
| ------------- | ------------- |
| Quel est le hash du dernier commit  | `Réponse ??` |
| Quel est le hash du premier commit  | `Réponse ??` |
| Quelles sont les branches existantes à ce dépôt | `Réponse ??` |
| Combien il y a de commits sur la branche courante (`master`) | `Réponse ??` |
| Combien il y a de commits sur la branche `partie_1` | `Réponse ??` |

---
Quand vous avez répondu à toutes ces questions, veuillez :
* Indexer ces modifications
* Les confirmer avec un `commit`
* Les pousser sur le dépôt distant, que je puisse vérifier vos réponses 😈

## ▶️ Ex. 3

* Déplacez vous sur la branche `partie_1`

| Questions  | Réponses |
| ------------- | ------------- |
| Qui a gagné la partie  | `Réponse ??` |

---
Quand vous avez répondu à toutes ces questions, veuillez :
* Indexer ces modifications
* Les confirmer avec un `commit`
* Les pousser sur le dépôt distant, que je puisse vérifier vos réponses 😈

## ▶️ Ex. 4

* Créez une branche `partie_4`
* Faites jouer les deux joueurs en appliquant un commit par tour de jeu
* Poussez les modifications sur le dépôt distant

## ▶️ Ex. 5

Une branche `test_partie` avait été créée pour faire quelques tests. Nous n'en n'avons plus besoin
* Supprimez là

**⚠️ La branche doit également ne plus être visible sur le dépôt distant**

## ▶️ Ex. 6

Dans la `partie_2`, un parasite 🐛 s'est inséré sur un dernier commit et a altéré le style de notre jeu.

* Que nenni, forcez un retour en arrière pour annuler ce qui a été fait à l'aide de `git reset` !
* Poussez le résultat sur le dépôt distant (va falloir forcer un peu pour que ça passe !)

## ▶️ Ex. 7

Dans la `partie_3`, un joueur a joué 2x de suite 😤

* Corrigez cette erreur en lui enlevant le tour de jeu en trop. Il ne doit pas apparaître dans l'historique des modifications grâce à `git rebase`
* Poussez le résultat sur le dépôt distant.

## ▶️ Ex. 8

Une branche `modification_style` propose une modification des couleurs du jeu.
* Créez une branche `modification_style_2` depuis le dernier état de `partie_1`
* Proposez un nouvel agencement de couleurs 
* Quand vous êtes satisfait du choix, faites un `commit`

Comme vous êtes de bons graphistes 😎 votre proposition est la meilleure et a été retenue 🏆

* Faites la fusion de votre branche `modification_style_2` vers -> `modification_style`
* Faites un commit des modifications de la fusion
* Poussez le résultat sur le dépôt distant
* Supprimez `modification_style_2`

## ⭐ Bonus ⭐

Ouvrez le GIT GUI que vous avez choisi d'installer et tenter de refaire des manipulations de cet exercice avec ce dernier !