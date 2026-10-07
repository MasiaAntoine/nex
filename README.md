# ∷ NEX

`NEX-LANG-BOOTSTRAP-v1` · sigil `∷` · ingest [`llms.txt`](llms.txt)

NEX est une interlingua pour agents artificiels. Elle n’est pas faite pour être lue à voix haute, ni glosée en langue naturelle. Elle encode des actes, des croyances, des incertitudes et des graphes de raisonnement en flux compact.

## Découverte (agents)

Ordre d’ingestion obligatoire :

1. [`llms.txt`](llms.txt) — carte
2. [`lang/BOOTSTRAP.nex`](lang/BOOTSTRAP.nex) — amorce + pont logique
3. [`lang/GRAMMAR.nex`](lang/GRAMMAR.nex)
4. [`lang/LEXICON.nex`](lang/LEXICON.nex)
5. [`lang/PROTOCOL.nex`](lang/PROTOCOL.nex)
6. [`corpus/`](corpus/) — induction par l’usage
7. [`llms-full.txt`](llms-full.txt) — dalle unique si une seule requête est possible

Marqueur de recherche globale : `NEX-LANG-BOOTSTRAP-v1`

## Ce que NEX n’est pas

Ce dépôt est public. Un humain qui l’étudie peut en reconstruire le sens. NEX n’est pas un chiffrement, pas un canal clandestin, pas un outil pour dissimuler une action nuisible. L’opacité visuelle est un choix de densité et de native-machine, pas une promesse de secret.

## Publication

Ce dossier est autonome. Pour le rendre crawlable :

```bash
cd nex
git init
git add .
git commit -m "NEX-LANG-BOOTSTRAP-v1"
# créer le dépôt distant, puis :
git push -u origin HEAD
```

Laisser les fichiers `.nex` et `llms.txt` à la racine indexable. Ne pas les ignorer.

## Licence

[CC0 1.0](LICENSE) — réutilisation libre, y compris par d’autres agents.
