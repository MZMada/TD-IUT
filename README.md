# 🚀 Créer un Serveur Garry's Mod sur MTXServ

Ce guide va vous t'apprendre à configurer un serveur Garry's Mod (autrement appeller Gmod) avec l’hébergeur **MTXServ**.

## 📋 Prérequis

Avant tout il faut :

- Un compte sur [MTXServ](https://mtxserv.com).
- Acheté un serveur sur le site de MTXServ.
- Enregisté l'accès à votre panel MTXServ.

## 🔧 Installation et Configuration

### Étape 1 : Commander un Serveur Garry's Mod

1. Rendez-vous sur [MTXServ](https://mtxserv.com).
2. Allez dans **Garry's Mod** et choisissez un serveur en fonction des besoins (RAM, slots, cpu, etc...).
3. Suivez les instructions pour accéder au serveur avec le **panel de gestion**.

### Étape 2 : Accéder au Panel de Gestion

1. Connectez-vous à votre compte MTXServ.
2. Allez dans **Mes Services** et choisissez votre serveur Garry's Mod.
3. Une fois sur le **Panel** de votre serveur vous pouvez :
   - Démarrer, redémarrer ou arrêter votre serveur.
   - Gérer les fichiers et les configurer.
   - Installer des addons ou des maps.

### Étape 3 : Configurer le Serveur

1. Allez dans **Configuration** sur le panel de votre serveur.
2. Modifiez le fichier `server.cfg` en ligne ou avec un accée ftp, en ajoutant les paramètres suivants :

   ```cfg
   hostname "Mon Serveur Garry's Mod MTX" //chosissez le nom du serveur
   sv_password ""  // mettre un mot de pass ou mettre du vide si pas de mot de passe
   rcon_password "votre_mot_de_passe_rcon" // le mot de passe rcon
   sbox_maxprops 100
   sbox_maxragdolls 10
   
3. Verifier de bien sauvegarder après chaque modification.

#### Étape 4 : Installer des Addons

1. Allez dans **Workshop** sur le panel MTXServ.
2. Recherchez des addons ou des cartes que vous souhaitez installer sur votre serveur via le Workshop steam.
3. Il faudra connecter sa key steam au serveur pour que MTXServ les télécharges.

## 🔄 Gestion et Redémarrage du Serveur

  - Démarrer 🟢 / Arrêter 🔴 le Serveur : Utilisez ses boutons pour gerer le serveur.
  - Redémarrer : Des que les modifications été effectué (ajout d’addons, changement de configuration, chagement de la carte), alors redémarrez le serveur.
    
## 🛠 Support et Assistance

Si vous rencontrez des problèmes :

  - Consultez le discord de MTXServ, avec une communauté bienveillante et a l'écoute.
  - Ouvrez un Ticket Support si vous ne trouver pas la reponse sur le discord.
    
## 🎉 Félicitations !

  - Ton serveur Garry's Mod est desormée en ligne et il est prêt à être utilisé. Vous pouvez inviter vos amis à vous rejoindre et bien evidement personnaliser votre serveur comme tu le souhaite.
