# e-plantShopping

## Project Overview

**e-plantShopping** is a React-based online plant shopping web application built with Vite and Redux state management. It allows users to browse plant categories, view plant details and pricing, add or remove items in a shopping cart, and adjust item quantities dynamically.

## Repository

This documentation corresponds to the **e-plantShopping** GitHub repository (`/home/project/e-plantShopping`).

## Key Features

* **About Us Section (`AboutUs.jsx`)**: Introduces the application and its focus on indoor and specialty plants.
* **Product Catalog (`ProductList.jsx`)**: Displays available plants organized into categories with options to add items to the cart.
* **Shopping Cart Management (`CartItem.jsx` & `CartSlice.jsx`)**: Supports adding items, updating quantities, calculating item and cart totals, and removing plants from the cart.
* **Centralized State (`store.js`)**: Coordinates cart state across components using Redux.

## Project Structure

* `src/App.jsx` & `src/main.jsx`: Main application entry point and layout routing.
* `src/ProductList.jsx` & `src/ProductList.css`: Product listing view and styling.
* `src/CartItem.jsx`, `src/CartSlice.jsx` & `src/CartItem.css`: Shopping cart UI, reducer logic, and styles.
* `src/AboutUs.jsx` & `src/AboutUs.css`: Project overview component and styles.

## Running Locally

Install dependencies and start the development or preview server:

```bash
npm install
npm run dev