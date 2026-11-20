# NeuroSole — Interactive Sneaker Shopping Experience

A React-based sneaker storefront with two browsing modes: an exploratory product experience and a conventional shop flow. The application includes cart and checkout routes.

## Features
- **Explore and Shop modes** — switch between an exploratory experience and the product-shopping view.
- **Cart interface** — shared cart state through a React context provider.
- **Checkout route** — dedicated checkout screen.
- **Animated interface** — Framer Motion transitions.
- **Client-side routing** — React Router routes the home and checkout views.

## Tech Stack
- React 19, Vite
- React Router
- Framer Motion
- Lucide React

## Run Locally
Requirements: Node.js and npm.

```bash
npm install
npm run dev
```

Vite prints the local development URL in the terminal.

## Quality Checks
```bash
npm run lint
npm run build
```

## Project Structure
```text
src/
├── components/   # Navigation, cart, explore/shop and checkout UI
├── context/      # Shared application state
├── App.jsx       # Route and application composition
└── main.jsx      # React entry point
```

## Notes
This repository contains the frontend application. Review the current source and deployment configuration before using it as a production commerce system; payment processing, inventory, and order fulfilment should not be assumed from the presence of a checkout screen.
