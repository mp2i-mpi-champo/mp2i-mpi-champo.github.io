---
title: "Info"
weight: 2
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
# bookHref: ''
# bookIcon: ''
---
# **Informatique**
Site de M. Karpman : [site](https://lzcnt.fr/CPGE/2026/)

## **Setup pour l'informatique**
Il est **vivement recommendé** d'avoir une machine avec **Linux**, MacOS est aussi acceptable et Windows avec WSL est... utilisable.

Pour le C, il vous faudra un compilateur, vous avez le choix entre [clang](https://clang.llvm.org/) et [gcc](https://gcc.gnu.org/).

Pour Ocaml, il faut un interpréteur : `utop` est préconisé. L'installation se fait *via* [opam](https://opam.ocaml.org/), qui vous permettra aussi de gérer les packages et versions ocaml.

Ensuite il suffit de l'installer avec `opam` :
```sh
$ opam install utop
```

## **Fonctionnement**
Le rythme est assez soutenu, le prof fonctionne avec un ensemble de diaporama : un par semaine le plus souvent.

Au niveau du travail en classe :
  - un TP de deux heures par semaine sur le chapitre en cours
  - un TD une semaine sur deux au S1 et toutes les semaines au S2
  - un DS environ toutes les 6 semaines

Il est conseillé de finir les TP à la maison, même si cela ne doit pas empiéter sur le reste, faites le si vous avez du temps et si ça vous donne envie. C'est surtout intéressant pour s'habituer à traiter des questions de programmations vraiment difficiles.

Les DS mixent questions de programmation et théorie, les premiers DS sont assez introductifs.
Note : la plupart des DS de sup sont quasiment que de la programmation et de l'algorithmique ; vous pouvez avoir une bonne note (13+) en ne traitant aucune question théorique. Il faut savoir programmer et réfléchir aux algorithmes avant d'apprendre à montrer des formules horribles sur les graphes.

## **Tips**
### **Pour le C**
Si vous chercher de la docu, le site [geekforgeeks](https://www.geeksforgeeks.org/) propose des articles sympa, vous avez aussi le [poly](https://lzcnt.fr/CPGE/2026/introc.pdf) rédigé par M. Karpman qui est très bien.

Quelques recommendations de flags de compilation :
  - `-Wall` et `-Wextra`, un must, active tous les warnings du compilateur pour vous prévenir des potentiels problèmes avec votre code
  - `-fsanitize=undefined`, un must aussi, permet d'afficher à l'éxécution les `undefined behavior` (choses qu'il est souvent préférable d'éviter)
  - `-fsanitize=address`, utile quand vous manipulez la heap, permet de prévenir à l'éxécution d'éventuels problèmes liés à la gestion mémoire

### **Pour Ocaml**
La [docu officielle](https://ocaml.org/manual/) est suffisante pour rechercher des méthodes.

## **Ressources supplémentaires**

- [La totale](https://bourotte.com/exos) : Exercices donnés en colle par une étudiante de L'ENS Lyon.
- [REQUIN](https://juliette.ponsonnet.org/requin.pdf) : Recueil de questions d'informatique. Vous pouvez tenter les problèmes d'algorithmique ; ils restent difficiles, mais le reste est pour les spé.
