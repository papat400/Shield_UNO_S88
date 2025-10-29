# Shield_UNO_S88

English
-------
An arduino UNO shield for S88 bus

This shield is designed to work with :
* An arduino UNO to command DCC/MFX electric train through a CanDIY shield like showed at https://wiki.mchobby.be/index.php?title=Railuino
* The Desktop Station project made by Yaasan, see https://desktopstation.net/index.html

Please note that to use this shield on top of the CanDIY shield, you will need to equip it with long headers.

The picture assembled_shields.jpg shows a view of the system (with an old basic version of my PCB).

The shield is the starting point of the S88 bus, with UNO connections as programmed in the TrackReporterS88_DS sketch (a part of the Desktop Station project).
See the S88 wiring on the S88_wiring.pdf file.

On the shield, 2 additional elements are provided:
* 1 "Reset" push button for the arduino UNO.
* 1 jumper allowing the S88 bus to be supplied with the + 5V from the arduino if necessary.

In the Eagle file's you'll find a simple version with only an S88-N connector (RJ45), and a second with an RJ45 and a 6 pins connector.

This PCB is designed for an RJ45 Stewart connector, type SS-7188S-A-NF (see datasheet).
If you want, you can change it with Eagle or a compatible software.

2021 03 28 : Added file Connection diagram.pdf, shows how to connect this S88 to the track and other switches.


Français
--------

Ce shield est conçu pour fonctionner avec:
* Un arduino UNO pour commander un train électrique DCC / MFX via un bouclier CanDIY comme indiqué sur https://wiki.mchobby.be/index.php?title=Railuino
* Le projet Desktop Station réalisé par Yaasan, voir https://desktopstation.net/index.html

Veuillez noter que pour utiliser ce module complémentaire par-dessus le module CanDIY, vous devrez l'équiper de connecteurs à broches longues.

L'image assembly_shields.jpg montre une vue du système (avec une ancienne version basique de mon PCB).

Le shield est le point de départ du bus S88, avec les connexions au UNO telles que programmées dans le croquis TrackReporterS88_DS (une partie du projet Desktop Station).
Voir le câblage S88 sur le fichier S88_wiring.pdf.

Sur le shield, 2 éléments supplémentaires sont prévus :
* 1 bouton poussoir "Reset" pour l'arduino UNO.
* 1 jumper permettant d'alimenter le bus S88 avec le +5V de l'arduino si cela s'avère nécessaire.

Dans le fichier Eagle, vous trouverez une version simple avec uniquement un connecteur S88-N (RJ45), et une seconde avec un connecteur RJ45 et un connecteur 6 broches.

Ce PCB est conçu pour un connecteur RJ45 de Stewart connector, type SS-7188S-A-NF (voir datasheet).
Si vous le souhaitez, vous pouvez le modifier avec Eagle ou un logiciel compatible.

28 mars 2021 : ajout d'un fichier Connection Diagram.pdf montrant comment connecter le détecteur S88 à la voie et aux autres accessoires.


Thierry.
