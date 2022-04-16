![thumbnail](thumbnail.jpeg)

# Hydrogen App by Son Hong-su
This EC site is a demo site I created for a study session hosted by Over40 Web Club.
This is created by Hydrogen and hosted by CLOUD FLARE.

- [Visit this site](https://sample-hydrogen.horumont.workers.dev/)
- [Slides used in the study session](https://www.canva.com/design/DAE7-Sx4SyA/l6wG0OS-XxMgqVJN8nWTwg/edit?utm_content=DAE7-Sx4SyA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
- [Document used in the site construction demo(Notion)](https://chiseled-practice-bd3.notion.site/a5b8237442c04cf9b11a7085257781e6)

Hydrogen is a React framework and SDK that you can use to build fast and dynamic Shopify custom storefronts.
[Check out the docs](https://shopify.dev/custom-storefronts/hydrogen)

## Getting started

**Requirements:**

- Node.js version 16.5.0 or higher
- Yarn

```bash
yarn
yarn dev
```

`shopify.config.js` is updated by Son Hong-su.

## Previewing a production build

To run a local preview of your Hydrogen app in an environment similar to Oxygen, build your Hydrogen app and then run `yarn preview`:

```bash
yarn build
yarn preview
```

## Building for production

```bash
yarn build
```

Then, you can run a local `server.js` using the production build with:

```bash
yarn serve
```

## Running tests

This project contains basic end-to-end (E2E) tests in the `/tests/e2e` folder powered by [Vitest](https://vitest.dev).

You can run tests in development, and they will automatically reload when you make changes to the component you provide to `hydrogen.watchForUpdates()`:

```bash
yarn test
```

To run tests in a continuous-integration (CI) environment like GitHub Actions:

```bash
yarn test:ci
```
