# Synology-DownloadStation-Hosts
Fichiers hosts pour ajouter des herbergeurs sur Download Station

# Fonctionnalités
- Fonctionne avec les comptes gratuit et premium

# Installation du fichier host
Récupérez le fichier host dans la partie **Lien** ou alors créez le avec la procédure disponible plus bas.

1. Connectez vous sur votre NAS Synology
2. Ouvrez Download Station
3. Allez dans la partie paramètres
4. Allez dans Hebergement de fichier
5. Cliquez sur Ajouter et selectionnez votre fichier Host
6. Une fois ajouté, cliquez sur modifier et ajouter votre compte si vous en avez un.

# Creation du fichier host
Sous Windows

1. Installez **7zip** sur votre PC dans le dossier **C:\Program Files\**
2. Récuperez le fichier **CreateHost.vbs** et le dossier de votre choix
2. Glissez tous les fichiers du dossier sur le script CreateHost.vbs
3. Entrez un nom pour le fichier host et valider
4. Le fichier host est créé sur le bureau

Sous linux

1. Récuperez le dossier de votre choix
2. Connectez vous sur le terminal et entrez la commande suivante
3. *tar zcf nomdufichier.host INFO fichier.php*

# Documentation
- http://global.download.synology.com/download/Document/DeveloperGuide/Developer_Guide_to_File_Hosting_Module.pdf
