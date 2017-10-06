---
layout: post
title:  "Les Algorithmes: Les Instructions (Partie 2/3)"
date:   2017-10-06 13:50
---
# Les Algorithmes: Les Instructions (Partie 2/3)
## 2017-10-06

Dans le poste on a appris le vocabulaire de base pour réaliser un algorithme, maintenant faut être capable de dialogue avec la machine.

Tout d'abord nous débutons par écrire un programme capable de garde une valeur et ensuite qu'il puisse l'afficher.

Les instructions qui permettent de “dialoguer” avec une machine s’appellent les instructions “d’entrée/sortie” ou de “lecture/écriture”

### Lecture

Pour pouvoir saisir une valeur on utilise des instructions tels que lire, entrer, ou saisir suivi du nom d'une variable.

```
variables
   x : entier
début algorithme
   lire x
   y prend la valeur 2*x
fin algorithme
```

Cet algorithme demande d’entrer un nombre entier, stocke la valeur de ce nombre dans la variable x, puis calcule le double du nombre entré et affecte ce double à la variable y.

### Ecriture

Dans notre pseudo-code nous utiliserons l’instruction afficher suivie du nom d’une variable ou d’une constante (nombre, texte …) pour afficher une valeur.

```
afficher 'Ce texte sera affiché'
```
Voici l'example d'un programme qui aficher votre age en 2100:
```
variables
   année, âge, âge_en_2100 : entiers
début algorithme
   afficher "Entrer l'année actuelle"
   lire année
   afficher "Entrer votre âge"
   lire âge
   âge_en_2100 prend la valeur âge + 2100 - année
   afficher "En 2100, vous aurez ", âge_en_2100, " ans."
fin algorithme
```
On arrive a la fin, je vous vois dans une prochaine fois!
