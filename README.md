# Quick Ring

Canal public de distribution de Quick Ring.

Quick Ring est une application Windows locale qui affiche le prochain rendez-vous Google Calendar dans la zone système, avec overlay discret et alertes de proximité.

Ce dépôt public fonctionne en mode release-only : il publie les installateurs, les notes de version et les empreintes de vérification. Le code source privé et l’historique de développement ne sont pas publiés ici.

## Télécharger

La version publique actuelle est `0.1.5`. Les fichiers installables sont disponibles dans les GitHub Releases du dépôt.

## Premier lancement

- Windows x64.
- Installation utilisateur sous `%LOCALAPPDATA%\Programs\QuickRing`.
- Configuration sous `%APPDATA%\QuickRing`.
- Démarrage Windows activé par défaut. Utilisez `--disable-autostart` ou `--no-autostart` pour installer sans lancement automatique.
- Aucun client OAuth Google n’est fourni dans la release publique.

Sans configuration Google locale, l’application démarre avec des événements de démonstration. Pour lire un vrai calendrier, l’utilisateur doit fournir son propre client OAuth Google Calendar en lecture seule.

## Sécurité OAuth

Quick Ring conserve le jeton de renouvellement Google Calendar dans le profil Windows courant et rejette les jetons qui contiennent des droits Google hors Calendar. L’autorisation Google est verrouillée par instance afin d’éviter plusieurs pages OAuth concurrentes.

## Vérification

Vérifiez l’empreinte SHA-256 de l’installateur avant exécution. Les checksums publiés sont dans `checksums/` et attachés à chaque release.
