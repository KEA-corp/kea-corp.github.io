# Mode et args du kea

| mod | description                | arg1               | arg2          | agr3        | arg4 |
|-----|----------------------------|--------------------|---------------|-------------|------|
| #   | merge de modules           | "add"              | chemin du mod |             |      |
| A   | afficher une variable      | var                |               |             |      |
| B   | comparaison logique        | var de sortie      | var1          | comparateur | var2 |
| C   | calcul                     | var de sortie      | var1          | opération   | var2 |
| D   | debug                      | "on"/"off"/"print" |               |             |      |
| E   | sortie de boucle           | nom de boucle      |               |             |      |
| F   | déclaration de fonction    | nom de boucle      |               |             |      |
| H   | copier une variable        | var de sortie      | var modelle   |             |      |
| I   | input                      | var                |               |             |      |
| L   | boucle a tours             | nom de boucle      | nb de tours   |             |      |
| R   | variable aleatoire         | var de sortie      | max (V)       |             |      |
| S   | afficher du texte          | texte              |               |             |      |
| T   | téléphoner a une fonction  | nom de la fonction |               |             |      |
| V   | assignation de variable    | var                | valleur       |             |      |
| X   | execution si condition     | nom de boucle      | var (B)       |             |      |
| Z   | break (récusif)            | nom de bcl a break |               |             |      |

Les fonctionalités du kea ne sont pas garanties dans toutes les versions.
[→ info sur l'implémentation](https://kea-corp.github.io/doc/doc/implemented)

# Comparateurs

| comparateur | description          |
|-------------|----------------------|
| = (ou ==)   | égal à               |
| !=          | différent de         |
| <           | inférieur à          |
| <=          | inférieur ou égal à  |
| >           | supérieur à          |
| >=          | supérieur ou égal à  |

# Opérateurs

| opérateur  | description         |
|------------|---------------------|
| +          | addition            |
| -          | soustraction        |
| *          | multiplication      |
| /          | division            |
| %          | reste de la division|
| ^  (ou **) | puissance           |