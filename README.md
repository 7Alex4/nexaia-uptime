# Nexaia Uptime

Surveillance externe gratuite des services exploités par Nexaia.

Le dépôt ne contient aucun code applicatif ni secret. Il vérifie uniquement des
endpoints HTTP publics depuis les runners standards gratuits de GitHub Actions.

## Black Sterling OS

Toutes les quinze minutes, le moniteur vérifie :

- `https://black-sterling-os.nexaia.app/api/health/live`
- `https://black-sterling-os.nexaia.app/api/health/ready`

GitHub notifie le propriétaire uniquement lorsqu'un contrôle échoue. Une
activité mensuelle automatisée empêche la désactivation des workflows
planifiés pour inactivité du dépôt public.
