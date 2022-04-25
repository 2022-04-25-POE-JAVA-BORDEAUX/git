# Commandes de base utilisation terminal

[Plus d'information sur les commandes Unix de base à connaitre](https://doc.ubuntu-fr.org/tutoriel/console_commandes_de_base)
## Resumé
### Afficher répertoire courant

`pwd`
### Lister le contenu d'un répertoire

`ls`
#### Options
`ls -a` : afficher également les fichiers et dossiers cachés
`ls -l` : afficher informations détaillées sur les fichiers et dossiers

### Changer de dossier courant

`cd cheminVersLeDossier/`

### Créer un dossier

`mkdir nomDuDossier`

### Créer un fichier

`touch nomFichier.txt`

### Déplacer, renommer les fichiers ou dossiers
`mv source destination`
#### Exemples

### Copier fichiers ou dossiers

`cp source destination`: permet de copier des éléments
#### Options

`cp -r dossier1/ dossier2` : l’option -r permet de copier un répértoire recursivement autrement dit copier les sous-dossiers du répértoire également

### Supprimer les fichiers ou dossiers

`rm fichier1.txt`: permet de supprimer des fichiers

#### Options

`rm -r dossier1` : suppression récursive autrement dit supprime également les sous-dossiers et leurs contenus

### Obtenir le manuel d'utilisation d'une commande avec toutes les options disponibles

`man commande`

### Exemples

`man find`

#### Afficher le contenu d'un fichier

`cat fichier1.txt` : afficher tout le contenu du fichier

`more fichier2.txt` : afficher progressivement le contenu d'un fichier en appuyant sur la touche entrée pour avancer ou la touche q pour quitter