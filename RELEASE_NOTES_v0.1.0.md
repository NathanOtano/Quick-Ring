# Quick Ring 0.1.0

Première release publique de Quick Ring.

## Contenu

- `QuickRingSetup-0.1.0.exe` : installateur utilisateur Windows x64.
- `SHA256SUMS.txt` : empreinte de vérification.

## Comportement

- Installe l’application sous `%LOCALAPPDATA%\Programs\QuickRing`.
- Crée une configuration vierge sous `%APPDATA%\QuickRing`.
- Ne lance pas de console au démarrage Windows.
- Garde le démarrage Windows désactivé par défaut.
- Utilise Google Calendar en lecture seule quand l’utilisateur fournit sa propre configuration OAuth locale.
- Démarre avec des événements de démonstration sans configuration Google.

## Sécurité

- Aucun code source privé publié.
- Aucun historique privé publié.
- Aucun fichier de calendrier ou donnée personnelle inclus.
- Aucun identifiant Google inclus.
- Installateur non signé pour l’instant : vérifiez le SHA-256 avant exécution.

SHA-256 :

```text
fcf2f982d32cf4394ae8c16dda58747982c2fb07986b80bf539bf8c0177daf6c  QuickRingSetup-0.1.0.exe
```
