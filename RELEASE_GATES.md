# Contrôles de publication

Objectif : publier un installateur utilisable sur un profil vierge sans fuite de données personnelles, de configuration locale ou d’historique privé.

## Mode

- Dépôt public en mode release-only.
- Historique public frais.
- Code source privé non publié.
- Binaires distribués uniquement via GitHub Releases.

## Gates v0.1.0

- Export : installateur produit par le script de release du repo privé.
- Historique : aucun commit privé dans ce dépôt public.
- Identifiants : aucun identifiant ou valeur d’accès n’est inclus.
- Données personnelles : aucun événement, calendrier, chemin local ou média privé n’est inclus.
- Configuration : première installation avec configuration vierge sous `%APPDATA%\QuickRing`.
- Runtime : smoke fixture réussi et smoke installateur sans démarrage réussi.
- Hash : SHA-256 publié pour l’installateur.
- Limite connue : l’installateur n’est pas encore signé par certificat de code signing.
