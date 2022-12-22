# Lerna and husky Getting Started Example

This repo is a small example of using Lerna 5+ and husky.

Watch this [10-minute walkthrough](https://youtu.be/1oxFYphTS4Y) to see how new versions of Lerna work.

This repo contains two packages or projects:

```
packages/
    header/
        src/
            ...
        package.json
        rollup.config.json
        jest.config.js

    footer/
        src/
            ...
        package.json
        rollup.config.json
        jest.config.js

package.json
```
Pasos:
- Raiz del proyecto: npx lerna@latest init
- En el package.json de la raiz especificar en "workspace" los distintos servicios
- En lerna.json poner independent en version
- En raiz "npx husky-init && npm install"