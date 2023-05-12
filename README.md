# SYS1
# FTP - Authentification
PASS cdts3500
password: cdts3500

# TELNET authentification
-Copier le lien du bouton "démarrer le challenge" et l'ouvrir dans un onglet qui va télécharger un fichier `ch2.pcap`

-2. Ouvrir ce fichier sur `wireshark`

-3. Filter sur la barre de recherche `TELNET`

-4. Rechercher sur la colonne info `Telnet Data... [Malformed packet]`

-5. Suivre et puis retrouver le mot de passe: "user"


# ETHERNET TRAME authentification

Copier le lien du bouton "démarrer le challenge" et l'ouvrir dans un onglet qui va ouvrir un fichier `txt` 

. Décoder le texte puis copier le mot de passe pour accéder au challenge suivant


- décodage hexadécimal 
- décodage en base64

# Authentification-Twitter

-Chercher le mot de passe : Ouvrir le fichier sur Wireshark . Choisir un paquet à protocole HTTP et clic droit pour pouvoir suivre ce protocole et appuyer sur le flux HTTP.

Authorization: Basic dXNlcnRlc3Q6cGFzc3dvcmQ=

-une sérue de chiffre et de lettre précédé par un == ou un = apparait 

-Nous allons donc devoir decode la série Bite64

-Le password sera affiché 

# Bluetooth - Fichier inconnu

 Il faut commencer par chercher le nom du téléphone : on va dans "Wireless" puis on appuie sur Equipement bluetooth et là on voit la colonne Nom du télephone que l'on notera . et l'adresse Mac se situe sous la section BD_ADDR .
 
 Pour effectuer la concaténation , il est nécessaire de changer les lettres minuscules de l'adresse MAC en majuscules et ajouter le nom du telephone à côté de l'adresse MAC.
 
 Accéder à un site de décode SHA 1 
 
 Entrer le mot de passe.
