![Vue Storefront](https://camo.githubusercontent.com/48c886ac0703e3a46bc0ec963e20f126337229fc/68747470733a2f2f643968687267346d6e767a6f772e636c6f756466726f6e742e6e65742f7777772e76756573746f726566726f6e742e696f2f32383062313964302d6c6f676f2d76735f3062793032633062793032633030303030302e6a7067)

# Commercejs integration for Vue Storefront Next

<a href="https://slack.vuestorefront.io">![Branch Develop](https://img.shields.io/badge/community%20chat-slack-FF1493.svg)</a>

> **Disclaimer:** This project is still in beta phase.

This repository is the integration of [Commerce.js](https://commercejs.com/) and [Vue Storefront Next](https://github.com/DivanteLtd/vue-storefront/tree/next).

This repository is a monorepo containing three projects:

- **api-client** - communicates with a backend;
- **composables** - exposes composable functions used to retrieve data using `api-client` and to map them to universal data formats using `getters`;
- **theme** - `nuxt` project that glues everything together. It extends our core theme and uses `composables` to retrieve data.

## How to start?

1. Install all required dependencies:

```sh
yarn install
```

2. (optional) Then you can verify if everything works properly by building all three projects:

```sh
yarn build
```

3. If everything built properly, you can start using your new integration with:

```sh
yarn dev
```
