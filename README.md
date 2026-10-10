RaceDeck
Tableau de bord gratuit pour les DS et capitaines d'équipe sur Zwift.
Écarts, groupes, puissance, parcours et TTT en direct, dans des modules flottants au-dessus de Zwift, sur ton téléphone ou dans OBS.
![Dernière version](https://img.shields.io/github/v/release/monnierremy70/racedeck?label=version&color=3d8bff)
![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-0078d4)
![Licence](https://img.shields.io/badge/licence-GPL--3.0-green)
> 🧪 **Version de test privée** : RaceDeck s'active avec une clé gratuite, une clé par PC. Voir [Activation](#-activation).
---
✨ Ce que fait RaceDeck
RaceDeck affiche en direct ce qui se passe autour du coureur que tu suis. Il lit seulement les données de course : il ne modifie rien dans Zwift et ne pilote rien.
Module	Ce qu'il affiche
Coureurs autour	écarts en secondes et en mètres, W/kg, watts, FC, cadence, aspiration
Coureur suivi	carte du coureur : puissance, FC, vitesse, groupes devant et derrière
Groupes	écart entre les groupes, taille, W/kg moyen, coureurs de ton équipe
Équipe / Pen	tes coureurs et le classement du pen, avec l'écart au 1er
TTT équipe	tes coureurs côte à côte : écart, watts ou W/kg, aspi, FC, moyenne de course et sur 20 min
Stats puissance	meilleurs efforts 5 s → 1 h en barres, et moyenne de la course
Parcours / Parcours +	km restants, D+ restant, profil coloré selon la pente, KOM et sprints à venir, zoom sur les montées avec le % de chaque tronçon
Et aussi :
🪟 Modules flottants au-dessus de Zwift : déplaçables, redimensionnables, verrouillables (les clics passent alors à Zwift)
📱 Téléphone et tablette : tous les modules en plein écran sur le même Wi-Fi (pratique sur Apple TV)
🎥 Overlay pour OBS : une adresse par module, à ajouter comme source navigateur
🔄 Mises à jour automatiques, signées : tes réglages sont conservés
🧩 Mods : ajoute tes propres modules avec un simple fichier .zip
🇫🇷 🇬🇧 Français et anglais
---
📋 Ce qu'il te faut
Un PC Windows 10 ou 11. Zwift peut tourner ailleurs : sur ce PC, une Apple TV, une tablette…
Un second compte Zwift « observateur » : gratuit, il suffit d'une autre adresse e-mail. Il sert uniquement à lire les données de course. Ne l'utilise pas dans Zwift en même temps.
L'ID Zwift du coureur à suivre : c'est le nombre dans l'adresse de son profil ZwiftPower (`…profile.php?z=123456`).
---
📥 Installation
Télécharge `RaceDeck-x.y.z-Windows.zip` dans la dernière version (rubrique Assets).
Fais un clic droit → Extraire tout, par exemple dans `Documents\RaceDeck`.
Lance `RaceDeck.exe`. Un raccourci est créé sur le Bureau.
> ⚠️ Si Windows affiche **« Windows a protégé votre ordinateur »**, clique sur **Informations complémentaires → Exécuter quand même**. L'application n'est pas signée par un éditeur connu, c'est normal.
Pas besoin de Node.js ni d'installation supplémentaire.
---
🔑 Activation
Au premier lancement, RaceDeck demande une clé d'activation gratuite :
Indique ton prénom, nom et e-mail, puis clique sur Créer ma demande.
Envoie le code de demande par e-mail : le bouton Envoyer par e-mail prépare le message, sinon copie le code et l'adresse affichés.
Colle la clé reçue, puis clique sur Activer RaceDeck.
La clé ne fonctionne que sur ton PC. Nouveau PC ou Windows réinstallé ? Refais simplement une demande.
---
🚀 Premiers pas
Configuration → Connexion : ID Zwift du coureur à suivre, puis e-mail et mot de passe du compte observateur. Coche Rester connecté, puis Se connecter.
Configuration → Équipe : indique le tag de ton équipe (par exemple `BIKES`) pour mettre tes coureurs en couleur.
Modules → Nouveau module : ajoute ce que tu veux. Clique sur le cadenas du module pour le déplacer au-dessus de Zwift, puis referme-le.
TTT : dans l'onglet Course, coche ★ devant tes coureurs pour les afficher dans le module TTT équipe.
💡 Pas de course en cours ? Le mode démo te permet de tout essayer avec de faux coureurs.
📱 Sur téléphone ou tablette
Configuration → Fenêtre et réseau : coche l'accès depuis le Wi-Fi, puis redémarre RaceDeck. Scanne le QR code affiché avec ton téléphone, puis va dans Modules → Ouvrir.
Le téléphone doit être sur la même box que le PC. Si Windows demande l'autorisation du pare-feu, choisis Réseaux privés → Autoriser.
🎥 Dans OBS
Modules → copie l'adresse OBS du module → dans OBS, Source → Navigateur, puis colle l'adresse.
---
🔒 Confidentialité et sécurité
RaceDeck lit les données de course via le compte observateur. Il n'envoie rien à Zwift d'autre que la connexion de ce compte.
Ton mot de passe n'est enregistré que si tu coches Rester connecté, chiffré par Windows sur ton PC. Il n'est envoyé qu'à Zwift.
Les mises à jour sont signées : RaceDeck refuse toute version qui ne vient pas de l'auteur.
Les mods tournent à part, en lecture seule : ils ne peuvent ni changer tes réglages, ni lire tes identifiants.
---
❓ Questions fréquentes
« Session en conflit » ? Le compte observateur est utilisé ailleurs en même temps (Zwift, Sauce for Zwift, un autre RaceDeck). Utilise un compte observateur réservé à RaceDeck.
Le téléphone n'arrive pas à ouvrir la page ? Vérifie que l'accès depuis le Wi-Fi est coché, que RaceDeck a bien été redémarré, que le pare-feu Windows autorise RaceDeck sur les réseaux privés, et que le téléphone n'est pas sur un Wi-Fi invité.
Une barre ou une fenêtre bloquée ? Clic droit sur l'icône RaceDeck près de l'horloge : tu peux tout verrouiller ou déverrouiller, masquer les modules, ou quitter.
Un bug, une idée ? Dans l'application : Configuration → Contact → Signaler un bug.
---
❤️ Soutenir
RaceDeck est gratuit et le restera. Si l'outil te rend service, un don m'aide à continuer de le développer : onglet Dons dans l'application.
---
📜 Licence et remerciements
RaceDeck est un logiciel libre sous licence GNU GPL v3.
Connexion aux données Zwift : Sauce for Zwift (Sauce, LLC, GPL-3.0)
Données des routes et des segments : zwift-data (Andi Pätzold, MIT)
Application : Electron (MIT)
QR codes : QR Code Generator (Kazuhiko Arase, MIT)
RaceDeck n'est ni affilié, ni approuvé, ni soutenu par Zwift, Inc. Zwift est une marque de Zwift, Inc.
---
<sub>Créé par Rémy Monnier pour les DS de la communauté Zwift.</sub>
