# Contrôles de publication

Objectif : publier un installateur utilisable sur un profil vierge sans fuite de données personnelles, de configuration locale ou d’historique privé.

## Mode

- Dépôt public en mode release-only.
- Historique public frais.
- Code source privé non publié.
- Binaires distribués uniquement via GitHub Releases.

## Gates v0.1.4

- Export : installateur produit par le script de release du repo privé.
- Historique : aucun commit privé dans ce dépôt public.
- Identifiants : aucun identifiant ou valeur d’accès n’est inclus.
- Données personnelles : aucun événement, calendrier, chemin local ou média privé n’est inclus.
- Configuration : première installation avec configuration vierge sous `%APPDATA%\QuickRing`.
- Runtime : tests automatisés réussis, installation silencieuse réussie, process unique vérifié, second lancement fermé en moins de cinq secondes.
- OAuth : jeton local vérifié avec deux scopes Calendar et aucun scope inattendu avant publication.
- Scan public strict : réussite avec `0` échec bloquant ; les alertes restantes concernent uniquement des chaînes génériques dans le binaire.
- Hash : SHA-256 publié pour l’installateur.
- Limite connue : l’installateur n’est pas encore signé par certificat de code signing.
