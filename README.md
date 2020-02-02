# nuxt-stack

Example nuxt stack that based on vuetify. Comes with tooling such as eslint, prettier, husky, editorconfig, jest, stylelint and vscode settings.

## Modules

| Key                                      | Description                                                       |
| :--------------------------------------- | :---------------------------------------------------------------- |
| [`vuetify`][vuetify]                     | Vuetify Module for Nuxt.js                                        |
| [`axios`][nuxt-axios]                    | Nuxt `axios` integration for making promise based HTTP requests   |
| [`dotenv`][nuxt-dotenv]                  | Loads `.env` and merges the contents with Nuxt's `env` object     |
| [`ga`][vue-analytics]                    | Google Analytics integration for Nuxt                             |
| [`installer`][vue-pwa-installer]         | Simple interface for installing a PWA to the home screen          |
| [`lazysizes`][lazysizes]                 | Lazily load images and videos when they become visible            |
| [`sitemap`][nuxt-sitemap]                | Automatically generate or serve a dynamic sitemap                 |
| [`styleResources`][nuxt-style-resources] | Share variables, mixins and functions across style files and SFCs |
| [`svgLoader`][nuxt-svg-loader]           | Import SVGs as Vue components                                     |
| [`webfonts`][webfontloader]              | Load custom webfonts from services like Google and Typekit        |

## Build Setup

```bash
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).

[vuetify]: https://github.com/nuxt-community/vuetify-module
[nuxt-axios]: https://axios.nuxtjs.org
[nuxt-dotenv]: https://www.npmjs.com/package/@nuxtjs/dotenv
[nuxt-sitemap]: https://www.npmjs.com/package/@nuxtjs/sitemap
[nuxt-style-resources]: https://www.npmjs.com/package/@nuxtjs/style-resources
[nuxt-svg-loader]: https://www.npmjs.com/package/nuxt-svg-loader
[webfontloader]: https://www.npmjs.com/package/webfontloader
[vue-analytics]: https://www.npmjs.com/package/vue-analytics
[lazysizes]: https://www.npmjs.com/package/lazysizes
[vue-pwa-installer]: https://www.npmjs.com/package/vue-pwa-installer
