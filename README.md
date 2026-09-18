# e-PlantShopping

e-PlantShopping is a React plant nursery shopping application. Users can browse
plants by category, add products to a cart, update quantities, remove products,
and review the total cost before checkout.

## Features

- Product catalog grouped by plant category.
- Add-to-cart buttons with visual feedback after adding a product.
- Redux-powered cart state shared across the application.
- Increase, decrease, and remove cart items.
- Live item count in the navigation cart icon.
- Per-item subtotals and total cart amount.
- Continue shopping and placeholder checkout actions.

## Technologies

- React 18
- Vite
- Redux Toolkit and React Redux
- CSS

## Project Structure

```text
src/
	App.jsx             Application landing page and navigation flow
	ProductList.jsx     Plant catalog and add-to-cart actions
	CartItem.jsx        Cart display and quantity controls
	CartSlice.jsx       Redux cart reducer and actions
	store.js            Redux store configuration
```

## Getting Started

Install dependencies and start the development server:

```bash
npm install
npm run dev
```

Create a production build or preview it locally:

```bash
npm run build
npm run preview
```

## GitHub Pages Deployment

The Vite base path is configured for this repository. Deploy the production
build with:

```bash
npm run deploy
```

This publishes the `dist` folder to the `gh-pages` branch. In the repository
settings, configure GitHub Pages to deploy from the `gh-pages` branch root.

Expected URL:

https://mijjinpy.github.io/e-plantShopping/
