<div align="center">
  <img src="https://user-images.githubusercontent.com/1626923/137092657-fb398d20-b592-4661-a1f9-4135db0b61d5.png" alt="Vue Storefront" height="80px" />
</div>

# Commercejs integration for Vue Storefront Next

<a href="http://discord.vuestorefront.io/">
<img src="https://discordapp.com/api/guilds/770285988244750366/widget.png?style=shield" alt="Discord Shield"/>
</a>

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
