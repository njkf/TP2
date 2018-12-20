B1 Réseau 2018 - TP2


I.	Exploration locale en solo
1.	Affichage d’informations sur la pile TCP/IP locale

J’ai ouvert PowerShell et tapé la commande « ipconfig /all »
Interface WIFI :
Carte réseau sans fil wifi
Adresse MAC : Adresse physique 84-A6-C8-06-FF-9A
Adresse IP : 10.33.2.81
Adresse de réseau : 10.33.0.0
Adresse de broadcast : 10.33.3.255
Interface Ethernet :
Carte Ethernet Ethernet
Adresse MAC : Adresse 8C-89-A5-05-8C-88
Adresse IP : Pas d’adresse IP
Adresse de réseau : 
Adresse de broadcast : 

 	Dans les informations de la carte Wifi, en tapant « ipconfig /all », on trouve l’adresse IP de « passerelle par défaut ».

Pour trouver les informations sur la carte IP, en utilisant l’interface graphique, il suffit d’ouvrir le centre de réseau et partage en cliquant droit sur l’icône du wifi dans le menu en bas à droite de l’écran. J’ai ensuite cliqué sur « modifier les paramètres de la carte ». Il suffit ensuite de faire un clic droit sur la carte voulu puis cliquer sur « statut » et aller dans « détails ».

La Gateway est un nœud agissant comme pivot, elle permet de sortir du réseau (du réseau Ingésup vers Internet par exemple).


2.	Modifications des informations
A.	Modification d’adresse IP – pt.1	

La première IP du réseau est : 10.33.0.1 et la dernière est : 10.33.3.254 car 10.33.3.255 est l’adresse de broadcast et 10.33.3.253 est l’adresse gateway

Pour changer l’adresse IP de la carte wifi, en utilisant l’interface graphique, il suffit d’ouvrir le centre de réseau et partage en cliquant droit sur l’icône du wifi dans le menu en bas à droite de l’écran. J’ai ensuite cliqué sur la connexion wifi sur laquelle j’étais connecté, en l’occurrence celle d’YNOV, puis sur « propriétés ». Il faut ensuite sélectionner le protocole Internet version 4 et cliquer sur propriétés. Il suffit ensuite de cocher « Utiliser l’adresse IP suivante » et écrire l’adresse IP, le masque, la passerelle et le serveur DNS voulus.
