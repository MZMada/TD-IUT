# 🚀 Créer un Serveur Garry's Mod sur MTXServ

Ce guide va vous explique comment configurer un serveur Garry's Mod (autrement appeller Gmod) avec l’hébergeur **MTXServ**. MTXServ qui facilite l'installation et la prise en mains de serveur Gmod.

## 📋 Prérequis

Avant tout il faut :

- Un compte sur [MTXServ](https://mtxserv.com).
- Acheter un serveur sur le site de MTXServ.
- Enregisté l'accès à votre panel MTXServ.

## 🔧 Installation et Configuration de Base

### Étape 1 : Commander un Serveur Garry's Mod

1. Rendez-vous sur [MTXServ](https://mtxserv.com).
2. Allez dans **Garry's Mod** et choisissez une offre de serveur en fonction de vos besoins (RAM, slots, cpu, etc.).
3. Suivez les instructions et accéder à votre serveur via le **panel de gestion**.

### Étape 2 : Accéder au Panel de Gestion

1. Connectez-vous à votre compte MTXServ.
2. Allez dans **Mes Services** et sélectionnez votre serveur Garry's Mod.
3. Vous arrivez maintenant sur le **Panel** de votre serveur où vous pouvez :
   - Démarrer, redémarrer ou arrêter votre serveur.
   - Gérer les fichiers et les configurations.
   - Installer des addons ou des mods.

### Étape 3 : Configurer le Serveur

1. Allez dans l’onglet **Configuration** du panel de votre serveur.
2. Modifiez le fichier `server.cfg` en ligne ou avec un accée ftp en ajoutant les paramètres suivants :

   ```cfg
   hostname "Mon Serveur Garry's Mod MTX"
   sv_password ""  // Laissez vide si vous ne voulez pas de mot de passe
   rcon_password "votre_mot_de_passe_rcon"
   sbox_maxprops 100
   sbox_maxragdolls 10
3. Verifier de bien sauvegarder après chaque modification.

#### Étape 4 : Installer des Addons (Facultatif)

1. Allez dans l’onglet Workshop sur le panel MTXServ.
2. Recherchez et ajoutez des addons ou des cartes que vous souhaitez installer sur votre serveur via le Workshop steam.
3. Il faudra connecter sa key steam au serveur pour que MTXServ les télécharges.

## 🔄 Gestion et Redémarrage du Serveur

  - Démarrer 🟢 /Arrêter 🔴 le Serveur : Utilisez les boutons disponibles sur le Dashboard de votre panel MTXServ .
  - Redémarrer : Si les modifications importantes on été effectué (ajout d’addons, changement de configuration, chagement de la carte), alors redémarrez votre serveur pour appliquer les changements.
    
## 🛠 Support et Assistance

Si vous rencontrez des problèmes :

  - Consultez le discord de MTXServ, avec une communauté bienveillante et a l'écoute.
  - Ouvrez un Ticket Support si vous ne trouver pas la reponse sur le discord.
    
## 🎉 Félicitations !

  - Ton serveur Garry's Mod est desormée en ligne et il est prêt à être utilisé. Vous pouvez inviter vos amis à vous rejoindre et bien evidement personnaliser votre serveur comme tu le souhaite.
