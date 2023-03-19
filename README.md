# VuewSampleApp

devbox install

curl -fsSL https://get.jetpack.io/devbox | bash

devbox init
devbox add nodejs

devbox shell

npm create vue@3

```sh
✔ Project name: … vue-project
✔ Add TypeScript? … Yes
✔ Add JSX Support? … No
✔ Add Vue Router for Single Page Application development? … Yes
✔ Add Pinia for state management? … Yes
✔ Add Vitest for Unit Testing? … Yes
✔ Add an End-to-End Testing Solution? › Cypress
✔ Add ESLint for code quality? … Yes
✔ Add Prettier for code formatting? … Yes
```

cd vue-project
npm install
npm run format
npm run dev

## Nuxt3

npx nuxi init

cd nuxt-app
npm install
npm run dev

npm install -D @nuxtjs/eslint-config-typescript eslint eslint-config-prettier husky lint-staged prettier typescript

add .eslintrc
add .prettierrc
