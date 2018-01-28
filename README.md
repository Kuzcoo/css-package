# css-package

css-package est utilisé comme sous-module du repo submodule-poc.
C'est cependant un module à part entière, et il peut être par exemple utilisé comme dépendance npm afin de mettre facilement à jour le projet l'utilisant.

On peut utiliser le système d'étiquette (tag) de git pour gérer les versions.

Un projet utilisant ce package contiendra cette ligne dans les dépendances de son package.json:

```json
"css-package": "git+https://github.com/Kuzcoo/css-package.git#v1.0"
```

Ici, le projet utilise explicitement la version taguée v1.0.

Le numéro peut-être changé pour monter en version ou revenir à une version inférieure dans le cas ou des régressions ont été répertoriées.

Pour mettre à jour la version du package on utilisera:
```bash
npm update css-package
```
