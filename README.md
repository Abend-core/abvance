# abvance

Outil web de gestion de tickets, sécurisé et en ligne, pensé pour faire travailler
ensemble une équipe de développement et ses clients sur les mêmes projets.

📄 **[Spécifications](docs/SPECIFICATIONS.md)** — document vivant, à lire avant toute
discussion technique.

## Démarrage

```bash
git clone https://github.com/Abend-core/abvance.git
cd abvance
```

## Workflow d'équipe

- `main` est la branche stable, on ne pousse pas dessus directement.
- On travaille sur une branche par sujet : `git switch -c feat/ma-fonctionnalite`
- On ouvre une Pull Request vers `main` pour relecture avant merge.

## Convention de commits

```
feat: nouvelle fonctionnalité
fix: correction de bug
docs: documentation
refactor: refonte sans changement de comportement
chore: outillage, config, dépendances
```
