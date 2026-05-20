# Quick Ring 0.1.4

Release publique de durcissement OAuth et démarrage Windows.

## Contenu

- `QuickRingSetup-0.1.4.exe` : installateur utilisateur Windows x64.
- `QuickRing-0.1.4-SHA256SUMS.txt` : empreinte de vérification.

## Changements

- Conservation du jeton de renouvellement Google Calendar.
- Rejet des jetons Google contenant des droits hors Calendar.
- Autorisation Google verrouillée pour éviter plusieurs pages OAuth concurrentes.
- Instance unique : relancer Quick Ring quand l’application tourne déjà ferme immédiatement la deuxième instance.
- Démarrage Windows activé par défaut, désactivable avec `--disable-autostart` ou `--no-autostart`.

## Sécurité

- Aucun code source privé publié.
- Aucun historique privé publié.
- Aucun fichier de calendrier ou donnée personnelle inclus.
- Aucun identifiant Google inclus.
- Installateur non signé pour l’instant : vérifiez le SHA-256 avant exécution.

SHA-256 :

```text
d9d1b787b225c0ac41149a8ad8718c3b2766c39a8936564a22ce22e2a257aae7  QuickRingSetup-0.1.4.exe
```
