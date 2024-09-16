<!--
Get your module up and running quickly.

Find and replace all on all files (CMD+SHIFT+F):
- Name: My Plugin
- Package name: gt-packages/t6
- Description: My new Nitro plugin
-->

# My Plugin

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![License][license-src]][license-href]
[![code style][code-style-src]][code-style-href]

My new Nuxt module for doing amazing things.

- [✨ &nbsp;Release Notes](/CHANGELOG.md)
  <!-- - [🏀 Online playground](https://stackblitz.com/github/your-org/t6?file=playground%2Fapp.vue) -->
  <!-- - [📖 &nbsp;Documentation](https://example.com) -->

## Install

```bash
pnpm install add -D t6
```

## Usage

### Nuxt

Add the plugin to your `nuxt.config.js`:

```ts
export default defineNuxtConfig({
  nitro: {
    plugins: ['@gt-packages/t6']
  }
})
```

### Nitro

Add the plugin to your `nitro.config.js`:

```ts
export default defineNitroConfig({
  plugins: ['@gt-packages/t6']
})
```

## Contribution

<details>
  <summary>Local development</summary>

```bash
# Install dependencies
npm install

# Generate type stubs
npm run dev:prepare

# Develop with the playground
npm run dev

# Build the playground
npm run dev:build

# Run ESLint
npm run lint

# Run Vitest
npm run test
npm run test:watch

# Release new version
npm run release
```

</details>

<!-- Badges -->

[npm-version-src]: https://img.shields.io/npm/v/@gt-packages/t6/latest.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-version-href]: https://npmjs.com/package/@gt-packages/t6
[npm-downloads-src]: https://img.shields.io/npm/dm/@gt-packages/t6.svg?style=flat&colorA=18181B&colorB=28CF8D
[npm-downloads-href]: https://npmjs.com/package/@gt-packages/t6
[license-src]: https://img.shields.io/npm/l/@gt-packages/t6.svg?style=flat&colorA=18181B&colorB=28CF8D
[license-href]: https://npmjs.com/package/@gt-packages/t6
[code-style-src]: https://antfu.me/badge-code-style.svg
[code-style-href]: https://github.com/gt-packages/antfu-eslint-config
