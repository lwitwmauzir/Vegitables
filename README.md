# Vegitables

A fully functional single-page **web app demo** for grocery/food ordering.

## Features
- Sign in flow (Google, Apple, Email mock auth)
- Search and category filtering
- Product catalog with add-to-cart
- Cart quantity controls (+ / -)
- Dynamic subtotal, tax, total
- Checkout form with validation
- Order placement and local persistence
- Lightweight account section

## Tech
- Plain HTML + CSS + Vanilla JavaScript
- Uses browser `localStorage` for cart/user/order state

## Run locally
Just open `index.html` in any modern browser.

For a local server:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.
