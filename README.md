# Paradise Nursery Shopping Application

A responsive e-commerce web application for an online plant shop called **Paradise Nursery**, developed using React and Redux Toolkit.

## Project Overview

**Paradise Nursery** provides plant enthusiasts with a seamless way to browse indoor and outdoor houseplants, view descriptions and prices, and manage a dynamic shopping cart.

### Key Features

- **Landing Page**:
  - Welcoming company introduction with a rich background greenhouse visual.
  - Informative "About Us" section detailing the nursery's mission and plant care expertise.
  - "Get Started" call-to-action button to navigate directly to the product catalog.

- **Product Listing**:
  - Organized houseplant categories (Air Purifying, Aromatic Fragrant, Insect Repellent, Medicinal, and Low Maintenance).
  - Detailed product cards showcasing thumbnails, names, descriptions, and prices.
  - Interactive "Add to Cart" buttons that disable dynamically once an item is added.
  - Sticky navigation bar with a live cart item count badge reflecting total items in real time.

- **Shopping Cart Management**:
  - View selected houseplants with thumbnails, unit prices, and subtotal per plant.
  - Quantity controls (`+` and `-`) to dynamically adjust quantities or remove items when quantity reaches zero.
  - Instant calculation of total cart amount.
  - Item deletion button to immediately remove unwanted items.
  - "Continue Shopping" button to return to the catalog and "Checkout" button with user feedback.

## Tech Stack

- **React 18**: UI component architecture and hooks
- **Redux Toolkit & React-Redux**: Global state management for cart items, quantities, and totals
- **Vite**: Fast frontend build tool and development server
- **CSS3**: Custom responsive styling, transitions, and hover effects

## Project Structure

```
e-plantShopping/
├── README.md
├── package.json
├── vite.config.js
├── public/
└── src/
    ├── App.jsx
    ├── App.css
    ├── AboutUs.jsx
    ├── AboutUs.css
    ├── ProductList.jsx
    ├── ProductList.css
    ├── CartItem.jsx
    ├── CartItem.css
    ├── CartSlice.jsx
    ├── store.js
    ├── main.jsx
    └── index.css
```

## Getting Started

### Prerequisites

- Node.js (version 16 or later)
- npm (Node Package Manager)

### Installation & Run

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd e-plantShopping
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open `http://localhost:5173` in your browser.

## License

This project is licensed under the Apache License 2.0.