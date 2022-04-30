# Vital

Opiniated Quasar + Vite starter template.

<br>

## Features

<b>

- [Quasar](https://quasar.dev), [Vite 2](https://vitejs.dev), [Vue 3](https://vuejs.org)

  - Use the [new `<script setup>` syntax](https://vuejs.org/api/sfc-script-setup.html)
  - [Reactivity Transform](https://vuejs.org/guide/extras/reactivity-transform.html) enabled
  - [TypeScript](https://www.typescriptlang.org), of course

<b>

- [File based routing](./src/pages) via [vite-plugin-pages](https://github.com/hannoeru/vite-plugin-pages#vite-plugin-pages)

- [Layout system](./src/layouts) via [vite-plugin-vue-layouts](https://github.com/JohnCampionJr/vite-plugin-vue-layouts#vite-plugin-vue-layouts)

- [Components auto importing](./src/components) via [unplugin-vue-components](https://github.com/antfu/unplugin-vue-components#unplugin-vue-components)

- APIs auto importing via [unplugin-auto-import](https://github.com/antfu/unplugin-auto-import#unplugin-auto-import) - directly use Composition API and others like `[pinia, vueuse...]` without importing

- [State Management](./src/stores) via [ Pinia](https://pinia.esm.dev/)

- [UnoCSS](https://github.com/antfu/unocss) - the instant on-demand Atomic CSS engine

- [Use icons from any icon sets with classes](https://github.com/antfu/unocss/tree/main/packages/preset-icons#unocsspreset-icons)

  - Only [Carbon Icons](<(https://icon-sets.iconify.design/carbon/)>) is pre-installed
  - To install other collections, `yarn add -D @iconify-json/[the-collection-you-want]`, for example `@iconify-json/mdi` for Material Design Icons
  - Find out more here: [Icônes](https://icones.netlify.app/) 🔍

<b>

- [VueUse](https://github.com/antfu/vueuse) - collection of useful Vue Composition Utilities

- [Unit Testing](./test/) with [Vitest](https://github.com/vitest-dev/vitest)

- Use [ESLint](https://eslint.org) and [Prettier](https://prettier.io) on VSCode and before you commit with [husky](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged)

- Deploy to [Vercel](https://vercel.com) or [Netlify](https://www.netlify.com) (zero-config)

<br>

<br>

## Getting started

### GitHub Template

[Create a repo from this template on GitHub](https://github.com/oumarbarry/vital/generate)

### Clone to local

Use [degit](https://github.com/Rich-Harris/degit) to clone to your machine with an empty git history

```bash
npx degit oumarbarry/vital my-vital-app
cd my-vital-app
yarn
```

<br>

## Scripts

- `yarn dev` - Start the app in development mode (hot-code reloading, error reporting, etc)
- `yarn build` - Build the app for production (the generated files will be on the `dist/spa` folder)
- `yarn test` - Run the unit tests with Vitest
- `yarn format` - Format the files with Prettier
- `yarn lint` - Lint the files with ESLint

<br>

### To Customize the configuration

See [Configuring quasar.config.js](https://quasar.dev/quasar-cli-vite/quasar-config-js).
