# Vue 3 + Typescript + Vite + WindiCSS

This template should help get you started developing with Vue 3 Typescript and WindiCSS in Vite.

This starter template also includes:

- [Vue Router 4.x](https://github.com/vuejs/vue-router-next)
- [Vuex 4.x ](https://next.vuex.vuejs.org/)

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)

- [![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/Cookiekira/vite-vue3-windi-starter)

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can enable Volar's `.vue` type support plugin by running `Volar: Switch TS Plugin on/off` from VSCode command palette.

## Project setup
```
pnpm install
```

### Compiles and hot-reloads for development
```
pnpm run dev
```

### Compiles and minifies for production
```
pnpm vite build
```

### Lints and fixes files
```
pnpm run lint
```

### Customize configuration
See [Configuring Vite](https://vitejs.dev/config/).
