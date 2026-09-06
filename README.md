
# cue-project

Vue 3 + TypeScript starter app built with Vite, featuring a counter component.

![Vue](https://img.shields.io/badge/Vue-3-42b883)
![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178c6)

## What it does

This is a Vue 3 single-page app scaffolded from the official `create-vue` template. It mounts a root `App.vue` component and includes a counter feature with increment, decrement, and reset buttons. The project ships with a full linting, formatting, and testing toolchain wired up out of the box, plus Tailwind CSS for styling.

## Tech stack

- [Vue 3](https://vuejs.org/) with `<script setup>` / TypeScript
- [Vite](https://vite.dev/) for dev server and bundling, with `vite-plugin-vue-devtools`
- [Tailwind CSS](https://tailwindcss.com/) via `@tailwindcss/vite`
- [Vitest](https://vitest.dev/) + `@testing-library/vue` + `jsdom` for testing
- [ESLint](https://eslint.org/) + `eslint-plugin-oxlint` (oxlint) + [Prettier](https://prettier.io/) for linting/formatting
- [Husky](https://typicode.github.io/husky/) + `lint-staged` for pre-commit checks

## Getting started

### Project setup

```sh
npm install
```

### Compile and hot-reload for development

```sh
npm run dev
```

### Type-check, compile and minify for production

```sh
npm run build
```

### Preview the production build

```sh
npm run preview
```

### Run unit tests

```sh
npm run test:run
```

### Lint and format

```sh
npm run lint
npm run format
```

## Recommended IDE Setup

[VS Code](https://code.visualstudio.com/) + [Vue (Official)](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur).

## Recommended Browser Setup

- Chromium-based browsers (Chrome, Edge, Brave, etc.):
  - [Vue.js devtools](https://chromewebstore.google.com/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)
  - [Turn on Custom Object Formatter in Chrome DevTools](http://bit.ly/object-formatters)
- Firefox:
  - [Vue.js devtools](https://addons.mozilla.org/en-US/firefox/addon/vue-js-devtools/)
  - [Turn on Custom Object Formatter in Firefox DevTools](https://fxdx.dev/firefox-devtools-custom-object-formatters/)

## Type Support for `.vue` Imports in TS

TypeScript cannot handle type information for `.vue` imports by default, so `vue-tsc` replaces the `tsc` CLI for type checking. In editors, [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) makes the TypeScript language service aware of `.vue` types.

<!-- TODO: add a screenshot -->

## License

No license file is present in this repository yet.
