# Quick Ring

Canal public de distribution de Quick Ring.

Quick Ring est une application Windows locale qui affiche le prochain rendez-vous Google Calendar dans la zone système, avec overlay discret et alertes de proximité.

Ce dépôt public fonctionne en mode release-only : il publie les installateurs, les notes de version et les empreintes de vérification. Le code source privé et l’historique de développement ne sont pas publiés ici.

## Télécharger

La version publique actuelle est `0.1.0`. Les fichiers installables sont disponibles dans les GitHub Releases du dépôt.

## Premier lancement

- Windows x64.
- Installation utilisateur sous `%LOCALAPPDATA%\Programs\QuickRing`.
- Configuration sous `%APPDATA%\QuickRing`.
- Démarrage Windows désactivé par défaut.
- Aucun client OAuth Google n’est fourni dans la release publique.

Sans configuration Google locale, l’application démarre avec des événements de démonstration. Pour lire un vrai calendrier, l’utilisateur doit fournir son propre client OAuth Google Calendar en lecture seule.

## Vérification

Vérifiez l’empreinte SHA-256 de l’installateur avant exécution. Les checksums publiés sont dans `checksums/` et attachés à chaque release.
