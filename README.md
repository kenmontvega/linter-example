# linter-example

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

------------
Comandos Linter
------------
instalar eslint
npm init @eslint/config

Ejecutar Eslint
npx eslint src\**

Corregir errores con Eslint
npx eslint src\** --fix

Añadir comandos al package.json 
para facil accesso

"lint": "eslint src\**",
"fix": "eslint src\** --fix",


Ejecutar Prettier
npx prettier --write .



Documentacion
Eslint
https://eslint.org/docs/latest/rules/
Vue linter
https://eslint.vuejs.org/rules/
Prettier
https://prettier.io/docs/en/install.html
