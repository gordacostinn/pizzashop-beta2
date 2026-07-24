# Pizza Shop

Pizza Shop is a mobile-first beta web application for managing daily sales in a pizzeria. It was built around a real-world workflow: adding products quickly, checking available dough, confirming orders, and reviewing the day's results.

## Live demo

https://gordacostinn.github.io/pizzashop-beta2/

## Features

- Pizza catalog with raw and baked prices.
- Promotions and preset business orders.
- Empanadas sold individually, by half-dozen, or by dozen.
- Custom business orders with editable quantity, price, preparation, and dough usage.
- Delivery cost and payment method selection.
- Live order preview, cancellation, and confirmation flow.
- Dough stock validation and manual stock adjustments.
- Daily order history and end-of-day sales summary.
- Responsive layout designed for mobile use.

## Built with

- HTML5
- CSS3
- JavaScript (ES6)
- `localStorage` for beta data persistence

## Run locally

Clone or download the repository and open `index.html` in a browser.

For a local development server, run:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080` in your browser.

## Project structure

```text
index.html              Start a new workday
ventas.html             Sales screen
resumen.html            End-of-day summary
styles.css              Main styles
ventas-mobile.css       Mobile sales layout
ventas-extras.css       Sales forms and business-order styles
ventas-stock.css        Stock adjustment styles
script.js               App logic and localStorage handling
```

## Current limitations

This is a client-side beta. Data is stored only in the browser currently in use, so it is not shared across devices and is not intended for production data.

## Next version

The next version will use Flask and SQL to add persistent storage, multi-device access, authentication, and a more complete reporting system.

## Author

Built by [Santiago Perazzo].
