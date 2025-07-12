# Product Catalog — Your Ultimate Electronics Showcase
Product Catalog is a modern, responsive website designed to showcase a wide range of electronic products, including phones, tablets, and accessories. Easily browse, sort, and explore detailed product information, add favorites, and manage your shopping cart. The clean and intuitive interface ensures a seamless browsing experience on both desktop and mobile devices.

# Live demo

Experience the live website: [ProductCatalog Demo](https://hetskoweb.github.io/product_catalog/)

# Technologies Used 💻

**Core**
* **React (v18.3.1)** - UI framework
* **TypeScript (v5.2.2)** - Type safety
* **Sass (v1.83.4)** - Styling

**UI/UX**
* **React Router (v6.25.1)** - Navigation
* **Swiper (v11.2.10)** - Image galleries

**Development && Deployment**
* **Vite (v5.3.1)** - Build tool
* **ESLint (v8.57.0)** - Code Quality
* **Prettier (v3.3.2)** - Code Formatting

# 🚀 Features

- ⚛️ **Single Page Application (SPA)** — Built using `React Router` for smooth client-side navigation without full page reloads
- 📱 **Responsive Design** — Fully responsive layout adapted for mobile, tablet, and desktop screens
- 🧩 **Modular Architecture** — Codebase organized into modules (`HomePage`, `CartPage`, `FavoritesPage`, etc.) for better scalability and maintenance
- 📦 **Product Catalog**
  - 📂 Categories: Phones, Tablets, Accessories
  - 🔍 Individual product detail pages with dynamic routing
  - 🔄 Async product loading with error and loading state handling
- 🛒 **Shopping Cart**
  - ➕ Add and remove products
  - 🔢 Adjust product quantities
  - ♻️ Global cart state using React Context API
- ❤️ **Favorites Page** — Save and view your favorite products
- 📁 **Local JSON API** — Simulates backend using a local `products.json` file
- 🎛️ **Sidebar Navigation** — Collapsible sidebar menu with smooth toggle animation and scroll lock
- 🧠 **Smart Data Fetching** — Reusable `fetchData` logic with loading/error states and retry handling
- 💅 **SCSS with Mixins** — Uses `@use` and custom mixins for media queries and styling
- 🧪 **TypeScript Support** — Fully typed with TypeScript for type safety and IDE autocompletion


# Additional Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/hetskoweb/product_catalog.git
cd product_catalog
```

2. **Install dependencies:**
```bash
npm install
# or
yarn install
```

3. **Run the project locally:**
```bash
npm start
# or
yarn start
```
