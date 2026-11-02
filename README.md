# GestionVehiculeProgramme Java en console qui gère un parc de véhicules.
Auteurs : Elodie et Coco

## Après le clone

Pour activer les hooks Git du projet après avoir cloné le dépôt, exécutez :

```bash
git config core.hooksPath .githooks
```

Cette commande permet d'utiliser les hooks `pre-commit` et `commit-msg` du projet.

Recherche par immatriculation (en cours)
Voir aussi : git lg
## Compiler
javac -d out $(find src/main -name "*.java")
