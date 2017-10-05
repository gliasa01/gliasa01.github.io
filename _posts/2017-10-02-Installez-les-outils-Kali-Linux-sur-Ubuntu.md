---
layout: post
title:  "Installez les outis Kali Linux sur Ubuntu"
date:   2017-10-02 20:38
---
# Kali Linux
## {{ post.date | date_to_string }}

Kali Linux est une distribution GNU/Linux, l'objectif de Kali Linux est de fournir une distribution regroupant l'ensemble des outils nécessaires aux tests de sécurité d'un système d'information, notamment le test d'intrusion.

Pour ce faire, nous allons installer les outils de Kali sur Ubuntu sans avoir besoin de le faire tourner dans une machine virtuel!
Katoolin a etais crée pour faciliter la tache, seulment avec quelques lignes de code on ta des outils tres puissant dans les mains.

### Installez Katoolin

L'installation ce fait entierement par ligne de commande. Ouvrons le terminal de votre distribution Linux et tapez le suivant:
```
sudo apt-get install git
sudo git clone https://github.com/LionSec/katoolin.git
sudo cp katoolin/katoolin.py /usr/bin/katoolin
sudo chmod +x /usr/bin/katoolin
```
Mantenant vous etais pret a l'installer, il vous suffit de suivre les petites instructions données par le programme.
