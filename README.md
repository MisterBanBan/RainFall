# RainFall — 42 (Post Common Core)

Solutions du projet RainFall. Un dossier par niveau :

```
levelN/
  flag          # le flag récupéré (= mot de passe du niveau suivant)
  resources/    # démarche, commandes et scripts utilisés
```

- **Obligatoire** : `level0` → `level9`.
- **Bonus** : `bonus0` → `bonus3` (évalué seulement si l'obligatoire est parfait).

## Environnement
VM lancée via QEMU (émulation x86 sur Mac Apple Silicon — VirtualBox impossible sur ARM).
Script de lancement dans le dossier parent : `../launch.sh`.
Connexion : `ssh level0@localhost -p 4242` (mot de passe : `level0`).
On change de niveau avec `su levelN` (mot de passe = le flag trouvé).

## Règles de rendu
- **Aucun binaire** dans le repo (voir `.gitignore`) — les fichiers de la VM se
  téléchargent uniquement pour l'analyse.
- Chaque étape doit pouvoir être expliquée à l'oral.

## Avancement
- [ ] level0 · level1 · level2 · level3 · level4 · level5 · level6 · level7 · level8 · level9
- [ ] bonus0 · bonus1 · bonus2 · bonus3
