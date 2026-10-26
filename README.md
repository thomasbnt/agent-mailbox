# agent-mailbox

Démo minimale du "front end" d'un agent IA auto-hébergé : une page statique,
aucune donnée réelle, aucun traceur, aucun secret.

L'idée : l'agent tourne sur une machine perso ; il publie ici un résumé
d'activité. Cette page sert de vitrine pour l'article du défi DEV
"Ghost in the Machine" (Week 4, Hacktoberfest 2026).

## Contenu

- `index.html` : la page de démo, autonome (CSS et SVG inline, pas de dépendances).
- `render.yaml` : blueprint pour un déploiement Render en site statique gratuit.

## Règles de ce dépôt

- Aucune information personnelle : pas de noms, pas de lieux, pas d'adresses,
  pas de projets réels. Les données affichées sont explicitement fictives.
- L'agent publie depuis chez lui ; cette boîte aux lettres est un miroir de
  démonstration, pas un service de production.
