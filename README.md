# Les fondements des réseaux Les protocoles et les outils CLI

Si vous travaillez dans l'administration informatique, suivez cette formation sur les réseaux et les protocoles associés. Avec Pierre Cabantous, vous aborderez les protocoles les plus courants, comme TCP/IP, HTTP, DNS, SMTP et bien d'autres encore. Vous utiliserez également les outils de gestion en ligne de commande ou à interface graphique. Au terme de cette formation, vous disposerez d'une bonne base technique sur les protocoles réseau.

## Céer un tchat avec netcat
Pour établir une comminucation entre deux PC avec netcat,  il faut tout d'abord **netcat**
* Pour Windows il faut télécharger le netcat au lien suivant:
   [Clique ici](https://eternallybored.org/misc/netcat/), et puis vous dezipper le fichier zip dans le repertoire **C://Wondows/sytem32** 
* Pour Linux Distrubution Debian, il faut tapper la commande suivante: <code>sudo apt-get install netcat </code>
  
### Etablissement de connexion TCP entre deux PC
* PC 1: dans  l'invite de commande taper <br><code>nc **adresse IP destination** port d'écoute </code>
* PC 2: dans  l'invite de commande taper <br><code>nc port d'écoute </code>