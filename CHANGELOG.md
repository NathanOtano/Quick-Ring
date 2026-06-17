# Journal des versions

## 0.1.5 - 2026-06-17

- L’overlay temporairement masqué réapparaît à chaque montée de niveau d’alerte : moins de 30 minutes, moins de 10 minutes, puis cinq minutes ou moins.
- L’overlay reste hors Alt-Tab quand il est masqué ou affiché, tout en conservant l’icône de zone système.
- Mise à jour de stabilité mineure pour le masquage par ligne quand plusieurs meetings proches sont affichés.

## 0.1.4 - 2026-05-20

- Durcissement OAuth : conservation du jeton de renouvellement Calendar et rejet des jetons contenant des droits hors Calendar.
- Verrou d’autorisation Google pour éviter les pages OAuth concurrentes.
- Instance unique Quick Ring : un second lancement se ferme immédiatement.
- Démarrage Windows activé par défaut, avec option d’installation `--disable-autostart`.
- Sélection plus fine des calendriers et des sources de calendrier affichées.

## 0.1.0 - 2026-05-09

- Première release publique de Quick Ring.
- Installateur utilisateur Windows x64.
- Tray icon, overlay discret, paramètres calendrier et démarrage Windows.
- Google Calendar en lecture seule avec configuration OAuth locale fournie par l’utilisateur.
- Aucun code source privé publié.
