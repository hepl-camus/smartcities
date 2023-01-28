# Projet Smartcities.

Dans le cadre du cours de MicroPython et du projet Smartcorridor chaque étudiant de B33 et M03 devra se créer son propre Github. 

Le but de mon Github (github.com/hepl-camus) est de vous donner des informations sur la manière dont vous devez structurer le vôtre. C'est une coquille (presque) vide que vous devrez chacun(e) remplir au fur et à mesure et qui servira à votre évaluation continue.

## Phase 1 : créer votre compte.

Allez sur github.com puis :

- Entrez votre email (utiliser votre email HEPL).
- Suivre les instructions.
- Choisir comme nom de github : hepl-votrenom.
- Choisir le compte gratuit.

Une fois le compte créé ajouter votre photo (type identité) comme avatar.

## Phase 2 : créer un repository.

- Son nom : smartcities.
- Type public, licence MIT, avec readme file


## Compléter le fichier README.md.

C'est le fichier explicatif racine. Il devra contenir des informations sur la description du RPi Pico, de MicroPython et de l’environnement de travail.

Une photo du brochage du RPi Pico W est utile.

Il comportera des liens vers plusieurs sous-répertoires. Chaque sous-répertoire contiendra un fichier descriptif README.md et les ressources liées aux sujetx traités : code, datasheets, photos, explications diverses...

Les répertoires sont les suivants :

- **GPIO** : LED simple, bouton-poussoir, interruption.
- **A/D_PWM** : lecture du potentiomètre, PWM (LED, musique, servo).
- **LCD** : documentation des fonctions de la librairie, affichage de la valeur du potentiomètre.
- **LED_neo** : utilisation des LEDs néopixel, documentation des fonctions de la librairie, arc-en-ciel.
- **sensors** : température et humidité, luminosité, PIR.
- **network** : Accès réseau avec le RPi Pico.

Il apparaitront sous la form d'une liste de liens :

- [GPIO](GPIO)
- [A/D_PWM](AD/PWM]
- [LCD](LCD)
- [LED_neo](LED_neo)
- [sensors](sensors)
- [network](network)

## Ressources

**Après chaque opération il faut cliquer sur Commit changes** pour enregistrer dans le github.

Pour créer un répertoire :

- Remonter au niveau de la racine du repository.
- Cliquer sur ADD FILE -> Create New File.
- Entrer nom du répertoire/README.md

Exemple pour créer le répertoire GPIO : smarticities/GPIO/README.md

\
Pour créer un lien (vers un répertoire ou externe) : `[nom à afficher](lien)`

Exemple lien vers le répertoire GPIO `[GPIO](GPIO)` qui apparaîtra comme [GPIO](GPIO)

\
Le langage pour formater les fichiers de type md est décrit [ici](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
