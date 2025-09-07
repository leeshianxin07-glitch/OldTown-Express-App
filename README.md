# OldTown Express Multi-Page Demo

A simple 3-page prototype that simulates a fast "Grab & Go" order flow.

## Pages
1. **menu.html** — choose drinks, add to cart, place order.
2. **preparing.html** — shows "Your order is being prepared..." with a 3-second countdown and progress bar.
3. **ready.html** — shows "Your order is ready to collect!" with order summary.

## Usage
- Open `menu.html` in a browser.
- Select items, place order → auto redirects to preparing → auto redirects to ready.
- Fully in English, lightweight HTML/CSS/JS only.

## Notes
- No server needed, works offline.
- LocalStorage is used to pass order summary between pages.
