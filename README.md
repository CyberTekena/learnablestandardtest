# Product Catalogue and Shopping Cart

A React storefront exercise featuring product browsing, product details, and a shopping-cart interface.

## Features and structure

- [src/App.jsx](src/App.jsx) maps the catalogue, `/product/:productId`, and `/cart`.
- [src/components/AllProductsSetion.jsx](src/components/AllProductsSetion.jsx) renders paginated product results with loading and error states.
- [src/features](src/features) contains API and state modules.
- [src/store.js](src/store.js) configures application state.

The project uses React, React Router, Redux-related state modules, and Vite. Interface copy and product content are demonstration material; this is not a live commercial store.

## Run locally

```sh
git clone https://github.com/CyberTekena/learnablestandardtest.git
cd learnablestandardtest
npm install
npm run dev
```

Open the URL printed by Vite. Product requests depend on the API configuration in `src/features/` and network availability.

## Development

- `npm run build` — build the frontend.
- `npm run preview` — preview the build.
- `npm run lint` — run the configured ESLint checks.

## Scope and next improvements

The three registered routes are the implemented navigation surface; other marketing links may not have destination pages. Verify product API behavior, cart persistence, invalid product IDs, and loading/error transitions before extending this into a production storefront. No payment-processing implementation is claimed.

## Verification

Documentation was checked against routes, source structure, and package scripts. Runtime checks were not run for this documentation update.

## Author

Tekena Ajuzieogu · [GitHub](https://github.com/CyberTekena)
