# package-seed
Package seed with all this goodies:

## .gitignore

## .editorconfig (generic & Itellij specific)

## Babel
    -. core-js
    -. register
    -. cli
    -. core
    -. plugin-proposal-class-properties
    -. plugin-transform-regenerator
    -. preset-env
    -. register
    -. babel-eslint
    -. babel-jest
    -. babel-loader

## ESlint
    -. eslint
    -. eslint-config-airbnb-base
    -. eslint-config-prettier
    -. eslint-plugin-babel
    -. eslint-plugin-html
    -. eslint-plugin-import
    -. eslint-plugin-prettier
    -. eslint-plugin-standard

## Prettier

## lint-staged
    
Usado junto a husky crea un staged de los cambios para hacer el linting sólo de estos archivos (conn lo que es mucho más rápido)
Si quisieramos usar lint-staged en un proyecto ya creado podríamos hacer esto: `npx mrm lint-staged` con este comando instala en el proyecto linst-staged y además configura los lintings y husky según la configuración que se tenga en el proyecto   
    
## Husky 
    -. husky
    -. npm-run-all
# Jest
    -. jest
    -. jest-canvas-mock
    -. jest-extended
    -. jest-junit
    -. jest-snapshot
    
# Webpack
    -. webpack
    -. webpack-cli
    -. webpack-stream    
    -. webpack-dev-server
    -. html-webpack-plugin