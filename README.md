# e-plantShopping

e-plantShopping is a plant-shopping demo built with React. Browse plants by category, add them to your cart, adjust quantities, and see the cart total.

## Features

- Plant catalog grouped into categories, including air-purifying, aromatic, insect-repellent, medicinal, and low-maintenance plants
- Shopping cart with item counts, quantity controls, item removal, and a total
- Landing page with introductory information about Paradise Nursery
- Responsive development and production builds powered by Vite

Checkout is currently a placeholder and displays a “Coming Soon” message. Cart contents are held in the app's Redux state and are not saved between page reloads.

## Requirements

- Node.js (a current LTS release is recommended)
- npm

## Getting started

Install dependencies:

```bash
npm install
```

Start the local development server:

```bash
npm run dev
```

Open the local URL printed by Vite in your browser. Select **Get Started** to browse the catalog.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Build the app for production in `dist/` |
| `npm run preview` | Build the app and serve the production build locally |
| `npm run lint` | Run ESLint |

## Tech stack

- React 18
- Redux Toolkit and React Redux for cart state
- Vite 5

## Project structure

```text
src/
  AboutUs.jsx       Landing-page introduction
  App.jsx           App entry view and landing-page navigation
  CartItem.jsx      Cart display and quantity controls
  CartSlice.jsx     Redux cart state and actions
  ProductList.jsx   Plant catalog and shopping interactions
  store.js          Redux store configuration
  main.jsx          React application entry point
```

Plant images are loaded from external image URLs, so an internet connection is needed to display them.
